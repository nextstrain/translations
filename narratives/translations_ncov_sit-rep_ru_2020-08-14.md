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
# [Независимый анализ по регионам](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

Так как здесь слишком много геномов для того, чтобы показать их на одном дереве, мы предоставляем региональный анализ для 6 показанных здесь регионов, в дополнение к нашему 'глобальному' анализу. 
Это позволяет нам сфокусироваться на разнородности внутри каждого региона, в то время как выбор подходящих образцов из других зон предоставляет возможность обзора всех передач между регионами с течением времени - как мы можем видеть на этом слайде!

На следующих слайдах мы собираемся предоставить обзор каждого из этих регионов с помощью переключения к соответствующему набору данных. (Это новая особенность Nextstrain Narratives!)

Полный анализ данных, поддерживаемых нами и другими, доступен по адресу [nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/).

<!-- ############ SLIDE BREAK ############# -->
# [Ситуация в Азии до 1 июня](https://nextstrain.org/ncov/asia/2020-08-11?dmax=2020-06-01&d=map&f_region=Asia&legendOpen)

Если мы рассмотрим ситуацию в Азии на основе геномов, собранных до июня 2020 года, мы увидим признаки как широкой передачи внутри Азии, так и передачи в другие регионы мира и из них.

#### Интерпретация линий и цветов

Здесь окрашены только страны Азии, остальные регионы представлены оттенками серого.
Цвет каждой линии передачи (линии между кругами) представляет место происхождения, поэтому все **цветные** линии представляют передачи, исходящие из страны в Азии (в этом примере).

#### Заносы в Азию

Это показывает, что многие передачи с участием азиатских и не азиатских стран были завезены в Азию (серые линии).
В таком интерфейсе особенно отчетливо видны передачи из Европы в Азию (хотя кажется, что линии идут из Германии, эта точка представляет всю Европу). Однако мы должны быть осторожными с интерпретацией этих предполагаемых передач, поскольку выборка образцов может играть большую роль (и у нас гораздо больше выборок из Европы, чем откуда-либо еще).

<!-- ############ SLIDE BREAK ############# -->
# [Ситуация в Азии после 1 июня](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

Глядя на геномы, отобранные после 1 июня (то есть за последние 2 месяца), мы видим, что меньшее количество стран преобладает в выборке.
Это ограничивает выводы, которые мы можем сделать, но похоже, что у нас может быть меньше передач между странами.

Это также очевидно при рассмотрении филогении, где у нас есть большие монофилетические (в той же части дерева) группировки геномов из Сингапура (желтый) и Бангладеш (светло-зеленый).

Эти данные согласуются с уменьшением международных поездок и более строгими мерами контроля.


<!-- ############ SLIDE BREAK ############# -->
# [Обзор ситуации в Океании](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Здесь мы можем исследовать ~790 геномов из Австралии и Новой Зеландии с дополнительными ~1100 последовательностями, чтобы обеспечить глобальный контекст.
На данном слайде мы окрасили образцы только из Австралии и Новой Зеландии.

Вы можете видеть, что эти образцы разбросаны по всему дереву, что указывает на то, что Океания подверглась (большей части) наблюдаемых геномных вариантов SARS-CoV-2.

Большинство образцов из Новой Зеландии (синие, фиолетовые, зеленые) происходят из узкой временной полосы, охватывающей март и апрель. Это связано с успешной стратегией контроля, применяемой правительством Новой Зеландии. Хотя страна вернулась к относительно нормальной жизни, границы, по-прежнему, остаются закрыты для всех гостей, чтобы ограничить шансы повторного проникновения вируса в страну. Вернувшиеся граждане должны пройти 14-дневный карантин перед въездом в страну.

На этой неделе правительство Новой Зеландии объявило о четырех новых случаях локальной передачи, которые не могут быть связаны с привезенными случаями. Генетическое секвенирование может помочь выяснить, как SARS-CoV-2 обошел строгий контроль - подробнее ниже!

_СОВЕТ: если вы наведете указатель мыши на круги на карте, то увидите соответствующие подсказки в выделенном дереве!_

<!-- ############ SLIDE BREAK ############# -->
# [Повторное возникновение вируса в Австралии](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

В Австралии и штате Виктория (столица: Мельбурн), показанных здесь оранжевым цветом, наблюдается повторное появление случаев COVID-19. Недавно были приняты дополнительные меры общественного здравоохранения, чтобы попытаться сдержать рост новых случаев.

Все эти недавние последовательности, по-видимому, являются субкладом клады 20B (прокрутите назад к предыдущему слайду, чтобы увидеть, как клад 20B вписывается во всю филогению).
Недавние даты и кластеризация являются признаками локальной вспышки.

Мы можем видеть аналогичную кластеризацию в последовательностях из Нового Южного Уэльса, где в последнее время число случаев также увеличилось.


<!-- ############ SLIDE BREAK ############# -->
# [Новые случаи, выявленные в Новой Зеландии на этой неделе](https://nextstrain.org/ncov/oceania/2020-08-11?c=gt-nuc_10097,23731&d=tree)

Новая Зеландия сообщила о более чем 100 днях отсутствия передачи вируса в общинах до выявления новых локальных случаев на этой неделе.
На данный момент кластер распространился примерно на 30 известных случаев (на момент публикации), главным образом, в крупнейшем городе Окленд.

Источник вспышки пока не известен, однако ученые отсеквенировали изоляты и сообщили, что они относятся к генетической связанной с панголинами линии B1.1.1; поэтому, хотя геномы еще не опубликованы, уже известно, что они попадают в область, отмеченную здесь синим цветом.
Эта линия появилась в Европе, но с тех пор наблюдается во многих регионах мира.

<!-- ############ SLIDE BREAK ############# -->
# [Ранняя ситуация в Европе](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 быстро распространился по Европе, вероятно, в основном за счет прямых передач из Азии.

К концу февраля, несмотря на всего [несколько сотен случаев](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea), официально зарегистрированных в Европе, вирус распространился, как минимум, в 15 европейских стран.

Учитывая, что в первые дни пандемии сбор образцов был менее распространен, SARS-CoV-2 почти наверняка уже циркулировал по всей Европе, в том числе и в странах, из которых у нас нет образцов.


<!-- ############ SLIDE BREAK ############# -->
# [Карантин в Европе](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

На протяжение марта и апреля большая часть Европы закрыла свои границы; многие страны ввели различные типы «изоляции», ограничили перемещения, закрыли предприятия и школы. Мы ожидаем, что эти ограничения снизили передачу заболевания между странами. Это повысило вероятность того, что мы увидим последовательности из любого заданного «кластера» страны с предыдущими последовательностями из этой же страны.

Однако SARS-CoV-2 уже был настолько перемешан по всей Европе, что разные варианты вируса циркулировали во многих странах. В большинстве стран множество различных вариантов вируса, относящихся к другим странам, циркулировали еще до введения карантина. Это означает, что филогенетическая картина остается сильно перемешанной даже после закрытия границ (показано несколькими цветами рядом друг с другом на дереве).

Тем не менее, мы видим некоторые ожидаемые признаки локальной передачи. Здесь Финляндия и Швеция имеют ярко выраженный кластер передачи зеленого и оранжевого цветов (примерно 1/3 от вершины), в то время как Испания (темно-синий) демонстрирует отчетливую локальную передачу внизу и вверху дерева. Исландия (фиолетовый) и Швейцария (голубой) также имеют кластеры местной передачи.

_Подсказка: вы можете раскрыть легенду, щелкнув «Country» в верхнем левом углу дерева! _


<!-- ############ SLIDE BREAK ############# -->
# [Недавнее секвенирование европейских образцов подчеркивает местную передачу и расширяет понимание предыдущего распространения SARS-CoV-2](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

Изучение образцов, загруженных за последнюю неделю, позволяет сделать два важных вывода.

Во-первых, мы видим тенденцию к объединению вершин в мини-кластеры. Это указывает на то, что передача внутри страны продолжает доминировать - вероятно, это результат различных мер, введенных по всей Европе. Вирус продолжал генетически диверсифицироваться во время изоляции, но с большей вероятностью ограничился одной страной, а это означает, что теперь мы можем лучше отличать местные "варианты" от таковых в других странах.

Некоторые образцы не следуют тенденции связывания с другими образцами из той же страны. Если навести указатель мыши на страну в легенде, на дереве будут подсвечены вершины, относящиеся к этой стране, и это поможет идентифицировать такие образцы. Например, в середине дерева мы можем видеть несколько шведских образцов (зеленый), вложенных в большую русскую кладу (красный).
Учитывая обильную подвыборку, нам следует быть осторожными, чтобы не переоценить предполагаемую передачу вируса между странами с этой точки зрения.

Во-вторых, мы можем видеть, что вершины имеют большую разницу в расстоянии по горизонтали, то есть образцы, представленные на прошлой неделе, представляют собой временное окно сбора образцов, начиная с начала марта.
Причины для секвенирования "старых" геномов различны, но эти образцы помогают нам лучше понять эволюцию вируса и географическое перемещение.


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
