---
title: Геномный анализ распространения COVID-19. Ситуационный отчет от 2020-05-15.
authors:
  - Sidney M. Bell
  - Emma Hodcroft
  - Nicola Müller
  - Cassia Wagner
  - James Hadfield
  - Richard Neher
  - Trevor Bedford
authorLinks:
  - https://twitter.com/sidneymbell
  - https://neherlab.org/emma-hodcroft.html
  - https://bedford.io/team/nicola-mueller/
  - https://bedford.io/team/cassia-wagner/
  - https://bedford.io/team/james-hadfield/
  - https://neherlab.org/richard-neher.html
  - https://bedford.io/team/trevor-bedford/
affiliations: "Fred Hutch, Seattle, USA; Biozentrum, Basel, Switzerland; CZI, CA, USA"
translators:
  - Varvara Kozyreva
  -
translatorLinks:
  - https://www.linkedin.com/in/varvara-kozyreva-374aa877/
  - 
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-05-14?d=tree&l=clock&legend=closed"

abstract: "Отчет проекта Nextstrain использует общедоступные геномные данные для отслеживания распространения и эволюции SARS-CoV-2. На этой неделе мы представяем обзор о вирусных мутациях и о том что они значат (или не значат) в плане пандемии COVID-19."
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->
<!-- numbers can be tagged ilke this: 161</tag> - this is just for us to help find them to update! Just leave in the </tag> bit. -->

<!-- This is left-side text -->
# [Резюме](https://nextstrain.org/ncov/2020-05-14?d=tree,entropy&p=grid)

Мы проанализировали 5,193 общедоступных генома COVID-19. Сопоставив эти вирусные геномы друг с другом, мы можем охарактеризовать эволюцию и всемирное распространение SARS-CoV-2. На этой неделе мы фокусируемся на вирусных мутациях. Мы охватим следующее:
недавнем распространении вируса в Азии и сообщаем о следующем:
<br><br>
* Как появляются мутации (нормальный процесс)
* Частота мутаций в SARS-CoV-2 (совершенно обычная)
* Сколько штамов SARS-CoV-2 находится в циркуляции (насколько мы знаем- один)  
* Как география и эпидемиология влияют на представления о разнице в вирусных генотипах (что запутано)


<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text 2-->
# [COVID-19 Resources](https://nextstrain.org/ncov/global/2020-05-14?d=tree&p=full&legend=closed)

#### Nextstrain Resources
* [START HERE: How to read a phylogeny](https://nextstrain.org/narratives/trees-background/).
* [Previous Situation Reports](https://nextstrain.org/ncov-sit-reps/).
* [Explanatory Twitter threads](https://bedford.io/misc/twitter/).
* [Background on coronaviruses](https://nextstrain.org/help/coronavirus/human-CoV).
* [Common misconceptions](https://nextstrain.org/narratives/ncov/sit-rep/2020-03-13?n=11).

#### External Resources
* [How coronavirus mutations and spreads (NYTimes)](https://www.nytimes.com/interactive/2020/04/30/science/coronavirus-mutations.html).
* [Ask a Scientist & FAQs](https://covid19.fas.org/l/en).
* [WHO Situation Reports](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports).
* [CDC Resources](https://www.cdc.gov/coronavirus/2019-ncov/index.html).

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Перерыв в ситуационных отчетах
<p>
На ранних этапах пандемии было неясно как SARS-CoV-2 распространяется между странами, где он циркулирут локально, и как местные вспышки связаны между собой.
За прошедшие 4 месяца, мы ответили на эти и другие вопросы в нашем Ситуационном Отчете. На данной стадии пандемии понятно, что некоторые общие мотивы по большей части повторяются в разных регионах и странах: 
</p>
<p/>

- Вспышки между даже очень удаленными друг от друга частями света глубоко взаимосвязанны.<p/>

- Посредством человеческой миграции и путешествий вирус был неоднократно занесен в большинство местных популяций.<p/>  

- После того как эти "искры" попали в новые местные популяции, многие из них выдохлись так и не вызвав широкой передачи. В зависимости от местных условий и немного от шанса, некоторые из этих искр переросли в местные вспышки.<p/>  

- В конечном счете, эти локальные вспышки разослали свои собственные искры, распространившись в новые местности.
<p/>

Неудивительно, что мы наблюдаем такую закономерность в странах, которые переживают свою первую волну инфекций. Что вызывает большую тревогу, так это то, что мы также видим такие тенденции после повторного заноса вируса в страны, в которых первоначальный пик уже прошел несколько месяцев до этого.  
В итоге, такой мотив может быть прерван, только когда страна способна эффективно тестировать, отслеживать и немедленно изолировать случаи. 
<br><br>

Это означает, что вспышки по всему миру глубоко связаны, и что борьба с COVID-19 будет всегда международной- мы не можем победить вирус в отдельной взятой стране если мы не победим его повсюду.
<br><br>

На данной стадии пандемии, доступ к геномной эпидемиологии наиболее остро необходим внутри локальных и гипер-локальных сообществ посредством местных отделов общественного здравоохранения.  
<br><br>

В связи с этим, данный Ситуационный Отчет будет на какое-то время нашим последним, поскольку наша цель- предоставить поддержку для подобных отчетов для местных сотрудников общественного здравоохранения.  
<br><br>

Мы, конечно же, продолжим ежедневные обновления глобальных и региональных версий программы по мере того, как будут размещаться новые последовательности. 
Если появятся новые данные в плане общей картины происходящего, мы также выпустим дополнительные Ситуационные Отчеты. 
Все эти обновления будут выложены в [twitter аккаунте Nextstrain](https://twitter.com/nextstrain) (как обычно).  
<br><br>

Вы также можете найти <a href="https://nextstrain.org/ncov-sit-reps/">все наши предыдущие Ситуационные Отчеты здесь</a>.

```

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Изменения в вирусных геномах на протяжении времени- норма](https://nextstrain.org/ncov/global/2020-05-14?c=num_date&d=tree,entropy&m=div&p=full&legend=open)

SARS-CoV-2, вирус вызывающий болезнь COVID-19, относится к [коронавирусам](https://nextstrain.org/help/coronavirus/human-CoV). Как и другие коронавирусы, SARS-CoV-2 обладает геномом закодированным в РНК (нежели в ДНК).
<br><br>
Вирусы инфицируют клетки, поскольку им нужно позаимствовать клеточный аппарат для размножения. У РНК-вирусов этот процесс значительно подвержен ошибкам, поскольку большинство РНК-полимераз (молекул, которые делают копии РНК) не способны проверять ошибки и корректировать свою работу. Это приводит к частым мутациям в вирусном геноме; эти мутации являются нормальными и ожидаемыми. 
<br><br>
Что важно, абсолютное большинство этих мутаций или "ломают" вирус настолько, что он больше не может передаваться и/или размножаться, или же никак не изменяют вирус из-за [вырожденности генетического кода](https://en.wikipedia.org/wiki/Synonymous_substitution).
Это означает, что мутации не изменяют белки, и оттого никак не влияют на функции вируса. 
Другие мутации могут слегка изменить белок вируса, при этом никак не повлияв на его функции. 
Редко, изменение в генетическом коде вируса может поспособствать его репликации и/или улучшить передачу, но почти все из этих изменений по-прежнему обладают весьма незначительным эффектом.

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Вариации в генетическом коде вируса полезны для отслеживания вспышек](https://nextstrain.org/ncov/global/2020-05-14?c=gt-ORF3a_57&d=tree,entropy&f_division=New%20York&m=div&p=full)

Эти различия между геномами вируса могут быть использованы как "хлебные крошки", чтобы отследить историю данного образца. 
Точно так же, как твои родственники разделяют уникальные комбинации генетических характеристик, так и близкородственные вирусные образцы делять уникальные комбинации генетических мутаций.
<br><br>
Например, здесь мы показываем вирусное "семейное дерево" в котором каждый образец расскрашен в соответствии с аминокислотой найденной в определенном локусе вирусного генома (в данном случае в гене "ORF1a", участок 57)
<br><br>
Если мы выделим образцы из Нью Йорка, мы увидим, что большинство случаев из Нью Йорка и Европы в этой позиции имеют аминокислоту гистидин ("H") вместо глутамина ("Q"). Этот участок генома в комбинации с другими участками говорит нам, что данные случаи тесно связаны между собой.  
<br><br>
Вы также можете видеть позицию в гене "ORF3a", выделенную на диаграмме внизу слева.
<br><br>
Для более глубокого объяснения этих концепций мы советуем [данное наглядное описание](https://www.nytimes.com/interactive/2020/04/30/science/coronavirus-mutations.html) от Jonathan Corum и Carl Zimmer.


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Скорость эволюции SARS-CoV-2 является типичной для коронавируса](https://nextstrain.org/ncov/global/2020-05-14?c=num_date&d=tree,entropy&l=clock&p=full)

Поскольку вирусные геномы неминуемо подвержены изменениям, эти различия накапливаются со временем со стабильной частотой.
<br><br>
Здесь на оси X показана дата сбора каждого образца. На оси Y показано *общее количество* мутаций которые отделяют каждый штамм от корня дерева. Каждый образец раскрашен в соответсвии с датой когда он был собран. 
<br><br>
Несмотря на то, что определенно существуют некоторые исключения, в среднем, изменения аккумулируются с частотой ~24 замены в год. Это значит, что если единичная вирусная линия передавалась от человека к человеку в течении целого года, то мы будем ожидать, что весь ее геном аккумулирует приблизительно 24 замен к концу года. 
Поскольку целый геном SARS-CoV-2 содержит ~30,000 основания, это соответствует приблизительно ~1-ой мутации на 1,000 оснований в год.
<br><br>
Для сравнения, вирус гриппа в среднем аккумулирует ~2 мутации на 1,000 оснований в год; ВИЧ аккумулирует ~4 мутации на 1,000 оснований в год.

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Насколько нам известно, существует только один штамм SARS-CoV-2](https://nextstrain.org/ncov/global/2020-05-14?branchLabel=clade&c=clade_membership&d=tree&p=full)

За прошедшее время было множество сообщений о различных "штаммах" SARS-CoV-2. 
Во-первых, уточнение: когда вирусологи используют слово "штамм", это часто попросту является удобным ярлыком, чтобы сослаться к одной группе образцов (например, наши обозначения отдельных ветвей на этой диаграмме). Это не означает, что они обладают какими-либо известными функциональными различиями.  
<br><br>
Напротив, слово "штамм" может использоваться, когда мы говорим о вирусных генотипах, которые являются функционально различными, в плане биологических (например, патогенность/тяжесть болезни) и/или эпидемиологических характеристик (например, способность к передаче). 
Что важно, чтобы определить являются ли 2 генотипа собственно функционально различными, требуется гораздо больше эксперементальных, клинических и эпидемиологических данных, чем те, которыми мы обладаем. 
<br><br>
Одна из наиболее известных гипотез о штаммах SARS-CoV-2 сравнивает вероятные штаммы "D614" и "G614".


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [D614G may be related to transmissibility, but could also be explained by geography](https://nextstrain.org/ncov/global/2020-05-14?c=gt-S_614&gmax=25778&gmin=21082&p=full)

[A recent pre-print](https://www.biorxiv.org/content/10.1101/2020.04.29.069054v1) suggests that a single mutation, D614G (from amino acid "D" to "G" at site 614 in the "S" ('spike') protein), may be responsible for increasing the transmissibility of SARS-CoV-2.
<br><br>
In many geographic areas, the relative frequency of 614D compared to 614G increased over time.
If a certain genotype leads to better transmissibility, we would expect it's frequency to increase over time.
There are, however, other explanations to why the relative frequency of some genotypes would increase over time.
<br><br>
For this site, we see a number of geographic locations where initially, most viral lineages in circulation had the D allele; later, this balance flips such that most lineages have the G allele.
This *could* be a hallmark of G being slightly "fitter" than D (e.g., if viruses with the G mutation had a slightly higher R0 through increased transmissibility).
<br><br>
However, this could also just be a side effect of the natural history of the pandemic.
Early on in the pandemic, most strains exported from China had a D allele. Later, most strains from Italy had a G allele. Recently, we've seen more exportation from Europe than from Asia overall (although there's certainly some sampling bias at play here, as well).
Thus, it could just be that this particular genotype got lucky, and spread so rapidly because it got there first.
<br><br>
There's a fair amount of debate regarding the relative merits of these two hypotheses. It'll be important to carefully tease these apart, but we don't have scientific consensus on this issue yet. For a more detailed explanation, [see this thread](https://twitter.com/trvrb/status/1257825352660877313).


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text 13-->
# [What you can do](https://nextstrain.org/ncov/2020-05-14?c=country&d=map&p=full)
#### ...as an individual
* Practice strict social distancing, especially if you are in a vulnerable group.
* Remember that even if you are not super vulnerable, many people around you are; follow these practices to protect others.
* Wash your hands "like you just chopped a jalapeno and have to change a contact lens."
* Stay home as much as possible -- especially  if you are sick; be prepared with extra supplies in case you need to self-quarantine.
* If you are an employer, encourage your employees to work from home wherever possible.

#### ...as an official
* Make testing free and broadly available.
* Put strong social distancing measures in place.
* Fund and implement extensive contact tracing efforts.
* Financially support those impacted by social distancing measures.


<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown
# Выводы  

#### Вирусы приобретают мутации естественным путем по мере их размножения. Это норма. Мутации также могут помочь нам с отслеживанием курса эпидемии.  

#### Частота мутаций SARS-CoV-2 является типичной для коронавирусов.

#### Насколько мы знаем, существует только один функциональный "штамм" SARS-CoV-2.  

#### Разобраться в биологическом эффекте специфической мутации сложно -- многие предполагаемые отличия могут быть обусловлены чистой случаностью и эпидемиологическими факторами.   
```

<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text -->
# [Scientific credit](https://nextstrain.org/ncov/global/2020-05-14?d=tree&c=author)

We would like to acknowledge the amazing and timely work done by all scientists involved in this outbreak.
Only through the rapid sharing of genomic data and metadata are analyses such as these possible.
<br><br>
**We encourage you to click on 'Explore the Data Yourself' and scroll down for a full list of authors; the author of each individual sequence is available by selecting it on the tree.**
<br><br>
We also gratefully acknowledge GISAID for providing the platform through which these data can be uploaded and shared.
