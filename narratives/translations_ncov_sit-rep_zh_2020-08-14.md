---
title: August 2020 update of COVID-19 genomic epidemiology
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
  - 李雪莹
translatorLinks:
  - https://xueyingcli.weebly.com/
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-08-11?d=map"
date: "2020 August 14"
abstract: "
新冠疫情现已遍及世界各地，[每周新增病例数达一百五十万](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports)， 全球累计确诊病例数已达到[一千八百万](https://ourworldindata.org/covid-cases) ，死亡病例数超过[600000例](https://ourworldindata.org/covid-deaths)。
\n\n
### 世界卫生组织在[2020年8月2日的状况报告中总结道](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports):
\n\n
### **\"随着各国放松了用于限制病毒传播的公共卫生和社会防疫措施，很多国家观察到了一些聚集性病例，甚至是病例数的重新上升。在较脆弱、资源贫瘠和存在战争冲突的地区，感染风险和易感程度更严重。在As countries have eased public health and social measures, implemented to limit transmission of the virus, a number of these countries have observed clusters or resurgences of cases. Risks and vulnerabilities are further magnified in fragile, low-resource and conflict-affected settings.\"**
\n\n
### 对新冠病毒基因组的测序在世界范围内仍在继续，有了这些数据，我们用Nextstrain来追踪病毒在地理上的传播和病毒的演化。The worldwide sequencing of the SARS-CoV-2 genome has continued unabated, and with this data we use Nextstrain to track the geographic movement and evolution of the virus.
目前，我们获得了超过75000条公开共享的序列，来自世界上一半的国家——这对于背后的科学家和公共卫生官员是一个出色的证明。To date, there are over 75,000 sequences publicly shared from half the countries in the world - an amazing testament to the scientists and public health officials behind this.
\n\n
### 我们用子抽样（subsampling）的方法来消除可能存在的抽样偏差的影响，来确保所分析的地区和时间区间是合理的。We use subsampling approaches to remove potential sampling biases in order to ensure that regions and time-periods are appropriately included for analysis.
（这也有助于满足计算上的要求。）(This also helps for the computational requirements.)
\n\n
### 这里，您可以看到约4300条基因组的地理分布。Here you can see the geographical distribution of ~4300 genomes.
每个国家的中心都有一个圆圈，颜色表明所处地区，半径与该国家的序列数成正比。Each circle is centered on an individual country, the colour indicates region and the radius scales with the number of genomes from that country ([点击此处查看如何解读Nextstrain上的地图](https://nextstrain.org/docs/visualisation/map-interpretation)).
\n\n
### 在本篇报告中，我们研究全球新冠疫情的基因组流行病学的整体趋势，然后对每个地区的最新情况提供具体的报告。In this report, we examine the global genomic epidemiology of COVID-19 broadly and provide specific updates for each world region.
"
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Please add your names & links to the 'translators' section above -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- table of contents slide -->
# [新冠疫情总览](https://nextstrain.org/ncov/global/2020-08-11?d=map)

### 目录
* [全球谱系分布Global clade distribution](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [棘突蛋白D614G突变 Spike Mutation](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [亚洲的情况Situation in Asia](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [大洋洲的情况Situation in Oceania](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [欧洲的情况Situation in Europe](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [南美的情况Situation in South America](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [非洲的情况Situation in Africa](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [北美的情况Situation in North America](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [结语Closing summary](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [科学贡献人员Credit](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Nextstrain的资料
* [入门篇：如何解读系统发生树](https://nextstrain.org/narratives/trees-background/zh)
* [之前的状况报告](https://nextstrain.org/ncov-sit-reps/)
* [冠状病毒的背景资料（英文）](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# 总结

在本篇报告中，我们分析了已公开的新冠病毒基因组序列。通过将病毒基因组互相比较，我们可以描述新冠病毒是如何在全球迁移和在社区内传播的。In this report, we analyzed publicly shared SARS-CoV-2 genomes. By comparing these viral genomes to each other, we can characterize how COVID-19 is moving around the world and spreading locally.

- 亚洲的19A和19B支的比例更高，而20A、20B和20C的支在欧洲和北美占比较大。Asia has a higher proportion of 19A & 19B clades, with 20A, 20B & 20C clades dominating in Europe & North America.

- 从全球来看，我们可以清楚地看到棘突蛋白中D614G突变显著上升。有假说认为，这个变异能够导致新冠病毒传播力增强。Globally, we can clearly see the rise to prominence of the D614G substitution in the Spike protein. This variant is hypothesised to cause an increase in SARS-CoV-2 transmission.

- 为了更好地展示在全球收集到的新冠病毒实时数据，我们建立了6个区域数据集和1个全球数据集，并在每个工作日都进行更新。To better display real-time builds of the SARS-CoV-2 data around the world, we run 6 regional and 1 global build, which are updated every weekday.

- 在亚洲，病毒流行的前期，存在大量的跨国传播。最近，我们看到病毒的传播主要变成了在国境之内，我们也在大多数地区都看到了这个趋势。In Asia, there were numerous between-country transmissions in the region early in the pandemic. More recently, we see a move to within-country links, a trend we see in most regions.

- 在大洋洲，新西兰的病例被控制在一个狭窄的时间窗口，对应于他们（截至本周为止）对病毒的消灭。澳大利亚最近病例数的骤增也出现了，至少在已公开的病例中，因为在此前流行的多样性的病毒中，出现了紧密聚在一起的病例。In Oceania, New Zealand's cases are contained in a narrow temporal band, corresponding to their elimination of the virus (until this week). Australia's recent surge in cases shows up, at least in the samples shared so far, as tightly clustering cases coming from previously circulating diversity.

- 新冠病毒在欧洲传播得极快——病毒很可能在被意识到之前就已经在很多国家中传播了。这导致了病毒流行早期，欧洲的样本大量地混杂在一起，使我们难以辨别和确认病毒在两地之间传播的方向。最近，我们可以看到特定国家与特定变异之间更明显的关联，因为旅行限令对病毒传播的控制。SARS-CoV-2 spread extremely quickly in Europe - the virus was likely being transmitted in many countries before they realised. This resulted in heavy mixing of European samples early in the pandemic, making it hard to distinguish and identfy introductions from one place to another. More recently, we can see more distinct variants associated with particular countries, as viruses have been constrained through travel restrictions.

- 像其他地区一样，南美曾经历多次输入事件，涵盖了新冠病毒基因组序列的多样性的大多数。在执行了旅行限令之后，病毒的序列开始更明显地聚在一起了。很遗憾，尽管很多国家正在经历严重的疫情，我们没有很容易地得到更多新近的序列。Like other regions, South America had multiple introductions, covering most of the known diversity of SARS-CoV-2. After travel restrictions came into place, sequences begin clustering more noticeably. Unfortunately, despite severe ongoing epidemics in many countries, more recent sequences are not readily available.

- 非洲也在病毒流行早期经历了多次、差异很大的输入事件。后续的旅行限令似乎限制了非洲各国之间病毒的混杂，大多数的序列都似乎来自统一国家早些时候流行的遗传多样性。Africa also had multiple, diverse introductions early in the pandemic. Subsequent travel restrictions seems to have limited mixing among African countries, with most sequences seeming to come from earlier circulating diversity in the same country.

- 美国的情形则有不同，那里，国内旅行没有受到很大限制：我们看到，各州的序列都混杂在一起，也能看到本地传播。在墨西哥和中美洲，我们看到了传播中的地理聚集的例子，特别是在美国加利福尼亚州和墨西哥的北下加利福尼亚州之间。A different picture is shown in the USA, where domestic travel has not been greatly restricted: we see mixing among all states, as well as local transmission. In Mexico & Central America, we see examples of geographical clustering in transmission, particularly between California (USA) & Baja California (Mexico).

```


<!-- ############ SLIDE BREAK ############# -->
# [遗传变异的世界分布Worldwide distribution of genetic variants](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

新冠病毒自从在2019年末出现以来，已经演化出了几种共同传播的变异。为了便于讨论，我们把这些变异归成了几支，每支由一些特征性的突变所定义。Since its emergence in late 2019, SARS-CoV-2 has diversified into several different co-circulating variants. To facilitate discussion of these variants, we have grouped them into clades which are defined by specific signature mutations.

我们目前定义了5个大的分支（详见[这篇博文](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming)）：We currently define 5 major clades (see [this blog post](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming) for details):

* 19A 和 19B 出现在武汉，在疫情的早期占比较大。emerged in Wuhan and dominated the early outbreak.
* 20A 来自于 19A，在3月占据了欧洲疫情，然后传播到全球。 emerged out of 19A, dominated the European outbreak in March, and has since spread globally.
* 20B 和 20C 是 20A的两个在遗传组成上有显著差异的大的亚分支。are large, genetically distinct subclades of 20A.


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


图中显示的是这些分支在世界各地的分布（颜色现在代表的是所属分支）。We're now looking at the distribution of these clades across the world (the color now represents clade membership).
您可以看到，位于亚洲的国家具有19A和19B（蓝色）的比例较高，这一支在疫情的早期占比较大。
You can see that countries in the Asia region have a higher proportion of 19A and 19B (blues) as that variant dominated in the early outbreak.
欧洲和北美的疫情是各个分支的混合体，但是主要以20B和20C为主（分别是黄色和橙色）。
Europe and North America have a mixture of all clades, but are dominated by 20B and 20C (yellow and orange, respectively).

#### 如果你有一些新冠病毒的序列，想知道它们属于哪个分支（以及在系统发生树中所估测的位置），我们制作了Nextclade工具([clades.nextstrain.org/](https://clades.nextstrain.org/))，您可以在浏览器中把您的FASTA文件拖拽上传到该页面。If you have SARS-CoV-2 sequences for which you'd like to know their clade (and estimated position on a phylogenetic tree), we made Nextclade ([clades.nextstrain.org/](https://clades.nextstrain.org/)) which lets you drag-and-drop your FASTA files onto the browser.


<!-- ############ SLIDE BREAK ############# -->
# [广为人知的D614G棘突蛋白突变The well-publicized D614G Spike Mutation](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

棘突蛋白基因中的D614G突变最近上了新闻，是很多推测的话题中心。
The D614G substitution in the gene coding for the Spike (S) protein has been in the news recently and the topic of much speculation.

根据证据的积累，G型变体（本图中为黄色）在体外实验中提高了新冠病毒的感染性，有可能在演化上被选择，选择提高的人传人的几率（[Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1) ）。然而，感染力的增加可能伴随着使病毒更易受中和抗体攻击的代价（[Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)）。
Evidence is building that the G variant (yellow in this view) increases infectivity of SARS-CoV-2 _in vitro_ and may have been evolutionarily selected for increased human-to-human transmission ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). However, an increase in infectivity may potentially come at the cost of making the virus more vulnerable to neutralizing antibodies ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

这里，我们可以看到这个变体，被推断为在病毒由动物传给人之后很快就出现了，然后传播到全球。Here we can see that this variant was inferred to have appeared very shortly after the initial zoonosis and subsequently spread around the world.
7月，614G变体在全世界所流行的大部分病毒中都存在。从它出现以来，这个突变发生了数次，也曾回复突变为614D型变体。
In July the 614G variant was present in the majority of circulating viruses worldwide. Since its initial appearance, the substitution has arisen multiple times and also reverted back to the 614D variant.

There is no evidence that these other substitutions and reversions have resulted in continued transmission chains.


<!-- ############ SLIDE BREAK ############# -->
# [Analysing regional builds independently](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

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