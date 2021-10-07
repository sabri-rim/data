# Data
Cette base de donnée represente les séries chronologiques quotidiennes lors du COVID , y compris les cas confirmés, les décès et les guérisons à partir du 13 février 2020 jusqu'au 04/10/2021.
ce jeux de données permet le suivis quotidien au pays nous donnant le dernier nombre de cas différents (actifs, confirmés, décès, guéris, etc.) pour différents pays/ régions du monde.

# Variables 
Province_State - Le nom de l'État aux États-Unis.

Country_Region - Le nom du pays (États-Unis).

Last_Update - La date la plus récente à laquelle le fichier a été envoyé.

Lat - Latitude.

Long_ - Longitude.

Confirmé - Nombre de cas agrégé pour l'état.

Décès - Nombre total de morts pour l'État.

Récupéré - Nombre de cas récupérés agrégé pour l'état.

Actifs - Cas confirmés agrégés qui n'ont pas été résolus (cas actifs = total des cas - total récupéré - total des décès).

FIPS - Code Federal Information Processing Standards qui identifie de manière unique les comtés aux États-Unis.

Incident_Rate - cas pour 100 000 personnes.

Total_Test_Results - Nombre total de personnes qui ont été testées.

People_Hospitalized - Nombre total de personnes hospitalisées. 

Case_Fatality_Ratio - Nombre de décès enregistrés * 100/ Nombre de cas confirmés.

UID - Identificateur unique pour chaque entrée de ligne.

ISO3 - Identificateurs de codes de pays officiellement attribués.

Testing_Rate - Total des résultats des tests pour 100 000 personnes. Les « résultats totaux des tests » sont égaux aux « Résultats totaux des tests (positifs + négatifs) » de COVID Tracking Project .

Hospitalization_Rate - Taux d'hospitalisation aux États-Unis (%) : = Nombre total d'hospitalisations / Nombre de cas. Le "Nombre total d'hospitalisations" est le nombre "Hospitalisé - Cumulatif" du COVID Tracking Project . Le « taux d'hospitalisation » et le « Nombre total d'hospitalisations » ne sont présentés que pour les États qui fournissent des données hospitalières cumulatives. 


# Exemple d'utilisation : 
# Tableau de bord creer par cette base de donnée 
https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6
https://public.tableau.com/profile/harshit.tyagi#!/vizhome/covid_book/Dashboard 


# Visualiser les 10 pays les plus touchés par le COVID
![image](https://user-images.githubusercontent.com/73078692/136005360-9ba0b672-5461-4a39-b214-274d53044698.png)





![image](https://user-images.githubusercontent.com/73078692/135878316-7f95e7d6-c88f-4942-a8b9-6613e80bfada.png)





![image](https://user-images.githubusercontent.com/73078692/136005986-c65b5148-1c95-49fe-8ebb-9c6fab572f81.png)


# Source : 
https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases


Il s'agit du référentiel de données du tableau de bord visuel du nouveau coronavirus 2019 exploité par le Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE). Également, soutenu par l'équipe ESRI Living Atlas et le laboratoire de physique appliquée de l'Université Johns Hopkins (JHU APL).
https://github.com/CSSEGISandData/COVID-19
