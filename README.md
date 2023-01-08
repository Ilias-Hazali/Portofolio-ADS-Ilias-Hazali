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

#### Reflectie
In het begin ben ik niet op een geschikte onderzoeksdoel uitgekomen. Dat is het geval omdat ik te weinig aan literatuuronderzoek had gedaan en te haastig aan het project wou starten. Door alle verzamelde informatie op rijtje te hebben, heb ik een beter idee geregen over het onderzoek en zijn we als groep sneller op een onderzoeksdoel uitgekomen. in het vervolg zal ik geen overhaaste beslissingen nemen zonder voldoende literatuuronderzoek te hebben uitgevoerd en zal me meer verdiepen in het vinden van gerelateerde onderzoek i.p.v. direct starten met het vinden van een oplossing.

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
- [marker.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/marker.csv) een csv-bestand dat de indeling van de terminal definieert. Een marker is een plaats in een stack waar je een container kan plaatsen. Alle posities en lengtes zijn in millimeters gedefinieerd.
- [stackentry.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/stackentry.csv] een csv-bestand waarin stack entry's worden gedefinieerd. een stack entry wordt uitgevoerd door stackcorrectie of handling
- [stacks.csv](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/stacks.csv) een csv-bestand dat de indeling van de terminal definieert. Een stack is een specifieke block in een terminal. Alle posities en lengtes zijn in millimeters gedefinieerd.
- [readme.txt](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/readme.txt)

## Data preparation
### Food Boost
#### [Eigen dataset gesimuleerd](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/zelf%20een%20Dataset%20simuleren.pdf)
#### Situatie
Om het doel te kunnen behalen van het onderzoek, is een geschikte dataset nodig. Aan de hand van die dataset, moet de voorkeurkeuken van elke gebruiker voorspeld kunnen worden. De dataset dient een gebruikerssimulatie te zijn waarin voor elke gebruiker bekend is wat zijn voorkeurkeuken is en de ingrediënten staan van alle recepten die de gebruiker als voorkeur heeft meegegeven.

#### Actie
Als eerst heb ik de datasets op de notebook server geüpload. Vervolgens heb ik `pandas` gebruikt om de datasets in te lezen.

![image](https://user-images.githubusercontent.com/121435298/209831484-dabaa753-99d1-419b-a80f-27dce8eb3693.png)

Vervolgens heb alle dataset geïnspecteerd en bekeken.

![image](https://user-images.githubusercontent.com/121435298/209832737-22526b11-1994-4d72-822d-3278b678e321.png)
![image](https://user-images.githubusercontent.com/121435298/209832877-1fc6f5d8-1c6b-46d8-94f5-d772731981f7.png)

De datasets zijn helaas niet direct geschikt om de voorspellingen te kunnen doen. Ik heb een aantal aanpassingen uitgevoerd op de datasets zodat ze overzichtelijker worden. Zo heb ik de kolom `Unnamed: 0` verwijdert omdat het toegevoegde waarde heeft op alle datasets.

![image](https://user-images.githubusercontent.com/121435298/209833690-ff9a23fc-de33-4bf3-97a4-120509f17911.png)

Daarna heb ik gekeken naar wat ik bij elke dataset kan doen om het overzichtelijker te krijgen. Voor de dataset `ingredients` heb ik gemerkt dat elke ingrediënt van een recept op een aparte rij staat.


![image](https://user-images.githubusercontent.com/121435298/209853073-cd6e8f44-e784-42e5-85f6-a6b8ebf56763.png)


Ik heb het gegroepeerd per recept en alle ingrediënten op een rij geplaatst. Dat heb ik in een paar stappen gedaan. Als eerst heb ik gegroepeerd per recept en vervolgend de `.agg()` methode gebruikt om de ingrediënten bij elkaar te joinen.![image](https://user-images.githubusercontent.com/121435298/209857310-727e4cbe-1022-4297-ad81-79d7f8f9c4c4.png)De ingrediënten staan nu bij elkaar per recepten  in een kolom cel zoals te zien is op de foto hierboven. Mijn doel was daarna om elke ingrediënt in een aparte kolom te krijgen. Omdat dat niet in een keer kan, heb ik dat in een aantal stappen moeten splitsen. Eerst heb ik de `.str.split()` methode gebruikt op de `ingredient` kolom. Dat heeft geresulteerd in een panda serie waarin alle ingrediënten geschieden van elkaar. En dat heb ik vervolgens naar een dataframe omgezet.![image](https://user-images.githubusercontent.com/121435298/209857565-d28b52ba-6f27-4525-b054-a8f2795e0de3.png) Daarna heb ik de kolom `recipe` uit de gegroepeerde dataset gefilterd. ![image](https://user-images.githubusercontent.com/121435298/209864011-88b8114e-4fd0-4bd1-b3bc-e81c04002f9d.png)
Dat heb ik gedaan zodat ik later `recipe` en `recipe_ingredients` aan elkaar kan samenvoegen. Dat resulteerde in het volgende dataframe: ![image](https://user-images.githubusercontent.com/121435298/209864064-7352a098-01d1-40e6-95a2-976e54a1a01b.png)

Voor de `tags` dataset heb ik bijna het zelfde gedaan. Eerst heb ik de kolom `Unnamed: 0` verwijdert daarna gegroepeerd met recipe en de tags bij elkaar samen gevoegd en dat heeft geresulteerd in het volgende dataframe: ![image](https://user-images.githubusercontent.com/121435298/209864281-8c3bf52b-0378-48f8-8ccb-a3eeb58ad8b4.png)

Ik heb nu een dataset gecreëerd waar de recepten met de bijbehorende tags en ingrediënten. Helaas kan ik met de dataset nog geen voorspellingen doen omdat de benodigde dataset uit `1` en `0` moet bestaan of categorische variabelen. Milan had op het moment dat ik nog bezig was met de data voor te bereiden al een dataset klaarstaan die we later hebben gebruikt om voorspellingen te kunnen doen en die ziet er als volgt uit: 

![image](https://user-images.githubusercontent.com/121435298/211157890-ee16ddef-0a97-4bc6-933e-23f3c3ed7b93.png)

De [dataset](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/userdata.csv) heeft de juiste formaat om de voorspellingen te kunnen doen. Maar na  het inspecteren, bleek dat de dataset nog wel aanpassingen nodig had om goede voorspellingen te kunnen doen. Zo hebben we besloten om de ingredienten en de tags waarvan de som van de rij niet mee te nemen bij de voorspellingen. Dat heb ik als volgt gedaan:
Eerst heb ik de dataset geupload en geïnspecteerd.

![image](https://user-images.githubusercontent.com/121435298/211158440-79379e8c-d047-45f1-929d-1d2372c5beeb.png)

Vervolgens de kolom 'user_id' verwijdert omdat het geen toegevoegde waarde had op de dataset.

![image](https://user-images.githubusercontent.com/121435298/211158555-943b4a4f-d2f2-4f86-8c9b-86ed100f1311.png)

Daarna heb ik de som genomen van alle rijen van de dataset om te kijken hoe vaak een ingredïent/tag voorkomt. Ik heb daarbij een plot gemaakt die de frequenties duidelijk zou weergeven, maar door de grote aantal kolom die de dataset bevat is het zeer onoverzichtelijk geworden en heb ik besloten om het op een andere manier te doen.

![image](https://user-images.githubusercontent.com/121435298/211161488-9f7dc567-8761-431a-bf17-3f0fc906f3e3.png)


Er bleek dat 542 van de 847 ingredienten/tags een totaal hadden die lager zijn dan 40. Na het verwijderen van al die kolommen hielden we 304 ingrediënten die vaker voorkomen en die we konden gebruiken om voorspellingen te doen. 

![image](https://user-images.githubusercontent.com/121435298/211158870-27cf72c1-b911-4cdb-be68-056578f93f30.png)

De andere kolomen heb ik een lijst gezet en verwijdert uit de oorspronkelijke dataset.

![image](https://user-images.githubusercontent.com/121435298/211161327-5e70d952-f37b-449e-a4a6-3c28ef2033df.png)

![image](https://user-images.githubusercontent.com/121435298/211161337-b282b4f9-b783-4dd4-a894-60cd7836be2e.png)


Klik [hier](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/userdata%20preparation.pdf) om de volledige pdf versie te bekijken van de aanpassing op de dataset die Milan heeft gecreerd.

Later zijn we nog doorgegaan met een andere dataset die uit meer rijen bestond en minder kolommen bevatte. Dat laatste komt doordat we de dataset hebben gefilterd en we hebben gekozen om door te gaan met data van de wereldkeukens die het meest voorkomen.
![image](https://user-images.githubusercontent.com/121435298/211208845-32b2be4e-055b-4fef-b126-58eb6b7ca9f2.png)



#### Reflectie
Op het moment dat Milan de gebruikerssimulatie al klaar had staan, had ik het gevoel dat ik over te weinig `pandas` kennis beschik. Ik heb sindsdien meer Datacamp courses uitgevoerd zodat ik mijn programmeer vaardigheden kan verbeteren. Ik heb veel geoefend met dataframes en ik heb nieuwe `pandas` technieken wat mij heeft geholpen verder te werken aan de dataset. Zo heb ik geleerd hoe ik dataframes beter kan bewerken door ze eerst goed te inspecteren en te prepareren en in het vervolg zal ik dezelfde methode aanhouden op het moment dat ik over te weinig kennis beschik om een onderzoek te kunnen uitvoeren. 


## Predictive Models









## Data Visualization



## Diagnostics of the learning process

## Evaluation
