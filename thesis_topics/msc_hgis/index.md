# Open Source Technologien für HGIS de las Indias

---
## Motivation
Das Historisch-Geographische Informationssystem (HGIS) von Lateinamerika (1701-1808) ist ein Projekt der Karl-Franzens-Universität Graz, das zwischen 2015 und 2019 mit Unterstützung des Fonds für wissenschaftliche Forschung der Republik Österreich (FWF) entwickelt wurde. 
Ziel ist es eine solide Systematik der administrativ-territorialen Struktur als Schnittstelle für weitere wissenschaftliche Projekte zu schaffen, sowie geographische digitale Methoden und Werkzeuge in der lateinamerikanistischen Geschichtsschreibung zu fördern. Zu diesem Zweck wurde:
* eine Systematisierung besiedelter Orte und kolonialer Gebietseinheiten mit eindeutigen Identifikatoren entwickelt, mit dem Potenzial, Daten in Bezug auf eine Entität / einen Ort zu verknüpfen;
* ein Ortsverzeichnis (Ortsdatenbank) mit zeitlich definierten Attributen und Koordinaten der zwischen 1701 und 1808 bestehenden besiedelten Orte (derzeit mehr als 13.000) erstellt;
* eine Rekonstruktion der territorialen Entwicklung von mehr als tausend Verwaltungseinheiten der spanischen Monarchie in Amerika zwischen 1701 und 1808 entwickelt;
* verschiedene mit diesen Orten/Gebieten verknüpfte Datensätze (Bevölkerung, Institutionen...) sowie unabhängig davon erstellte räumliche Phänomene (Postwege, Schiffsrouten...) erstellt;
* eine dynamische Webanwendung erstellt, mit der grundlegende Karten verschiedener Themen für jedes Jahr von 1701 bis 1808 visualisiert werden können (siehe Abbildung 1);
* Open-Access-Geometrien für spezialisierte Projekte und dienen somit als Ausgangspunkt für andere Projekte bereitgestellt;
* beispielhafte Karten für bestimmte Räume und Zeiten entwickelt und angeboten.

Die Architektur des WebGIS baut aktuell auf ein kommerzielles Produkt (ESRI) auf, dessen Lizenz nicht verlängert werden kann/wird (aufgrund von fehlenden Förderungen). Dennoch soll ein Betrieb des WebGIS weiterhin möglich gemacht werden – was aufgrund der Kostenbeschränkungen nur mir Open-Source Technologien möglich ist. 

{% 
    include figure.html 
    image="images/theses/msc_hgis/HGIS.jpg" 
    caption="Screenshot des WebGIS von HGIS de las Indias' 
%}

## Aufgabenstellung und Ziele
Ziel der Masterarbeit ist es – ausgehend von der aktuell existierenden Architektur von HGIS de las Indias eine Open-Source Systemarchitektur zu entwerfen, die Transition des gesamten Systems zu planen und schlussendlich zu implementieren. Besonderes Augenmerk wird auf die WebGIS Komponente gelegt. 
Der Ablauf der Arbeit umfasst folgende Schritte:
* Requirements Elicitation (mittels geeigneter Methoden [semi-strukturierte Interviews, …])
* Entwicklung der Systemarchitektur (fully open-source)
  * Räumliche Datenbank (objekt-relational)
  * CyberGIS / WebGIS unter Verwendung von OGC Standards (WMS/WFS) – wie zB geonode, OpenLayers, …
  * WebGIS Frontend (Leaflet, OpenLayers, …)
  * Linked Data Endpoint
* Entwicklung einer Migrationsstrategie für
  * Daten (räumlich / nicht-räumlich)
  * Prozesse
  * Backend
  * Frontend/UI
* Umsetzung und Implementierung 
  * Open-Source Architektur 
  * Backend Entwicklung/Integration
  * Frontend Entwicklung (i.e. WebGIS)
  * Migration vom bestehenden kommerziellen System in die neue Architektur (Daten, Prozesse, etc.)
* Evaluation: 
  * Strukturell/funktional: Anforderungen (Requirements) erfüllt?
  * User Experience Evaluation (i.e. mit AttrakDiff)


## Anforderungen 
Kenntnisse im Programmieren,
WebGIS & CyberGIS 
webbasierte Architekturen
Kenntnisse im Bereich konzeptionelle Datenbank Modellierung sowie Datenmigration 
Interesse im Bereich Semantic Web (Linked Data) 


## Kollaboration
{% 
    include figure.html 
    image="images/theses/msc_hgis/uni_graz_logo.png" 
    width="300px" 
%}
Universität Graz
Institut für Geschichte
Werner Stangl


