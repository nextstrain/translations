---
title: Actualización de Agosto 2020 de la Epidemiologia Genética del COVID-19
authors:
  - James Hadfield
  - Cassia Wagner
  - Eli Harkins
  - Trevor Bedford
  - Richard Neher
  - Emma Hodcroft
authorLinks:
  - https://bedford.io/team/james-hadfield/
  - https://bedford.io/team/cassia-wagner/
  - https://bedford.io/team/eli-harkins/
  - https://bedford.io/team/trevor-bedford/
  - https://neherlab.org/richard-neher.html
  - https://neherlab.org/emma-hodcroft.html
affiliations: "Fred Hutch, Seattle, USA; Biozentrum, Basel, Switzerland"
translators:
  - Roy Costilla
  - Claudio S. Fuente
  - Miguel I. Paredes
translatorLinks:
  - https://researchers.uq.edu.au/researcher/18392/
  - https://twitter.com/ClaudioSFuente1
  - https://twitter.com/miguelp1120
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-08-11?d=map"
date: "14 de Agosto del 2020"
abstract: "
La pandemia se ha expandido en todo el mundo, con mas de [1.5 millones de casos nuevos cada semana](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports), un total de casos reportados de [18 millones](https://ourworldindata.org/covid-cases) y mas de [600,000 fallecidos](https://ourworldindata.org/covid-deaths).
\n\n
### La situación [fue resumida por la OMS el 2 de Agosto del 2020](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports):
\n\n
### **\"Al relajar las medidas de salud publica y de distanciamiento social, implementadas para limitar la transmisión del virus, muchos países han experimentado nuevos brotes o el resurgimiento de nuevos casos. Los riegos y las vulnerabilidades se han amplificado en contextos frágiles, de escasos recursos y afectados por conflictos.\"**
\n\n
### The worldwide sequencing of the SARS-CoV-2 genome has continued unabated, and with this data we use Nextstrain to track the geographic movement and evolution of the virus.
To date, there are over 75,000 sequences publicly shared from half the countries in the world - an amazing testament to the scientists and public health officials behind this.
\n\n
### We use subsampling approaches to remove potential sampling biases in order to ensure that regions and time-periods are appropriately included for analysis.
(This also helps for the computational requirements.)
\n\n
### Here you can see the geographical distribution of ~4300 genomes.
Each circle is centered on an individual country, the colour indicates region and the radius scales with the number of genomes from that country ([see here for help interpreting the map in Nextstrain](https://nextstrain.org/docs/visualisation/map-interpretation)).
\n\n
### In this report, we examine the global genomic epidemiology of COVID-19 broadly and provide specific updates for each world region.
"
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Please add your names & links to the 'translators' section above -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- table of contents slide -->
# [Resumen COVID-19](https://nextstrain.org/ncov/global/2020-08-11?d=map)

### Tabla de contenidos
* [Distribucion global de los clados](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [Mutacion D614G en el gen Spike](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [Situación en Asia](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [Situación en Oceanía](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [Situación en Europa](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [Situación en Sudamérica](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [Situación en África](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [Situación en Norte América](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [Resumen](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [Creditos](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Recursos Nextstrain
* [EMPIEZA AQUÍ: Como leer filogenias/arboles filogenéticos](https://nextstrain.org/narratives/trees-background/)
* [Reportes de la situación del COVID19 previos](https://nextstrain.org/ncov-sit-reps/)
* [Información adicional de los virus corona](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Resumen Ejecutivo

En este repote, analizamos genomas de SARS-CoV-2 compartidos públicamente. Al comparar estos genomas virales uno contra el otro, podemos caracterizar cómo el COVID-19 se está moviendo alrededor del mundo y esparciendo localmente.

- Asia tiene una proporción mas alta de los clados 19A y 19B, con los clados 20A, 20B y 20C dominando en Europa y América del Norte.

- Globalmente, podemos ver de forma clara el crecimiento hacia la prominencia de la sustitución D614G en la Proteína Spike. Esta variante es hipotéticamente la responsable de un incremento en la transmisión del SARS-CoV-2.

- Para exhibir mejor versiones en tiempo real del SARS-CoV-2 alrededor del mundo, mantenemos 6 versiones regionales y 1 global, que son actualizadas cada día hábil de la semana.

- En Asia, existieron numerosas transmisiones entre países de la región durante el principio de la pandemia. Más recientemente observamos un movimiento hacia vínculos dentro de los países, una tendencia que se observe en gran parte de las regiones.

- En Oceanía, los casos de Nueva Zelanda están contenidos en una estrecha banda temporal, correspondiente a su eliminación del virus (hasta esta semana). El reciente aumento de caos de Australia aparece, al menos en las muestras compartidas hasta ahora, como un apretado cúmulo de casos provenientes de diversidades previamente circulantes.

- El SARS-CoV-2 se expandió extremadamente rápido en Europa - el virus estaba probablemente transmitiendose en muchos países antes de que se percataran. Esto ha resultado en una mezcla intensa de muestras al principio de la pandemia, haciendo dificil distinguir e identificar introducciones de un lugar a otro. Mas recientemente podemos observar variantes mas diferenciadas y asociadas con paises específicos, ya que los virus han sido contenidos a través de las restricciones de viaje.

- Al igual que otras regiones, América del Sur tuvo múltiples introducciones, cubriendo la mayor parte de la diversidad conocida del SARS-CoV-2. Luego de entrar en vigencia las restricciones de viaje, las secuencias comenzaron a agruparse de forma mas notoria. Desafortunadamente, y a pesar de las epidemias en curso en muchos paises, no hay disponibles secuencias mas recientes.

- África también ha tenido múltiples y diversas introducciones temprano en la pandemia. La restricciones de viaje subsiguientes parecen haber limitado la mezcla entre paises africanos, con la mayoría de las secuencias aparentemente derivando de circulaciones mas tempranos dentro del mismo país

- Una imagen diferente se observa en los EEUU, donde los viajes domésticos no han sido grandemente restringidos: observamos mezclas entre todos los Estados, al igual que transmisión local. En México y Centroamérica, observamos ejemplos de cúmulos geográficos de transmisión, particularmente entre California (EEUU) y Baja California (México).

```


<!-- ############ SLIDE BREAK ############# -->
# [Distribución Mundial de Variantes Genéticas](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

Desde su surgimiento a fines de 2019, el SARS-CoV-2 se ha diversificado en varias y distintas variantes co-circulantes. Para facilitar la discusión de estas variantes las hemos agrupada en clados que son definidos por mutaciones distintivas.

Actualmente definimos 5 clados (ver [este post del blog](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming) para detalles):

* 19A y 19B emergieron en Wuhan y dominaron el brote inicial.
* 20A emergió de 19A, dominó el brote europeo de Marzo y se ha expandido desde entonces globalmente.
* 20B y 20C son grandes y genéticamente distintos Subclados de 20A.


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


Estamos ahora observando a la distribución de estos clados a lo largo del Mundo (el color ahora ahora representa el clado de pertenencia).
Se puede observar que los países de la región Asiática tienen una mayor proporción de 19A y 19B (azules), ya que esa variante dominó el brote inicial.
Europa y América del Norte tienen una mezcla de todos los clados, per se encuentran dominados por 20B y 20C (amarillo y naranja, respectivamente).

#### Si tienes secuencias de las cuales quieras conocer sus clados (y su posición estimada en el árbol filogénético), hicimos Nextclade ([clades.nextstrain.org/](https://clades.nextstrain.org/)) que te permite arrastrar-y-soltar tus archivos FASTA directamente en el navegador.


<!-- ############ SLIDE BREAK ############# -->
# [La bien publicitada Proteína Spike D614G](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

La substitución D614G en el código genético de la Proteína Spike (S) ha estado en las noticias recientemente y ha sido tema de mucha especulación.

La evidencia que se está desarrolando muestra que la variante G (amarillo en esta vista) incrementa la infectividad del SARS-CoV-2 _in vitro_ y puede que haya sido evolutivamente seleccionada para un incremento en la transmisión Humano-a-Humano ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). Sin embargo, un increment en la infectividad, puede que venga potencialmente al costo de hacer al virus mas vulnerable para los anticuerpos neutralizantes. ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

Aquí podemos ver que esta variante fue inferida de haber aparecido poco después de la zoonosis inicial y subsecuentemente se esparció alrededor del mundo.
En Julio la variante 614G se encontraba presente en la mayoría de los virus circulantes alrededor del mundo. Desde su aparición inicial, la sustitución ha surgido en múltiples ocasiones y también se ha revertido hacia la variante 614D.
No hay evidencia de que esas otras sustituciones y reversiones hayan resultado en cadenas de transmisión contínuas.


<!-- ############ SLIDE BREAK ############# -->
# [Analizando Versiones Regionales independientemente](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

Al haber demasiados genomas para mostrar en un único árbol, proveemos un análisis regional para cada una de las 6 regiones mostradas aquí, además de nuestra versión global.
Esto nos permite enfocarnos en la diversidad dentro de cada región, al tiempo que elegimos muestras adecuadas fuera de esa región, para poder mantener un panorama de todas las transmisiones entre-regiones a lo largo del tiempo - ¡como podemos ver en esta sección!

En las siguientes secciones vamos a proveer un panorama de cada una de esas regiones al cambiar entre la correspondiente base de datos. (¡Esta es una nueva característica de las Narrativas de Nextstrain!)

Un inventario completo de las versiones mantenidas por nosotros y otros se encuentra disponible en [nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/).

<!-- ############ SLIDE BREAK ############# -->
# [Situación en Asia antes de Junio](https://nextstrain.org/ncov/asia/2020-08-11?dmax=2020-06-01&d=map&f_region=Asia&legendOpen)

Al examinar la situación en Asia usando los genomas muestreados antes de Junio del 2020, observamos amplia evidencia de transmisión dentro de Asia así como de transmisión desde otras partes del mundo.

#### Interpretando las líneas y los colores
Aquí solo países asiáticos han sido coloreados, y las otras regiones del mundo se muestran en gris. El color de cada línea de transmisión (líneas entre los círculos) representa el lugar de origen, de manera que todas las **líneas de color** representan transmisiones originadas dentro de país asiático (en este ejemplo).

#### Transmisiones hacia Asia
Esto muestra que muchas de las transmisiones hacia países asiáticos y no asiáticos fueron importadas (líneas en gris). Las transmisiones desde Europa a Asia son particularmente prominentes (aunque el grafico muestran líneas desde Alemania, este punto representa toda Europa). Sin embargo, es importante interpretar esta conclusión con cautela pues podría ser causada por sesgos en el muestreo (mayoría de muestras disponibles son de Europa).  


<!-- ############ SLIDE BREAK ############# -->
# [Situación en Asia después del 1ro de Junio](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

Al observar los genomas disponibles después del 1ro de Junio (en los últimos dos meses), vemos que las muestras son mayormente de ciertos países. Aunque esto limita las conclusiones que podemos obtener, al parecer existen pocas transmisiones entre países.

Nuestra ultima afirmación se basa en la filogenia del virus, donde se observan grupos monofilético grandes (en la misma parte del árbol) de genomas de Singapur (en amarillo) y Bangladesh (verde claro).

Estos datos son consistentes con mayores restricciones a los viajes internacionales y controles fronterizos mas estrictos.


<!-- ############ SLIDE BREAK ############# -->
# [Resumen de Oceanía](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Aquí exploramos cerca de ~790 genomas de Australia y Nueva Zelandia, junto con ~1100 secuencias de todo el mundo como contexto.
Solo muestras de Australia y Nueva Zelandia se muestran en colores.

Vemos que estas muestras están repartidas en todo el árbol filogenéticos, lo que indica que Oceanía ha estado expuesta a casi toda la diversidad genómica del SARS-CoV-2.

La mayor parte de las muestras de Nueva Zelandia (en azul, morado, y verde) provienen de una banda temporal definida entre Marzo y Abril, gracias a la exitosa estrategia de control del gobierno. Mientras el país ha regresado a una normalidad relativa, las fronteras permanecen cerradas para todos los que no son ciudadanos, lo que limita las posibilidades de que el virus re-ingrese al país. Los ciudadanos que regresan al país son puestos en una cuarentena obligatoria de 14 días.

Esta semana, el gobierno anuncio cuatro nuevos casos de transmisión comunitaria, aparentemente no relacionados con ninguno de los ciudadanos retornados. El secuenciamiento genómico podría proporcionar claves para saber como el SARS-CoV-2 supero los estrictos controles fronterizos (ver mas abajo!).

_DATO: si desplazas el cursor sobre los círculos en el mapa, las terminaciones relevantes del árbol se observan resaltadas.

<!-- ############ SLIDE BREAK ############# -->
# [Resurgimiento en Australia](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

Australia, y especialmente el estado de Victoria (capital: Melbourne), resaltado aquí en naranja, ha visto un resurgimiento de casos del COVID-19 y ha recientemente implementado medidas adicionales de salud pública para tratar de controlar este aumento de casos.

Todos los genomas recientes aparecen ser un subclado del clado 20B (regrese a la dispositiva anterior para ver cómo encaja el clado 20B en la filogenia entera). Las fechas recientes y el agrupamiento de los casos implican la existencia de un brote local.

Podemos apreciar un agrupamiento similar en las secuencias de Nueva Gales del Sur, de donde los casos también han aumentado recientemente


<!-- ############ SLIDE BREAK ############# -->
# [Nuevos casos detectados en Nueva Zelanda esta semana](https://nextstrain.org/ncov/oceania/2020-08-11?c=gt-nuc_10097,23731&d=tree)

Nueva Zelanda reportó más de 100 días sin transmisión comunitaria del virus antes de detectar casos en la comunidad esta semana. Al momento de publicación de este reporte, el grupo de casos incluye más de 30 casos conocidos que fueron encontrados principalmente en Auckland, la ciudad más grande.

La fuente del grupo de casos aún no se conoce, sin embargo, científicos han secuenciado las muestras aisladas y reportan que los casos pertenecen al linaje de pangolines B1.1.1. Aunque los genomas aún no se han publicado, se sabe que se encuentran en la región coloreada aquí en azul. Este linaje se originó en Europa, pero desde entonces se ha observado en diversas regiones del mundo.


<!-- ############ SLIDE BREAK ############# -->
# [Situación temprana en Europa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 se esparció rapidamente por Europa, probable y principalmente a través de transmisiones directo desde Asia.

Para finales de Febrero, y aunque sólo habían [unos pocos cientos de casos](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea) reportados oficialmente en Europa, el virus se había esparcido a por lo menos 15 países europeos.

Dado que el muestreo era menos común en los primeros días de la pandemia, el SARS-CoV-2 se encontraba ya casi con seguridad circulando a lo ancho de Europa, incluyendo países de los cuales no tenemos muestras.


<!-- ############ SLIDE BREAK ############# -->
# [Confinamiento en Europa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

A lo largo de Marzo y Abril gran parte de Europa cerró sus fronteras, y muchos impusieron distintos tipos de "Confinamiento" donde se restringió el movimiento y se cerraron comercios y escuelas. Esperamos que estas restriciones hayan disminuido la transmisión entre países, haciendo más factible el ver secuencias de determinados países formar "cúmulos" con secuencias previas del mismo páis.

Sin embargo, el SARS-CoV-2 se encontraba ya tan mezclado a lo largo de Europa que distintas variantes del virus estaban circulando a lo largo de distintos países. La mayor parte de los países tenían numerosas variantes distintas circulando antes del confinamiento que estaban relacionadas con virus circulando en otros países. Esto significa que el panorama filogenétivo permanece bien mezclado incluso luego del cierre de fronteras (mostrado por múltiples colores cerca unos de otros en el árbol).

A pesar de esto, podemos observar algunos signos de transmisión local esperables. Aquí, Finlandia y Suecia presentan un cúmulo de transmisión muy distintivo en verde y naranja (alrededorde 1/3 desde arriba), mientras que España (azul oscuro) muestra transmisión local distintiva en lo mas bajo y lo mas alto del árbol. Islandia (violeta) y Suiza (azul clado) también muestras cúmulos de transmisión local.

_Hint: You can expand the legend by clicking 'Country' at the top-left of the tree!_


<!-- ############ SLIDE BREAK ############# -->
# [Secuenciamiento reciente de Europa resalta transmisión local y enrique la comprensión de expansiones anteriores del SARS-CoV-2](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

Examinando sólo muestras subidas en la última semana se resaltan dos puntos importantes.

Primero, podemos observar una tendencia hacia agrupamientos de puntas en mini-cúmulos. Esto indica que la transmisión dentro de países continúa dominando, probablemente producto de varias regulaciones introducidas a lo largo de Europa. El virus continuó diversificándose genéticamente durante el confinamiento, pero fue más frecuentemente confinado a un sólo país, por lo cual podemos ahora distinguir mejor "variantes" locales de esos países.

Algunas muestras no siguen esta tendencia de conectarse a otras muestras del mismo país. Al detenerse sobre un país en la leyenda se resaltan puntas en el árbol de ese país para ayudar a identificar esas muestras. Por ejemplo, en el medio del árbol, podemos observar algunas muestras Suecas (verde) anidades entre un gran clado Ruso (Rojo).
Dado el intenso sub-muestreo, es necesario mantener cautela en no sobreinterpretar supuestas transmisiones entre países en esta vista.

En segundo lugar, podemos ver que las puntas una amplia diferencia en el espaciado horizontal -- p.ej. las muestras remitidas la semana pasada representan una colección de muestras que se extienede hasta principios de Marzo.
Las razones para secuenciar genomas "viejos" varía, pero estas muestras nos ayudan a completar nuestra compresión de la evolución viral y el movimiento geográfico.


<!-- ############ SLIDE BREAK ############# -->
# [La situación inicial en América del Sur](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmax=2020-04-15)

Las primeras secuencias de SARS-CoV-2 de América del Sur son de casos de los finales de febrero y principios de marzo y se encuentran regadas a través del árbol filogenético, implicando que hubo múltiples introducciones del virus hacia la región. A medida que los viajes internacionales disminuyeron empezando en marzo, podemos ver evidencia de transmisión local continua en varios países.

La mayoría de las secuencias de Brasil (resaltadas con un verde claro) son parte de dos grupos grandes del virus (se pueden encontrar la parte superior del árbol). También podemos apreciar evidencia que esta variante se propagó alrededor del continente a Chile, Uruguay y Argentina.

Podemos apreciar grupos distintos de transmisión del virus en Colombia (naranja), Chile (turquesa), Uruguay (azul más claro) y Argentina (azul más oscuro) que se encuentran a través del árbol entero.


<!-- ############ SLIDE BREAK ############# -->
# [La situación actual en América del Sur](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmin=2020-05-01)

Desafortunadamente, mientras que el SARS-CoV-2 continúa propagándose a través de América del Sur, la generación de secuencias no ha seguido el mismo ritmo. Aunque el conteo de casos sigue siendo alto en gran parte del continente, desde mayo solo se han compartido 68 muestras de 5 países (Brasil, Ecuador, Uruguay, Argentina y Chile).

Aunque nuestras inferencias están limitadas por el muestreo escaso, en la mayoría de los casos las muestras más recientes se encuentran entre de la diversidad del virus anteriormente muestreada del mismo país u otros países de América del Sur. Esto sugiere que las variantes que circulan ahora son descendientes de las introducidas que ocurrieron al principio de la epidemia.


<!-- ############ SLIDE BREAK ############# -->
# [SARS-CoV-2 en África](https://nextstrain.org/ncov/africa/2020-08-11?d=tree,map&f_region=Africa&legendOpen&transmissions=hide&p=grid)

Al igual que América del Sur, África tuvo varias introducciones de SARAS-CoC-2 al continente, la mayoría probablemente desde Europa. Esto se observa en la distribución de muestras africanas a lo largo del Árbol - incluso muestras de un mismo país contienen diversas variantes.

Ahora tenemos secuencias de países a lo largo de África y a través de la epidemia, aunque los esfuerzos por secuenciar parecen haber disminuido de forma sutil recientemente. 
Sudáfrica ha contribuido en gran proporción al secuenciamiento.


<!-- ############ SLIDE BREAK ############# -->
# [Agrupamientos en África](https://nextstrain.org/ncov/africa/2020-08-11?d=tree&f_region=Africa&legendOpen&p=full&f_country=Democratic%20Republic%20of%20the%20Congo,Senegal,South%20Africa)

En la República Democrática del Congo, Senegal y Sudáfrica, podemos observar claros signos de transmisión local mostrados aquí como cúmulos de secuencias en el árbol.
De Senegal y Sudáfrica, tenemos muestras recolectadas más recientemente.
Estas muestras caen generalmente dentro de la vieja diversidad del país, tal y como cabría esperarse de una continuada transmisión local.

Aunque debemos ser cautos con nuestras conclusiones, ya que se encuentran enormemente limitadas por un muestreo sesgado, las muestras recientes desde África no sugieren una importación continuada de casos desde otros lugares.
Este resultado probablemente refleja las continuadas restricciones en el movimiento global.


<!-- ############ SLIDE BREAK ############# -->
# [United States epidemic is a mixture of local and within-country transmission](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&p=full)

Here we show genomes from the United States epidemic from April 15 to present day. In mid-April, all U.S. states were on lockdown. [States have since implemented heterogeneous reopening policies](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html).

In this tree, just like in the trees for other regions, we see examples of local virus transmission as shown by similarly-colored tips clustering together over time. If you click, "Explore the Data Yourself", and filter the location to Yakima County, you can see a clear example of introduction and growth of genetically related viruses into this region of Washington State. (You can also [click here](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&f_location=Yakima%20County&p=grid) to do this, but you will leave the narrative.)

However, on the tree, we  also see within-country transmission across the U.S. as shown by mixing of colors at the tree tips. On the map, within-country transmission looks like transmission lines extending between states. These observations are consistent with few domestic travel restrictions and states' reopening policies.


<!-- ############ SLIDE BREAK ############# -->
# [Central American sequencing shows geographically-clustered transmission](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map,entropy&f_country=Belize,Costa%20Rica,Guatemala,Jamaica,Mexico,Panama&p=grid&transmissions=hide)

There has been limited sequencing from Central America, especially over the past two months, which restricts the inferences we can draw about the epidemic. From the genomes that have been shared, we see geographic clustering of SARS-CoV-2 genomes.

Toward the bottom of the tree in clade 19B, we see a cluster of transmission in Panama starting in mid-February. Several later sequences in Panama from June and July nest in with this cluster, suggesting there's continued local transmission of this virus genotype in the country.

In Mexico, we also see clear geographic clustering of transmission through May. Without more recent sequencing, we cannot make inferences about the epidemic in later months.

In the center of the tree, there is a cluster of cases in Baja California (in light blue). These cases were likely imported from California, USA (green branches on the tree) in March. This inferred importation is consistent with known travel links between the neighboring locations although we should be cautious about interpreting inferred transmission locations given sparse sequencing.


<!-- ############ SLIDE BREAK ############# -->
# [Closing summary](https://nextstrain.org/ncov/global/2020-08-11?d=map)

As the pandemic reaches its eighth month of global circulation, we can now see distinct changes over time in the picture painted by viral genetics, largely determined by changing behaviour.

Multiple early transmissions to the USA, Oceania, Europe, and across Asia, were initially incredibly well-mixed, as our global travel patterns distributed the virus incredibly effectively. Soon afterwards, diverse introductions to South America and Africa, often from Europe and North America, seeded local epidemics there.

As the scale of the viral spread and severity of COVID-19 became apparent, travel ground to a halt in much of the world. After this point, we can see a distinct shift to local transmission during 'lockdowns' and the most severe travel restrictions. One outcome of this is that we can now sometimes better identify the source for viruses, as local epidemics have in some cases become more genetically distinct. In the USA, the absence of strict domestic travel has helped maintain well-mixed epidemics between states.

Borders are now re-opening and travel has resumed, though not nearly to pre-pandemic levels. This, combined with the lag time from when samples are taken to when they are available publicly, means we only see a few signs of between-country mixing. In general, recent samples tend to continue to cluster with past sequences from the same country, indicating continued transmission of previously circulating variants.

Unfortunately, many countries have seen a rise in cases in the last few weeks, usually associated with reopening. As the Northern Hemisphere prepares to move into autumn and colder weather, further reopening, and school resuming, we must remain vigilant about rising case counts. As winter progresses in the Southern Hemisphere, we see worrying signs that seasonality could indeed lead to more trouble containing transmission - Australia's initial success with the virus has been dampened by recent outbreaks. Continuing to scale up Test, Trace, and Isolate, careful hand-hygiene, and conscientious mask-wearing can help keep our societies as open as possible while we continue to battle SARS-CoV-2.

<!-- ############ SLIDE BREAK ############# -->
# [Scientific credit](https://nextstrain.org/ncov/global/2020-08-11?d=tree&c=author)

We would like to acknowledge the amazing and timely work done by all scientists involved in this outbreak.
Only through the rapid sharing of genomic data and metadata are analyses such as these possible.

**We encourage you to click on 'Explore the Data Yourself' and scroll down for a full list of authors; the author of each individual sequence is available by selecting it on the tree.**

We also gratefully acknowledge GISAID for providing the platform through which these data can be uploaded and shared.
