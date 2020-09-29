# Collision Severity Background

Accidents in traffic lead to associated fatalities and economic losses every year worldwide and thus is an area of primary concern to Society from loss prevention point of view. In Great Britain, recent statistics showing that there are nearly 3 deaths per 100,000 people, for all road users. Motorways are potential sites of fatal highway accidents in UK. The accident data analysis, visualization and better accident severity prediction models will be helpful in enhancing the safety performance of road trafﬁc system. Traffic accidents are generally classified into fatal, serious and slight accidents based on their severity. Each accident severity has some pattern relation with accident related physical features such as accident location, weather conditions, light conditions, season, month, day, time, driver experience etc.
  Modelling accident severity prediction and improving the model are critical to the effective performance of road traffic systems for improved safety.
In accident severity modelling, the input vectors are the characteristics of the accident, such as driver behavior and attributes of vehicle, highway and environment characteristics while the output vector is the corresponding class of accident severity.
There are two main engineering approaches for dealing with traffic safety problems: the reactive approach and the proactive approach. The reactive approach, or retrofit approach, consists of making the necessary improvements to variable, for instance, taking necessary actions at identified hazardous sites in order to reduce collision frequency and severity at these sites. The proactive approach, on the other hand, includes a collision prevention approach, like, preventing a potential unsafe road conditions from occurring in the first place.
  We focus on proactive approach which involves prediction of accident severity and working backwards, the concerned entity implements appropriate preventive measures to improve road safety. By recognizing the key factors that influence accident severity, the solution may be of great utility to various Government Departments/Authorities like Police, R&B and Transport from public policy point of view. The results of analysis and modelling can be used by these Departments to take appropriate measures to reduce accident impact and thereby improve traffic safety. It is also useful to the Insurers in terms of reduced claims and better underwriting as well as rate making.

# Description of the data and use

The dataset is taken from Kaggle - UK roads safety: Traffic accidents and vehicles. The dataset contains around 0.194 million records and 37 columns. We will do data cleaning and preprocessing. The data corresponding to slight severity is 84.84%, serious severity is 13.86% and for fatal severity is 1.30%. In addition to severity information, the data contains information regarding accident characteristics (accident occurrence time and accident location), vehicle characteristics (vehicle type involved and vehicle condition), environmental factors (weather condition and visibility distance), and road conditions (pavement condition, road geometrics and roadway surface condition, etc.).
Previous studies indicated that the factors associated with accident severity mainly include road characteristics, accidents characteristics, vehicle characteristics, driver characteristics, and environmental factors.  Several processing techniques as under sampling and oversampling will tried. Our main aim is to predict the serious and fatal severity with high precision and F1 score. Seven different classifiers will be tried on this dataset. 

Data Pre-Processing:
Data preprocessing is an important stage for handling the data before using it in the data mining algorithms. This process involves various steps, including cleaning, normalization, feature selection, transformation. 

Dataset Description: 
1.	Number of Vehicles - Number of Vehicles involved in an accident 
2.	Number of Casualties - Number of Casualties involved in an accident 
3.	Road Type 1: Roundabout 2: One-way street 3: Dual carriageway 4: Single carriageway 5: Slip 
4.	Road Speed limit - The Speed limitation of the road where the accident happened 
5.	Light Conditions 1: Daylight 2: Darkness - lights lit 3: Darkness - lights unlit 4: Darkness - no lighting 5: Darkness - lighting unknown 
6.	Road Surface Conditions 1: Dry 2: Wet or damp 3: Snow 4: Frost or ice 5: Flood over 3cm. deep 6: Oil or diesel 7: Mud 8: Data missing or out of range 
7.	Weather Conditions 1: Fine no high winds 2: Raining no high winds 3: Snowing no high winds 4: Fine and high winds 5: Raining and high winds 6: Snowing and high winds 7: Fog or mist 8: Other 9: Unknown 
8.	Urban or Rural Area 1: Urban 2: Rural 

Accidents are classified into 2 categories: 1. Fatal 2. Slight
