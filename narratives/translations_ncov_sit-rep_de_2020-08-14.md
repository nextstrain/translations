---
title: August 2020 Update zur genomischen Epidemiologie von COVID-19
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
translators: Elisabeth Hirth,
translatorLinks:
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-08-11?d=map"
date: "2020 August 14"
abstract: "
Die Pandemie ist derzeit weltweit weitverbreitet mit mehr als [1,5 Millionen neuen Faellen pro Woche](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports) und einer Gesamtzahl an berichteten Faellen von [18 Millionen](https://ourworldindata.org/covid-cases) und mehr als [600.000 Todesfaellen](https://ourworldindata.org/covid-deaths).
\n\n
### Die Situation [ist von der Weltgesundheitsorganisation WHO am 2.August 2020 zusammengefasst worden](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports):
\n\n
### **\"Sobald Laender angefangen haben Massnahmen im Gesundheits- und Sozialwesen zu lockern, die implementiert worden sind zur Einschraenkung der Verbreitung des Virus,  konnten viele dieser Laender eine Klusterbildung oder ein Wiederaufleben an steigenden Fallzahlen feststellen. Risikos und Schwachstellen haben sich weiter verstaerken koennen in fragilen, ressourcenarmen und von Konflikten betroffenen Gegenden.\"**
\n\n
### Die weltweite Sequenzierung des SARS-CoV-2 Genoms wurde unvermindert weitergefuehrt. Wir nutzen diese Daten in Nextstrain, um die geografische Ausbreitung und eine Weiterentwicklung des Virus verfolgen zu koennen.
Bis jetzt wurden ueber 75.000 Sequenzen aus der Hälfte der Länder der Welt  oeffentlich geteilt - eine Meisterleistung ermoeglicht durch Wissenschaftler und Gesundheitsbehoerden.
\n\n
### Wir verwenden Subsampling-Ansaetze, um potenzielle Stichprobenverzerrungen zu beseitigen und um sicherzustellen, dass Regionen und Zeiträume für die Analyse angemessen berücksichtigt werden.
(Das hilft auch den Rechenanforderungen.)
\n\n
### Im Folgenden ist die geografische Verteilung von ungefaehr 4300 Genomen dargestellt.
Jeder Kreis ist auf einem einzelnen Land zentriert, die Farbe indiziert die Region und der Radius steigt mit der Anzahl an sequenzierter Genome in dem Land ([Hier koennen Sie Hilfe zur Interpretation der Karte in Nextstrain finden](https://nextstrain.org/docs/visualisation/map-interpretation)).
\n\n
### In diesem Bericht untersuchen wir die globale genomische Epidemiologie von COVID-19 umfassend und geben spezifische Updates fuer jede Region weltweit.

---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Please add your names & links to the 'translators' section above -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- table of contents slide -->
# [COVID-19 Zusammenfassung](https://nextstrain.org/ncov/global/2020-08-11?d=map)

### Inhaltsverzeichnis
* [Globalde Kladenverteilung](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [D614G Spike Mutation](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [Situation in Asien](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [Situation in Ozeanien](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [Situation in Europa](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [Situation in Suedamerika](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [Situation in Afrika](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [Situation in Nordamerika](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [Abschliessende Zusammenfassung](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [Danksagung](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Nextstrain Quellen
* [BEGINNEN SIE HIER: Wie phylogenetische Bäume zu interpretieren sind.](https://nextstrain.org/narratives/trees-background/)
* [Fruehere Lageberichte.](https://nextstrain.org/ncov-sit-reps/)
* [Hintergrundwissen zu Coronaviren.](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Zusammenfassung

Wir haben oeffentlich zugaengliche SARS-CoV-2 Genome analysiert. Durch das Vergleichen dieser Virengenome untereinander kann die Verbreitung von COVID-19 sowohl global als auch kommunal charakterisiert werden.

- Asien hat ein einen hohen Anteil an 19A & 19B Kladen, waehrend 20A, 20B & 20C Kladen in Europa und Nordamerika dominieren.

- Auf globaler Ebene kann ein eindeutig Anstieg der D614G-Substitution im Spike Protein festgestellt werden. Ueber diese Variante wird gemutmasst, den Anstieg an SARS-CoV-2 Uebertragungen zu verursachen.

- Um den weltweiten aktuellen Stand der SARS-CoV-2 Daten darzustellen, betreiben wir 6 regionale und 1 globale Builds, die jeden Wochentag aktualisiert werden.

- In Asien gab es viele Uebertragungen zwischen den Laendern zu Beginn der Pandemie. Derzeit sehen wir einen Wechsel hin zu einer Verbreitung des Virus innerhlab des jeweiligen Landes. 

- Neuseelands Fälle sind in einem engen zeitlichen Bereich enthalten, der ihrer Beseitigung des Virus entspricht (bis zu dieser Woche). Der jüngste Anstieg der Fälle in Australien zeigt sich - zumindest in den bisher geteilten Stichproben - in einer engen Häufung von Fällen, die aus der zuvor zirkulierenden Vielfalt stammen. 

- SARS-CoV-2 bereitet sich sehr schnell in Europa aus - wahrscheinlich konnte sich das Virus in vielen Laendern ausbreiten bevor es festgestellt werden konnte. Das resultierte in einer starken Durchmischung an europaeischen Stichproben zu Beginn der Pandemie, was eine Einführungen von einem Ort zum anderen zu unterscheiden und zu identifizieren erschwert. Derzeit können wir deutlichere Varianten sehen, die mit bestimmten Ländern verbunden sind, da Viren durch Reisebeschränkungen eingeschränkt worden sind.

- Wie in anderen Regionen sichtbar, gab es in Suedamerika auch vielfache Einschleppungen des Virus, was einen Grossteil der bekannten Vielfalt von SARS-CoV-2 abdeckt. Nachdem Reisenbeschraenkungen eingefuehrt worden sind, ist eine Konzentrierung an Sequenzen sichtbar. Leider sind neuere Sequenzen trotz schwerer anhaltender Epidemien in vielen Ländern nicht ohne weiteres verfügbar.

- Afrika hatte auch viele verschiedene Einschleppungen zu Beginn der Pandemie. Nachfolgende Reiseeinschraenkungen scheinen die Durchmischung zwischen afrikanischen Laendern limitiert zu haben, wobei die meisten Sequenzen aus früherer zirkulierender Vielfalt im selben Land zu scheinen stammen.

- Ein anderes Bild zeigt sich in den USA, wo Inlandsreisen nicht stark eingeschraenkt worden sind: Wir erkennen sowohl eine Durschmischung zwischen allen Bundesstaaten als auch eine kommunal bedingte Uebertragung des Virus. In Mexiko & Zentralamerika sehen wir Beispiele für geografische Clusterbildung bei der Übertragung, insbesondere zwischen Kalifornien (USA) und Baja California (Mexiko)..

```


<!-- ############ SLIDE BREAK ############# -->
# [Weltweite Verteilung von Genvarianten](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

Seit der Entstehung des Virus Ende 2019 hat sich SARS-CoV-2 in verschieden Genvarianten mutieren koennen, die sich derzeit auch im Umlauf befinden. Um die Diskussion dieser Varianten zu erleichtern, haben wir sie in Klassen eingeteilt, die durch spezifische Signaturmutationen definiert sind.

Derzeit koennen 5 Hauptkladen definiert werden (unter [diesem Blog post](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming) koennen weitere Details entnommen werden):

* 19A und 19B stammten aus Wuhan und hat den Anfang der Epidemie beherrscht.
* 20A entstammte aus 19A, welche die Epidemie in Europa in Maerz dominiert hat und sich seitdem global ausbreitet.
* 20B und 20C sind grosse, genetisch eindeutige Unterkladen von 20A.


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


Gerade verfolgen wir die weltumfassende Verbreitung dieser Kladen (die Farbe repraesentiert die Kladenzugehoerigkeit).
Es gibt Laender in Asien, die einen hoeheren Anteil an 19A und 19B (hier in blau) aufweisen, was der Variantendominanz zu Beginn der Epidemie entspricht. Europa und Nordamerika weisen eine Durchmischung aller Kladen auf, wobei 20B und 20C (jeweils gelb und orange) dominieren.

#### Falls Sie SARS-CoV-2 Sequenzen haben und diese gerne einer Klade zuordnen wollen (und einer wahrscheinliche Position in einem phylogenetischen Baum), haben wir die Platform Nextclade generiert ([clades.nextstrain.org/](https://clades.nextstrain.org/)), unter der Sie mittels drag-and-drop Ihre FASTA Daten hochladen koennen.


<!-- ############ SLIDE BREAK ############# -->
# [Die bekannt gewordene D614G Spike Mutation](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

Die D614G-Substitution im Gen, das für das Spike (S) -Protein kodiert, war kürzlich in den Nachrichten und wurde vielfach spekuliert.

Es scheint, dass die G-Variante (hier gelb dargestellt) die Infektiositaet von SARS-CoV-2 _in vitro_ erhoeht und daher evolutionsbedingt fuer die Mensch-zu-Mensch Uebertragung ausgeaehlt worden ist ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). Allerdings kann eine Erhoehung der Infektiositaet das Virus anfaelliger fuer neutralisierende Antikoerper werden lassen ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

Hier können wir sehen, dass diese Variante sehr kurz nach der anfänglichen Zoonose aufgetreten ist und sich anschließend auf der ganzen Welt verbreitet hat.
Im Juli machte die 614G Variante den Grossteil der zirkuliernden Viren weltweit aus. Seit dem ersten Auftreten ist die Substitution mehrfach aufgetreten und wieder zur 614D-Variante zurückgefallen..
Es gibt keinen Beweis dafuer, dass diese Substitutionen oder Reversionen in kontinuierliche Uebertragungsketten resultiert sind. 


<!-- ############ SLIDE BREAK ############# -->
# [Regionale Builds unabhängig analysieren](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

Da es viel zu viele Genome fuer einen einzelnen Baum gibt, haben wir regionale Analysen fuer jede der 6 Regionen durchgefuehrt, die hier neben dem globalen Build dargestellt sind.
Das ermoeglicht uns die Diversitaet innerhalb jeder Region darstellen zu koennen und geeignete Stichproben außerhalb der Region auszuwählen, sodass wir einen Überblick über alle Übertragungen zwischen den Regionen über die Zeit behalten können - wie wir auf dieser Folie sehen können! 

Im Nachfolgenden stellen wir einen Ueberblick zu jeder dieser Regionen zur Verfuegung, in dem wir zum jeweiligen Datensatz wechseln. (Das ist ein neues Feature in Nextstrain!)

Ein vollständiges Inventar der von uns und anderen verwalteten Builds finden Sie unter [nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/).

<!-- ############ SLIDE BREAK ############# -->
# [Situation in Asien vor Juni](https://nextstrain.org/ncov/asia/2020-08-11?dmax=2020-06-01&d=map&f_region=Asia&legendOpen)

Wenn wir die Sitatuion in Asien anhand von Genomdaten, die vor Juni 2020 gesammelt worden sind, anschauen, sehen wir eine starke Uebertragung des Virus sowohl innerhalb Asiens als auch zu und aus anderen Teilen der Welt.

#### Interpretation der Linien und Punkte

Im Folgenden wuerden nur asiatische Laender angefaerbt, wobei andere Teile der Welt in grau gehalten worden sind. 
Die Farbe jeder Uebertragungslinie (Linien zwischen den Kreisen) repraesentiert den Ursprungsort, heisst dass alle "farbigen" Linien Uebertragungen darstellen, die aus einem Land innerhalb Asiens stammen (in diesem Beispiel).

#### Uebertragungen nach Asien

Das zeigt, dass viele Uebertragungen asiatischer und nicht-asiatischer Laender Einschleppungen nach Asien waren (graue Linien).
Besonders ausgepraegt in dieser Ansicht sind die Uebertragungen aus Europa nach Asien (obwohl es aussieht, als ob die Linie ihren Ursprung in Deutschland habe, soll dies ganz Europa repraesentieren). Wir müssen jedoch vorsichtig sein, wie wir diese abgeleiteten Übertragungen interpretieren, da Stichprobenverzerrungen eine große Rolle spielen können (und wir haben viel mehr Stichproben aus Europa als irgendwo anders).


<!-- ############ SLIDE BREAK ############# -->
# [Situation in Asien vor dem 1.Juni](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

Schaut man sich die genomischen Daten nach dem 1.Juni an (beispielsweise die letzten 2 Monate), sehen wir, dass die Beprobung von wenigen Laendern dominiert wird. Das schraenkt die Schlussfolgerungen, die wir treffen koennen, ein, aber es scheint, dass es weniger Uebertragungen zwischen den Laendern gibt.

Das ist auch in der Phylogenie sichtbar, wo große monophyletische (im gleichen Teil des Baumes) Gruppierungen von Genomen aus Singapur (gelb) und Bangladesch (hellgrün) auffindbar sind. 

Diese Daten sind mit kohaerent mit der Einschraenkung von Auslandsreisen und strenger Kontrolmassnahmen. 


<!-- ############ SLIDE BREAK ############# -->
# [Ueberblick ueber Ozeanien](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Im Folgenden sehen wir ungefaehr 790 Genome aus Australien und Neuseeland mit zusaetzlichen 1100 Sequenzen als globale Referenz. Nur Proben aus Ozeanien sind eingefaerbt worden.

Diese Proben sind ueber den ganzen Baum verteilt, was indiziert, dass Ozeanien (fast allen) entdeckten SARS-CoV-2 Varianten ausgesetzt war.

Der Grossteil der Neuseelandproben (hier blau, lila, gruen) stammen aus einem engen Zeitraum (zwischen Maerz und April). Dies liegt an der erfolgreichen Kontrollstrategie seitens der neuseelaendischen Regierung. Waehrend das Land  fast zurueck zur Normalitaet gelangt ist, sind die Grenzen fuer Nichtbuerger noch immer geschlossen, um die Chancen einer Wiederinfektion durch das Virus zu limitieren. Rueckkehrer muessen fuer 14 Tage in die Quarantaene bevor sie einreisen duerfen. 

Diese Woche berichtete die neuseelaendische Regierung ueber 4 Neuinfektionen, welche nicht mit ankommenden Faellen verknuepft werden konnten. Genetische Sequenzierung koennte bei der Aufklaerung, wie SARS-CoV-2 die strengen Kontrollen umgehen konnte, helfen -- Weiteres siehe unten!

_Tipp: Wenn Sie mit der Maus ueber die Kreise auf der Karte gehen, dann sehen Sie die relevanten Hinweise im Baum hervorgehoben!_


<!-- ############ SLIDE BREAK ############# -->
# [Wiederaufleben in Australien](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

In Australien und im Bundesstaat Victoria (Hauptstadt: Melbourne), die hier in Orange dargestellt sind, sind COVID-19-Fälle erneut aufgetreten, und kürzlich wurden weitere Maßnahmen im Bereich der öffentlichen Gesundheit ergriffen, um diesen Anstieg einzudämmen.

Die neusten Genome scheinen alle der Unterklade von Klade 20B zuzugehoeren (Scrollen Sie zurück zur vorherigen Folie, um zu sehen, wie Klade 20B in die gesamte Phylogenie passt).
Die neusten Daten und Klusters sind Anzeichen fuer eine lokale Epidemie.

Aehnliche Klusters koenne in den Sequenzen aus New South Wales gesehen werden, wo die Fallzahlen auch neuerdings zugenommen haben.


<!-- ############ SLIDE BREAK ############# -->
# [New cases detected in New Zealand this week](https://nextstrain.org/ncov/oceania/2020-08-11?c=gt-nuc_10097,23731&d=tree)

New Zealand had reported over 100 days without community transmission before detecting cases in the community this week.
The cluster has now spread to around 30 known cases (at time of publication), primarily based in the largest city, Auckland.

The source is not yet known, however scientists have sequenced the isolates and reported that they fall into pangolin lineage B1.1.1; so while the genomes are yet to be released they are known to fall in the region colored in blue here.
This lineage originated in Europe, but has since been observed in multiple regions around the world.


<!-- ############ SLIDE BREAK ############# -->
# [Early situation in Europe](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 spread rapidly across Europe, likely primarily through direct transmissions from Asia.

By the end of February, even though there were just [a few hundred cases](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea) officially reported in Europe, the virus had spread to at least 15 European countries.

Given that sampling was less common in the early days of the pandemic, SARS-CoV-2 was almost certainly already circulating across must of Europe, including in countries for which we don't have samples.


<!-- ############ SLIDE BREAK ############# -->
# [Lockdown in Europe](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

Through March and April much of Europe closed their borders, and many imposed differing types of 'lockdown' where movement was restricted and businesses and schools closed. We expect that these restrictions decreased between-country transmission, making it more likely that we see sequences from any given country 'cluster' with previous sequences from that country.

However, SARS-CoV-2 was already so mixed across Europe that different variants of the virus were circulating across multiple countries. Most countries had numerous distinct variants circulating before lockdown that were related to the viruses circulating in other countries. This means the phylogenetic picture remains well-mixed even after borders closed (shown by multiple colors near each other on the tree).

However, we can see some signs of the local transmission that we would expect. Here, Finland and Sweden have a very distinct transmission cluster in green and orange (about 1/3 from the top), while Spain (dark blue) shows distinct local transmission at the bottom and top of the tree. Iceland (purple) and Switzerland (light blue) also show clusters of local transmission.

_Hint: You can expand the legend by clicking 'Country' at the top-left of the tree!_


<!-- ############ SLIDE BREAK ############# -->
# [Recent European sequencing highlights local transmission and enriches understanding of previous SARS-CoV-2 spread](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

Examining only samples uploaded in the past week highlights two important points.

Firstly, we can see a tendency towards groupings of tips into mini-clusters. This indicates that within-country transmission is continuing to dominate - likely a product of the various regulations introduced throughout Europe. The virus continued to diversify genetically during the lockdown, but was more likely to be confined to one country, meaning we can often now better distinguish local 'variants' from those in other countries.

Some samples do not follow this trend of linking to other samples from the same country. Hovering over a country in the legend highlights tips in the tree from that country and will help identify such samples. For instance, in the middle of the tree, we can see some Swedish samples (green) nested within a larger Russian clade (red).
Given the heavy subsampling, we need to remain cautious to not over interpret putative between-country transmissions from this view.

Secondly, we can see that the tips have a large difference in horizontal spacing -- i.e. the samples submitted in the past week represent a sample collection time window extending back to early March.
The reasons for sequencing "old" genomes varies, but these samples help us fill in our understanding of viral evolution and geographical movement.


<!-- ############ SLIDE BREAK ############# -->
# [The early situation in South America](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmax=2020-04-15)

South America's first SARS-CoV-2 sequences are from late February and early March, and are scattered across the tree, suggesting multiple introductions. As international travel decreased in March, we can see evidence of sustained local transmission in several countries.

Many of Brazil's (light green) sequences are part of two large clusters (near top of the tree), with some evidence that this variant also moved around the continent to Chile, Uruguay, and Argentina.

We can also see distinct clusters of transmission involving Colombia (orange), Chile (turquoise), Uruguay (lighter blue), and Argentina (darker blue) scattered through the tree.


<!-- ############ SLIDE BREAK ############# -->
# [The more recent situation in South America](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmin=2020-05-01)

Unfortunately, while SARS-CoV-2 continues spreading widely in South America, sequence generation has not kept pace. Though cases remain high across much of the continent, only 68 samples from 5 countries (Brazil, Ecuador, Uruguay, Argentina, & Chile) have been shared since May.

Though our inferences are limited by the sparse sampling, in many cases these more recent samples nest within the earlier diversity sampled in the same country, or other South American countries. This suggests the varients circulating now are descendants of those introduced early in the epidemic.


<!-- ############ SLIDE BREAK ############# -->
# [SARS-CoV-2 in Africa](https://nextstrain.org/ncov/africa/2020-08-11?d=tree,map&f_region=Africa&legendOpen&transmissions=hide&p=grid)

Like South America, Africa had several introductions of SARS-CoV-2 to the continent, many likely from Europe. This is shown by the spread of African samples across the tree - even samples from the same country include diverse variants.

We now have sequences from countries across Africa throughout the epidemic, though sequencing efforts seem to have declined slightly more recently.
South Africa has contributed a large proportion of the sequencing.


<!-- ############ SLIDE BREAK ############# -->
# [Clustering in Africa](https://nextstrain.org/ncov/africa/2020-08-11?d=tree&f_region=Africa&legendOpen&p=full&f_country=Democratic%20Republic%20of%20the%20Congo,Senegal,South%20Africa)

In the DRC, Senegal, and South Africa, we can see clear signs of local transmission, shown as clusters of sequences in the tree.
From Senegal and South Africa, we also have samples collected more recently.
These samples generally fall within the older diversity of the country, as we would expect from continued local transmission.

Though we must be cautious with our conclusions as they are greatly limited by highly biased sampling, the recent samples from Africa we have do not suggest continued importation of variants from elsewhere.
This finding likely reflects the continued restrictions in movement globally.


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
