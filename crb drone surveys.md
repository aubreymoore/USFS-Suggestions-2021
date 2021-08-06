**USFS Project Suggestion, August 2021**

# Detection, Surveillance and Mapping of Coconut Rhinoceros Beetle Damage Using Automated Analysis of Drone Imagery

## Problem Definition

Coconut rhinoceros beetle damage, such as v-shaped cuts to fronds and bore holes in crowns, is distinctive and is easily detected by trained observers.

Bimonthy CRB damage surveys on Guam use an innovative method. High definition digital images are recorded along roadsides of all major routes at a rate of one per second by a smart phone attached to a vehicle. Later, a computer program developed using an artificial intelligence technique called *deep learning* examines every image, finds all coconut palms, measures CRB damage to each palm, and generates an interactive map which is published on the internet ([Click here to see an example map]()).

Roadside damage surveys are useful for rapid island-wide CRB damage monitoring on Guam. But use of aerial drone imagery would allow rapid automated surveys in off-road areas. Such a system my be key to success of eradication attempts, such as the one on Rota. In addition, this system could also be used for eraly detection monitoring.

## Proposal

Funding is requested to develop and test an automated system for detecting and mapping CRB damage to coconut trees using aerial drone imagery.

This work will build on an existing system which maps CRB damage using automated analysis of ground-based roadside video surveys which uses a smart phone mounted on a road vehicle for data acquisition. An automated image digital image analysis workflow uses an object detector which finds all coconut palms in each video frame and assigns a damage index (0-4 scale) to each palm. The damage index is based on a standard methodology used by CRB experts working on islands in the south Pacific. A second object detector counts v-shaped cuts in fronds (characteristic CRB feeding damage). Results are visualized using interactive web maps. For details on this ground-based CRB damage survey methodology see the attached file **roadside.pdf**.

Adapting this system to use aerial drone imagery will facilitate:

* CRB damage detection over large areas of remote, otherwise inaccessible, terrain
* early detection and delimiting surveys in rapid response projects on islands where CRB has not yet established, increasing chances of eradication
* monitoring temporal and spatial changes in CRB damage on islands where CRB has established
* measuring changes in CRB damage in response to biological control, sanitation, and other mitigation tactics

The major technical challenge in converting the existing system to use drone images instead of ground-based roadside images as input is retraining the deep learning object detectors. This task will be contracted out to Onepanel Inc., the tech company which developed the original CRB damage detectors. Estimated contract cost is $70,000.

The proposed aerial drone CRB damage survey method will be tested on Guam where a CRB biological control program is underway, and on the island of Rota, 35 miles north of Guam, where a CRB eradication project is underway.

The proposed project should be considered as a proof of concept trial. Future development, not included in the scope of work for this proposal, could lead to precise aerial pesticide application by drone to individual trees whenever new CRB damage is detected. Pesticide choice could include conventional insecticides, biological control agents for CRB (OrNV, *Metarhizium majus*), or an attracticide (CRB pheromone plus toxicant).

## Partners

* **PI:** Aubrey Moore, University of Guam
* **Cooperator:** Glenn Dulla, Guam Department of Agriculture
* **Cooperator:** Dallas Berringer, USDA-APHIS-PPQ, Guam
* **Cooperator:** Donald Scott, Onepanel Inc.
* **Cooperator:** Rota
* **Cooperator:** Michael Jordan, USFS, Guam

**Note: Listed partners have not yet confirmed cooperation.**

## Deliverables

* All software and documentation, including deep learning object detectors, will be free, open-source, and made available in a public GitHub repository
* A CRB early detection package be assembled and made available for use on American-affiliated Pacific Islands. The package will include a Mavic 2 Pro drone in a hard case and a laptop computer loaded with a *turn key* software package for converting drone imagery into damage survey maps. 

## Budget

$120,000
