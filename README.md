# Spatial-Infrastructure-Sustainability-Assessment-SISA-
This is a QGIS Plugin which is implemented based on the sustainability assessment framework designed in Dr. Mengmeng Liu's PHD dissertation (2019-05). It can help users evaluate sustainability of any defined object in multiple sustainability dimensions at different spacial scales.It provides components to define sustainability assessment objectives, to select indicators, to calculate the value of some indicators, to conduct multi-criteria decision analysis (pre-analysis, weighting, and aggregation of indicators), to evaluate the uncertainty and sensitivity of the assessment results, and to visualize sustainability evaluation results in multiple ways. 

The author mainly used Python to implement the data analysis functions and modules in the designed spatial sustainability assessment framework. The data visualization and some statistical analysis functions are implemented in Python and R. The spatial databased can be built by the open source PostgreSQL or SpatiaLite. All the processing functions related to the database are written in SQL. 

Before installing or using this plugin in QGIS, please install the software, packages or libraries (listed below) that support the framework and then to make some configurations following the instructions below.

-------
Software and Packages Support the Proposed Framework
Software	       Detail Information
QGIS 	           Version 2.18.21
Python	         Version 2.7
R	               version 3.5.2
PostgreSQL	     Need to be installed if users want to access PostGIS database from the proposed framework.
SpatiaLite	     Need to be installed if users want to access SpatiaLite database from the proposed framework.

-------
Python Packages:	
1)	qgis Python API
2)	numpy+mkl
3)	scipy
4)	pandas
5)	sciki-learn: version 0.19.0
6)	networkx
7)	igraph
8)	rpy2: version 2.7.8
9)	psycopg2: version 2.7.3.2
10)	pyodbc: version 3.0.7
11)	pyQT 4
-------
R packages:	
1)	ggplot2
2)	corrplot
3)	spdep, sp
-------

After installing all the software and packages listed above, users can copy the code folder (“SustainAssess”) into the following place: “..\.qgis2\python\plugins”. 
Then users open QGIS, under the menu “Plugins”, click “Manage and Install Plugins …”, the following window will open. 
In the “Search” textbox, type in “spatial sustainability assessment”, choose it and activate it. 
<img width="575" alt="Figure 3_21 Activate Spatial Sustainability Assessment Plugin in QGIS" src="https://user-images.githubusercontent.com/10712058/89110924-010da400-d41e-11ea-8065-9289841ecc38.png">

Close the plugin management window, back to the QGIS main view, you can see a menu named “Sustainability.
<img width="318" alt="Figure 3_22 Sustainability Menu in QGIS" src="https://user-images.githubusercontent.com/10712058/89110923-010da400-d41e-11ea-8498-8328b2b64b9c.png">

-------

Detail User Instructions for SISA can be found (https://github.com/helen-liu/Spatial-Infrastructure-Sustainability-Assessment-SISA-/issues/2#issue-671238231)
