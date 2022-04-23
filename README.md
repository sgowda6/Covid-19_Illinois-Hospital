DEscription:
The American Hospital Association is conducting a country wide  analysis to determine the COVID-19 precautions taken by hospitals around the United States via twitter data. In this project a total of 46 Illinois hospitals both rural and urban were taken into consideration. The total tweet dataset was about 11,000 dated from January 2020 to September 2020. The tools and techniques used were Twint for twitter data scraping, CorEx for topic modelling to find coherent meaningful topics measured across a corpus of text and finally an in depth exploratory analysis was performed to find the significant correlation between topics.A tweeting pattern that has made a considerable impact in generating awareness during COVID-19 by the hospitals is analysed.

CorEx
The principle of Cor-relation Ex-planation is a way to build rich representations that are informative about relationships in data, the two-thirds of the tweets collected by twint were manually segmented into topics and CorEx was then used for finding coherent meaningful topics measured across a corpus of text. 
The major dependencies of CorEx is it requires numpy and scipy, segmenting and topic modelling was done using two methods Unsupervised and Semi-Supervised learning.
Unsupervised topic modelling using CorEx is the way to generate a set of top ten  keywords for corresponding topics.
Semi-Supervised topic Modelling using CorEx uses manually generated keywords and the anchor key words topic which was generated in unsupervised learning which were mutually exclusive for every topic.

Used Exploratory Analysis to Predict Measures Hospitals should take to generate awareness
