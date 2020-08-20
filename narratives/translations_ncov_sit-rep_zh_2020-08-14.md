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
并没有证据表明，这些后来发生的614G突变和回复成614D的突变导致了持续的传播链。
There is no evidence that these other substitutions and reversions have resulted in continued transmission chains.


<!-- ############ SLIDE BREAK ############# -->
# [对各地区数据的分别分析Analysing regional builds independently](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

As there are too many genomes to show in a single tree, we provide a regional analysis for each of the 6 regions shown here, in addition to our main 'global' build.
因为序列数目过多，无法在一棵演化树上全部展现，我们为图中显示的6个地区都分别提供了针对该地区的分析，在我们的主要的“全球”数据分析之外。
This allows us to focus on the diversity within each region, while choosing appropriate out-of-region samples, so we can maintain an overview of all of the between-region transmissions over time - as we can see on this slide!
这使我们能够关注每个地区之内的遗传多样性，并且选择合适的地区之外的的样本，所以我们能够对跨大区的传播随着时间的变化保持整体的把握——正如此图所示。

In the next slides we're going to provide an overview of each of those regions by switching to the corresponding dataset. (This is a new feature in Nextstrain Narratives!)
在下面的页面中，我们会对每一个地区提供整体的概括，通过转到相对应的数据集。（这也是 Nextstrain 报告的新功能！）

A full inventory of builds maintained by us and others is available at [nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/).
由我们和其他人所维护的数据分析的全部列表请见[nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/) 。

<!-- ############ SLIDE BREAK ############# -->
# [亚洲地区六月前的情况Asia situation pre-June](https://nextstrain.org/ncov/asia/2020-08-11?dmax=2020-06-01&d=map&f_region=Asia&legendOpen)

如果我们查看在2020年6月前所采集的基因组数据，来了解亚洲的情况，我们看到，既有广泛的亚洲地区内的传播，又有对世界其他地区的输入和输出。If we examine the situation in Asia from genomes collected before June 2020, we see signs of both extensive within-Asia transmission as well as transmissions to and from other regions of the world.

#### 图中的线条和颜色Interpreting the lines and colors

图中，只有亚洲的国家有颜色，亚洲外的地区为灰色。Here only countries in Asia have been colored, with the other regions represented by shades of grey.
The color of each transmission line (lines between circles) represents the origin location, so all of the **colored** lines represent transmissions originating from a country within Asia (in this example).
每一条传播的线（圆圈之间的连线）的颜色代表病毒所来自的地点，所以所有 **彩色的** 线条代表病毒来源于亚洲内的国家（在这幅图中）。

#### 输入亚洲的病例Transmissions into Asia

图中显示，很多亚洲和非亚洲国家的传播属于输入病例（灰色线条）。This shows that many of transmissions involving Asian and non-Asian countries were importations into Asia (grey lines).
在这幅图中格外明显的是从欧洲传入亚洲的病例（虽然图中的线看起来像是来自德国，但这个点代表欧洲全体）。
然而，我们必须谨慎，如何解读这些推断的传播链，因为取样偏差可能有很大影响（我们获得的欧洲样本比其他地方都多）。
Especially pronounced in this view are those transmissions from Europe to Asia (though the lines seem to come from Germany, this point represents all of Europe). However, we must be cautious about how we interpret these inferred transmissions, as sampling biases can play a large role (and we have many more samples from Europe than anywhere else).


<!-- ############ SLIDE BREAK ############# -->
# [亚洲地区在6月1日之后的情况Asia situation after June 1](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

现在我们来看6月1日之后（也就是在过去的两个月内）采集到的基因组数据，我们看到样本所主要来自的国家变少了。Looking at the genomes sampled after June 1 (i.e. in the past 2 months), we see that the sampling is dominated by fewer countries.
这给我们下结论增加了一些限制，但是看起来，在国家之间的病毒传播可能是变少了。
This limits the conclusions we can draw, but it appears that we may have fewer transmissions between countries.

这在系统发生树上也很明显，来自新加坡（黄色）和孟加拉国（浅绿色）的基因组各自都在树上聚成了大的单系群（也就是在树上位于同一位置）。
This is also evident looking at the phylogeny, where we have large monophyletic (in the same part of the tree) groupings of genomes from Singapore (yellow) and Bangladesh (light green).

These data are consistent with less recent international travel and stricter control measures.
这些数据与近期国际旅行的减少，和更严格的管控措施相一致。

<!-- ############ SLIDE BREAK ############# -->
# [大洋洲概况](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Here we can explore ~790 genomes from Australia and New Zealand with an extra ~1100 sequences to provide global context.
在这幅图中，我们可以查看澳大利亚和新西兰的约790条序列，以及约1100条其他地区的序列，来提供国际背景。
Only samples from Australia and New Zealand are colored.
只有澳大利亚的新西兰的样本是彩色的。

您可以看到，这些样本遍布整棵演化树，表明大洋洲曾接受过（大部分）我们能观察到的新冠病毒的遗传多样性。
You can see that these samples are spread throughout the tree, indicating that Oceania has been exposed to (most of) the observed genomic diversity of SARS-CoV-2.

新西兰的大部分样本（蓝色、紫色、绿色）来自一个很窄的时间窗口，包括3月和4月，这是由于新西兰政府所采取的成功的管控措施。虽然新西兰已经基本回到常态，新西兰的边境仍对非公民关闭边境，来限制病毒重新输入的几率。回国的公民必须在入境之前隔离14天。
The majority of New Zealand's samples (blues, purples, greens) come from a tight temporal band covering March and April, which is due to the successful control strategy employed by the New Zealand government. While the country is back to relative normality, the borders are still closed to all non-citizens to limit the chances for the virus to re-enter the country. Returning citizens must quarantine for 14 days before entering the country.

This week, the New Zealand government announced four new cases of community transmission which cannot be linked to arriving cases. Genetic sequencing may be able to help uncover how SARS-CoV-2 bypassed the strict controls -- more below!
本周，新西兰政府发布，发现四个社区传播的新病例，不能追溯到境外输入的来源。基因测序或许能够帮助发现新冠病毒是如何躲过如此严格的管控措施的——请继续阅读！

_HINT: if you hover your mouse over the circles on the map you can see the relevant tips in the tree highlighted!_
_提示：将鼠标悬停在地图上的圆圈上，演化树上，该地区所对应的样本点就会突出显示！_

<!-- ############ SLIDE BREAK ############# -->
# [Resurgence in Australia病毒在澳大利亚卷土重来](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

Australia, and the state of Victoria (capitol city: Melbourne), shown here in orange, have been seeing a reemergence of COVID-19 cases and have recently implemented further public health measures to try to curb this increase.
澳大利亚，和维多利亚州（首府为墨尔本），在图中以橙色表示，已看到新冠病毒病例的重新出现，近期已经采取了进一步的公共卫生防疫措施，来遏制病例数上升的势头。

These most recent genomes all appear to be a subclade of clade 20B (scroll back to the previous slide to see how clade 20B fits into the entire phylogeny).
The recent dates and clustering are signs of a local outbreak.
这些最新的基因组都是20B这一支下的一支（可以翻到前页查看20B这一支在整个演化树中所处的位置）。近期的日期和聚类是本地疫情爆发的标志。

We can see similar clustering in sequences from New South Wales, where cases have also increased recently.
新南威尔士州的序列也有类似的聚集现象，那里的病例数最近也有所增长。



<!-- ############ SLIDE BREAK ############# -->
# [新西兰本周检测到的新病例New cases detected in New Zealand this week](https://nextstrain.org/ncov/oceania/2020-08-11?c=gt-nuc_10097,23731&d=tree)

New Zealand had reported over 100 days without community transmission before detecting cases in the community this week.
在本周报告本地传播的病例之前，新西兰已经有超过100天没有报道有本地传播了。

The cluster has now spread to around 30 known cases (at time of publication), primarily based in the largest city, Auckland.
这一簇病毒现在已经传播到约30例已知病例（截至本报告发布之时），主要位于该国最大的城市，奥克兰。

The source is not yet known, however scientists have sequenced the isolates and reported that they fall into pangolin lineage B1.1.1; so while the genomes are yet to be released they are known to fall in the region colored in blue here.
病毒的来源尚不知晓，然而，科学家已经对样本进行测序，报告病例属于穿山甲支B1.1.1。所以，虽然基因组还没有公开，已经知道这些样本在树上应该位于本图中蓝色的区域。
This lineage originated in Europe, but has since been observed in multiple regions around the world.
这一支起源于欧洲，但是已经在世界上多个地区被观察到过。


<!-- ############ SLIDE BREAK ############# -->
# [欧洲的早期情况](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 spread rapidly across Europe, likely primarily through direct transmissions from Asia.
新冠病毒曾快速地在欧洲各地传播，很有可能主要来自直接由亚洲输入的。

By the end of February, even though there were just [a few hundred cases](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea) officially reported in Europe, the virus had spread to at least 15 European countries.
截至二月底，尽管欧洲官方报告当时只有[几百例](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea)，病毒至少传到了15个欧洲国家。

Given that sampling was less common in the early days of the pandemic, SARS-CoV-2 was almost certainly already circulating across must of Europe, including in countries for which we don't have samples.
基于疫情早期的样本不多，新冠病毒几乎是肯定在欧洲大部分国家都已经在传播了，包括我们没有样本的国家。


<!-- ############ SLIDE BREAK ############# -->
# [Lockdown in Europe](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

Through March and April much of Europe closed their borders, and many imposed differing types of 'lockdown' where movement was restricted and businesses and schools closed. We expect that these restrictions decreased between-country transmission, making it more likely that we see sequences from any given country 'cluster' with previous sequences from that country.
在三月和四月，欧洲的大部分地区都关闭了边境，很多国家实施了不同程度的“封城”，限制了出行，关闭了商店和学校。我们预期，这些限制会降低国与国之间的传播，让我们更容易看到，一个国家的序列与该国之前的序列“聚集”在一起。

However, SARS-CoV-2 was already so mixed across Europe that different variants of the virus were circulating across multiple countries. Most countries had numerous distinct variants circulating before lockdown that were related to the viruses circulating in other countries. This means the phylogenetic picture remains well-mixed even after borders closed (shown by multiple colors near each other on the tree).
然而，新冠病毒在欧洲的大量混杂，使得该病毒的不同变体都在多个国家同时传播。大多数国家都有大量的不同的与其他国家的病毒亲缘关系紧密的变体，在封城之前。这意味着，在系统发生树上，即使在边境关闭之后，各国的序列仍然充分混杂在一起（在树上表现为，不同的颜色的点相靠近）。

However, we can see some signs of the local transmission that we would expect. Here, Finland and Sweden have a very distinct transmission cluster in green and orange (about 1/3 from the top), while Spain (dark blue) shows distinct local transmission at the bottom and top of the tree. Iceland (purple) and Switzerland (light blue) also show clusters of local transmission.
然而，我们可以看到一些所预期的本地传播的迹象。这里，芬兰和瑞典，分别是绿色和橙色，有一个非常独特的簇（位于树的上方约三分之一处），而西班牙（深蓝色）在树的上部和底部都有一个独立的本地传播簇。冰岛（紫色）和瑞士（淡蓝色）也表现出了本地传播的簇。

_提示：可以点击树左上角的“国家（Country）”来展开图例_

_Hint: You can expand the legend by clicking 'Country' at the top-left of the tree!_


<!-- ############ SLIDE BREAK ############# -->
# [近期欧洲的测序工作表明了本地传播的存在，丰富了我们对之前新冠病毒传播的认识Recent European sequencing highlights local transmission and enriches understanding of previous SARS-CoV-2 spread](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

Examining only samples uploaded in the past week highlights two important points.
分析在上一周上传的样本数据，我们可以得到两个重要的信息。

Firstly, we can see a tendency towards groupings of tips into mini-clusters. This indicates that within-country transmission is continuing to dominate - likely a product of the various regulations introduced throughout Europe. The virus continued to diversify genetically during the lockdown, but was more likely to be confined to one country, meaning we can often now better distinguish local 'variants' from those in other countries.
首先，我们可以看到一个趋势，树枝的尖端聚成了小的簇。这表明，国境内传播仍持续占大部分——很有可能是欧洲各国所采取的各种防疫措施的产物。病毒在封城期间在遗传上仍然在多样化，但更有可能是局限在一个国家之内，意味着我们现在可以常常更好的区分把本地的变异和其他国家的区分开来。

Some samples do not follow this trend of linking to other samples from the same country. Hovering over a country in the legend highlights tips in the tree from that country and will help identify such samples. For instance, in the middle of the tree, we can see some Swedish samples (green) nested within a larger Russian clade (red).
一些样本并没有遵循这个趋势，与同一国家的其他样本有所关联。把鼠标悬停在图例中的国家上，就可以在树上显示该国的样本，可以让我们看到这样的样本。比如，在树的中部，我们就看到一些瑞典的样本（绿色）位于一个俄国样本组成的一大支之中（红色）。
Given the heavy subsampling, we need to remain cautious to not over interpret putative between-country transmissions from this view.
因为我们在子抽样的过程中抽掉了很多样本，我们需要保持谨慎，不要过度解读，这幅图中可能反应出的跨国传播。

Secondly, we can see that the tips have a large difference in horizontal spacing -- i.e. the samples submitted in the past week represent a sample collection time window extending back to early March.
其次，我们可以看到，树枝的末端之间的水平距离相差很大——也就是说，上周提交的样本代表了一个很宽的取样时间窗口，一直包括到三月上旬。
The reasons for sequencing "old" genomes varies, but these samples help us fill in our understanding of viral evolution and geographical movement.
对这些“老样本”进行基因组测序是出于不同的原因，但是这些样本帮助我们填充了对病毒演化和地理迁移的理解。


<!-- ############ SLIDE BREAK ############# -->
# [南美洲早期的情况](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmax=2020-04-15)

South America's first SARS-CoV-2 sequences are from late February and early March, and are scattered across the tree, suggesting multiple introductions. As international travel decreased in March, we can see evidence of sustained local transmission in several countries.
南美的第一条新冠病毒序列是来自二月下旬和三月上旬，并散布全树，表明有多次输入事件。随着三月国际旅行的减少，我们可以看到在一些国家存在持续的本地传播的证据。

Many of Brazil's (light green) sequences are part of two large clusters (near top of the tree), with some evidence that this variant also moved around the continent to Chile, Uruguay, and Argentina.
巴西（浅绿色）的很多序列都属于两个大的样本簇（接近树的顶部），有一些证据，这个变体也在南美大陆上传播，到达了智利、乌拉圭和阿根廷。

We can also see distinct clusters of transmission involving Colombia (orange), Chile (turquoise), Uruguay (lighter blue), and Argentina (darker blue) scattered through the tree.
我们也可以看到不同的传播链，包括哥伦比亚（橙色）、智利（蓝绿色）、乌拉圭（浅蓝色）、阿根廷（深蓝色），散布于树的各处。

<!-- ############ SLIDE BREAK ############# -->
# [南美洲近期的情况The more recent situation in South America](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmin=2020-05-01)

Unfortunately, while SARS-CoV-2 continues spreading widely in South America, sequence generation has not kept pace. Though cases remain high across much of the continent, only 68 samples from 5 countries (Brazil, Ecuador, Uruguay, Argentina, & Chile) have been shared since May.
很遗憾，虽然新冠病毒仍然在南美洲广泛传播，对它的测序并未能保持相同的步伐。虽然在南美洲仍存在很高的病例数，五月以来，只有来自五个国家（巴西、厄瓜多尔、乌拉圭、阿根廷和智利）的68个样本得以发布。

Though our inferences are limited by the sparse sampling, in many cases these more recent samples nest within the earlier diversity sampled in the same country, or other South American countries. This suggests the varients circulating now are descendants of those introduced early in the epidemic.
虽然我们的推断受到了低样本量的限制，在很多情况下，这些近期的样本与在同一国家或者其他南美国家取得的早期遗传多样性之内。这表明，现在正流行的病毒是疫情早期输入的病毒的后代。

<!-- ############ SLIDE BREAK ############# -->
# [新冠病毒在非洲SARS-CoV-2 in Africa](https://nextstrain.org/ncov/africa/2020-08-11?d=tree,map&f_region=Africa&legendOpen&transmissions=hide&p=grid)

Like South America, Africa had several introductions of SARS-CoV-2 to the continent, many likely from Europe. This is shown by the spread of African samples across the tree - even samples from the same country include diverse variants.
与南美洲的情况类似，非洲曾经历了多起输入事件，可能很多来自欧洲。这可以从非洲样本散布在演化树各处看出来——即使是来自于同一国家的样本，都包括不同的遗传变体。

We now have sequences from countries across Africa throughout the epidemic, though sequencing efforts seem to have declined slightly more recently.
South Africa has contributed a large proportion of the sequencing.
我们现在有疫情全程的来自非洲各国的序列，虽然最近测序工作似乎稍有减少。
南非贡献了一大部分的序列。


<!-- ############ SLIDE BREAK ############# -->
# [非洲的聚类Clustering in Africa](https://nextstrain.org/ncov/africa/2020-08-11?d=tree&f_region=Africa&legendOpen&p=full&f_country=Democratic%20Republic%20of%20the%20Congo,Senegal,South%20Africa)

In the DRC, Senegal, and South Africa, we can see clear signs of local transmission, shown as clusters of sequences in the tree.
From Senegal and South Africa, we also have samples collected more recently.
These samples generally fall within the older diversity of the country, as we would expect from continued local transmission.
在民主刚果、塞内加尔和南非，我们可以看到明显的本地传播的标志，也就是序列在演化树上聚集成簇的现象。
对于塞内加尔和南非，我们也有近期收集的样本。
这些样本基本上处于本国之前的遗传组成之内，与持续的本地传播的预期相符。
Though we must be cautious with our conclusions as they are greatly limited by highly biased sampling, the recent samples from Africa we have do not suggest continued importation of variants from elsewhere.
虽然我们必须对下结论保持谨慎，因为取样是有高度偏差的，但是我们所有的非洲近期的样本不支持，还存在其他地区对该地的输入。
This finding likely reflects the continued restrictions in movement globally.
这个结果很有可能是全球仍有旅行限制的结果。


<!-- ############ SLIDE BREAK ############# -->
# [United States epidemic is a mixture of local and within-country transmission美国疫情混合了本地传播和国内传播](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&p=full)

Here we show genomes from the United States epidemic from April 15 to present day. In mid-April, all U.S. states were on lockdown. 这幅图展示了美国的样本，从4月15日到今日。在四月中旬，美国所有州都进入了封锁状态。 [各州后续采取了程度不一的重启措施](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html)。

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
