# Portofolio Ilias Hazali
## [Datacamp Courses](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/Datacamp%20assignement.jpg)![](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/datacamp%20course%2015%20van%20de%2016.jpg)

Tijdens de minor heb ik een aantal Datacamp cursussen afgerond. [Hier](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/Datacamp%20assignement.jpg) en [hier](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/datacamp%20course%2015%20van%20de%2016.jpg) kunt een overzicht bekijken van de afgeronden cursussen en de bijbehorenden scoren. 

## Domain Knowledge
### Foodboost project
#### Situatie
Tijdens de minor heb ik gewerkt aan het project Food Boost. Aan het begin van het project heb ik eerst de opdracht omschrijving gelezen om de doestelling van het project beter te begrijpen. Het doel van de opdracht is om mensen te helpen hun voeding aan passen. Dat komt omdat in de laatste jaren steeds meer belangstelling is voor gezonder en duurzamer eten. Echter is het niet gemakkelijk om te bepalen of een recept duurzamer of gezonder is. Ieder persoon dient dus zijn eigen voeding en voedingsschema bij te houden om te kunnen concluderen of hij/zij gezonder of duurzamer eet en dat kost te veel tijd en energie. Dat heeft als gevolg dat mensen snel afhaken en zich niet meer bezig houden met een voedingsdieet. Voor de opdracht dient dus een onderzoeksdoel geformuleerd te worden, waar minimaal zes aan wordt gewerkt, die tot een oplossing kan leiden voor de probleemstelling.

#### Actie
Vervolgens ben ik online gaan oriënteren om te kijken of er al iets bekend is over de probleemstelling. Het eerste waar ik tegen aan liep is de Food Boost challenge. Volgens [Foodboostchallenge.nl](https://foodboostchallenge.nl/), is de challenge aangemaakt om jongen op een slimme manier , op school of tijdens hun dagelijkse leven, gezonder te laten eten en drinken. En dat willen ze bereiken door de ongezonde eetkeuze van jongeren te veranderen naar een gezonde keuze. Met dat informatie, kwam ik al met de voorstel om te voorspellen welke jongeren ongezond eten en om voor die doelgroep recepten te voorspellen die paste bij de dieet die ze kunnen volgen. Al heel snel bleek dat de datasets die we in bezit hadden niet geschikt waren om de voorspelling te kunnen doen. Ook online heb ik geen datasets kunnen vinden die geschikt waren voor dit onderzoeksdoel. Toen ben ik doorgegaan met literatuuronderzoek.

Vervolgens heb ik artikelen gevonden waarin een recept recommandatie wordt gedaan aan de hand van Aritifical Intelligence. Een aantal zijn:
-	[Improving Food Recipe Suggestions With Hierarchical Classification of Food Recipes]( https://www.diva-portal.org/smash/get/diva2:1192855/FULLTEXT02) Fathollahzadeh, P. (2018). Improving Food Recipe Suggestions with Hierarchical Classification of Food Recipes.
-	[Aanraden van een verscheidenheid aan recepten]( https://libstore.ugent.be/fulltxt/RUG01/002/946/124/RUG01-002946124_2021_0001_AC.pdf) Snyers, L., & Neirinck, P. Aanraden van een verscheidenheid aan recepten.
-	[Expert System for Recommendations of Healthy Food Recipes using machine learning]( https://web.p.ebscohost.com/abstract?direct=true&profile=ehost&scope=site&authtype=crawler&jrnl=13053515&AN=150195513&h=0RLoN%2bYfTvVskMH8ow%2bzAcNAAV9cCyvI%2fDP3sYvOy6RXbPgLfPClcTY5vQi98Cbzd0Xdez%2b94Qn4lIB7SnBRyg%3d%3d&crl=c&resultNs=AdminWebAuth&resultLocal=ErrCrlNotAuth&crlhashurl=login.aspx%3fdirect%3dtrue%26profile%3dehost%26scope%3dsite%26authtype%3dcrawler%26jrnl%3d13053515%26AN%3d150195513) Jhamat, N., Mustafa, G., Arshad, Z., & Abbas, R. (2021). Expert System for Recommendations of Healthy Food Recipes using machine learning. Ilkogretim Online, 20(5).

#### Resultaat
Nadat iedere groepslid literatuuronderzoek te hebben uitgevoerd, hebben we de onderzoeksdoel geformuleerd en dat is om voor mensen recepten aan te raden op basis van hun voorkeuren. Het is idee is een applicatie te bouwen die een tinder scherm weergeeft waar de gebruiker een aantal recepten naar links (geen voorkeur) of naar rechts (voorkeur) kan schuiven. Aan de hand van de recepten die de gebruiker als voorkeur heeft aangegeven wordt de favoriete keuken van een gebruiker bepaalt aan de hand van de ingrediënten waaruit die recepten bestaan. Vervolgens wordt, aan de hand van de ingrediënten van de gebruiker waar de voorkeurrecepten uit bestaan, een vergelijking gemaakt met de recepten binnen de voorkeurkeuken van dezelfde gebruiker en worden vier recepten aangetoond die het meest overeenkomen met de voorkeurrecepten.

#### Refelctie
In het begin ben ik niet op een geschikte ondoerzoeksdoel uitgekomen. Dat is het geval omdat ik te weinig aan literatuuronderzoek had gedaan en te haastig aan het project wou starten. Door alle verzamelde infortie op rijtje te hebben, heb ik een beter idee geregen over het onderzoek en zijn we als groep sneller op een onderzoeksdoel uitgekomen. in het vervolg zal ik geen overhaastebeslissingen nemen zonder voldoende literatuuronderzoek te hebben uitgevoerd en zal me meer verdiepen in het vinden van geralateerde onderzoek i.p.v. direct starten met het vinden van een oplossing.

## Data collection
### Foodboost
Voor het foodboost project zijn een aantal datasets beschikbaar gesteld door de opdrachtgever:
- [recipes.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/recipes.csv) een csv-bestand met de title van de recepten, de benodigde tijd dat voor een recept nodig is om te bereiden, de aantal calorieën van een recept, de aantal sterren dat een recept heeft gekregen, een link naar het recept en een foto van het recept.
- [ingredients.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/ingredients.csv) een csv-bestand waarin de ingredienten staan van 71808 recepten.
- [tags.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/tags.csv) een csv-bestand met de recepten en de bijbehordende tags.
- [nutritions.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/nutritions.csv) een csv-bestand met de soort nutrition van elke recept en de hoeveelheid daarvan.

### Container project
- [actions.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/actions.csv)  een csv-bestand met de informatie over waar een container naar toe wordt getransporteerd.
- [containerlocationinformation.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/containerlocationinformation.csv)
- [handling.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/handling.csv) een csv bestand met alle handelingen van de containers.
- [machine.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/machine.csv) een csv-bestand dat dat informatie geeft over de locatie over de containers. de locatie waar de container was en waar de container naar toe wordt verplaatst.
- [marker.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/marker.csv) een csv-bestand dat de indeling van de terminal definieert.een marker is een plaats in een stack waar je een container kan plaatsen. Alle posities en lengtes zijn in milimeters gedefinieerd.
- [stackentry.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/stackentry.csv] een csv-bestand waarin stack entry's worden gedefinieerd. een stack entry wordt uitgevoerd door stackcorrectie of handling
- [stacks.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/stacks.csv) een csv-bestand dat de indeling van de terminal definieert. Een stack is een specefieke block in een terminal. Alle posities en lengtes zijn in milimeters gedefinieerd.
- [readme.txt](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/readme.txt)

## Data preparation
### Food Boost
#### Situatie
Om het doel te kunnen behalen van het onderzoek, is een geschikte dataset nodig. Aan de hand van die dataset, moet de voorkeurkeuken van elke gebruiker voorspeld kunnen worden. De dataset dient een gebruikerssimulatie te zijn waarin voor elke gebruiker bekend is wat zijn voorkeurkeuken is en de ingrediënten staan van alle recepten die de gebruiker als voorkeur heeft meegegeven.

#### Actie
Als eerst heb ik de datasets op de notebook server geüpload. Vervolgens heb ik `pandas` gebruikt om de datasets in te lezen.
![image](https://user-images.githubusercontent.com/121435298/209831484-dabaa753-99d1-419b-a80f-27dce8eb3693.png)
Vervolgens heb alle dataset geinspecteerd en bekeken.
![image](https://user-images.githubusercontent.com/121435298/209832737-22526b11-1994-4d72-822d-3278b678e321.png)
![image](https://user-images.githubusercontent.com/121435298/209832877-1fc6f5d8-1c6b-46d8-94f5-d772731981f7.png)
De datasets zijn helaas niet direct geschikt om de voorspellingen te kunnen doen. Ik heb een aantal aanpassingen uitgevoerd op de datasets zodat ze overzichtelijker worden. Zo heb ik de kolom `Unnamed: 0` verwijdert omdat het toegevoegde waarde heeft op alle datasets.
![image](https://user-images.githubusercontent.com/121435298/209833690-ff9a23fc-de33-4bf3-97a4-120509f17911.png)
Daarna heb ik gekeken naar wat ik bij elke dataset om het overzichtelijker te krijgen. Voor de dataset `ingredients` heb ik gemerkt dat elke ingrediënt van een recept op een aparte rij staat.
![image](https://user-images.githubusercontent.com/121435298/209853073-cd6e8f44-e784-42e5-85f6-a6b8ebf56763.png)
Ik heb het gegroepeerd per recept en alle ingredienten op een rij geplaatst. Dat heb ik in een paar stappen gedaan. Als eerst heb ik gegroeperd per recept en vervolgend de `.agg()` methode gebruikt om de ingredienten bij elkaar te joinen. ![image](https://user-images.githubusercontent.com/121435298/209853540-b51aac7c-7273-4ab8-b8ef-5a0a20bf6ab3.png). De ingredienten staan nu bij elkaar per recepten staan allemaal bij elkaar in een kolom cel zoals te zien is op de foto hierboven. Mijn doel was daarna om elke ingrediënt in een aparte kolom te krijgen. Omdat dat niet in een keer kan, heb ik dat in een aantal stappen moeten doen. Eerst heb ik de `.str.split()` methode gebruikt op de `ingredient` kolom. Dat heeft geresulteerd in een panda serie waarin alle ingrediënten geschieden van elkaar. En dat heb ik vervolgens naar een dataframe omgezet.![image](https://user-images.githubusercontent.com/121435298/209854386-85bea458-e6ea-433e-9b7e-1ce82214ca20.png). Daarna







## Data Visualization

## Predictive Models

## Diagnostics of the learning process

## Evaluation
