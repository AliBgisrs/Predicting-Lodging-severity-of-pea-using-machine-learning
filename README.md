# Predicting-Lodging-severity-of-pea-using-machine-learning
Predicting the severity of lodging in dry peas using machine learning, RGB, and multispectral sensors




If you aim to forecast the severity of lodging in dry peas exclusively using RED, GREEN, and BLUE values with a Random Forest model, please utilize the 'LodgingSeverityPrediction' tool. Conversely, if your goal is to predict lodging scores in dry peas using RED, GREEN, BLUE, red edge, NIR bands, and crop height values in conjunction with an XGBOOST model, we recommend using the 'LodgingScorePrediction' tool.


![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/697875e3-3dd1-45a1-8557-1762dd98b2be)

  
Table of Contents

•	Installation
•	Usage
•	Contributing
•	License

Installation

ARCGIS PRO

[Download the tool and rf model (rf_model2.pkl).]


[Go to the insert tab of your ArcGIS PRO project]

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/c42f324f-232f-4073-a2a2-463671b61d68)
 

[Select add folder and browse to the folder that you have saved your script and add that folder]

[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of LodgingSeverityPrediction.atbx, then open it to find the script]

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/fa3da501-7c97-4f24-8182-46b78e7bc32d)

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/b3e2176a-51ab-41c5-8c05-3badf92cfd33)

 

 

[Double click and open the script]

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/0fb142fd-568b-411b-94c3-4266b0bf94be)

[Push the model directory to select the folder that rf_model2.pkl is located on there. Call the new data path to select a new excel dataset (your new dataset that contain the value for RED, GREEN, values). Note: You should have an excel file and your data should be saved on the first sheet of that excel file. Your file should have the columns with the name of RED, GREEN, and BLUE with the format type of float 64. Finally, define an output folder to save the results.

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/f1cfc60d-0155-4c70-95a2-d63476dad109)

 


 
Usage

If you want to predict the severity of lodging in dry pea just using the RED, GREEN, and BLUE values, this tool helps you

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/191c7034-b293-4cef-b6cb-326f3f4aae83)

  
After running the tool, a new excel file with the name of rf_results.xlsx can be seen in your directory folder.

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/22a4204b-6e41-4c9b-9cb2-67bca59a465c)

 
If you open that file, a new column has been created that shows the values of lodging severity from 0 to 2. Zero value means no lodging, 1 means slight lodging and 2 means severe lodging. The accuracy of the model that supports this script (Random Forest) is 89%.

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/5080e0d0-17d3-4f0a-81cd-da53dab31ac1)
 

Contributing

[Please run the script, use it, and help me to improve the performance of that script using your valuable suggestions.]

License

About the Author

[Developed by Aliasghar Bazrafkan.]

Acknowledgments

[I would like to express my sincere appreciation to my supervisor, Dr. Paulo Flores, from North Dakota State University (NDSU), for providing invaluable support and guidance throughout the development of this script. His expertise and encouragement have been instrumental in making this project possible].

Contact

[Aliasghar.bazrafkan@ndus.edu]


Additional Notes
[https://sites.google.com/ndsu.edu/floreslab/home?authuser=0]

