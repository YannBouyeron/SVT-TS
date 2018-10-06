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

<img align="center" src="http://acces.ens-lyon.fr/acces/thematiques/paleo/variations/paleoclimats/images/cor_temp.gif" alt="">


*Jouzel J., C. Lorius, S. Johnsen and P. Grootes, 1994 :  
Climate instabilities : Greenland and Antarctic records. 
Compte Rendu de l'Académie des Sciences de Paris. vol. t. 319, série II, 65-77 *

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
