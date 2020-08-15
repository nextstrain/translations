---
title: Последняя информация о геномной эпидемиологии COVID-19 на Август 2020
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
  - Varvara Kozyreva
translatorLinks:
  - https://twitter.com/varvarakozyreva
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-08-11?d=map"
date: "14 августа 2020"
abstract: "
На данный момент пандемия широко распространена по всему миру, с более чем [1.5 миллионами новых случаев за каждую неделю](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports), [18 миллионами](https://ourworldindata.org/covid-cases) общих зафиксированных случаев и более [600,000 смертей](https://ourworldindata.org/covid-deaths).
\n\n
### Ситуация [резюмированная ВОЗ на 2 Августа 2020](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports):
\n\n
### **\"По мере того, как страны ослабили эпидемические и социальные меры, направленные на ограничение распространения вируса, многие из этих стран наблюдают вспышки или возобновление случаев. Риски и уязвимость особенно умножаются в хрупких ситуациях, связанных с недостатком ресурсов и конфликтами.\"**
\n\n
### Всемирное секвенирование геномов SARS-CoV-2 не прекращалось, и с этими данными мы продолжаем использовать платформу Nextstrain, чтобы отслеживать географическое передвижение и эволюцию вируса.
К сегодняшнему дню, в общественном доступе имеется более 75,000 последовательностей из половины стран со всего мира- замечательное свидетельство работы ученых и сотрудников системы общественного здравоохранения, которые стоят за этим. 
\n\n
### Мы используем методы подвыборки с целью исключения возможных погрешностей выборки, для того чтобы убедиться, что регионы и временные периоды адекватно представлены в анализе. (Это также помогает с вычислительными требованиями)
\n\n
### На этом слайде вы можете видеть географическое распределение ~4300 геномов.
Каждый круг размещается в центре конкретной страны, цвет соответствует региону мира, а радиус пропорционален количеству геномов из данной страны ([см. помощь в интерпретации карты Nextstrain здесь](https://nextstrain.org/docs/visualisation/map-interpretation)).
\n\n
### В данном отчете мы рассматриваем глобальную геномную эпидемиологию COVID-19 в широком плане и представляем специальные обновления для каждого региона мира. 
"
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Please add your names & links to the 'translators' section above -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- table of contents slide -->
# [Обзор по COVID-19](https://nextstrain.org/ncov/global/2020-08-11?d=map)

### Содержание
* [Всемирное распространение генетических вариантов](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [Мутация D614G в Спайковом белке](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [Ситуация в Азии](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [Ситуация в Океании](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [Ситуация в Европе](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [Ситуация в Южной Америке](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [Ситуация в Африке](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [Ситуация в Северной Америке](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [Заключительные выводы](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [Благодарности](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Ресурсы Nextstrain
* [НАЧНИТЕ ЗДЕСЬ: Как читать филогенетические деревья](https://nextstrain.org/narratives/trees-background/ru)
* [Предыдущие Ситуационные Отчеты](https://nextstrain.org/ncov-sit-reps/)
* [Главная информация о коронавирусах](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Обзор

В данном отчете мы анализируем общественно-доступные геномы SARS-CoV-2. Путем сравнения этих вирусных геномов мы можем охарактеризовать передвижение COVID-19 по всему миру и его локальное распространение.

- Азия обладает большей пропорцией генетических линий 19A & 19B, в то время как линии 20A, 20B и 20C доминируют в Европе и Северной Америке.

- Всемирно, мы отчетливо видим растущее значение мутации D614G в Спайковом белке. Этот вариант предположительно вызывает усиленную передачу SARS-CoV-2.

- Для того чтобы лучшим образом отобразить сборку данных о SARS-CoV-2 в реальном времени по всему миру, мы поддерживаем 6 региональных сборок и 1 глобальную, которые обновляются каждый рабочий день.

- В Азии, в самом начале пандемии наблюдалось множество передач между странами. В недавнее время, мы наблюдаем переход к цепям передачи внутри стран, -такая тенденция видна в большинстве регионов.

- В Океании, случаи из Новой Зеландии ограничиваются узкой временной полосой, которая соответствует устранению вируса в стране (вплоть до этой недели). Недавняя волна случаев в Австралии выглядит как близкий кластер случаев (по крайней мере, на основании образцов доступных на данный момент), происходящих от разнообразия находящегося в циркуляции изначально.  

- SARS-CoV-2 распространился чрезвычайно быстро в Европе - вирус вероятно распространялся во многих странах до того, как они это осознали. Это привело к значительному перемешиванию европейских образцов на ранних этапах пандемии, затрудняя нашу способность различать и идентифицировать заносы из одного места в другое. В недавнее время, мы могли наблюдать более отличные варианты, связанные с конкретными странами, в связи с тем, что вирус был сдержан путем ограничений путешествий. 

- Как и в других регионах, множество заносов произошло в Южную Америку, охватывая большую часть разнообразия SARS-CoV-2. После того, как были введены ограничения на путешествия, кластеризация образцов стала более заметной. К сожалению, несмотря на продолжающиеся серьезные эпидемии во многих странах, недавние последовательности не всегда доступны. 

- В Африке тоже произошло множество разнородных заносов в начале пандемии. Последующие ограничения на путешествия, судя по всему, ограничили перемешивание между африканскими странами, с большинством последовательностей, по-видимому, происходящих от раннее циркулирующего разнообразия в тех же самых странах. 

- Другая картина наблюдается в США, где внутренние перемещения не были значительно ограничены: мы видим как перемешивание между всеми штатами, так и местную передачу. В Мексике и Центральной Америке, мы видим примеры географической кластеризации передач, в частности между Калифорнией (США) и Нижней Калифорнией (Baja California, Мексика). 

```


<!-- ############ SLIDE BREAK ############# -->
# [Всемирное распространение генетических вариантов](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

С момента его появления в конце 2019, SARS-CoV-2 диверсифицировался в несколько различных одновременно циркулирующих вариантов. Чтобы помочь обсуждению этих вариантов, мы объединили их в ветви, которые определяются специфическими отличительными мутациями.

На данный момент мы выделяем 5 главных ветвей (подробнее см. [этот пост](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming)):

* 19A и 19B возникли в городе Ухань и доминировали в ранней вспышке.
* 20A произошел от 19A, доминировал в европейской вспышке в марте и с тех пор распространился глобально.
* 20B и 20C являются большими, генетически отличными подразделениями 20A.


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


Здесь мы рассматриваем распределение данных ветвей по всему миру (цвет соответствует принадлежности к ветви).
Вы можете видеть, что страны Азии обладают большей пропорцией 19A и 19B (синий), поскольку этот вариант доминировал в ранней вспышке. 
В Европе и Северной Америке присутствует смесь всех ветвей, однако 20B и 20C доминируют (желтый и оранжевый, соответственно).

#### Если вы хотите знать к какой ветви относятся ваши последовательности SARS-CoV-2 (и оценить их положение на филогенетическом дереве), мы создали Nextclade ([clades.nextstrain.org/](https://clades.nextstrain.org/)), который позволяет перетащить ваши FASTA файлы в браузер.

<!-- ############ SLIDE BREAK ############# -->
# [Получившая широкую огласку мутация D614G в Спайковом белке](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

Замена D614G в гене, кодирующем Спайковый (S) белок, в последнее время упоминалась в новостях и является темой для многих домыслов. 

Накапливается все больше доказательств того, что вариант G (желтый цвет на данном слайде) увеличивает инфективность SARS-CoV-2 _in vitro_ и, возможно, был эволюционно селектирован из-за усиленной передачи от человека к человеку ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). Однако, повышенная инфекционность может потенциально достигаться ценой большей уязвимости вируса по отношению к нейтрализующим антителам ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

Здесь мы видим, что по предсказаниям данный вариант возник вскоре после первоначального зооноза и впоследствии распространился по всему миру. 
В июле вариант 614G присутствовал в большинстве циркулирующих вирусов всемирно. С момента ее первого появления, эта замена возникала несколько раз и также возвращалась назад к варианту 614D. 
У нас нет свидетельств того, что эти замены и реверсии привели к последующим цепям передач. 


<!-- ############ SLIDE BREAK ############# -->
# [Независимый анализ по регионам Analysing regional builds independently](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

As there are too many genomes to show in a single tree, we provide a regional analysis for each of the 6 regions shown here, in addition to our main 'global' build.
This allows us to focus on the diversity within each region, while choosing appropriate out-of-region samples, so we can maintain an overview of all of the between-region transmissions over time - as we can see on this slide!

In the next slides we're going to provide an overview of each of those regions by switching to the corresponding dataset. (This is a new feature in Nextstrain Narratives!)

A full inventory of builds maintained by us and others is available at [nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/).

<!-- ############ SLIDE BREAK ############# -->
# [Asia situation pre-June](https://nextstrain.org/ncov/asia/2020-08-11?dmax=2020-06-01&d=map&f_region=Asia&legendOpen)

If we examine the situation in Asia from genomes collected before June 2020, we see signs of both extensive within-Asia transmission as well as transmissions to and from other regions of the world.

#### Interpreting the lines and colors

Here only countries in Asia have been colored, with the other regions represented by shades of grey.
The color of each transmission line (lines between circles) represents the origin location, so all of the **colored** lines represent transmissions originating from a country within Asia (in this example).

#### Transmissions into Asia

This shows that many of transmissions involving Asian and non-Asian countries were importations into Asia (grey lines).
Especially pronounced in this view are those transmissions from Europe to Asia (though the lines seem to come from Germany, this point represents all of Europe). However, we must be cautious about how we interpret these inferred transmissions, as sampling biases can play a large role (and we have many more samples from Europe than anywhere else).


<!-- ############ SLIDE BREAK ############# -->
# [Asia situation after June 1](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

Looking at the genomes sampled after June 1 (i.e. in the past 2 months), we see that the sampling is dominated by fewer countries.
This limits the conclusions we can draw, but it appears that we may have fewer transmissions between countries.

This is also evident looking at the phylogeny, where we have large monophyletic (in the same part of the tree) groupings of genomes from Singapore (yellow) and Bangladesh (light green).

These data are consistent with less recent international travel and stricter control measures.


<!-- ############ SLIDE BREAK ############# -->
# [Oceania overview](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Here we can explore ~790 genomes from Australia and New Zealand with an extra ~1100 sequences to provide global context.
Only samples from Australia and New Zealand are colored.

You can see that these samples are spread throughout the tree, indicating that Oceania has been exposed to (most of) the observed genomic diversity of SARS-CoV-2.

The majority of New Zealand's samples (blues, purples, greens) come from a tight temporal band covering March and April, which is due to the successful control strategy employed by the New Zealand government. While the country is back to relative normality, the borders are still closed to all non-citizens to limit the chances for the virus to re-enter the country. Returning citizens must quarantine for 14 days before entering the country.

This week, the New Zealand government announced four new cases of community transmission which cannot be linked to arriving cases. Genetic sequencing may be able to help uncover how SARS-CoV-2 bypassed the strict controls -- more below!

_HINT: if you hover your mouse over the circles on the map you can see the relevant tips in the tree highlighted!_


<!-- ############ SLIDE BREAK ############# -->
# [Resurgence in Australia](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

Australia, and the state of Victoria (capitol city: Melbourne), shown here in orange, have been seeing a reemergence of COVID-19 cases and have recently implemented further public health measures to try to curb this increase.

These most recent genomes all appear to be a subclade of clade 20B (scroll back to the previous slide to see how clade 20B fits into the entire phylogeny).
The recent dates and clustering are signs of a local outbreak.

We can see similar clustering in sequences from New South Wales, where cases have also increased recently.


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
