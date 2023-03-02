# Linked Data enabled Spatial Data Infrastructure for Rock Glacier Monitoring

---
## Motivation
The dTS project approaches the challenge of intelligent data use for future-oriented development of tourism regions from a digital sustainability perspective, leveraging digitalization and data-driven technologies to address a) ecological, b) economical, c) and societal challenges from a transdisciplinary perspective in the domain of regional tourism. The main goal for the dTS project is to use the combination of AI and agentbased modelling/simulation to contribute to resilient and sustainable regional tourism in Austria on the example of visitor flow control. The active control and management of visitor flows based on the intelligent use of data can help to sustainably alter the behavior of tourists and lead to a better balance of capacities in the long run. Two use cases in the Land Salzburg have been selected with the aim of strengthening the entire region, exhaust mobility resources, and work towards carbon-neutrality. Therefore, the technical developments within the project need to be accompanied by a sustainable point of view to ensure its effectiveness and optimal integration within the regional tourist ecosystem. At the same time, all technical solutions will be following privacy-by-design patterns and strategies concerning the overall architecture, algorithms, data handling, as well as interaction with the system as a whole. 
To answer the question: “How can the combination of AI and agent-based modelling/simulation contribute to resilient and sustainable regional tourism in Austria on the example of visitor flow control?”, dTS proposes a scalable and portable model for resilient and sustainable tourism. To achieve the development of such a framework, two use cases with different technological maturity levels are being examined. The result will be the design of a scalable data exchange and simulation platform that is also capable to serve as a data circle for visitor flows. Using artificial intelligence and agent-based simulations, the authentic movement and behavior patterns of the target groups are to be learned and understood to then incorporate these findings in the sense of a sustainable and gentle mobility concept. This also enables the modelling of "whatif" scenarios in the sense of decision support for the respective administrations. 
For the project the consortium is utilizing a multitude of data sources that are used as proxy for the human behavior (i.e. tourist behavior). Among them are: mobile phone data, NEAR data, bike-related data, touristic POIs and data of the Salzburg Tourism Card. In order to develop accurate simulations, the consortium is interested in a geostatistical analysis of the movement of people represented by the data. Of special interest are the interdependencies with sport events (e.g. soccer games), holidays, cultural events (e.g. Salzburger Festspiele) or any other event.
{% 
    include figure.html 
    image="images/theses/msc_dTS_spatiotemporal_statistics/01.png" 
    caption="Fig.1: Example of a population density mapping with respect to different temporal contexts."
%}

## Objectives and Goals
The objective of the MSc thesis is to employ spatial statistics to analyze existing movement data concerning the density of people the City of Salzburg. Due to the fact, that data on several years are available, this analysis should include the temporal dimension as well (day- vs. nighttime, winter vs. summer, week vs. weekend, events, etc.). 

The analysis utilized methods originating from distance-based analysis in Geography – i.e. hot spot and cluster analysis, Kernel Density estimation as well as spatial autocorrelation (global and local). In order to evaluate the spatial relationship between population density and other phenomena the usage of Geographically Weighted Regression techniques seems appropriate. The analysis should be carried out for each dataset separately, and for an integrated data set (that represents all movement data).

The thesis consists of the following work packages: 
* Literature analysis (thorough analysis of the existing literature) 
* Formulation of hypotheses (research questions) 
* Identification of geostatistical methods (and testing – using a small data sample) 
* Development of a methodology for the geostatistical and temporal analysis 
* Implementation of the analysis using open-source tools where possible (with respect to reproducibility and replicability) 
* Documentation of the results

## Requirements
* Basic programming skills (Python)
* Interested in spatial analysis (in particular spatial statistics)
* Interested in working scientifically


## Cooperation partners:
{% 
    include figure.html 
    image="images/theses/msc_dTS_spatiotemporal_statistics/logo_datenvorsprung.png" 
%}
Datenvorsprung GmbH
www.datenvorsprung.at
Sophie Neubauer und Philipp Neubauer

{% 
    include figure.html 
    image="images/theses/msc_dTS_spatiotemporal_statistics/logo_donauuni.png" 
%}
Department for E-Governance and Administration
University for Continuing Education Krems | Danube University Krems
Thomas Lamp

