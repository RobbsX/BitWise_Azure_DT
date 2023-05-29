# BitWise
BitWise University Course Project - Digital Twin Implementation


<img width="521" alt="image" src="https://github.com/RobbsX/BitWise_Azure_DT/assets/79597633/878c128d-81bd-4c96-bb94-bb8b5f20e166">

We import telemetry data to our Digital Twin. That data is taken from the Wiener Linien API. On the Digital Twin, we conduct analysis and gain decision data. This decision data is then used for decisions for the Physical System. The Digital Twin’s static data is stored on the blockchain.

Why do we need the digital Twin?
We can monitor and analyse data. With that, we can derive decisions for the Physical System. These decisions are derived in real-time and can be used right away, and, thus, can be seen as highly critical data.


Twin Graph Prototye Implementation:


<img src="AzureDTExplorer with Real Time Data 2.png" width="600" />

<img src="AzureDTExplorer with Real Time Data.png" width="600" />


And here is the overview of the Model graph: 

<img src="AzureDTExplorer with Component.png" width="600" />

The Metadata File concerns the Vienna Transportation Dataset API. 

The client python file requests data from the API, gets it as a JSON and parses it. 
