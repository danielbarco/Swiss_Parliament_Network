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

We retrieved the data by personal communication with the federal office combined with public available data on: https://www.parlament.ch/centers/documents/de/zutrittsberechtigte-nr.pdf

The data source includes PDFs with tables from the Swiss National parliament:

Dezember 2012 <br /> 
Januar 2014 → 2013 <br /> 
Dezember 2014 <br /> 
Dezember 2015 <br /> 
Januar 2016 <br /> 
Januar 2018 <br /> 
Oktober 2019 <br /> 

The connections from organizations to lobbies have been made according to the API of lobbywatch.ch  

## Network Analysis 

Undirected Weighted Network:
nodes: parties and external organisations (like WWF, Bauernverband, and so on)
edges: connection between parties and external organisations (weighted -> if you have for WWF 4 in-going edges from SP, the edge has to be thicker than if there is e.g. just 1 edge from FDP)

## Presentation
http://bit.ly/Swiss_Parliament_Network
