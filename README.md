<h1>2021 Olympics ETL Pipeline using Microsoft Azure Services</h1>


<h2>Description</h2>
In this project, I developed a data pipeline to process and analyze data from the 2021 Tokyo Olympics using Azure's cloud ecosystem. 
The pipeline involved ingesting raw data into Azure DataLake Storage Gen2 with Data Factory, transforming it with PySpark in Azure Databricks, and storing the processed data in the same Datalake. 
Then Azure Synapse Analytics was used for efficient querying and analysis. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PySpark</b> 
- <b>SQL</b>
- <b>Data Factory</b>
- <b>DataLake Storage Gen2</b>
- <b>Azure Databricks</b>
- <b>Synapse Analytics</b>

<h2>Project walk-through:</h2>

<p align="center">
    <span style="font-size: 18px;">Create a container in Data Lake Gen2 to store the raw and transformed data</span> <br/>

    <img src="https://i.imgur.com/v2M9Wa0.png" height="80%" width="80%" />
    <br />
    <br />
    <span style="font-size: 18px;">Ingest the datasets using Data Factory</span> <br/>
    <img src="https://i.imgur.com/yLmv3fJ.png" height="80%" width="80%" />
    <br />
    <br />
    <span style="font-size: 18px;">Data transformations using Azure Databricks</span> <br/>
    <img src="https://i.imgur.com/za4PKW2.png" height="80%" width="80%" />
    <br />
    <br />
    <img src="https://i.imgur.com/oX6i5Le.png" height="80%" width="80%" />
    <br />
    <br />
    <span style="font-size: 18px;">Use Synapse Analytics to proceed with the querying and analysis</span> <br/>
    <img src="https://i.imgur.com/aa8DD0v.png" height="80%" width="80%" />
    <br />
    <br />
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
