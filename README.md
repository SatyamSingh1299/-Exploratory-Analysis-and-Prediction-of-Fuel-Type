# Title: Exploratory Analysis and Prediction of Fuel Type

Data Citation: Global Powerplant Database, World Research Institute.
URL: http://datasets.wri.org/dataset/globalpowerplantdatabase






## Abstract:
In a world where energy is the epicenter of human civilization, people must understand energy needs. When the energy needs are accounted for, there will be a need to find a method to generate more energy. On that note, many new power plants have been established. Currently, there are around 35000 known power plants all around the globe. Keeping track of these power plants has now become essential to identify and reallocate the need for the establishment of new plants. However, it is a known fact that various types of power plants convert energy from various fuel types. As such, after identifying that there is a need for the establishment of a new power plant, there also is a need to decide on the type of plant to be established. 

All of these decisions now fall into the hands of a data analyst who has to identify the optimal need for the plant. There have been many Machine Learning models that can identify the need for more energy. However, Little research has been done to make a model that identifies the type of plant being established. This project is to analyze previous data on most of the available plants in the world and use the EDA to prepare a model that can predict the type of plant that can supposedly be established without the intervention of the human intellect. This model accelerates the process to identify the types of plants that need to be established and suggests a type of power plant depending on the capacity, required generation rates, location, etc., This potentially can accelerate and simplify the decision-making process for establishing power plants.





## Package Description:
The "Exploratory Analysis and Prediction of Fuel Type" comes in a package of 4 files.
- 'global_powerplant_database.csv': The data used for the project.
- 'AIT614_Final_proj_code_EDA.html': The code for the exploratory data analysis on the data.
- 'AIT614_Final_proj_code_EDA.ipynb': EDA Code for cross compatibility with other platforms.
- 'AIT614_Final_proj_code_ML.html': The code for Machine Learning model on the data.
- 'AIT614_Final_proj_code_ML.ipynb': ML Code for cross compatibility with other platforms
- 'README.txt': This file Containing the instructions on how to successfully run the code.




Link for Video instructions on setting up DataBricks Community User account:

https://youtu.be/QvBCsB0nm50





## Instructions for setting up the Databricks Workspace and running ML code:
1. Create 11.3 LTS cluster from the create tab by selecting the version from the dropbox after entering into the DataBricks platform. (Note: It might take a while for the cluster to be up and running)
2. Open a New Notebook and then import the 'AIT614_Final_proj_code_EDAs.html' file using the "Import Notebook" option from the file tab attaching the created 11.3 LTS ML cluster 
3. Now using the "Upload data to DBFS" option in file, upload the CSV file "global_powerplant_database.csv" to the dbfs and copy the pyspark version of the dataframe calling snippet code. and click done.
4. Replace the copied code with the code in the 4th command or "cmd 4".




## Instructions for setting up the Databricks Workspace and running ML code:

1. Create a 7.3 LTS ML cluster from the create tab by selecting the version from the dropbox after entering into the DataBricks platform. (Note: It might take a while for the cluster to be up and running)
2. Open a New Notebook and then import the 'AIT614_Final_proj_code_ML.html' file using the "Import Notebook" option from the file tab attaching the created 7.3 LTS ML cluster 
3. Now using the "Upload data to DBFS" option in file, upload the CSV file "global_powerplant_database.csv" to the dbfs and copy the pyspark version of the dataframe calling snippet code. and click done.
4. Replace the copied code with the code in the 4th command or "cmd 4", also include
",inferSchema = "true"" within load ro ensure the schema is also considered.
5. Press Run all to run all the code and observe the results.

Note: The snippet "cmd 24" takes about 20 to 30 minutes to successfully execute.







## References:
[1]https://www.statista.com/study/48975/energy-production-in-the-united-states/?locale=en 

[2]https://www.statista.com/study/74593/electricity-worldwide/

[3]https://www.vertex42.com/ExcelTemplates/simple-gantt-chart.html?utm_source=ms&utm_medium=file&utm_campaign=office&utm_content=url
