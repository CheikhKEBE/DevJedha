# kayak
L'objectif est de mettre en place un programme permettant de donner aux touristes le maximum d'informations sur leurs futures lieux de vacances : temps, hotels,...
Pour ce faire, nous allons utiliser les techniques de scrapping, la récupérations des données via API, visulaiser les données via plotly et les stocker dans un datalake S3.


### Préalable
Faut d'abord exécuter le spider cities, comme suit : scrapy crawl cities -o cities.json afin de généner cities.json qui sera utilisé dans Plan_your_trip_with_Kayak.ipynb
