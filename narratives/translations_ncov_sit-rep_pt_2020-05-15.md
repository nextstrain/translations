---
title: Análise genômica da COVID-19. Relatório da situação até 15-05-2020.
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
  - Miguel Andrade
translatorLinks:
  - https://www.linkedin.com/in/miguel-andrade-10500025/
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-05-14?d=tree&l=clock&legend=closed"

abstract: "Os informes da Nextstrain utilizam dados genômics compartilhados publicamente para rastrear a disseminação e a evolução do SARS-CoV-2. Esta seman, damos uma visão geral das mutações virais e o que elas significam (e não significam) para a pandemia de COVID-19."
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->
<!-- numbers can be tagged ilke this: 161</tag> - this is just for us to help find them to update! Just leave in the </tag> bit. -->

<!-- This is left-side text -->
# [Sumário executivo](https://nextstrain.org/ncov/2020-05-14?d=tree,entropy&p=grid)

nós analisamos 5.193 genomas de COVID-19 compartilhados publicamente. Ao comparar esses genomas virais entre si, nós podemos caracterizar como o SARS-CoV-2 está evoluindo e se movendo em todo o mundo. Esta semana, nós focamos nas mutações virais. Nós cobrimos:
<br><br>
* De onde as mutações virais vem (elas são normais)  
* A taxa de mutação no SARS-CoV-2 (muito típica)
* Quantas cepas de SARS-CoV-2 estão circulando (até onde sabemos: 1)  
* Como a geografia e a epidemiologia contribuem para as diferenças percebidas nos genótipos virais (isso é complicado)


<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text 2-->
# [Fontes sobre a COVID-19](https://nextstrain.org/ncov/global/2020-05-14?d=tree&p=full&legend=closed)

#### Nextstrain Resources
* [COMECE AQUI: Como interpretar árvores filogenéticas](https://nextstrain.org/narratives/trees-background/).
* [Informes anteriores](https://nextstrain.org/ncov-sit-reps/).
* [Tópicos explicativos do Twitter](https://bedford.io/misc/twitter/).
* [Informações acerca dos coronavirus](https://nextstrain.org/help/coronavirus/human-CoV).
* [Equívocos comuns](https://nextstrain.org/narratives/ncov/sit-rep/2020-03-13?n=11).

#### External Resources
* [Como os coronavirus mutam e se espalham (NYTimes)](https://www.nytimes.com/interactive/2020/04/30/science/coronavirus-mutations.html).
* [Pergunte a um cientista & Perguntas Frequentes](https://covid19.fas.org/l/en).
* [Relatórios de situação da OMS](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports).
* [Materiais do CDC (Centro de Controle de Doenças/EUA)](https://www.cdc.gov/coronavirus/2019-ncov/index.html).

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Situation Report Hiatus
<p>
No inicio da pandemia, não estava claro como o SARS-CoV-2 estava se movendo entre os países, onde estava circulando localmente, e como os surtos localizados estavam relacionados.
Nos últimos quatro meses, nós abordamos estas questões - e outras - nos nossos relatórios de situação semanais. Nesta fase da pandemia, é claro que alguns padrões chave são amplamente consistentes nas regiões e países:  
</p>
<p/>

- Surtos em partes distantes do mundo estão profundamente interligados.<p/>

- Através da migração humana e viagens, o vírus foi introduzido na maioria das comunidades várias vezes.<p/>  

- Uma vez que essas "faíscas" chegam a uma nova comudade, muitas fracassam sem causar transmissão generalizada. Sugeitos às condições locais e um pouco de chance, algumas desss faíscas crescem em surtos locais.<p/>  

- Eventualmente, esses surtos locais emitem faíscas por conta própria, disceminando o vírus para novas localidades.  
<p/>

De maneira esperada, nós vemos esse padrão em países que estão esperimentando sua primeira onda de infecções. Mais alarmante, também vemos esse padrão após a reintrodução do vírus em países onde o pico iniccial passou meses antes.
Por fim, esse padrão só é quebrado quando um país é capaz de testar, rastrear e isolar efetivamente os casos imediatamente.
<br><br>

Isso significa que surtos em todo o mundo estão profundamente conectados e a batalha contra o COVID-19 será sempre global -- não podemos conquistar o vírus em qualquer lugar sem enviá-lo a qualquer lugar.
<br><br>

Nesta fase da pandemia, a epidemiologia genômica é mais urgentemente necessária nas comunidades locais e hiperlocais, por meio dos escritórios locais de saúde pública.
<br><br>

Como tal, este será o nosso último relatório da situação semanal por um tempo, embora nosso objetivo seja apoiar relatórios semelhantes de autoridades locais de saúde pública.
<br><br>

Nós vamos, é claro, continuar com atualizações diárias das compilações globais e regionais à medida que novas seqüências forem disponibilizadas.

Quando os dados revelarem alguma coisa nova, também emitiremos relatórios de situação adicionais.
Todas essas atualizações serão postadas na [conta do twitter do Nextstrain](https://twitter.com/nextstrain) (como sempre).  
<br><br>

Você também pode encontrar <a href="https://nextstrain.org/ncov-sit-reps/">todos os nossos relatórios de situação anteriores aqui </a>.

```

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Mudanças no genoma viral ao longo do tempo são normais](https://nextstrain.org/ncov/global/2020-05-14?c=num_date&d=tree,entropy&m=div&p=full&legend=open)

SARS-CoV-2, o vírus que causa a doença COVID-19, é um [coronavirus](https://nextstrain.org/help/coronavirus/human-CoV). Como outros coronaviruses, SARS-CoV-2 possui o genoma codificado em RNA (ao invés de DNA).
<br><br>
Vírus infectam células porque eles precisam pegar a maquinaria celular emprestada para replicar (reproduzir). Para os vírus de RNA, esse processo é batante propenso a erro, como a maioria das RNA polimerases (as máquinas moleculares que fazem cópias de RNA) não são capazes de revisar e corrigir o seu trabalho. Isso leva a mutações frequentes no genoma viral; Isso é normal e experado.
<br><br>
É importante ressaltar que a grande maioria dessas mutações "quebra" o vírus de modo que ele não pode mais transmitir e/ou replicar, ou essas mutações não mudam o vírus por causa da [codificação redundante](https://pt.wikipedia.org/wiki/Substitui%C3%A7%C3%A3o_sin%C3%B4nima).
Isso significa que as mutações não mudam as proteínas, e consequentemente a funão, do vírus de qualquer forma.
Outras mudanças podem modificar a proteína do vírus muito levement, mas não impactam na função.
Raramente, uma mudança no código genético do vírus pode ajudá-lo a replicar e/ou transmitir melhor, mas quase todas essas mudanças ainda têm apenas um pequeno efeito.

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Variação no código genético viral é útil para o rastreamento de surtos](https://nextstrain.org/ncov/global/2020-05-14?c=gt-ORF3a_57&d=tree,entropy&f_division=New%20York&m=div&p=full)

Essas diferenças nos genomas entre vírus podem ser usadas como "migalhas de pão" para rastrear o histórico de uma determinada amostra.
Assim como as pessoas da sua família compartilham combinações únicas de características genéticas, amostras virais estreitamente relacionadas compartilham combinações únicas de mutações genéticas.
<br><br>
Por exemplo, aqui mostramos a "árvore genealógica" viral com cada amostra colorida pelo tipo de aminoácido que está presente em um local específico no genoma viral (gene "ORF3a", sítio 57).
<br><br>
Destacando amostras de Nova York, vemos que a maioria dos casos de Nova York e da Europa tem o aminoácido Histidina ("H") em vez de Glutamina ("Q") nessa posição. Isso, combinado com todos os outros sítios do genoma, nos diz que esses casos estão todos intimamente relacionados entre si.
<br><br>
Você também pode ver a posição no gene "ORF3a" destacada no gráfico na parte inferior esquerda.
<br><br>
Para uma explicação mais aprofundada desses conceitos, recomendamos [Essa explicação visual](https://www.nytimes.com/interactive/2020/04/30/science/coronavirus-mutations.html) de Jonathan Corum e Carl Zimmer.


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [A taxa evolutiva do SARS-CoV-2 é típica para um coronavirus](https://nextstrain.org/ncov/global/2020-05-14?c=num_date&d=tree,entropy&l=clock&p=full)

Como os genomas virais mudam inevitavelmente, essas diferenças tendem a se acumular a uma taxa constante ao longo do tempo.
<br><br>
Aqui, o eixo x mostra a data em que cada amostra foi coletada. O eixo y mostra o *número total* de mutações que cada cepa está distante da raiz da árvore. Cada amostra é colorida pela data em que foi coletada.
<br><br>
While there are certainly some outliers, on average, we see changes accumulate at a rate of ~24 substitutions per year. This means that if a single viral lineage were transmitting from one person to the next for a full year, we'd expect its entire genome to accumulate roughly 24 substitutions by the end of the year.
As the whole SARS-CoV-2 genome is ~30,000 bases, this corresponds to roughly ~1 mutation per 1,000 bases in a year.
<br><br>
For context, influenza would average ~2 mutations per 1,000 bases per year; HIV would average ~4 mutations per 1,000 bases per year.

<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [As far as we know, there is only 1 strain of SARS-CoV-2](https://nextstrain.org/ncov/global/2020-05-14?branchLabel=clade&c=clade_membership&d=tree&p=full)

There have been many reports about multiple "strains" of SARS-CoV-2.
First, a clarification: when virologists use the word "strain," it's often just as a useful label so we can all refer to the same group of samples (e.g., our clade labels, shown here). This does *not* imply any known functional difference.
<br><br>
Separately, "strain" can be used to refer to viral genotypes that are functionally distinct, either biologically (e.g., pathogenicity/disease severity) and/or epidemiologically (e.g., transmissibility).
Importantly, though, determining whether two genotypes actually *are* functionally distinct requires much more experimental, clinical and epidemiological data than we currently have.
<br><br>
One of the most prominent hypotheses about SARS-CoV-2 strains compares possible "D614" vs "G614" strains.


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
# Takeaways  

#### Viruses naturally acquire mutations as they replicate. This is normal. Mutations can also help us trace the course of epidemics.  

#### SARS-CoV-2 mutation rate is very typical for coronaviruses.

#### As far as we know, there is only 1 functional "strain" of SARS-CoV-2.  

#### Teasing apart the biological impact of specific mutations is tricky -- many perceived differences can be attributed to chance and epidemiological factors.  
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
