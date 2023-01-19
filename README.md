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
#### [Eigen dataset gesimuleerd](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/zelf%20Dataset%20simuleren%20final%20pdf.pdf)
#### Situatie
Om het doel te kunnen behalen van het onderzoek, is een geschikte dataset nodig. Aan de hand van die dataset, moet de voorkeurkeuken van elke gebruiker voorspeld kunnen worden. De dataset dient een gebruikerssimulatie te zijn waarin voor elke gebruiker bekend is wat zijn voorkeurkeuken is en de ingrediënten staan van alle recepten die de gebruiker als voorkeur heeft meegegeven.

#### Actie
Als eerst heb ik de datasets op de notebook server geüpload. Vervolgens heb ik `pandas` gebruikt om de datasets in te lezen.

![image](https://user-images.githubusercontent.com/121435298/209831484-dabaa753-99d1-419b-a80f-27dce8eb3693.png)

Vervolgens heb alle dataset geïnspecteerd en bekeken. Daarbij heb ik gekeken naar de datatype van alle elementen en vervolgens heb ik gekeken of er velden zijn waarvan de waarde ontbrak.

![image](https://user-images.githubusercontent.com/121435298/209832737-22526b11-1994-4d72-822d-3278b678e321.png)
![image](https://user-images.githubusercontent.com/121435298/209832877-1fc6f5d8-1c6b-46d8-94f5-d772731981f7.png)
![image](https://user-images.githubusercontent.com/121435298/212538394-99d3d5c7-c1cb-4a9d-8188-6d156afd6dbc.png)

De datasets zijn helaas niet direct geschikt om de voorspellingen te kunnen doen. Ik heb een aantal aanpassingen uitgevoerd op de datasets zodat ze overzichtelijker worden. Zo heb ik de kolom `Unnamed: 0` verwijdert omdat het toegevoegde waarde heeft op alle datasets.

![image](https://user-images.githubusercontent.com/121435298/209833690-ff9a23fc-de33-4bf3-97a4-120509f17911.png)

Daarna heb ik gekeken naar wat ik bij elke dataset kan doen om het overzichtelijker te krijgen. Voor de dataset `ingredients` heb ik gemerkt dat elke ingrediënt van een recept op een aparte rij staat.


![image](https://user-images.githubusercontent.com/121435298/209853073-cd6e8f44-e784-42e5-85f6-a6b8ebf56763.png)


Ik heb het gegroepeerd per recept en alle ingrediënten op een rij geplaatst. Dat heb ik in een paar stappen gedaan. Als eerst heb ik gegroepeerd per recept en vervolgend de `.agg()` methode gebruikt om de ingrediënten bij elkaar te joinen.![image](https://user-images.githubusercontent.com/121435298/209857310-727e4cbe-1022-4297-ad81-79d7f8f9c4c4.png)De ingrediënten staan nu bij elkaar per recepten  in een kolom cel zoals te zien is op de foto hierboven. Mijn doel was daarna om elke ingrediënt in een aparte kolom te krijgen. Omdat dat niet in een keer kan, heb ik dat in een aantal stappen moeten splitsen. Eerst heb ik de `.str.split()` methode gebruikt op de `ingredient` kolom. Dat heeft geresulteerd in een panda serie waarin alle ingrediënten geschieden van elkaar. En dat heb ik vervolgens naar een dataframe omgezet.![image](https://user-images.githubusercontent.com/121435298/209857565-d28b52ba-6f27-4525-b054-a8f2795e0de3.png) Daarna heb ik de kolom `recipe` uit de gegroepeerde dataset gefilterd. ![image](https://user-images.githubusercontent.com/121435298/209864011-88b8114e-4fd0-4bd1-b3bc-e81c04002f9d.png)
Dat heb ik gedaan zodat ik later `recipe` en `recipe_ingredients` aan elkaar kan samenvoegen. Dat resulteerde in het volgende dataframe: ![image](https://user-images.githubusercontent.com/121435298/209864064-7352a098-01d1-40e6-95a2-976e54a1a01b.png)

Voor de `tags` dataset heb ik bijna het zelfde gedaan. Eerst heb ik de dataset geinspecteerd, daaruit bleek dat de dataet geen missing values bevatte. Vervolgens heb ik de kolom `Unnamed: 0` verwijdert. Daarna gegroepeerd op recipeen en als laatste de datasets 'tags' en 'ingredients' samengevoegd en dat resulteerde in het volgende dataframe: ![image](https://user-images.githubusercontent.com/121435298/209864281-8c3bf52b-0378-48f8-8ccb-a3eeb58ad8b4.png)

Ik heb nu een dataset gecreëerd waar de recepten met de bijbehorende tags en ingrediënten. Helaas kan ik met de dataset nog geen voorspellingen doen omdat de benodigde dataset uit `1` en `0` moet bestaan of categorische variabelen. Milan had op het moment dat ik nog bezig was met de data voor te bereiden al een dataset klaarstaan die we later hebben gebruikt om voorspellingen te kunnen doen en die ziet er als volgt uit: 

![image](https://user-images.githubusercontent.com/121435298/211157890-ee16ddef-0a97-4bc6-933e-23f3c3ed7b93.png)

De [dataset](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/userdata.csv) heeft de juiste formaat om de voorspellingen te kunnen doen. Maar na  het inspecteren, bleek dat de dataset nog wel aanpassingen nodig had om goede voorspellingen te kunnen doen. Zo hebben we besloten om de ingredienten en de tags waarvan de som van de rij lager zijn dan 40 niet te gebruiken om voorspellingen mee te kunnen doen. Dat heb ik als volgt gedaan:
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

Later zijn we nog doorgegaan met een andere [dataset](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/final_userdata_min_40.csv) die uit meer rijen bestond en minder kolommen bevatte. Dat laatste komt doordat we de dataset hebben gefilterd en gekozen hebben om door te gaan met de data van wereldkeukens die het meest voorkomen.
![image](https://user-images.githubusercontent.com/121435298/211208845-32b2be4e-055b-4fef-b126-58eb6b7ca9f2.png)



#### Reflectie
Op het moment dat Milan de gebruikerssimulatie al klaar had staan, had ik het gevoel dat ik over te weinig `pandas` kennis beschik. Ik heb sindsdien meer Datacamp courses uitgevoerd zodat ik mijn programmeer vaardigheden kan verbeteren. Ik heb veel geoefend met dataframes en ik heb nieuwe `pandas` technieken wat mij heeft geholpen verder te werken aan de dataset. Zo heb ik geleerd hoe ik dataframes beter kan bewerken door ze eerst goed te inspecteren en te prepareren en in het vervolg zal ik dezelfde methode aanhouden op het moment dat ik over te weinig kennis beschik om een onderzoek te kunnen uitvoeren. 


## Predictive Models

Het idee is dus om de favoriete keuken van een gebruiker te voorspellen zodat er een goede aanbeveling wordt gedaan binnen de voorspelde keuken. Daarvoor is een model benodigd die de juiste keuken van elke gebruiker kan vooorspellen. Na de dataset te hebben geinspeceteerd en de doelvariabele te hebben gedefinieerd, is er uitgerold dat we hier te maken hebben met een classicatie. Volgens [askpython](https://www.askpython.com/python/regression-vs-classification) , dient bij een categorische output een classificatie model gebruikt te worden om voorspellingen te kunnen doen.

De bedoeling is om de kolom 'kitchen' te voorspellen aan de hand van de ingrediënten die de recepten bevatten die gebruiker als voorkeur heeft meegegeven. Na literatuuronderzoek te hebben gedaan, bleek dat er verschillende [classificatie modellen](https://monkeylearn.com/blog/what-is-a-classifier/) bestaan. Ik heb gekozen om de KNeighbors-classificatie model te testen op ons gesimuleeerde [dataset](https://github.com/Ilias-Hazali/Portofolio-ADS-Ilias-Hazali/blob/main/final_userdata_min_40.csv). 
![image](https://user-images.githubusercontent.com/121435298/212939500-b5e0a0f6-dacf-4069-9e38-b8a5f6821a55.png)

De dataset heb ik geimporteerd en geinspecteerd en vervolgens de kolomen van alle keukenstypes verwijdert. Ook heb ik de kolom "liked_recipes" verwijderd.
![image](https://user-images.githubusercontent.com/121435298/212973707-e49238fd-9322-4142-9a3a-bd563abc945d.png)

Omdat de doelvariabele een categorische variabele is, heb ik besloten om het om te zetten naar een nummerieke variabele. 
![image](https://user-images.githubusercontent.com/121435298/212978625-e94b3385-0c1f-4db6-891f-7b813e60e321.png)

Dat heb ik als volgt gedaan: De Aziatische keuken kreeg het getal 0, Frans:1, Hollands:2, Italiaans:3, Mexicaans:4, Amerikaans:5, Mediteraans:6.
![image](https://user-images.githubusercontent.com/121435298/212978832-4632f105-37ec-48ff-89ce-1f9afee13c77.png)![image](https://user-images.githubusercontent.com/121435298/212978878-72f49850-f142-4362-ad2f-cb47205cbdc2.png)

 Vervolgens heb ik de X en y gedefinieerd.
![image](https://user-images.githubusercontent.com/121435298/212979429-fa60dd1f-8435-4a55-b328-ee35f841d84c.png)

De doelvariabele type is bij het omzeten naar een numieriek variabele niet omgezet naar een integer type. Dat moest gebeuren omdat de 'train_test_split' anders niet kan werken.
![image](https://user-images.githubusercontent.com/121435298/212980269-01fa521b-0e4e-47f1-a68b-b58e550ea68f.png)

Daarna heb ik de dataset gesplitst in een train, validatie en test sets. Dat heb ik gedaan zodat ik het model kan trainen met de trainset en kan valideren op de validatie set en uiteindelijk te testen om nieuwe data en dat is de testset.
![image](https://user-images.githubusercontent.com/121435298/212985275-1a9ae6c8-1dc3-405f-89d7-6c9074cd3171.png)

Nu dat da de dataset gesplistst is, heb ik de 'KNeighborsClassifer' gedefinieerd en de trainingset gebruikt om het trainen. Vervolgens het getraind model gebruikt om de doelvariabele van de validatieset te voorspellen.
![image](https://user-images.githubusercontent.com/121435298/212986582-65c17150-3ffe-4a5c-9c67-bff92173f31f.png)

Het model gaf een score van 0.9537366548042705
![image](https://user-images.githubusercontent.com/121435298/213451408-0dc346be-59b7-4e2c-a35c-9335be41ef55.png)

Vervolgens heb ik een ander model getest genaamd 'OneVsRestClassifier'. Dat model heb ik gefit op dezelfde trainingsset en 'X_val' mee voorspeld en had een 0.9786476868327402 als score.
![image](https://user-images.githubusercontent.com/121435298/213451585-a2881df0-6c40-40b8-a2bc-fbf0c0e6c896.png)

Vervolgens wou ik een ander model gaan testen en ik kwam achter dat elk model afzonderlijk te testen te veel tijd zou kosten en zeer onoverzichtelijk wordt. dus heb ik een functie aangemaakt die het werk kan versimpelen en meerdere classificatie modellen met elkaar kan vergelijken. Dat heb ik als volgt gedaan:
Eerst heb alle classifiers die ik wilde testen geimporteerd. Daarna een leeg lijst aangemaakt waarin ik elk model een naam geef en aanroep.
![image](https://user-images.githubusercontent.com/121435298/213184811-bb17e867-81c3-4df7-9d64-dbed9d6ab3af.png)

Vervolgens heb ik een dataframe aangemaakt zodat ik een overzicht kan maken van de resultaten van elk model.
![image](https://user-images.githubusercontent.com/121435298/213185189-232baa2d-7fe1-4e44-8a27-506e0c2c9035.png)

Daarna een For-loop aangemaakt die elk model aanroept, fit op de trainset en de waarde van de 'X_val' voorspelt. Tevens wordt de 'Precsion_score', 'recall_score', 'accuracy_score'en de 'f1_score' van elk model bepaald en aan de dataframe toegeveogd.
![image](https://user-images.githubusercontent.com/121435298/213188434-c528a395-5c46-4d7e-b817-24b9874995f5.png)

Omdat we bij dit onderzoek opzoek zijn naar het model die het beste kan voorspellen, heb ik de accuracy score van alle modellen met elkaar vergeleken. Want de accuracy score is de score dat aangeeft hoe vaak een model een voorspelling goed heeft.
![image](https://user-images.githubusercontent.com/121435298/213458732-2d3d4fd3-1932-4cd8-aede-cf3e0da70b97.png)

Maar volgens [vitalflux](https://vitalflux.com/accuracy-precision-recall-f1-score-python-example/) is de accuracy geen goede maat om modellen met elkaar te vergelijken. In dat geval dienen de modellen aan de hand van hun 'roc auc score' met elkaar vergeleken te worden. Dus heb ik de roc auc score van alle modellen berekend en het model met de hoogste score gekozen. Dat laatste heb ik gedaan omdat de 'roc auc score' de relatie tussen de 'True positives' en de 'False positives' en hoe hoger de score hoe beter dat relatie is. De "DecisionTreeClassifier' had de 




## Data Visualization



## Diagnostics of the learning process

## Evaluation
