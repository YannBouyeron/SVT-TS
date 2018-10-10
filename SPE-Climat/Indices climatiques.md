# Les indices climatiques.

La prévision des climats futurs nécessite l’identification des principaux paramètres responsables des variations climatiques. Cette identification des facteurs responsables des fluctuations climatiques est à rechercher dans l’analyse des climats passés ou paléoclimats.
Il faut pour cela trouver des indices climatiques permettant de reconstituer les paléoclimats.

## Le delta isotopique des glaces polaires.

Les calottes glaciaires qui recouvrent les pôles sont constituées d'une accumulation de neige déposée années après années et compressée sous son propre poids. Les carottes de glace extraites de forages (documents 2 et 3 page 84) donnent accès à des échantillons de glace issus de précipitations neigeuses dont l'âge dépend de la profondeur de l'échantillon. En certains forages, les glaces les plus profondes ont jusqu'à 800 000 ans.

Il existe plusieurs isotopes stables de l'oxygène dont 16O et 18O qui sont les plus abondants (respectivement 99,8 % et 0,2 %). On les retrouve dans tous les composés oxygénés naturels, notamment l'eau et les carbonates. L'eau (océan, vapeur, pluie, glace, etc.) est constituée essentiellement à partir de l'isotope 16 de l'oxygène qui est le plus répandu.

### La notion de delta isotopique.

Le δ18O indique la différence entre le rapport 18O / 16O mesuré dans échantillon d'eau et le rapport 18O / 16O moyen des océans actuels  (nommé SMOW). Il est exprimé en pour mille et il se calcule selon la formule suivante :

<p align="center">δ18O = 1000 . [(18O/16O)mesuré/(18O/16O)SMOW - 1]</p>

SMOW désigne la composition moyenne de l’océan (Standard Mean Ocean Water), qui vaut :  (18O/16O)SMOW = 2005,2.10-6

Lorsque la concentration en 18O de l'eau diminue le δ18O diminue.

### Les variations du δ18O.

<p align="center">Moyennes mensuelles du δ18O des eaux de précipitation:</p>

 
<table>

<tr>
<td><img src="http://acces.ens-lyon.fr/acces/thematiques/paleo/variations/paleoclimats/images/glob2-O18.gif" alt=""></td>
    
<td><img src="http://acces.ens-lyon.fr/acces/thematiques/paleo/variations/paleoclimats/images/glob3-O18.gif" alt=""></td> 
    
</tr>
</table>


Le δ18O varie en fonction de la latitude: plus la latitude est élevée plus le δ18O est faible. Le δ18O varie aussi en fonction du temps (saisons); il est plus faible en janvier qu'en juillet. La variation temporelle s'observe surtout aux hautes latitudes.

Ces variations spatiales et temporelles suggèrent une influence de la température sur le δ18O. Pour tester cette hypothèse il faut mesurer la corrélation entre le δ18O et la température:

### Étude de la corrélation δ18O / température.

Le dossier temp_18o contient des fichiers xlsx mettant en relation la date, le δ18O mesuré dans l’eau de pluie et la température mesurée , en différents lieux. On peut donc tracer les graphiques suivants : δ18O = f(température) et afficher leurs droites de régression, ainsi que leurs équations et coefficients de corrélation R, pour différents lieux.



<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/halley.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/murmansk.png" alt=""></td> 

</tr>

<tr>

<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/barrow.png" alt=""></td> 

<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/kinshasa.png" alt=""></td> 

</tr>
</table>



En fonction du lieu choisi, il n'existe pas toujours une corrélation entre les valeurs du δ18O des eaux de précipitations et la moyenne mensuelle (ou annuelle) des températures de l'air. La corrélation est forte (les points s'alignent) aux hautes latitudes (Pôles), mais très faibles (mauvais alignement, points dispersés) aux faibles latitudes (Équateur).

La corrélation observée entre t° et δ18O aux hautes latitudes est une corrélation positive: une augmentation de la température de l'air est corrélée à une augmentation du δ18O des précipitations. Les informations relatives à la notion de δ isotopique et au principe de fractionnement isotopique de l'oxygène, permettent de préciser le sens de la corrélation: c'est l'augmentation de la température de l'air qui induit l'augmentation du δ18O des eaux de précipitations. Une augmentation du δ18O traduit donc une augmentation de la température. Et inversement. 

### Application.

Aux hautes latitudes, si on connaît (mesure) le δ18O, on peut alors déterminer la température de l'air au moment de la précipitation grâce à l'équation de la droite de régression. Le δ18O constitue ainsi un thermomètre isotopique.

Les équations des droites de régression varient en fonction de la localisation. L’utilisation du δ18O pour reconstituer les variations paléoclimatiques en un lieu donné nécessite donc d’utiliser l’équation spécifique à ce lieu.

<p align="center"> <img src="http://acces.ens-lyon.fr/acces/thematiques/paleo/variations/paleoclimats/images/cor_temp.gif" alt=""></p>


<i>Jouzel J., C. Lorius, S. Johnsen and P. Grootes, 1994 :  
Climate instabilities : Greenland and Antarctic records. 
Compte Rendu de l'Académie des Sciences de Paris. vol. t. 319, série II, 65-77</i>

Les équations des droites de régression du graphique de Jouzel sont du type : y = a.x + b c'est à dire δ = a.(Température) + b            
Donc: Température = (δ - b) / a 

On peut donc mesurer graphiquement cette relation à partir du graphique de Jouzel:

- À vostok (Antarctique): t° = (δD + 31,5) / 6,5
- À GRIP (Arctique): t° = (δ18O + 14) / 0,66

Les carottes de glaces, issues des forages réalisés en Antarctique (pôle Sud) et au Groenland (pôle Nord), donnent accès à des échantillons de glaces anciennes que l'on peut dater (plus la profondeur de la carotte est élevée, plus la glace est âgée) et sur lesquelles on peut mesurer le delta isotopique. 

Le dossier ice_18o contient des fichiers xlsx qui mettent en relation, pour différents forages, l’âge de la glace, et le δ18O mesuré:

<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/delta_vostok.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/delta_grip.png" alt=""></td> 

</tr>
</table>




Connaissant la relation entre la température et le delta isotopique de l'eau (équations des droites de Jouzel à Vostok et à GRIP),  on peut alors déterminer la température qui régnait au moment des précipitations à l'origine des échantillons de glace en antarctique et en arctique:

<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/temp_vostok.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/temp_grip.png" alt=""></td> 

</tr>
</table>


L'application de l'équation de la droite de Jouzel montre que la température actuelle en Antarctique est de - 62°, alors qu'il y a 21000 ans lors du dernier minima du δD la température était de -70°. Il y' a 21000 ans la température au dessus de l'antarctique était inférieure de 8°C à la température actuelle. On trouve un écart de 10° C pour le Groenland.

L'analyse du δ18O (ou du δD) des carottes glaciaires met ainsi en évidence sur 400 000 ans une alternance de périodes froides (δ faible) et de périodes chaudes (δ élevé) avec un écart de température d'une dizaine de degrés Celsius. Ces périodes sont approximativement synchrones en Antarctique et au Groenland. Il s'agit donc de changements globaux d'un ou plusieurs paramètres du climat. Ces périodes "froides" (périodes glaciaires) ont une périodicité de 100 000 ans et sont entrecoupées de périodes chaudes (périodes inter-glaciaires) d'environ 10 000 ans.

## Le delta isotopique des foraminifères benthiques.

Les foraminifères sont des organismes unicellulaires hétérotrophes (protozoaires) aquatiques. Ils vivent dans un test calcaire («coquille» constituée de carbonate de calcium: CaCO3 contenant du 18O et du 16O) qui s'accumule à leur mort dans certaines conditions sur les fonds marins. Le groupe est très diversifié tant d'un point de vue morphologique que biologique. Ainsi certaines espèces sont planctoniques alors que d'autres vivent sur les fonds océaniques (on les dit alors benthiques) où la température est considérée constante au cours du temps.




### Les facteurs influençant le δ18O des foraminifères 


Le δ18O des foraminifères dépend de la température et du δ18O de l'eau de mer: 

- Corrélation positive entre le δ18O des foraminifères et le δ18O de l'eau de mer:      

<h6 align="center">δ18O foraminifères = f (δ18O eau de mer)</h6>

- Corrélation négative entre le δ18O des foraminifères et la température de l'eau de mer:     

<h6 align="center">δ18O foraminifères = - f (T° eau)</h6>



Les foraminifères benthiques (FB) vivent au fond des océans où la température est constante; le δ18O des foraminifères benthiques dépend donc uniquement du δ18O de l'eau: il existe une corrélation positive entre le δ18O des foraminifères benthiques et le δ18O de l'eau de mer: 

<h6 align="center">δ18O FB = f (δ18O eau de mer)</h6>

### Les facteurs influençant le δ18O de l’eau des océans

En période plus froide qu'actuellement, l'eau s'évapore sous les tropiques, précipite sous forme de neige et s'accumule sous forme de glace dans les glaciers et les calottes polaires; donc le volume des océans diminue tandis que le volume des calottes polaires augmente. 
L'eau qui s'évapore des océans et qui s'accumule sous forme de glace est appauvrie en 18O ( δ18O de la glace polaire = -40 à – 50 pour mille); l'eau qui reste dans les océans se retrouve donc relativement enrichie en 18O; le δ18O de l'eau de mer est alors supérieur à l'actuel c'est à dire supérieur à 0.

<p></p>

En période plus chaude qu'actuellement, la glace des calottes polaires fond et le volume des océans augmente. 
L'eau provenant de la fonte des calottes polaires qui retourne aux océans est appauvrie en 18O; le δ18O de l'eau de mer diminue et devient alors inférieur à l'actuel c'est à dire inférieur à 0

<p></p>

On en déduit que le δ18O de l'eau de mer dépend du volume relatif entre les océans et les calottes glaciaires: il existe une corrélation positive entre le δ18O de l'eau de mer et le volume des calottes glaciaires: 

<h6 align="center">δ18O eau de mer = f (volume calottes glaciaires)</h6>


Le volume des calottes glaciaires dépend du climat global:

<h6 align="center"> V calottes = -f (T° globale)</h6>

Le δ18O de l'eau de mer dépend donc aussi du climat global: il existe une corrélation négative entre le δ18O de l'eau de mer et la température globale: 

<h6 align= "center">δ18O eau de mer = - f (T° globale)</h6>




Il existe donc une corrélation négative entre le δ18O des FB et le climat global:   

<h6 align="center"> δ18O FB = - f (T° globale) </h6>


Les forages des fonds océaniques donnent accès à des sédiments océaniques contenant des restes de tests calcaires de foraminifères que l'on peut dater (plus les sédiments sont profonds plus ils sont anciens). Ces données sont disponibles dans le dossier ocea_o18. En mesurant le δ18O de ces tests calcaires, et connaissant la relation ci dessus, il est alors possible de reconstituer les variations paléo-climatiques:

- Une augmentation du δ18O des FB témoigne d'une augmentation du volume des calottes glaciaires, c'est à dire d'un refroidissement climatique. 

- Une diminution du δ18O des FB témoigne d'une diminution du volume des calottes glaciaires, c'est à dire  d'un réchauffement climatique.   

<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/75D13DDD-D4A1-452F-BE36-0FF4B9A2070C.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/BF36B891-1BD7-46B0-B487-C4BD165AC9BA.png" alt=""></td> 


<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/F0D26D5F-1C26-4AFE-827C-4E6734A5E6D9.png" alt=""></td> 

</tr>
</table>



Le δ18O des foraminifères benthiques dépend du volume relatif océans / calottes glaciaires et donc du climat. Les mesures du δ18O des tests calcaires des foraminifères benthiques des sédiments océaniques, mettent ainsi en évidence une alternance de périodes à δ18O des formainifères benthiques élevé c'est à dire des périodes plus froides qu'actuellement (périodes glaciaires d'environ 80 000 ans) , entrecoupées de périodes à δ18O des foraminifères benthiques faible c'est à dire des périodes plus chaudes qu'actuellement (périodes interglaciaires d'environ 15 000 ans). Ces résultats sont concordants (mêmes variations paléo-climatiques) sur les trois forages océaniques étudiés, et concordants avec les résultats issus du delta isotopique des glaces polaires; ils traduisent des changements climatiques globaux à l'échelle planétaire.
