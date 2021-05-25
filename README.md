# Covid-19-Cases-on-World-Map-Batch-Processing-
## Description 📌
In this project i have read last one year covid-19 data(Confirmed,Recovered,Deaths) for each country datewise, processed it and performed some aggregation on it and stored processed data into mysql and visualized it on the world map.
### steps how to perform this.
1 setup hadoop hdfs and yarn to store the data into hadoop \
2 fetch the data from hadoop using spark. \
3 write spark application to perform aggregation on it. \
4 store the processed data into mysql. \
5 setup grafana into your local system and add worldmap plugin into it. \
6 visualize the processed data which is saved in mysql on grafana.
## Screenshots and result
<img src="https://github.com/itsvikas0304/Covid-19-Cases-on-World-Map-Batch-Processing-/blob/main/images/p3.PNG">
<img src="https://github.com/itsvikas0304/Covid-19-Cases-on-World-Map-Batch-Processing-/blob/main/images/p1.PNG">
<img src="https://github.com/itsvikas0304/Covid-19-Cases-on-World-Map-Batch-Processing-/blob/main/images/p2.PNG">

## data sources
* https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
* https://github.com/datasets/covid-19/tree/main/data

