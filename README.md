# Selective_Color_Naming
Final project for SI 699: Big Data Analytics. 


The flowers folder contains the images from the publicly available research dataset by Maria-Elena Nilsback and Andrew Zisserman which were used in the survey and project analysis. 

The Color Naming folder contains resources made available on Joost van der Weijer's website, related to the research paper by van de Weijer, Schmid, and Verbeek in 2007, "Learning Color Names from Real-World Images". 

There are three code files in the form of Jupyter Notebooks (.ipynb).The libraries required to run this project in full are pandas, numpy, cv2, and matplotlib. 

The first code file to run is the 699_image_processing file, which contains code to read the images and perform image segmentation using OpenCV and apply color name labels using the color naming reference chart. 

The second code file is the 699_label_creation file, which uses the image data from the first file as well as the results of surveying human participants (stored in pick2-results.csv) to produce two color name labels per image. Four different programmatic strategies are used, in addition to human labels derived from the survey data. 

The third code file is the 699_scoring_and_analysis file. This file will produce scores out of 4 based on the accuracy of the computer labels compared to the human labels. The code also produces a summary bar graph and visually displays the foreground and background segmentation of three images. 
