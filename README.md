# RefactorProject

It takes a monolithic application and its clustering metadata, and:
1. Creates clusters with the meta data recommendation.
2. Computes the movable subgraphs and API candidates.
3. Relocates the subgraphs based on the isolation information and reduces cross-cluster dependencies.

**Folders and their contents**

jpt: Contains the source code of the project.

Results: Contain the generated microservice clusters for five applications (DayTrader, Acmeair, PetClinic, PlantsByWebsphere, and Mayocat). 

Respective folder for each application in the results also contains computed metadata and a screenshot of experimental result.
