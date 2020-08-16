---
title: August 2020: Update zur genomischen Epidemiologie von COVID-19
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
translators: Elisabeth Hirth
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
### **\"Sobald Laender angefangen haben Massnahmen im Gesundheits- und Sozialwesen zu lockern, die implementiert worden sind zur Einschraenkung der Verbreitung des Virus,  konnten viele dieser Laender eine Klusterbildung oder ein Wiederaufleben an steigenden Fallzahlen feststellen. Risikos und Schwachstellen haben sich weiter in fragilen, ressourcenarmen und von Konflikten betroffenen Gegenden verstaerken koennen.\"**
\n\n
### Die weltweite Sequenzierung des SARS-CoV-2 Genoms wurde unvermindert weitergefuehrt. Wir nutzen diese Daten in Nextstrain, um die geografische Ausbreitung und eine Weiterentwicklung des Virus verfolgen zu koennen.
Bis jetzt wurden ueber 75.000 Sequenzen aus der Hälfte der Länder der Welt oeffentlich geteilt - eine Meisterleistung ermoeglicht durch Wissenschaftler und Gesundheitsbehoerden.
\n\n
### Wir verwenden Subsampling-Ansaetze, um potenzielle Stichprobenverzerrungen zu beseitigen und somit sicherstellen zu koennen, dass Regionen und Zeiträume für die Analyse angemessen berücksichtigt werden.
(Das hilft auch den Rechenanforderungen.)
\n\n
### Im Folgenden ist die geografische Verteilung von ungefaehr 4300 Genomen dargestellt.
Jeder Kreis ist auf einem einzelnen Land zentriert, die Farbe indiziert die Region und der Radius steigt mit der Anzahl an sequenzierter Genome in dem jeweiligen Land ([Hier koennen Sie Hilfe zur Interpretation der Karte in Nextstrain finden](https://nextstrain.org/docs/visualisation/map-interpretation)).
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

- Asien hat einen hohen Anteil an 19A & 19B Kladen, waehrend 20A, 20B & 20C Kladen in Europa und Nordamerika dominieren.

- Auf globaler Ebene kann ein eindeutiger Anstieg der D614G-Substitution im Spike Protein festgestellt werden. Ueber diese Variante wird gemutmasst, dass sie den Anstieg an SARS-CoV-2 Uebertragungen verursachen kann.

- Um den weltweiten aktuellen Stand der SARS-CoV-2 Daten darzustellen, betreiben wir 6 regionale und 1 globalen Builds, die jeden Wochentag aktualisiert werden.

- In Asien gab es viele Uebertragungen zwischen den Laendern zu Beginn der Pandemie. Derzeit sehen wir einen Wechsel hin zu einer Verbreitung des Virus innerhlab des jeweiligen Landes. 

- Neuseeland's Fälle sind in einem engen zeitlichen Bereich enthalten, der der Beseitigung des Virus entspricht (bis zu dieser Woche). Der jüngste Anstieg der Fälle in Australien zeigt - zumindest in den bisher geteilten Stichproben - eine engen Anhäufung von Fällen, die aus der zuvor zirkulierenden Vielfalt stammen. 

- SARS-CoV-2 bereitet sich sehr schnell in Europa aus - wahrscheinlich konnte sich das Virus in vielen Laendern ausbreiten bevor es festgestellt werden konnte. Das resultierte in einer starken Durchmischung an europaeischen Stichproben zu Beginn der Pandemie, was eine Einschleppung von einem Ort zum anderen zu unterscheiden und zu identifizieren erschwert. Derzeit können wir deutlichere Varianten sehen, die mit bestimmten Ländern verbunden sind, da die Virenausbreitung durch Reisebeschränkungen eingeschränkt worden ist.

- Wie in anderen Regionen sichtbar, gab es in Suedamerika auch vielfache Einschleppungen des Virus, was einen Grossteil der bekannten Vielfalt von SARS-CoV-2 abdeckt. Nachdem Reisebeschraenkungen eingefuehrt worden sind, ist eine Konzentrierung an Sequenzen sichtbar. Leider sind neuere Sequenzen trotz schwerer anhaltender Epidemien in vielen Ländern nicht ohne weiteres verfügbar.

- Afrika hatte auch viele verschiedene Einschleppungen zu Beginn der Pandemie. Nachfolgende Reiseeinschraenkungen scheinen die Durchmischung zwischen afrikanischen Laendern limitiert zu haben, wobei die meisten Sequenzen aus früherer zirkulierender Virenvielfalt im selben Land zu stammen scheint.

- Ein anderes Bild zeigt sich in den USA, wo Inlandsreisen nicht stark eingeschraenkt worden sind: Wir erkennen sowohl eine Durschmischung zwischen allen Bundesstaaten als auch eine kommunal bedingte Uebertragung des Virus. In Mexiko & Zentralamerika sehen wir Beispiele für geografische Klusterbildung bei der Übertragung, insbesondere zwischen Kalifornien (USA) und Baja California (Mexiko)..

```


<!-- ############ SLIDE BREAK ############# -->
# [Weltweite Verteilung von Genvarianten](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

Seit der Entstehung des Virus Ende 2019 hat sich SARS-CoV-2 in verschiedene Genvarianten mutieren koennen, die sich derzeit auch im Umlauf befinden. Um die Diskussion dieser Varianten zu erleichtern, haben wir sie in Klassen eingeteilt, die durch spezifische Signaturmutationen definiert sind.

Derzeit koennen 5 Hauptkladen definiert werden (unter [diesem Blog post](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming) koennen weitere Details entnommen werden):

* 19A und 19B stammten aus Wuhan und haben den Anfang der Epidemie beherrscht.
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

Die D614G-Substitution im Gen, das für das Spike (S) - Protein kodiert, war kürzlich in den Nachrichten und wurde vielfach diskutiert.

Es scheint, dass die G-Variante (hier gelb dargestellt) die Infektiositaet von SARS-CoV-2 _in vitro_ erhoeht und daher evolutionsbedingt fuer die Mensch-zu-Mensch Uebertragung ausgewaehlt worden ist ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). Allerdings kann eine Erhoehung der Infektiositaet das Virus anfaelliger fuer neutralisierende Antikoerper werden lassen ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

Hier können wir sehen, dass diese Variante sehr kurz nach der anfänglichen Zoonose aufgetreten ist und sich anschließend auf der ganzen Welt verbreitet hat.
Im Juli machte die 614G Variante den Grossteil der zirkuliernden Viren weltweit aus. Seit dem ersten Auftreten ist die Mutante mehrfach aufgetreten und wieder zur 614D-Variante zurückgefallen.
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

Im Folgenden wurden nur asiatische Laender angefaerbt, wobei andere Teile der Welt in grau gehalten worden sind. 
Die Farbe jeder Uebertragungslinie (Linien zwischen den Kreisen) repraesentiert den Ursprungsort, heisst dass alle "farbigen" Linien Uebertragungen darstellen, die aus einem Land innerhalb Asiens stammen (in diesem Beispiel).

#### Uebertragungen nach Asien

Das zeigt, dass viele Uebertragungen asiatischer und nicht-asiatischer Laender Einschleppungen nach Asien waren (graue Linien).
Besonders ausgepraegt in dieser Ansicht sind die Uebertragungen aus Europa nach Asien (obwohl es aussieht, als ob die Linie ihren Ursprung in Deutschland habe, soll dies ganz Europa repraesentieren). Wir müssen jedoch vorsichtig sein, wie wir diese abgeleiteten Übertragungen interpretieren, da Stichprobenverzerrungen eine große Rolle spielen können (und wir haben viel mehr Stichproben aus Europa als irgendwo anders her).


<!-- ############ SLIDE BREAK ############# -->
# [Situation in Asien nach dem 1.Juni](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

Schaut man sich die genomischen Daten nach dem 1.Juni an (beispielsweise die letzten 2 Monate), sehen wir, dass die Beprobung von wenigen Laendern dominiert wird. Das schraenkt die Schlussfolgerungen, die wir treffen koennen, ein. Aber es scheint, dass es weniger Uebertragungen zwischen den Laendern gibt.

Das ist auch in der Phylogenie sichtbar, wo große monophyletische (im gleichen Teil des Baumes) Gruppierungen von Genomen aus Singapur (gelb) und Bangladesch (hellgrün) auffindbar sind. 

Diese Daten sind kohaerent mit der Einschraenkung von Auslandsreisen und strenger Kontrolmassnahmen. 


<!-- ############ SLIDE BREAK ############# -->
# [Ueberblick ueber Ozeanien](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Im Folgenden sehen wir ungefaehr 790 Genome aus Australien und Neuseeland mit zusaetzlichen ca. 1100 Sequenzen als globale Referenz. Nur Proben aus Ozeanien sind eingefaerbt worden.

Diese Proben sind ueber den ganzen Baum verteilt, was indiziert, dass Ozeanien (fast allen) entdeckten SARS-CoV-2 Varianten ausgesetzt war.

Der Grossteil der Neuseelandproben (hier blau, lila, gruen) stammen aus einem engen Zeitraum (zwischen Maerz und April). Dies liegt an der erfolgreichen Kontrollstrategie seitens der neuseelaendischen Regierung. Waehrend das Land  fast zurueck zur Normalitaet gelangt ist, sind die Grenzen fuer Nichtbuerger noch immer geschlossen, um die Chancen einer Wiederinfektion durch das Virus zu limitieren. Rueckkehrer muessen fuer 14 Tage in die Quarantaene bevor sie einreisen duerfen. 

Diese Woche berichtete die neuseelaendische Regierung ueber 4 Neuinfektionen, welche nicht mit ankommenden Faellen verknuepft werden konnten. Genetische Sequenzierung koennte bei der Aufklaerung helfen, wie SARS-CoV-2 die strengen Kontrollen umgehen konnte -- Weiteres siehe unten!

_Tipp: Wenn Sie mit der Maus ueber die Kreise auf der Karte gehen, dann sehen Sie die relevanten Hinweise im Baum hervorgehoben!_


<!-- ############ SLIDE BREAK ############# -->
# [Wiederaufleben in Australien](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

In Australien und im Bundesstaat Victoria (Hauptstadt: Melbourne), die hier in orange dargestellt sind, sind COVID-19-Fälle erneut aufgetreten und kürzlich wurden weitere Maßnahmen im Bereich der öffentlichen Gesundheit ergriffen, um diesen Anstieg einzudämmen.

Die neusten Genome scheinen alle der Unterklade von Klade 20B zuzugehoeren (Scrollen Sie zurück zur vorherigen Folie, um zu sehen, wie Klade 20B in die gesamte Phylogenie passt).
Die neusten Daten und Klusters sind Anzeichen fuer eine lokale Epidemie.

Aehnliche Klusters koenne in den Sequenzen aus New South Wales gesehen werden, wo die Fallzahlen auch neuerdings zugenommen haben.


<!-- ############ SLIDE BREAK ############# -->
# [Neue Faelle wurden in Neuseeland diese Woche gemeldet](https://nextstrain.org/ncov/oceania/2020-08-11?c=gt-nuc_10097,23731&d=tree)

Neuseeland hatte zuvor gemeldet, dass es keine Community Uebertragungen in einem Zeitraum von 100 Tagen gegeben hatte. Jedoch wurden innert dieser Wochhe neue Faelle gemeldet. Das Cluster hat sich nun um 30 bekannte Faelle erhoeht (bis zum Zeitpunkt der Veroeffentlichung), hauptsaechlich innerhalb der groessten Stadt Auckland.

Die Quelle ist bis jetzt noch unbekannt, aber Wissenschaftler haben die Virusisolate sequenziert und berichtet, dass diese in die Pangolin-Linie B1.1.1 fallen; Bis jetzt weiss man also bevor die Genomdaten veroeffentlicht werden, dass sie in die hier blau eingefaerbte Region passen. Diese Virenlinie hat ihren Ursprung in Europa, aber wurde bereits in mehreren Teilen der Welt gefunden.


<!-- ############ SLIDE BREAK ############# -->
# [Anfaenge in Europa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 hat sich schnell innerhalb Europas ausbreiten koennen, hauptsaechlich durch direkte Uebertragungsketten aus Asien.

Obwohl nur [einigen 100 Faellen](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea) in Europa bis Ende Februar berichtet worden war, war das Virus zu diesem Zeitpunkt bereits in mindestens 15 Laendern detektiert worden.

Geht man von einer niedrigen Testrate innerhalb der Anfaenge der Pandemie aus, kann davon ausgegangen werden, dass das Virus schon frueh in Europa im Umlauf gewesen sein musste, auch in Laendern, aus denen wir keinerlei Proben haben.


<!-- ############ SLIDE BREAK ############# -->
# [Lockdown in Europa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

Zwischen Maerz und April waren die Grenzen groesstenteils innerhalb Europas geschlossen und viele Laender implementierten unterschiedliche "Lockdown"-Methoden, wie zum Beispiel die Einschraenkung der Bewegungsfreiheit und das Schliessen von Schulen und Geschaeften. Wir erwarten daher einen Abfall in der Uebertragungsrate zwischen den Laendern, was bedeutet, dass jegliche Sequenzen aus einem Land mit frueheren Sequenzen aus diesem Land klustern. 

Dennoch konnte sich SARS-CoV-2 bereits so stark innerhalb Europas ausbreiten, so dass verschiedene Varianten in vielen Laendern auffindbar sind. Viele Laender hatten zahlreiche eindeutige Varianten vor dem Lockdown, die bereits mit anderen Viren in anderen Laendern verwandt waren. Das bedeutet, dass das phylogenetische Bild sehr durchmischt ist, obwohl Grenzen geschlossen worden sind (hier durch nah beieinander liegende Farben auf einem Baum indiziert).

Aber es gibt ein paar erwartungsgemaesse Hinweise zur komunalen Uebertragung. Finnland und Schweden weisen ausgepraegte Uebertragunsgkluster in gruen und orange auf (ca. 1/3 von oben), waehrend hingegen Spanien (dunkelblau) eine eindeutige lokale Uebertragunge an beiden Baumenden aufweist. Sowohl Island (lila) als auch die Schweiz (hellblau) weisen lokale Uebertragungskluster vor. 

_Tipp: Die Legende kann durch klicken auf 'Country' oben links im Baum erweitert werden!_


<!-- ############ SLIDE BREAK ############# -->
# [Kuerzliche europaeische Sequenzsdaten heben die lokale Uebertragung hervor und helfen uns die fruehere Ausbreitung von SARS-CoV-2 besser zu verstehen](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

Wenn man nur Proben aus den letzten paar Wochen betrachtet, dann koennen 2 wichtige Punkte festgestellt werden:

Erstens sehen wir eine Tendenz hinzu Gruppierungsn aus Baumspitzen in Minikluster. Das deutet darauf hin, dass Uebertragung zwischen den Laendern weiterhin dominant ist - hoechstwahrscheinlich aufgrund von verschiedenen implementierten Regulationen innerhalb Europas. Das Virus konnte waehrend des Lockdowns weiterhin mutieren, aber war wahrscheinlich beschraenkt auf ein Land, was bedeutet, dass wir lokale "Varianten" von denen aus anderen Laendern besser unterscheiden koennen. 

Einige Proben folgen nicht diesem Zuegehoerigkeitstrend. Faehrt man ueber ein Land in der Legende, werden die Baumspitzen hervorgehoben, was hilfreich zur Identifikation solcher Proben ist. Beispielsweise sieht man in der Baummitte einige schwedische Proben (gruen) innerhalb einer grossen russichen Klade (rot).
Aufgrund von starkem Subsampling sollte man trotzdem vorsichtig mit Interpretationen bezueglich potenzieller Uebertragungen zwischen einzelnen Laendern sein.

Zweitens sehen wir, dass die Baumspitzen grosse Unterschiede in den horizontalen Abbstaenden aufweisen -- z.B. sind die Proben, die letzte Woche hochgeladen worden sind eine Probensammlung, die bis Anfang Maerz zurueckreicht.
Die Gruende fuer das Sequenzieren von "alten" Proben sind sehr vielfaeltig, aber diese Proben helfen uns die Virusentwicklung und geographische Ausbreitung besser verstehen zu koennen.


<!-- ############ SLIDE BREAK ############# -->
# [Die anfaengliche Situation in Suedamerika](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmax=2020-04-15)

Die ersten suedamerikanischen SARS-CoV-2 Sequenzen stammen von Ende Februar bzw. Anfang Maerz und sind ueber den gesamten Baum verstreut, was auf viele Einschleppungen hindeutet. Sobald Auslandsreisen im Maerz eingeschraenkt worden sind, sieht man Hinweise auf eine anhaltenden Uebertragungsrate in verschiedenen Laendern.

Viele brasilianische Sequenzen (hellgruen) sind Teil von 2 grossen Klustern (in der Naehe von der Baumspitze). Das deutet darauf hin, dass diese Variante sowohl in Chile als auch Uruguay und Argentinien im Umlauf ist. 

Zusaetzlich gibt es eindeutige Uebertragungskluster in Kolumbien (orange), Chile (tuerkis), Uruguay (hellblau) und Argentinien (dunkelblau), die ueber den gesamten Baum verstreut sind. 


<!-- ############ SLIDE BREAK ############# -->
# [Die jetzige Situation in Suedamerika](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmin=2020-05-01)

Waehrend SARS-CoV-2 weiterhin im Umlauf ist und sich stark in Suedamerika ausbreitet, konnte die Sequenzierarbeit leider nicht mithalten. Obwohl die Fallzahlen kontinental sehr hoch sind, wurden nur 68 Proben aus 5 Laendern (Brasilien, Equador, Uruguay, Argentinien und Chile) seit Mai geteilt.

Trotz dass unsere Schlussfolgerungen wegen dieser niedrigen Beprobungsrate sind, sieht man, dass viele dieser erst kuerzlich sequenzierter Proben zu der anfaenglich diversen Probenpopulation innerhalb eines Landes oder anderer suedamerikanischer Laender passt. Das deutet darauf hin, dass die Virusvarianten, die gerade im Umlauf sind Nachkoemmlinge derer sind, die am Anfang der Epidemie eingeschleppt worden sind.


<!-- ############ SLIDE BREAK ############# -->
# [SARS-CoV-2 in Afrika](https://nextstrain.org/ncov/africa/2020-08-11?d=tree,map&f_region=Africa&legendOpen&transmissions=hide&p=grid)

Sowie nach Suedamerika gab es auch mehrerer Einschleppungen des Virus SARS-CoV-2 nach Afirka, hoechstwahrscheinlich aus Europa. Das zeigt sich durch die Verteilung der afrikanischen Proben im Baum - sogar Proben aus dem gleichen Land weisen unterschiedliche Virusvarianten auf.

Wir haben nun Sequenzierdaten von Laendern in Afrika im Verlauf der Epidemie, wobei die Sequenzierarbeit derzeit leicht abnimmt. Suedafrika hat einen Grossteil an Sequenzierdaten beigetragen.


<!-- ############ SLIDE BREAK ############# -->
# [Clustering in Afrika](https://nextstrain.org/ncov/africa/2020-08-11?d=tree&f_region=Africa&legendOpen&p=full&f_country=Democratic%20Republic%20of%20the%20Congo,Senegal,South%20Africa)

Wir finden eine eindeutige lokale Uebertragung, die sich durch Sequenzenkluster im Baum manifestiert, in der DR Kongo, im Senegal und in Suedafrika. Aus dem Senegal und Siedafrika gibt es aktuelle Proben. Diese Proben fallen in die alte gleiche Virenvielfalt des jeweiligen Landes, wie es von einer angehenden landesweiten Uebertragung erwartet werden wuerde.

Trotzdem muss man vorsichtig mit vorzeitigen Schlussfolgerungen sein aufgrund hoher Stichprobenverzerrung. Zudem zeigen die jetzigen Proben aus Afrika keine anhaltende Einfuehrung von Virusvarianten anderswoher. Das reflektiert die derzeitigen weltweiten Reisebeschraenkungen.


<!-- ############ SLIDE BREAK ############# -->
# [Die Epidemie in den USA ist eine Mischung aus lokaler und zwischen den Laendern Uebertragung](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&p=full)

Im Folgenden sieht man genomische Daten aus der Epidemie in den USA vom 15. April bis zum heutigen Datum. Mitte April waren alle U.S. amerikanischen Staaten im Lockdown. [Die Bundesstaaten haben seitdem unterschiedlichhe Wiedereroeffnungen implementiert](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html).

In diesem Baum - aehnlich wie in den Baeumen aus anderen Gegenden - sehen wir Beispiele fuer eine lokale Virusuebertragung, die hier durch das Klustern von aehnlich angefaerbten Baumspitzen ueber die Zeit indiziert wird. Wenn Sie nun auf "Explore the Data Yourself" klicken und Yakima County heraus filtern, kann man ein eindeutiges Beispiel fuer die Einschleppung und die Zunahme an genetisch verwandten Viren in dieser Region in dem Bundesstaat Washington finden. (Sie koennen auch [hier klicken](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&f_location=Yakima%20County&p=grid), aber dafuer muessen Sie diesen Bericht verlassen.)

Auf dem Baum sehen wir jedoch auch eine Übertragung innerhalb des Landes in den USA, das durch das Mischen der Farben an den Baumspitzen gezeigt wird. Auf der Karte sieht die Übertragung innerhalb eines Landes wie eine Übertragungsleitung zwischen den Staaten aus. Diese Beobachtungen stehen im Einklang mit wenigen inländischen Reisebeschränkungen und den Richtlinien zur Wiedereröffnung von Staaten.


<!-- ############ SLIDE BREAK ############# -->
# [Zentralamerika weist eine geografisch beschraenkte Uebertragung auf](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map,entropy&f_country=Belize,Costa%20Rica,Guatemala,Jamaica,Mexico,Panama&p=grid&transmissions=hide)

Sequenzierungen in den letzten 2 Monaten hat in Zentralamerika nachgelassen, was Schlussfolgerungen zur aktuellen Lage der Epidemie vorort erschwert. Wir sehen ein geografisches Klustern von SARS-CoV-2-Genomen innerhalb der vorhandenen Sequenzierdaten.

Am Boden des Baumes der 19B Klade gibt es ein Uebertragungskluster in Panama, das Mitte Februar angefangen hat. Einigen Sequenzierdaten aus Panama (Juni bis Juli) passen in dieses Kluster hinein, was darauf hindeutet, dass die oertliche Uebertragung dieses Virengenotyps im Land weitergeht.

In Mexiko gibt es ein eindeutiges geografisches Uebertragungskluster im Mai, aber ohne weitere Sequenzierdaten koennen keine naeheren Aussagen zu der Epidemie gemacht werden.

In der Baummitte gibt es ein Fallkluster in Baja California (hellblau). Diese Faelle stammen hoechstwahrscheinlich aus Kalifornien, USA (gruene Aeste) im Maerz. Diese abgeleitete Einschleppung des Virus steht im Einklang mit bekannten Reiseverbindungen zwischen den benachbarten Standorten, obwohl wir bei der Interpretation abgeleiteter Übertragungsorte bei geringer Sequenzierung vorsichtig sein sollten


<!-- ############ SLIDE BREAK ############# -->
# [Schlusswort](https://nextstrain.org/ncov/global/2020-08-11?d=map)

Waehrend die Pandemie seit ungefaehr 8 Monaten weltweit im Umlauf ist, koennen wir eindeutige Veraenderungen ueber die Zeit in Form von Virengenetik und starken Verhaltensaenderungen. 

Viele anfaengliche Uebertragungen in die USA, nach Ozeanine, Europa und Asien waren zunaechst stark durchmischt aufgrund von Auslandsreisen, die die Ausbreitung des Virus verstaerkt hatten. Kurze Zeit spaeter entwickelten sich oertliche Epidemien in Suedamerika und Afrika, aufgrund von Viruseinschleppungen hauptsaechlich aus Europa und Nordamerika.

Als das Ausmass der Virusausbreitung und die Schlimme von COVID-19 bewusst wurde, wurde das Reisen weltweit vielerorts eingeschraenkt. Anschliessend sieht man eine eindeutige Verlagerung hinzu oertlichen Uebertragungen des Virus waherend der "Lockdowns" und der strengsten Reisebeschraenkungen. Ein Ergebnis ist, dass wir nun teilweise den Ursprung der Viren festmachen koennen, da die Epidemien mancherorts genetisch eindeutig sind. In den USA hat das Fehlen strenger Inlandsreisen dazu beigetragen, die gemischten Epidemien zwischen den Staaten aufrechtzuerhalten

Grenzen werden nun wieder geoeffnet und Reisen ist wieder moeglich, obwohl wir noch nicht vorpandemische Zustaende erreicht haben. Dies, zusammen mit der Verzögerungszeit von der Probenahme bis zur öffentlichen Verfügbarkeit, bedeutet, dass wir nur wenige Anzeichen einer Vermischung zwischen den Ländern ausmachen koennen. Generell klustern neue Proben tendenziell weiterhin mit alten Proben aus demselben Land, was darauf hinweist, dass die Uebertragung mit bereits zirkulierenden Virusvarianten verlaeuft. 

Leider konnten einige Laender einen Anstieg an Fallzahlen innerhalb der letzten paar Wochen festmachen, was wahrscheinlich auf die Lockerungen der Massnahmen zurueuckfuehrbar ist. Waehrend sich die noerdliche Hemisphaere auf den Herbst und kaelteres Wetter, weitere Lockerungen und Schulbeginn vorbereitet, sollten wir weiterhin wachsam den Anstieg der Fallzahlen beobachten. Da Winter in der suedlichen Hemisphaere voranschreitet, sehen wir besorgniserregende Anzeichen dafuer, dass die Saesonalitaet tatsaechlich zu Problemen bei der Uebertragung fuehren kann - Australiens anfaenglicher Erfolg mit dem Virus wurde durch die neueren Ausbrueche gedaempft. Wenn wir weiterhin verstaerkt testen, Kontaktverfolgung praktizieren, Faelle isolieren, sorgfaeltige Handhygiene durchfuehren und gewissenhaft Masen Tragen, koennen wir unsere Gesellschaften weitestgehend offen halten waehrend wir weiterhin SARS-CoV-2 bekaempfen.

<!-- ############ SLIDE BREAK ############# -->
# [Wissenschaftliche Danksagung](https://nextstrain.org/ncov/global/2020-08-11?d=tree&c=author)

Wir wuerden uns recht herzlich bei allen Wissenschaftlern weltweit fuer ihr bewundernswertes und zeitaufwaendiges Engagegement in dieser Epidemie bedanken.
Nur durch das schnelle Teilen von genomischen Daten und Metadaten konnten Analysen wie diese moeglich gemacht werden.

**Wir moechten Sie gerne dazu ermutigen auf 'Explore the Data Yourself' zu klicken und runter zu scrollen, um eine komplette Autorenliste zu finden; der Autor jeder einzelnen Sequenz kann durch Auswahl im Baum gefunden werden.**

Wir moechten uns auch recht herzlich bei GISAID bedanken fuer das Bereitstellen der Platform, mit der diese Daten hochgeladen und geteilt werden konnten.
