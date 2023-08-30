# Predicting-Lodging-severity-of-pea-using-machine-learning
Predicting the severity of lodging in dry peas using machine learning and RGB sensor



Description

[If you want to predict the severity of lodging in dry pea just using the RED, GREEN, and BLUE values and machine learning this tool helps you.]

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/697875e3-3dd1-45a1-8557-1762dd98b2be)

  
Table of Contents

•	Installation
•	Usage
•	Contributing
•	License

Installation

ARCGIS PRO

[Download the tool and csv folder, put csv folder in your C drive.]


[Go to the insert tab of your ArcGIS PRO project]

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/c42f324f-232f-4073-a2a2-463671b61d68)
 

[Select add folder and browse to the folder that you have saved your script and add that folder]

[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of LodgingSeverityPrediction.atbx, then open it to find the script]

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/fa3da501-7c97-4f24-8182-46b78e7bc32d)

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/b3e2176a-51ab-41c5-8c05-3badf92cfd33)

 

 

[Double click and open the script]

 ![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/00cb6bb6-784d-49f0-a845-03d5298f47bd)

[Call the input file (your new dataset that contain the value for RED, GREEN, values). Note: You should have an excel file and your data should be saved on the first sheet of that excel file. Your file should have the columns with the name of RED, GREEN, and BLUE with the format type of float 64.

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/f1cfc60d-0155-4c70-95a2-d63476dad109)

 

Before running the tool ,you should paste csv folder in your C drive directory to save the results on there. 

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/aad279c9-904e-4497-96f8-bed64f44c6e7)

 
Usage

If you want to predict the severity of lodging in dry pea just using the RED, GREEN, and BLUE values, this tool helps you

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/48a07759-d225-4b26-aaa1-adacc12d7b5a)

  
After running the tool, a new excel file with the name of rf_results.xlsx can be seen in the csv folder.

![image](https://github.com/AliBgisrs/Predicting-Lodging-severity-of-pea-using-machine-learning/assets/109620013/8ba0af8a-4d34-4c0c-ace5-2fb59ac400f6)

 
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

