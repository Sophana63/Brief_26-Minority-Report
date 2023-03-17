# Brief 26 - Minority Report, Rapport de Dashboard Power BI

<p>Ce dépôt contient trois rapports de dashboard Power BI créés pour différentes missions.</p>

## <span style="color: #FF8C00">Mission 1 : Dashboard de l'équipe d'innovation</span>

Ce rapport de dashboard est destiné à une équipe d'innovation travaillant sur plusieurs projets. Le rapport est conçu pour être présenté à l'équipe de direction. Le rapport de dashboard comprend des données de trois fichiers CSV : achats.csv, impressions.csv et clics.csv. Le rapport visualise les données de ces fichiers pour fournir des informations sur le travail de l'équipe.

Le rapport se trouve dans le dossier mission 1:
- `/01_INPUT_DATA`: achats.csv, impressions.csv et clics.csv
- `/02_RAPPORT`: le modèle au format PowerBi
- `/03_OUTPUT_DATA` : [le fichier pdf](/mission1/03_OUTPUT_DATA/mission1.pdf)

Lien vers le site internet : [app.powerbi.com](https://app.powerbi.com/links/OKSFUQFwlD?ctid=a2e466aa-4f86-4545-b5b8-97da7c8febf3&pbi_source=linkShare)

<hr>

## <span style="color: #FF8C00">Mission 2 : Dashboard de consultation nationale</span>

Ce rapport de dashboard a été créé pour le gouvernement français afin de visualiser les données d'une consultation nationale. Le rapport se concentre sur l'un des thèmes de la consultation et fournit des visualisations pour le nombre de contributions au fil du temps et la répartition des contributions par département. De plus, le dashboard comprend deux filtres pour filtrer les données par type d'auteur et par département.

Le rapport se trouve dans le dossier mission 2:
- `/data`: les données **cr-ril(1).json** (pour les départements) et **events-1-.json** (pour les auteurs)
- `/ouput`: [le fichier pdf](/mission2/output/mission2.pdf)
- `/` : le modèle au format PowerBi (mission2.pbix)

Lien vers le site internet : [app.powerbi.com](https://app.powerbi.com/links/ytyxf6ZEoI?ctid=a2e466aa-4f86-4545-b5b8-97da7c8febf3&pbi_source=linkShare)


<hr>

## <span style="color: #FF8C00">Mission 3 : Dashboard d'accès à l'eau potable dans le monde</span>

Ce rapport de dashboard a été créé pour une ONG ayant pour ambition de donner accès à l'eau potable à tout le monde. Le rapport présente une vue globale de l'accès à l'eau potable dans le monde. Il permet de choisir le pays à cibler une fois que le bailleur de fonds aura donné sa réponse sur le domaine d'expertise qu'il souhaite financer. Le rapport de dashboard comprend des visualisations pour la qualité de l'eau, la disponibilité de l'eau et l'accès à l'eau potable dans différents pays.

Le rapport se trouve dans le dossier mission 3:
- `/donnees_eau_portable`: les données en CSV dont un en xlsx (Dictionnaire de données.xlsx qui n'est pas utile)
- `/`: visualisation : [le fichier pdf](/mission3/mission3.pdf)
- `/` : le modèle au format PowerBi (mission3.pbix)

### La mission 3 contient 2 pages

`Page 1` : Vue mondiale avec une agrégation des indicateurs au niveau mondiale (par continent) avec les indicateurs suivants:

1. le taux de mortalité dû à de l’eau insalubre
2. Rapport d’habitants ayant accès à l’eau potable
3. Morts dû à l'eau insalubre
4. Stabilité politique 

`Page 2` : une vue mondiale avec une agrégation des indicateurs pour le continent ou le pays sélectionnés par l’utilisateur:

1. la population / densité de population 
2. la population totale par année
3. Rapport Femme/Homme
4. Rapport Rural/Urban
5. la population par pays
6. Rapport entre 
    - Population utilisant au moins les services d'eau potable de base
    - Population utilisant des services d'eau potable gérés en toute sécurité
    - Taux de mortalité dû à de l’eau insalubre


Lien vers le site internet : [app.powerbi.com](https://app.powerbi.com/links/6vtwBtAW0u?ctid=a2e466aa-4f86-4545-b5b8-97da7c8febf3&pbi_source=linkShare&bookmarkGuid=4cb63d04-a3d2-4860-94e3-d616e4aecf05)