# Federal Parliament External Entry Behaviour

HSLU MSc IDS AMS FS19:  Analytics and Modelling of Social Interactions

## Team
- [Daniel Barco](https://github.com/danielbarco)
- [Tanja Schär](https://github.com/maximumawesomeness)
- [Jonas Widmer](https://github.com/jonwidi)

## Date
Lucerne, 20.12.2019

## Research Question

What are the interactions between Swiss political fractions and  lobby groups with special access to the Swiss parliament from 2012 to 2019?

## Data Source

We have different sources for “Ständerat” and “Nationalrat” filed as PDFs with tables 

Nationalrat:

Dezember 2012 <br /> 
Januar 2014 → 2013 <br /> 
Dezember 2014 <br /> 
Dezember 2015 <br /> 
Januar 2016 <br /> 
Januar 2018 <br /> 
Oktober 2019 <br /> 

## Network Analysis 

Undirected Weighted Network:
nodes: parties and external organisations (like WWF, Bauernverband, and so on)
edges: connection between parties and external organisations (weighted -> if you have for WWF 4 in-going edges from SP, the edge has to be thicker than if there is e.g. just 1 edge from FDP)
