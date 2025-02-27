# Real State Prices Predictor

This is a machine learning project designed to predict Real State prices in Bogota, Colombia. A web app is used as an interface to gather data and make predictions of new input.

# Data Set

The original data was obtained from the repository [bogota-apartments](https://github.com/builker-col/bogota-apartments/). The raw data used is V 1.3.0 and was downloaded from this [container](https://www.dropbox.com/scl/fi/63rkv8ehjcqogptpn06gp/builker.scrapy_bogota_apartmentsV1.3.0_october_1_2023.json?rlkey=wvwpyu3buy0ii84wxayywz8ot&dl=1) you can also download it from this [link](). A converted CSV file is added into this repository. Look for [IA-MODEL/data/builker_raw_data](). Or preprocess by your self using notebook [data-preprocessing.ipyht]().

The raw data was gathered using scrapping techniques from:
- [Metrocuadrado](https://www.metrocuadrado.com/)
- [Habi](https://habi.co/)

This dataset has relevant information about each porperty as: area, number of rooms, number of restrooms, property age, selling price, administration costs and others. 

The raw data has 68973 instances and 16 features(columns). key Features 
- precio_venta
- area
- habitaciones
- baños
- administracion
- parqueaderos
- sector
- estrato
- antiguedad
- estado
- longitud
- latitud

Acknowledgments: 
- @erik172 for the creation of Acknowledgments for the author of the book repository

# Exploratory Data Analysis (EDA)
- Data cleaning: Handling missing values and worng data codification.
- Outlier Detection: Identifying not congruent data, realted with prices and area
- Data transformation: Transforming categorical and scaling numerical features.

# Instalation and requirements
-----------
# models and experiments
-----------
# How to Use
-----------
# Results and Visualization
-----------
# Contact
-----------


