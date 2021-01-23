# Let's Talk Data!
*Final Thinkful Capstone*
*by Kalika Kay Curry*


Marketing. Is. Tough.

Identifying a viable demographic - is no small feat.

Introducing, TalkData!

This project is to construct a product as a working machine learning model that can be used to predict the demographic of the individuals who have participated in this device plan. The plan provides the users' location coordinates, time they accessed the app, phone brand, phone model, applications that they're using, the category those applications belong to, and indicates whether or not the applications are in use.

The project is built using several Jupyter Notebooks. By seperating the process out over several files, I was able to progress faster - as my system is prone to frequent freezes/crashes while I determine the most amount of data I can process in a given time.

# Notebook Details

*  [Talkdata Analaysis and Presentation](https://github.com/KalikaKay/TalkData/blob/main/TalkData%20Analysis%20and%20Presentation.ipynb) 
> A presentable notebook outlying the methods and procedures used in creating the product.
* [Preprocessing](https://github.com/KalikaKay/TalkData/blob/main/Preprocessing.ipynb)
> The preprocessing part of the project. It includes all steps that were taken to obtain/provide a single datasource absent any unnecessary columns and with no null values.
* [Correrlation Matrix](https://github.com/KalikaKay/TalkData/blob/main/Correlation%20Matrix.ipynb) 
> Expanding on the preprocessing notebook, it includes a correlation matrix.
* [EDA](https://github.com/KalikaKay/TalkData/blob/main/EDA.ipynb)
> Exploratory data analysis workbook walks you through the analysis.
* [Model Selection](https://github.com/KalikaKay/TalkData/blob/main/Model%20Selection%20Gender.ipynb)
> Creates several models, performs a gridsearch, builds and chooses the parameters for the dimensionality reduction, and displays the results. Test are run on several supervised classification models and one unsupervised model. 
* [Performance Enhancing](https://github.com/KalikaKay/TalkData/blob/main/Performance%20Enhancing.ipynb) 
> Work done to further enhance the model performance. Additional models reviewed to check for balanced accuracy.
* [Group Classification](https://github.com/KalikaKay/TalkData/blob/main/Group%20Classification.ipynb) 
> The results from a group classification attempt using supervised learning models. This attempt was revisits; receiving more succesful results after moving in a different direction. 
* [Deep_Learning-Gender](https://github.com/KalikaKay/TalkData/blob/main/Deep_Learning_Gender.ipynb)
> Classification on gender using a deep neural network. 
* [Exercise_Deep_Learning_Convolutional](https://github.com/KalikaKay/TalkData/blob/main/Exercise_Deep_Learning_Convolutional.ipynb)
> Classification using a convolutional neural network. 
* [gender.pdf](https://github.com/KalikaKay/TalkData/blob/main/gender.pdf)
> print out of the gender classification decision tree.
* [gender](https://github.com/KalikaKay/TalkData/blob/main/gender)
> a text representation of the classification decision tree.
* [Deep Learning Demographic Predictions](https://github.com/KalikaKay/TalkData/blob/main/Deep_Learning_Demographic_Prediction.ipynb) 
> Uses the model built in the deep learning gender notebook to predict the ages, adds these results to the the gender learning's test dataset, and uses that information to predict users' demographcis.
* [GeoPlot](https://github.com/KalikaKay/TalkData/blob/main/GeoPlot.png)
> A map of the users access by location.

