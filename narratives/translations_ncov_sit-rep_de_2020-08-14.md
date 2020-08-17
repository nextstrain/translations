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
Das neuartige Coronavirus ist derzeit weltweit verbreitet, mit mehr als [1,5 Millionen neün Fällen pro Woche](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports) und einer Gesamtzahl an bestätigten Fällen von [18 Millionen](https://ourworldindata.org/covid-cases) und mehr als [600.000 Todesfällen](https://ourworldindata.org/covid-deaths).
\n\n
### Die Situation [ist von der Weltgesundheitsorganisation WHO am 2.August 2020 zusammengefasst worden](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports):
\n\n
### **\"Sobald Länder angefangen haben Massnahmen in Gesellschaft und Gesundheitswesen zu lockern, die zur Eindämming der Verbreitung des Virus implementiert worden sind,  konnten viele dieser Länder Cluster oder ein Wiederansteigen der Fallzahlen feststellen. Insbesondere fragile, ressourcenarme und von Konflikten betroffenen Gegenden haben ein erhöhtes Risiko und sind verwundbar.\"**
\n\n
### Die weltweite Sequenzierung von SARS-CoV-2 Genomen wurde unvermindert weitergeführt. Wir nutzen diese Daten in Nextstrain, um die geografische Ausbreitung und Weiterentwicklung des Viruses verfolgen zu können.
Bis jetzt wurden über 75.000 Sequenzen aus der Hälfte der Länder weltweit öffentlich geteilt - eine Meisterleistung ermöglicht durch Wissenschaftler und Gesundheitsbehörden.
\n\n
### Wir verwenden Subsampling-Ansätze, um potenzielle Stichprobenverzerrungen zu beseitigen und somit sicherstellen zu können, dass alle Regionen und Zeiträume für die Analyse angemessen berücksichtigt werden.
(Das hilft auch die Analyze zu beschleunigen.)
\n\n
### Im Folgenden ist die geografische Verteilung von ungefähr 4300 Genomen dargestellt.
Jeder Kreis ist auf einem einzelnen Land zentriert, die Farbe indiziert die Region und der Radius steigt mit der Anzahl an sequenzierter Genome in dem jeweiligen Land ([Hier können Sie Hilfe zur Interpretation der Karte in Nextstrain finden](https://nextstrain.org/docs/visualisation/map-interpretation)).
\n\n
### In diesem Bericht untersuchen wir die globale genomische Epidemiologie von COVID-19 umfassend und geben spezifische Updates für jede Region weltweit.

---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Please add your names & links to the 'translators' section above -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text dösn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- table of contents slide -->
# [COVID-19 Zusammenfassung](https://nextstrain.org/ncov/global/2020-08-11?d=map)

### Inhaltsverzeichnis
* [Globale Kladenverteilung](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [D614G Spike Mutation](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [Situation in Asien](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [Situation in Ozeanien](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [Situation in Europa](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [Situation in Südamerika](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [Situation in Afrika](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [Situation in Nordamerika](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [Abschliessende Zusammenfassung](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [Danksagung](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Nextstrain Qüllen
* [BEGINNEN SIE HIER: Wie phylogenetische Bäume zu interpretieren sind.](https://nextstrain.org/narratives/trees-background/)
* [Frühere Lageberichte.](https://nextstrain.org/ncov-sit-reps/)
* [Hintergrundwissen zu Coronaviren.](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Zusammenfassung

Wir haben öffentlich zugängliche SARS-CoV-2 Genome analysiert. Durch das Vergleichen dieser Virengenome untereinander kann die Verbreitung von COVID-19 sowohl global als auch kommunal charakterisiert werden.

- Asien hat einen hohen Anteil an 19A & 19B Kladen, während 20A, 20B & 20C Kladen in Europa und Nordamerika dominieren.

- Auf globaler Ebene kann ein eindeutiger Anstieg der D614G-Substitution im Spike Protein festgestellt werden. Ueber diese Variante wird gemutmasst, dass sie den Anstieg an SARS-CoV-2 Uebertragungen verursachen kann.

- Um den weltweiten aktüllen Stand der SARS-CoV-2 Daten darzustellen, betreiben wir 6 regionale und 1 globalen Builds, die jeden Wochentag aktualisiert werden.

- In Asien gab es viele Uebertragungen zwischen den Ländern zu Beginn der Pandemie. Derzeit sehen wir einen Wechsel hin zu einer Verbreitung des Virus innerhlab des jeweiligen Landes.

- Neuseeland's Fälle sind in einem engen zeitlichen Bereich enthalten, der der Beseitigung des Virus entspricht (bis zu dieser Woche). Der jüngste Anstieg der Fälle in Australien zeigt - zumindest in den bisher geteilten Stichproben - eine enge Anhäufung von Fällen, die aus der zuvor zirkulierenden Vielfalt stammen.

- SARS-CoV-2 bereitete sich sehr schnell in Europa aus - wahrscheinlich konnte sich das Virus in vielen Ländern ausbreiten bevor es festgestellt werden konnte. Das resultierte in einer starken Durchmischung an europäischen Stichproben zu Beginn der Pandemie, was eine Einschleppung von einem Ort zum anderen zu unterscheiden und zu identifizieren erschwert. Derzeit können wir deutlichere Varianten sehen, die mit bestimmten Ländern verbunden sind, da die Virenausbreitung durch Reisebeschränkungen eingeschränkt worden ist.

- Wie in anderen Regionen sichtbar, gab es in Südamerika auch vielfache Einschleppungen des Virus, was einen Grossteil der bekannten Vielfalt von SARS-CoV-2 abdeckt. Nachdem Reisebeschränkungen eingeführt worden sind, ist eine Konzentrierung an Sequenzen sichtbar. Leider sind neüre Sequenzen trotz schwerer anhaltender Epidemien in vielen Ländern nicht ohne weiteres verfügbar.

- Afrika hatte viele verschiedene Einschleppungen zu Beginn der Pandemie. Nachfolgende Reiseeinschränkungen scheinen die Verbreitung von Viren zwischen afrikanischen Ländern limitiert zu haben, wobei die meisten Sequenzen von früherer zirkulierender Viren im selben Land abzustammen scheinen.

- Ein anderes Bild zeigt sich in den USA, wo Inlandsreisen nicht stark eingeschränkt worden sind: Wir erkennen sowohl eine Durschmischung zwischen allen Bundesstaaten als auch eine kommunal bedingte Uebertragung des Virus. In Mexiko & Zentralamerika sehen wir Beispiele für geografische Klusterbildung bei der Übertragung, insbesondere zwischen Kalifornien (USA) und Baja California (Mexiko).

```


<!-- ############ SLIDE BREAK ############# -->
# [Weltweite Verteilung von Genvarianten](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

Seit der Entstehung des Virus Ende 2019 hat sich SARS-CoV-2 in verschiedene Genvarianten mutieren können, die sich derzeit auch im Umlauf befinden. Um die Diskussion dieser Varianten zu erleichtern, haben wir sie in Klassen eingeteilt, die durch spezifische Signaturmutationen definiert sind.

Derzeit können 5 Hauptkladen definiert werden (unter [diesem Blogpost](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming) können weitere Details entnommen werden):

* 19A und 19B stammten aus Wuhan und haben den Anfang der Epidemie beherrscht.
* 20A entstammte aus 19A, welche die Epidemie in Europa im März dominiert hat und sich seitdem global ausbreitet.
* 20B und 20C sind grosse, genetisch eindeutige Unterkladen von 20A.


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


Gerade verfolgen wir die weltumfassende Verbreitung dieser Kladen (die Farbe repräsentiert die Kladenzugehörigkeit).
Es gibt Länder in Asien, die einen höheren Anteil an 19A und 19B (hier in blau) aufweisen, was der Variantendominanz zu Beginn der Epidemie entspricht. Europa und Nordamerika weisen eine Durchmischung aller Kladen auf, wobei 20B und 20C (jeweils gelb und orange) dominieren.

#### Falls Sie SARS-CoV-2 Sequenzen haben und diese gerne einer Klade zuordnen wollen (und einer wahrscheinliche Position in einem phylogenetischen Baum), haben wir die Platform Nextclade generiert ([clades.nextstrain.org/](https://clades.nextstrain.org/)), unter der Sie mittels drag-and-drop Ihre FASTA Daten hochladen können.


<!-- ############ SLIDE BREAK ############# -->
# [Die bekannt gewordene D614G Spike Mutation](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

Die D614G-Substitution im Gen, das für das Spike (S) - Protein kodiert, war kürzlich in den Nachrichten und wurde vielfach diskutiert.

Es scheint, dass die G-Variante (hier gelb dargestellt) die Infektiosität von SARS-CoV-2 _in vitro_ erhöht und daher evolutionsbedingt für die Mensch-zu-Mensch Uebertragung ausgewählt worden ist ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). Allerdings kann eine Erhöhung der Infektiosität das Virus anfälliger für neutralisierende Antikörper werden lassen ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

Hier können wir sehen, dass diese Variante sehr kurz nach der anfänglichen Zoonose aufgetreten ist und sich anschließend auf der ganzen Welt ausgebreitet hat.
Im Juli machte die 614G Variante den Grossteil der zirkuliernden Viren weltweit aus. Seit dem ersten Auftreten ist die Mutante mehrfach aufgetreten und wieder zur 614D-Variante zurückgefallen.
Es gibt keinen Beweis dafür, dass diese widerholten Substitutionen oder Reversionen zu kontinuierliche Uebertragungsketten geführt haben.


<!-- ############ SLIDE BREAK ############# -->
# [Regionale Builds unabhängig analysieren](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

Da es viel zu viele Genome für einen einzelnen Baum gibt, haben wir regionale Analysen für jede der 6 Regionen durchgeführt, die hier neben dem globalen Build dargestellt sind.
Das ermöglicht uns die Diversität innerhalb jeder Region darstellen zu können und geeignete Stichproben außerhalb der Region auszuwählen, sodass wir einen Überblick über alle Übertragungen zwischen den Regionen über die Zeit behalten können - wie wir auf dieser Folie sehen können!

Im Nachfolgenden stellen wir einen Ueberblick zu jeder dieser Regionen zur Verfügung, in dem wir zum jeweiligen Datensatz wechseln. (Das ist ein neüs Feature in Nextstrain!)

Ein vollständiges Inventar der von uns und anderen verwalteten Builds finden Sie unter [nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/).

<!-- ############ SLIDE BREAK ############# -->
# [Situation in Asien vor Juni](https://nextstrain.org/ncov/asia/2020-08-11?dmax=2020-06-01&d=map&f_region=Asia&legendOpen)

Wenn wir die Situation in Asien anhand von Genomdaten, die vor Juni 2020 gesammelt worden sind, anschaün, sehen wir eine starke Uebertragung des Virus sowohl innerhalb Asiens als auch zu und aus anderen Teilen der Welt.

#### Interpretation der Linien und Punkte

Im Folgenden wurden nur asiatische Länder angefärbt, wobei andere Teile der Welt in grau gehalten worden sind.
Die Farbe jeder Uebertragungslinie (Linien zwischen den Kreisen) repräsentiert den Ursprungsort, heisst dass alle "farbigen" Linien Uebertragungen darstellen, die aus einem Land innerhalb Asiens stammen (in diesem Beispiel).

#### Uebertragungen nach Asien

Das zeigt, dass viele Uebertragungen zwischen asiatischen und nicht-asiatischen Länder Einschleppungen nach Asien waren (graü Linien).
Besonders ausgeprägt in dieser Ansicht sind die Uebertragungen aus Europa nach Asien (obwohl es aussieht, als ob die Linie ihren Ursprung in Deutschland habe, soll dies ganz Europa repräsentieren). Wir müssen jedoch vorsichtig sein, wie wir diese abgeleiteten Übertragungen interpretieren, da Stichprobenverzerrungen eine große Rolle spielen können (und wir haben viel mehr Stichproben aus Europa als irgendwo anders her).


<!-- ############ SLIDE BREAK ############# -->
# [Situation in Asien nach dem 1.Juni](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

Schaut man sich die genomischen Daten nach dem 1.Juni an (beispielsweise die letzten 2 Monate), sehen wir, dass die Beprobung von wenigen Ländern dominiert wird. Das schränkt die Schlussfolgerungen, die wir treffen können, ein. Aber es scheint, dass es weniger Uebertragungen zwischen den Ländern gibt.

Das ist auch in der Phylogenie sichtbar, wo große monophyletische (im gleichen Teil des Baumes) Gruppierungen von Genomen aus Singapur (gelb) und Bangladesch (hellgrün) auffindbar sind.

Diese Daten sind kohärent mit der Einschränkung von Auslandsreisen und strenger Kontrolmassnahmen.


<!-- ############ SLIDE BREAK ############# -->
# [Ueberblick über Ozeanien](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Im Folgenden sehen wir ungefähr 790 Genome aus Australien und Neuseeland mit zusätzlichen ca. 1100 Sequenzen als globale Referenz. Nur Proben aus Ozeanien sind eingefärbt worden.

Diese Proben sind über den ganzen Baum verteilt, was indiziert, dass Ozeanien (fast allen) entdeckten SARS-CoV-2 Varianten ausgesetzt war.

Der Grossteil der Proben aus Neuseeland (hier blau, lila, grün) stammen aus einem engen Zeitraum (zwischen März und April). Dies liegt an der erfolgreichen Kontrollstrategie seitens der neuseeländischen Regierung. Während das Land fast zurück zur Normalität gelangt ist, sind die Grenzen für Nichtbürger noch immer geschlossen, um die Chancen einer Wiederinfektion durch das Virus zu limitieren. Rückkehrer müssen für 14 Tage in die Quarantäne bevor sie einreisen dürfen.

Diese Woche berichtete die neuseeländische Regierung über 4 Neuinfektionen, welche nicht mit ankommenden Fällen verknüpft werden konnten. Genetische Sequenzierung könnte bei der Aufklärung helfen, wie SARS-CoV-2 die strengen Kontrollen umgehen konnte -- Weiteres siehe unten!

_Tipp: Wenn Sie mit der Maus über die Kreise auf der Karte gehen, dann sehen Sie die relevanten Hinweise im Baum hervorgehoben!_


<!-- ############ SLIDE BREAK ############# -->
# [Wiederaufleben in Australien](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

In Australien und im Bundesstaat Victoria (Hauptstadt: Melbourne), die hier in orange dargestellt sind, sind COVID-19-Fälle erneut aufgetreten und kürzlich wurden weitere Maßnahmen im Bereich der öffentlichen Gesundheit ergriffen, um diesen Anstieg einzudämmen.

Die neusten Genome scheinen alle der Unterklade von Klade 20B zuzugehören (Scrollen Sie zurück zur vorherigen Folie, um zu sehen, wie Klade 20B in die gesamte Phylogenie passt).
Die neusten Daten und Kluster sind Anzeichen für eine lokale Epidemie.

Aehnliche Kluster könne in den Sequenzen aus New South Wales gesehen werden, wo die Fallzahlen auch neürdings zugenommen haben.


<!-- ############ SLIDE BREAK ############# -->
# [Neü Fälle wurden in Neuseeland diese Woche gemeldet](https://nextstrain.org/ncov/oceania/2020-08-11?c=gt-nuc_10097,23731&d=tree)

Neuseeland hatte zuvor gemeldet, dass es keine Community Uebertragungen in einem Zeitraum von 100 Tagen gegeben hatte. Jedoch wurden innert dieser Wochhe neü Fälle gemeldet. Der Cluster hat sich nun um 30 bekannte Fälle erhöht (bis zum Zeitpunkt der Veröffentlichung) hauptsächlich innerhalb der grössten Stadt Auckland.

Die Qülle ist bis jetzt noch unbekannt, aber Wissenschaftler haben die Virusisolate sequenziert und berichtet, dass diese in die Pangolin-Linie B1.1.1 fallen; Bis jetzt weiss man also bevor die Genomdaten veröffentlicht werden, dass sie in die hier blau eingefärbte Region passen. Diese Virenlinie hat ihren Ursprung in Europa, aber wurde bereits in mehreren Teilen der Welt gefunden.


<!-- ############ SLIDE BREAK ############# -->
# [Anfänge in Europa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 hat sich schnell innerhalb Europas ausbreiten können hauptsächlich durch direkte Uebertragungsketten aus Asien.

Obwohl über nur [einige 100 Fälle](https://www.ecdc.europa.eu/en/cases-2019-ncov-eüea) in Europa bis Ende Februar berichtet worden war, war das Virus zu diesem Zeitpunkt bereits in mindestens 15 Ländern detektiert worden.

Geht man von einer niedrigen Testrate innerhalb der Anfänge der Pandemie aus, kann davon ausgegangen werden, dass das Virus schon früh in Europa im Umlauf gewesen sein musste, auch in Ländern, aus denen wir keinerlei Proben haben.


<!-- ############ SLIDE BREAK ############# -->
# [Lockdown in Europa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

Zwischen März und April waren die Grenzen grösstenteils innerhalb Europas geschlossen und viele Länder implementierten unterschiedliche "Lockdown"-Methoden, wie zum Beispiel die Einschränkung der Bewegungsfreiheit und das Schliessen von Schulen und Geschäften. Wir erwarten daher einen Abfall in der Uebertragungsrate zwischen den Ländern, was bedeutet, dass jegliche Sequenzen aus einem Land mit früheren Sequenzen aus diesem Land klustern.

Dennoch konnte sich SARS-CoV-2 bereits so stark innerhalb Europas ausbreiten, so dass verschiedene Varianten in vielen Ländern auffindbar sind. Viele Länder hatten zahlreiche eindeutige Varianten vor dem Lockdown, die bereits mit anderen Viren in anderen Ländern verwandt waren. Das bedeutet, dass das phylogenetische Bild sehr durchmischt ist, obwohl Grenzen geschlossen worden sind (hier durch nah beieinander liegende Farben auf einem Baum indiziert).

Aber es gibt ein paar erwartungsgemässe Hinweise zur komunalen Uebertragung. Finnland und Schweden weisen ausgeprägte Uebertragunsgkluster in grün und orange auf (ca. 1/3 von oben), während Spanien (dunkelblau) hingegen eine eindeutige lokale Uebertragunge an beiden Baumenden aufweist. Sowohl Island (lila) als auch die Schweiz (hellblau) weisen lokale Uebertragungskluster vor.

_Tipp: Die Legende kann durch klicken auf 'Country' oben links im Baum erweitert werden!_


<!-- ############ SLIDE BREAK ############# -->
# [Kürzliche europäische Sequenzsdaten heben die lokale Uebertragung hervor und helfen uns die frühere Ausbreitung von SARS-CoV-2 besser zu verstehen](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

Wenn man nur Proben aus den letzten paar Wochen betrachtet, dann können 2 wichtige Punkte festgestellt werden:

Erstens sehen wir eine Tendenz hinzu Gruppierungsn aus Baumspitzen in Minikluster. Das deutet darauf hin, dass Uebertragung zwischen den Ländern weiterhin dominant ist - höchstwahrscheinlich aufgrund von verschiedenen implementierten Regulationen innerhalb Europas. Das Virus konnte während des Lockdowns weiterhin verbreiten, aber war wahrscheinlich beschränkt auf ein Land, was bedeutet, dass wir lokale "Varianten" von denen aus anderen Ländern besser unterscheiden können.

Einige Proben folgen nicht diesem Zügehörigkeitstrend. Fährt man über ein Land in der Legende, werden die Baumspitzen hervorgehoben, was hilfreich zur Identifikation solcher Proben ist. Beispielsweise sieht man in der Baummitte einige schwedische Proben (grün) innerhalb einer grossen russichen Klade (rot).
Aufgrund von starkem Subsampling sollte man trotzdem vorsichtig mit Interpretationen bezüglich potenzieller Uebertragungen zwischen einzelnen Ländern sein.

Zweitens sehen wir, dass die Baumspitzen grosse Unterschiede in den horizontalen Abbständen aufweisen -- z.B. sind die Proben, die letzte Woche hochgeladen worden sind eine Probensammlung, die bis Anfang März zurückreicht.
Die Gründe für das Sequenzieren von "alten" Proben sind sehr vielfältig, aber diese Proben helfen uns die Virusentwicklung und geographische Ausbreitung besser verstehen zu können.


<!-- ############ SLIDE BREAK ############# -->
# [Die anfängliche Situation in Südamerika](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmax=2020-04-15)

Die ersten südamerikanischen SARS-CoV-2 Sequenzen stammen von Ende Februar bzw. Anfang März und sind über den gesamten Baum verstreut, was auf viele Einschleppungen hindeutet. Sobald Auslandsreisen im März eingeschränkt worden sind, ssh man Hinweise auf eine anhaltenden Uebertragungsrate in verschiedenen Ländern.

Viele brasilianische Sequenzen (hellgrün) sind Teil von 2 grossen Klustern (in der Nähe von der Baumspitze). Das deutet darauf hin, dass diese Variante sowohl in Chile als auch Uruguay und Argentinien im Umlauf ist.

Zusätzlich gibt es eindeutige Uebertragungskluster in Kolumbien (orange), Chile (türkis), Uruguay (hellblau) und Argentinien (dunkelblau), die über den gesamten Baum verstreut sind.


<!-- ############ SLIDE BREAK ############# -->
# [Die jetzige Situation in Südamerika](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmin=2020-05-01)

Während SARS-CoV-2 weiterhin im Umlauf ist und sich stark in Südamerika ausbreitet, konnte die Sequenzierarbeit leider nicht mithalten. Obwohl die Fallzahlen kontinental sehr hoch sind, wurden nur 68 Proben aus 5 Ländern (Brasilien, Equador, Uruguay, Argentinien und Chile) seit Mai geteilt.

Trotz dass unsere Schlussfolgerungen wegen dieser niedrigen Beprobungsrate sind, sieht man, dass viele dieser erst kürzlich sequenzierter Proben zu der anfänglich diversen Probenpopulation innerhalb eines Landes oder anderer südamerikanischer Länder passt. Das deutet darauf hin, dass die Virusvarianten, die gerade im Umlauf sind Nachkömmlinge derer sind, die am Anfang der Epidemie eingeschleppt worden sind.


<!-- ############ SLIDE BREAK ############# -->
# [SARS-CoV-2 in Afrika](https://nextstrain.org/ncov/africa/2020-08-11?d=tree,map&f_region=Africa&legendOpen&transmissions=hide&p=grid)

Sowie nach Südamerika gab es auch mehrerer Einschleppungen des Virus SARS-CoV-2 nach Afirka, höchstwahrscheinlich aus Europa. Das zeigt sich an der Verteilung der afrikanischen Proben auf dem Baum - sogar Proben aus dem gleichen Land weisen unterschiedliche Virusvarianten auf.

Wir haben nun Sequenzierdaten von Ländern in Afrika im Verlauf der Epidemie, wobei die Sequenzierarbeit derzeit leicht abnimmt. Südafrika hat einen Grossteil an Sequenzierdaten bereit gestellt.


<!-- ############ SLIDE BREAK ############# -->
# [Clustering in Afrika](https://nextstrain.org/ncov/africa/2020-08-11?d=tree&f_region=Africa&legendOpen&p=full&f_country=Democratic%20Republic%20of%20the%20Congo,Senegal,South%20Africa)

Wir finden eine eindeutige lokale Uebertragung, die sich durch Sequenzenkluster im Baum manifestiert: in der DR Kongo, im Senegal und in Südafrika. Aus dem Senegal und Südafrika gibt es aktülle Proben. Diese Proben fallen in die alte gleiche Virenvielfalt des jeweiligen Landes, wie es von einer angehenden landesweiten Uebertragung erwartet werden würde.

Trotzdem muss man vorsichtig mit vorzeitigen Schlussfolgerungen sein aufgrund hoher Stichprobenverzerrung. Zudem zeigen die jetzigen Proben aus Afrika keine anhaltende Einführung von Virusvarianten anderswoher. Das reflektiert die derzeitigen weltweiten Reisebeschränkungen.


<!-- ############ SLIDE BREAK ############# -->
# [Die Epidemie in den USA ist eine Mischung aus lokaler und internationaler Uebertragung](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&p=full)

Im Folgenden sieht man genomische Daten aus der Epidemie in den USA vom 15. April bis zum heutigen Datum. Mitte April waren alle U.S. amerikanischen Staaten im Lockdown. [Die Bundesstaaten haben seitdem unterschiedlichhe Lockerungen implementiert](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html).

In diesem Baum - ähnlich wie in den Bäumen aus anderen Gegenden - sehen wir Beispiele für eine lokale Virusübertragung, die hier durch das Klustern von ähnlich angefärbten Baumspitzen über die Zeit indiziert wird. Wenn Sie nun auf "Explore the Data Yourself" klicken und Yakima County heraus filtern, kann man ein eindeutiges Beispiel für die Einschleppung und die Zunahme an genetisch verwandten Viren in dieser Region in dem Bundesstaat Washington finden. (Sie können auch [hier klicken](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&f_location=Yakima%20County&p=grid), aber dafür müssen Sie diesen Bericht verlassen.)

Auf dem Baum sehen wir jedoch auch eine Übertragung innerhalb des Landes in den USA, das durch das Mischen der Farben an den Baumspitzen gezeigt wird. Auf der Karte sieht die Übertragung innerhalb eines Landes wie eine Übertragungsleitung zwischen den Staaten aus. Diese Beobachtungen stehen im Einklang mit wenigen inländischen Reisebeschränkungen und den Richtlinien zur Wiedereröffnung von Staaten.


<!-- ############ SLIDE BREAK ############# -->
# [Zentralamerika weist eine geografisch beschränkte Uebertragung auf](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map,entropy&f_country=Belize,Costa%20Rica,Guatemala,Jamaica,Mexico,Panama&p=grid&transmissions=hide)

Sequenzierungen in den letzten 2 Monaten hat in Zentralamerika nachgelassen, was Schlussfolgerungen zur aktüllen Lage der Epidemie vorort erschwert. Wir sehen ein geografisches Klustern von SARS-CoV-2-Genomen innerhalb der vorhandenen Sequenzierdaten.

Am Boden des Baumes der 19B Klade gibt es ein Uebertragungskluster in Panama, das Mitte Februar angefangen hat. Einige Sequenzierdaten aus Panama (Juni bis Juli) passen in dieses Kluster hinein, was darauf hindeutet, dass die örtliche Uebertragung dieses Virengenotyps im Land weitergeht.

In Mexiko gibt es ein eindeutiges geografisches Uebertragungskluster im Mai, aber ohne weitere Sequenzierdaten können keine näheren Aussagen zu der Epidemie gemacht werden.

In der Baummitte gibt es ein Fallkluster in Baja California (hellblau). Diese Fälle stammen höchstwahrscheinlich aus Kalifornien, USA (grüne Aeste) im März. Diese abgeleitete Einschleppung des Virus steht im Einklang mit bekannten Reiseverbindungen zwischen den benachbarten Standorten, obwohl wir bei der Interpretation abgeleiteter Übertragungsorte bei geringer Sequenzierung vorsichtig sein sollten.


<!-- ############ SLIDE BREAK ############# -->
# [Schlusswort](https://nextstrain.org/ncov/global/2020-08-11?d=map)

Während die Pandemie seit ungefähr 8 Monaten weltweit im Umlauf ist, können wir eindeutige Veränderungen über die Zeit in Form von Virengenetik und starken Verhaltensänderungen feststellen.

Viele anfängliche Uebertragungen in die USA, nach Ozeanien, Europa und Asien waren zunächst stark durchmischt aufgrund von Auslandsreisen, die die Ausbreitung des Virus verstärkt hatten. Kurze Zeit später entwickelten sich örtliche Epidemien in Südamerika und Afrika, aufgrund von Viruseinschleppungen hauptsächlich aus Europa und Nordamerika.

Als das Ausmass der Virusausbreitung und die Ernsthaftigkeit von COVID-19 bewusst geworden ist, wurde das Reisen weltweit vielerorts eingeschränkt. Anschliessend sieht man eine eindeutige Verlagerung hin zu örtlichen Uebertragungen des Virus waherend der "Lockdowns" und der strengen Reisebeschränkungen. Ein Ergebnis ist, dass wir nun teilweise den Ursprung der Viren festmachen können, da die Epidemien mancherorts genetisch eindeutig sind. In den USA hat das Fehlen strenger Inlandsreisen dazu beigetragen das Durchmischen der Epidemien zwischen den Staaten aufrechtzürhalten

Grenzen werden nun wieder geöffnet und Reisen ist wieder möglich, obwohl wir noch nicht vorpandemische Zustände erreicht haben. Dies, zusammen mit der Verzögerungszeit von der Probenahme bis zur öffentlichen Verfügbarkeit heisst, dass wir nur wenige Anzeichen einer Vermischung zwischen den Ländern ausmachen können. Generell klustern neü Proben tendenziell weiterhin mit alten Proben aus demselben Land, was darauf hinweist, dass die Uebertragung mit bereits zirkulierenden Virusvarianten verläuft.

Leider konnten einige Länder einen Anstieg an Fallzahlen innerhalb der letzten paar Wochen festmachen, was wahrscheinlich auf die Lockerungen der Massnahmen zurüuckführbar ist. Während sich die nördliche Hemisphäre auf den Herbst und kälteres Wetter, weitere Lockerungen und Schulbeginn vorbereitet, sollten wir weiterhin wachsam den Anstieg der Fallzahlen beobachten. Da der Winter in der südlichen Hemisphäre voranschreitet, sehen wir besorgniserregende Anzeichen dafür, dass die Säsonalität tatsächlich zu Problemen bei der Uebertragung führen kann - Australiens anfänglicher Erfolg mit dem Virus wurde durch die neüren Ausbrüche gedämpft. Wenn wir weiterhin verstärkt testen, Kontaktverfolgung praktizieren, Fälle isolieren, sorgfältige Handhygiene betreiben und gewissenhaft Masken tragen, können wir unsere Gesellschaften weitestgehend offen halten während wir weiterhin SARS-CoV-2 bekämpfen.

<!-- ############ SLIDE BREAK ############# -->
# [Wissenschaftliche Danksagung](https://nextstrain.org/ncov/global/2020-08-11?d=tree&c=author)

Wir würden uns recht herzlich bei allen Wissenschaftlern weltweit für ihr bewundernswertes und zeitaufwändiges Engagegement in dieser Epidemie bedanken.
Nur durch das schnelle Teilen von genomischen Daten und Metadaten konnten Analysen wie diese möglich gemacht werden.

**Wir möchten Sie gerne dazu ermutigen auf 'Explore the Data Yourself' zu klicken und runter zu scrollen, um eine komplette Autorenliste zu finden; der Autor jeder einzelnen Sequenz kann durch Auswahl im Baum gefunden werden.**

Wir möchten uns auch recht herzlich bei GISAID für das Bereitstellen der Platform bedanken, mit der diese Daten hochgeladen und geteilt werden konnten.
