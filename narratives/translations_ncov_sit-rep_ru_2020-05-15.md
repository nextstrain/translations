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
  - Irina Kalita
translatorLinks:
  - https://www.linkedin.com/in/varvara-kozyreva-374aa877/
  - https://scholar.google.com/citations?user=0qPBuNUAAAAJ
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-05-14?d=tree&l=clock&legend=closed"

abstract: "Отчет проекта Nextstrain использует общедоступные геномные данные для отслеживания распространения и эволюции SARS-CoV-2. На этой неделе мы представляем обзор о вирусных мутациях, а также о том, что они означают (или не означают) для пандемии COVID-19."
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->
<!-- numbers can be tagged ilke this: 161</tag> - this is just for us to help find them to update! Just leave in the </tag> bit. -->

<!-- This is left-side text -->
# [Резюме](https://nextstrain.org/ncov/2020-05-14?d=tree,entropy&p=grid)

Мы проанализировали 5,193 общедоступных генома COVID-19. Сопоставив эти вирусные геномы друг с другом, мы можем охарактеризовать эволюцию и всемирное распространение SARS-CoV-2. На этой неделе мы фокусируемся на вирусных мутациях. Мы охватим следующее:

<br><br>
* Как появляются мутации (это нормальный процесс)
* Частота мутаций в SARS-CoV-2 (совершенно обычная)
* Сколько штаммов SARS-CoV-2 циркулирует (насколько мы знаем - один)  
* Как география и эпидемиология влияют на представления о разнице в вирусных генотипах (что запутано)


<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text 2-->
# [Ресурсы по COVID-19](https://nextstrain.org/ncov/global/2020-05-14?d=tree&p=full&legend=closed)

#### Nextstrain Ресурсы
* [НАЧНИТЕ ЗДЕСЬ: Как читать филогенетические деревья](https://nextstrain.org/narratives/trees-background/ru).
* [Предыдущие ситуационные отчеты](https://nextstrain.org/ncov-sit-reps/).
* [Поясняющие обсуждения в Twitter](https://bedford.io/misc/twitter/).
* [Главная информация о коронавирусах](https://nextstrain.org/help/coronavirus/human-CoV).
* [Распространенные заблуждения](https://nextstrain.org/narratives/ncov/sit-rep/2020-03-13?n=11).

#### Внешние Источники
* [Как коронавирус мутирует и распространяется (Нью-Йорк Таймс)](https://www.nytimes.com/interactive/2020/04/30/science/coronavirus-mutations.html).
* [Спроси ученого & Часто Задаваемые Вопросы](https://covid19.fas.org/l/en).
* [Ситуационные Отчеты Всемирной Организации Здравоохранения](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports).
* [Ресурсы центра по контролю и профилактике заболеваний США](https://www.cdc.gov/coronavirus/2019-ncov/index.html).

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Перерыв в ситуационных отчетах
<p>
На ранних этапах пандемии было неясно, как SARS-CoV-2 распространяется между странами, где он циркулирует локально и как местные вспышки связаны между собой.
За прошедшие 4 месяца, мы ответили на эти и другие вопросы в нашем Ситуационном Отчете. На данной стадии пандемии понятно, что некоторые общие мотивы по большей части повторяются в разных регионах и странах: 
</p>
<p/>

- Вспышки между даже очень удаленными друг от друга частями света глубоко взаимосвязаны.<p/>

- Посредством человеческой миграции и путешествий вирус был неоднократно занесен в большинство местных популяций.<p/>  

- После того как эти "искры" попали в новые местные популяции, многие из них погасли, так и не вызвав широкой передачи. В зависимости от местных условий и немного от шанса, некоторые из этих искр переросли в местные вспышки.<p/>  

- В конечном счете, эти локальные вспышки разослали свои собственные искры, которые распространились в новые местности.
<p/>

Неудивительно, что мы наблюдаем такую закономерность в странах, которые переживают свою первую волну инфекции. Что вызывает большую тревогу, так это то, что мы также видим такие тенденции после повторного заноса вируса в страны, в которых первоначальный пик уже прошел несколько месяцев до этого. В итоге, такой сценарий может быть остановлен, только когда страна способна эффективно тестировать, отслеживать и немедленно изолировать случаи. 
<br><br>

Это означает, что вспышки по всему миру глубоко связаны и борьба с COVID-19 будет всегда международной - мы не можем победить вирус в отдельно взятой стране, если мы не победим его повсюду.
<br><br>

На данной стадии пандемии, доступ к геномной эпидемиологии наиболее остро необходим внутри локальных и гипер-локальных сообществ посредством местных отделов общественного здравоохранения.  
<br><br>

В связи с этим, данный Ситуационный Отчет будет на какое-то время нашим последним, поскольку наша цель - предоставить поддержку подобных отчетов для местных сотрудников общественного здравоохранения.  
<br><br>

Мы, конечно же, продолжим ежедневные обновления глобальных и региональных версий программы по мере того, как будут размещаться новые последовательности. 
Если появятся новые данные в плане общей картины происходящего, мы также выпустим дополнительные Ситуационные Отчеты. 
Все эти обновления будут выложены в [twitter аккаунте Nextstrain](https://twitter.com/nextstrain) (как обычно).  
<br><br>

Вы также можете найти <a href="https://nextstrain.org/ncov-sit-reps/">все наши предыдущие Ситуационные Отчеты здесь</a>.

```

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Изменения в вирусных геномах на протяжении времени - норма](https://nextstrain.org/ncov/global/2020-05-14?c=num_date&d=tree,entropy&m=div&p=full&legend=open)

SARS-CoV-2, вирус вызывающий болезнь COVID-19, относится к [коронавирусам](https://nextstrain.org/help/coronavirus/human-CoV). Как и другие коронавирусы, SARS-CoV-2 обладает геномом, закодированным в РНК (нежели в ДНК).
<br><br>
Вирусы инфицируют клетки, поскольку им нужно позаимствовать клеточный аппарат для размножения. У РНК-вирусов этот процесс значительно подвержен ошибкам, поскольку большинство РНК-полимераз (молекул, которые делают копии РНК) не способны проверять ошибки и корректировать свою работу. Это приводит к частым мутациям в вирусном геноме; эти мутации являются нормальными и ожидаемыми. 
<br><br>
Важно отметить, что абсолютное большинство этих мутаций или "ломают" вирус настолько, что он больше не может передаваться и/или размножаться, или же никак не изменяют вирус из-за [вырожденности генетического кода](https://en.wikipedia.org/wiki/Synonymous_substitution).
Это означает, что мутации не изменяют белки, и поэтому никак не влияют на функции вируса. 
Другие мутации могут слегка изменить белок вируса, при этом никак не повлияв на его функции. 
Редко, когда изменение в генетическом коде вируса может поспособствать его репликации и/или улучшить передачу, но почти все из этих изменений по-прежнему обладают весьма незначительным эффектом.

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Вариации в генетическом коде вируса полезны для отслеживания вспышек](https://nextstrain.org/ncov/global/2020-05-14?c=gt-ORF3a_57&d=tree,entropy&f_division=New%20York&m=div&p=full)

Эти различия между геномами вируса могут быть использованы как "хлебные крошки", чтобы отследить историю данного образца. 
Точно так же, как твои родственники разделяют уникальные комбинации генетических характеристик, так и близкородственные вирусные образцы делят уникальные комбинации генетических мутаций.
<br><br>
Например, здесь мы показываем вирусное "семейное дерево", в котором каждый образец раскрашен в соответствии с аминокислотой, найденной в определенном локусе вирусного генома (в данном случае: в гене "ORF3a", участок 57).
<br><br>
Если мы выделим образцы из Нью-Йорка, мы увидим, что большинство случаев из Нью-Йорка и Европы в этой позиции имеют аминокислоту гистидин ("H") вместо глутамина ("Q"). Этот участок генома в комбинации с другими участками говорит нам о том, что данные случаи тесно связаны между собой.  
<br><br>
Вы также можете видеть позицию в гене "ORF3a", выделенную на диаграмме внизу слева.
<br><br>
Для более глубокого объяснения этих концепций мы советуем [данное наглядное описание](https://www.nytimes.com/interactive/2020/04/30/science/coronavirus-mutations.html) от Jonathan Corum и Carl Zimmer.


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Скорость эволюции SARS-CoV-2 является типичной для коронавируса](https://nextstrain.org/ncov/global/2020-05-14?c=num_date&d=tree,entropy&l=clock&p=full)

Поскольку вирусные геномы неминуемо подвержены изменениям, эти различия накапливаются с постоянной скоростью с течением времени.
<br><br>
Здесь на оси X показана дата сбора каждого образца. На оси Y показано *общее количество* мутаций, которые отделяют каждый штамм от корня дерева. Каждый образец раскрашен в соответсвии с датой его сбора. 
<br><br>
Несмотря на то, что, несомненно, существуют некоторые исключения, в среднем, изменения накапливаются с частотой ~24 замены в год. Это значит, что если единичная вирусная линия передавалась от человека к человеку в течение целого года, то мы будем ожидать, что к концу года весь ее геном будет иметь приблизительно 24 замены. 
Поскольку целый геном SARS-CoV-2 содержит ~30,000 оснований, это соответствует приблизительно 1 мутации на 1,000 оснований в год.
<br><br>
Для сравнения, вирус гриппа в среднем аккумулирует ~2 мутации на 1,000 оснований в год; ВИЧ аккумулирует ~4 мутации на 1,000 оснований в год.

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Насколько нам известно, существует только один штамм SARS-CoV-2](https://nextstrain.org/ncov/global/2020-05-14?branchLabel=clade&c=clade_membership&d=tree&p=full)

За прошедшее время было множество сообщений о различных "штаммах" SARS-CoV-2. 
Во-первых, уточнение: когда вирусологи используют слово "штамм", это часто попросту является удобным ярлыком, чтобы сослаться к одной группе образцов (например, наши обозначения отдельных ветвей на этой диаграмме). Это не означает, что они обладают какими-либо известными функциональными различиями.  
<br><br>
Напротив, слово "штамм" может использоваться, когда мы говорим о вирусных генотипах, которые являются функционально различными, в плане биологических (например, патогенность/тяжесть болезни) и/или эпидемиологических характеристик (например, способность к передаче). 
Важно отметить, что для определения того, являются ли 2 генотипа на самом деле функционально различными, требуется гораздо больше эксперементальных, клинических и эпидемиологических данных, чем те, которыми мы обладаем. 
<br><br>
Одна из наиболее известных гипотез о штаммах SARS-CoV-2 сравнивает возможные штаммы "D614" и "G614".


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Мутация D614G может быть связана со способностью к передаче, но также может быть объяснена географически](https://nextstrain.org/ncov/global/2020-05-14?c=gt-S_614&gmax=25778&gmin=21082&p=full)

[Недавний препринт](https://www.biorxiv.org/content/10.1101/2020.04.29.069054v1) предполагает, что одиночная мутация, D614G (аминокислота "D", находящаяся в участке 614 в "S" ('spike') белке, была заменена на аминокислоту "G"), могла привести к увеличению передаваемости SARS-CoV-2.
<br><br>
Во многих географических районах относительная частота 614D по сравнению с 614G со временем увеличилась.
Если определенный генотип приводит к лучшей передаче, мы ожидаем, что его частота будет продолжать увеличиваться.
Однако есть и другие объяснения того, почему относительная частота некоторых генотипов со временем возрастает.
<br><br>
Здесь мы видим ряд географических мест, где изначально большинство циркулирующих вирусных линий имели аллель D; позже этот баланс меняется так, что у большинства линий есть аллель G.
Это *может* быть признаком того, что G немного "более приспособлен", чем D (например, если вирусы с мутацией G имели немного более высокое R0 благодаря повышенной передаваемости).
<br><br>
Однако это также может быть лишь побочным эффектом естественной истории пандемии.
В начале пандемии большинство штаммов, привезенных из Китая, имели аллель D. Позже у большинства штаммов из Италии была аллель G. В последнее время мы в целом наблюдали больше ввозов из Европы, чем из Азии (хотя, безусловно, здесь также присутствует некоторая погрешность выборки).
Таким образом, возможно, что этому конкретному генотипу повезло и он распространился так быстро, потому что попал туда первым.
<br><br>
Относительно достоинств этих двух гипотез идет много споров. В дальнейшем, будет очень важно тщательно разобраться в этом вопросе, но пока у нас нет научного консенсуса относительно этих гипотез. Для более подробного объяснения, [перейдите по этой ссылке](https://twitter.com/trvrb/status/1257825352660877313).


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text 13-->
# [Что можешь сделать ты](https://nextstrain.org/ncov/2020-05-14?c=country&d=map&p=full)
#### ...лично
* Практикуй строгое социальной дистанцирование, особенно если ты относишься к уязвимой группе.
* Помни, что, даже если ты не сильно подвержен опасности, то многие люди, окружающие тебя, могут быть уязвимы; следуй этим мерам предосторожности, чтобы защитить окружающих.
* Мой руки так, как будто ты "только что порезал острый перец халапеньо и должен поменять контактные линзы".
* Оставайся дома, насколько это возможно, - особенно, если ты болен; запасись дополнительными предметами первой необходимости, на случай если тебе придется находиться под домашним карантином.
* Если ты работодатель, поощряй своих сотрудников работать на дому, если возможно.

#### ...как должностное лицо
* Обеспечь свободное и широкодоступное тестирование.
* Учреди строгие меры социального дистанцирования.
* Обеспечь финансирование и введи массовые действия по отслеживанию контактов.
* Финансово поддерживай тех, кто наиболее пострадал в связи с мерами социального дистанцирования.


<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown
# Выводы  

#### Вирусы приобретают мутации естественным путем по мере их размножения. Это норма. Мутации также могут помочь нам с отслеживанием курса эпидемии.  

#### Частота мутаций SARS-CoV-2 является типичной для коронавирусов.

#### Насколько мы знаем, существует только один функциональный "штамм" SARS-CoV-2.  

#### Разобраться в биологическом эффекте специфической мутации сложно - многие предполагаемые отличия могут быть обусловлены чистой случайностью и эпидемиологическими факторами.   
```

<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text -->
# [Благодарности научному сообществу](https://nextstrain.org/ncov/global/2020-05-14?d=tree&c=author)

Мы хотели бы отметить удивительную и своевременную работу всех ученых, вовлеченных в исследование этой эпидемии. 
Только благодаря быстрому обмену генетическими данными и метаданными стали возможны анализы, подобные этому.
<br><br>
**Мы призываем вас нажать «Исследовать данные самостоятельно» («Explore the Data Yourself») и прокрутить вниз, чтобы увидеть полный список авторов; вы также можете увидеть автора каждой отдельной последовательности, выбрав ее на дереве.**
<br><br>
Также мы хотели бы поблагодарить GISAID за предоставление платформы, через которую эти данные могут быть загружены и распространены.