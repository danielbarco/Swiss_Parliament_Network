# Federal Parliament External Entry Behaviour

HSLU MSc IDS AMS FS19:  Analytics and Modelling of Social Interactions

#Team
- [Daniel Barco](https://github.com/danielbarco)
- [Tanja Schär](https://github.com/maximumawesomeness)
- [Jonas Widmer](https://github.com/jonwidi)

#Date
Lucerne, 01.01.2020

#Research Question

What’s the Swiss Parties relations from to external stakeholders regarding their entry possibilities to the Federal Parliament Building in Berne and can we cluster them to lobbies? 

We’re going to analyse them per Year

##Process

##Data Source

We have different sources for “Ständerat” and “Nationalrat” filed as PDFs with tables 

Dictionary Deutsche Namen Partei als FRanzsöische Partei

Wahlen: 05.12.2011, 29.11.2015, Nov. 2019

Ständerat: 
Dezember 2012 → 2012
Januar 2014 → 2013 
Dezember 2014→ 2014
Dezember 2015 → 2015
Januar 2016 → 2016
Januar 2018 → 2018
Oktober 2019 → 2019 
2017 is missing

Nationalrat:

Dezember 2012
Januar 2014 → 2013
Dezember 2014
Dezember 2015
Januar 2016
Januar 2018
Oktober 2019

##Network Analysis 

Undirected Weighted Network:
nodes: parties and external organisations (like WWF, Bauernverband, and so on)
edges: connection between parties and external organisations (weighted -> if you have for WWF 4 in-going edges from SP, the edge has to be thicker than if there is e.g. just 1 edge from FDP)
