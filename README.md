# Characters’ Networks in Fanfiction: Exploring Characters Adaptations and Evolution through Networks
**Author**: Jiaming Chen  
**Supervisor**: Federico Pianzola  
**Program**: Master of Digital Humanities, University of Groningen  
**Date**: August 31, 2024
## Overview

This thesis investigates how fanfiction writers adapt and evolve character relationships from the original canon using computational network analysis. 

Using 97 fanfictions based on the cult film *The Rocky Horror Picture Show* from AO3, I constructed character co-occurrence networks with three different methods (text window co-occurrence, dialogue-based, and verb-based interactions) and compared them with the original movie character network. The study combines **distant reading** (network analysis + image clustering) with **close reading** to explore character adaptations, centrality shifts, and interaction patterns in fanfiction.

## Key Contributions

- Developed three distinct methods for constructing character networks from textual data, incorporating NLP (spaCy) for entity and verb extraction.
- Applied network metrics (centrality, density, community detection) and visual clustering to analyze character prominence and relationship changes.
- Demonstrated that fanfiction tends to preserve core relationships while elevating secondary characters and emphasizing action-oriented interactions.
- Reflected on the strengths and information loss in abstracting narratives into networks — a mixed-method practice bridging close and distant reading.

## Technologies & Methods

- **Programming**: Python
- **Text Processing**: spaCy, custom character name & verb dictionaries
- **Network Analysis**: NetworkX 
- **Visualization**: Network graphs + image clustering
- **Data Source**: AO3 fanfiction corpus (97 stories) + movie character network datas


## A brief description of the contents of the files in the folder.
1. The characternetwork data of movie: The Rocky Horror Picture show.json
2. The verbs identified by spaCy as the "root" in a sentence structure in 97 fanfictions.:Root_dic_verbs.json
3. Signed score based on verbs catergories:ROOT_dic_verbs_score.json
4. The 97 fan fictions data: originalwork_txt.zip
5. Verbs classification result: verb_cater_1.json

## For the code:
Due to the large file size, we can't upload the code directly at once, so we upload a sample code for each method of building the network, aslo the zip files accordingly. Since we're just running the same code on different stories in each method.  
Method 1：An example of Creating a  character network based on Co-occurrence in text window.  
Method 2: An example of Creating a  character network based on characters; dialogue.  
Method 3.1:An example of Creating a  character network based on Root verbs.  
Method 3.2:An example of Creating a  character network based on verb types.  

