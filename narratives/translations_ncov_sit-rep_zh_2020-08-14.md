---
title: 新型冠状病毒（COVID-19）的基因组流行病学分析：2020年8月更新
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
新冠疫情现已遍及世界各地，全球[每周新增病例数超过一百五十万](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports)， 累计确诊病例数已达[一千八百万](https://ourworldindata.org/covid-cases) ，死亡病例数超过[60万](https://ourworldindata.org/covid-deaths)。
\n\n
### 世界卫生组织在[2020年8月2日的状况报告中总结道](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports):
\n\n
### **\"随着各国放松了用于限制病毒传播的公共卫生和社会防疫措施，很多国家出现了聚集性病例，或出现病例数回升的现象。在较脆弱、资源贫瘠和存在战争冲突的地区，人们所面临的风险和脆弱性更为严峻。\"**
\n\n
### 在世界范围内，对新冠病毒（SARS-CoV-2）基因组的测序仍在稳定地进行中。我们用Nextstrain来分析这些数据，追踪病毒在地理上的传播及其演化。
目前，我们获得了世界上半数国家所公开分享的超过 75000 条病毒基因组序列——这是对于数据背后的科学家和公共卫生工作者的杰出工作的有力证明。
\n\n
### 我们用子抽样（subsampling）的方法来消除可能存在的抽样偏差的影响，来确保所分析的地理和时间区间是合理的。
（这也有助于满足计算上的要求。）
\n\n
### 在这幅图中，您可以看到约 4300 条基因组的地理分布。
每个国家的中心都有一个圆圈，其颜色表明所处地区，半径与该国家的序列数成正比。([点击此处查看如何解读Nextstrain上的地图（英文）](https://nextstrain.org/docs/visualisation/map-interpretation)).
\n\n
### 在本篇报告中，我们研究全球新冠疫情的基因组流行病学的整体趋势，并对每个地区的最新情况提供具体的报告。
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
* [病毒在全球的谱系分布](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [棘突蛋白基因的D614G突变](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [亚洲的情况](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [大洋洲的情况](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [欧洲的情况](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [南美的情况](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [非洲的情况](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [北美的情况](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [结语](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [科学贡献人员](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Nextstrain的资料
* [入门篇：如何解读系统发生树](https://nextstrain.org/narratives/trees-background/zh)
* [之前的状况报告](https://nextstrain.org/ncov-sit-reps/)
* [冠状病毒的背景资料（英文）](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# 总结

在本篇报告中，我们分析了已公开的新冠病毒基因组序列。通过将病毒基因组互相比较，我们可以描述新冠病毒是如何在全球各地迁移和在社区内传播的。

- 在亚洲，“19A”和“19B”两个病毒分支所占比例更高，而“20A”、“20B”和“20C”等病毒分支在欧洲和北美占比较大。

- 在全球范围内，我们可以清楚地看到棘突蛋白的D614G突变在种群中的频率显著上升。有假说认为，这个变异能够导致新冠病毒传播力增强。

- 为了更好地显示在全球收集到的新冠病毒实时数据，我们建立了6个区域数据集和1个全球数据集，并在每个工作日都进行更新。

- 在亚洲，病毒在流行的早期存在大量的跨国传播。近期，我们看到病毒传播的范围转向了在国境之内的传播，这也是我们在全球大多数地区都能看到的一个趋势。

- 在大洋洲，新西兰所报告的病例都处于在一个狭窄的时间窗口之内，对应于他们（在本周之前）已经消除了疫情。澳大利亚最近病例数骤增的情况也显示在数据中——至少在已公开的样本中，能够看到有一些病例的序列紧密地聚在一起，在遗传多样性上，它们也位于当地之前所流行的病毒的范围内。

- 新冠病毒曾在欧洲极快地传播——它很可能在人们意识到之前就已经在很多国家中传播了。这导致在病毒流行的早期，欧洲的样本大量地混杂在一起，使我们难以辨别和确认病毒在地区之间传播的方向。最近，由于旅行限令限制了病毒的传播，我们可以看到特定国家与特定变异之间更明显的关联。 More recently, we can see more distinct variants associated with particular countries, as viruses have been constrained through travel restrictions.

- 像其他地区一样，南美曾经历多次输入事件，其病毒的遗传多样性涵盖了我们已知的大部分新冠病毒基因组序列的多样性。在旅行限令开始实施之后，病毒的序列开始更明显地聚在一起了。很遗憾，尽管很多国家正在经历严重的疫情，我们没有很容易地得到更多新近的序列。Like other regions, South America had multiple introductions, covering most of the known diversity of SARS-CoV-2. After travel restrictions came into place, sequences begin clustering more noticeably. Unfortunately, despite severe ongoing epidemics in many countries, more recent sequences are not readily available.

- 非洲也在病毒流行早期经历了多次、差异很大的输入事件。后续的旅行限令似乎限制了非洲各国之间病毒的混杂，大多数的序列都似乎来自同一国家早些时候流行的遗传多样性。Africa also had multiple, diverse introductions early in the pandemic. Subsequent travel restrictions seems to have limited mixing among African countries, with most sequences seeming to come from earlier circulating diversity in the same country.

- 美国的情形则有不同，当地的国内旅行没有受到很大限制：我们看到各州的序列都混杂在一起，同时也看到了本地传播的现象。在墨西哥和中美洲，我们看到了传播中的地理聚集的例子，特别是在美国加利福尼亚州和墨西哥的北下加利福尼亚州之间。 In Mexico & Central America, we see examples of geographical clustering in transmission, particularly between California (USA) & Baja California (Mexico).

```


<!-- ############ SLIDE BREAK ############# -->
# [新冠病毒变体在全世界的分布](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

新冠病毒自从在2019年末出现以来，已经演化出了几种变体（variants），同时在地球上传播。为了便于讨论，我们根据一些特征性的突变，把这些变体归成了几个分支（clades）。

我们目前定义了5个大的分支（详见[这篇博文](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming)）：

* 19A 和 19B 出现在武汉，在疫情的早期占比较大。
* 20A 来自于 19A，在三月占据了欧洲疫情的较大比重，然后从那里传播到了全球。
* 20B 和 20C 是 20A 的在遗传组成上有显著差异的两个亚分支。


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


图中显示的是这些分支在世界各地的分布（现在图中的颜色代表的是所属分支）。
您可以看到，亚洲国家具有 19A 和 19B （蓝色）的比例较高，因为这一支在疫情的早期占比较大。
欧洲和北美的疫情混合了所有的分支，但以 20B 和 20C 为主（分别是黄色和橙色）。

#### 如果您想知道手中新冠病毒的序列属于哪个分支（以及估测其在系统发生树中的位置），我们制作了Nextclade工具([clades.nextstrain.org/](https://clades.nextstrain.org/))，您可以通过在浏览器中把FASTA文件拖拽上传到该页面来使用。

<!-- ############ SLIDE BREAK ############# -->
# [著名的棘突蛋白D614G突变](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

棘突蛋白基因中的D614G突变最近上了新闻，是很多推测的话题中心。
The D614G substitution in the gene coding for the Spike (S) protein has been in the news recently and the topic of much speculation.

有证据显示，G型变体（本图中为黄色）在体外实验中提高了新冠病毒的感染性，有可能因其提高的人传人的几率而在演化中被选择（[Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1) ）。然而，感染力的增加可能伴随着使病毒更易受中和抗体攻击的代价（[Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)）。

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
在这棵树上，正如其他地区的树一样，我们看到病毒在本地传播的案例，也就是相似颜色、不同时间的样本点聚在一起。您可以点击“探索数据（Explore the Data Yourself）”，把过滤条件中的地点设为华盛顿州的亚基马（Yakima County），就可看到一个清楚的例子，遗传学上亲缘关系很近的病毒是如何进入这个地区并在这里传播的。（也可以[点击此处](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&f_location=Yakima%20County&p=grid) ，但会离开本篇报告。）


However, on the tree, we  also see within-country transmission across the U.S. as shown by mixing of colors at the tree tips. On the map, within-country transmission looks like transmission lines extending between states. These observations are consistent with few domestic travel restrictions and states' reopening policies.
然而，在树上，我们也看到在美国内部，病毒在各地之间传播，也就是不同颜色的样本点混在一起。在地图上，国内传播被表示为在各州之间相连的线条。这些观察与美国几乎没有国内旅行限制，各州推行重启计划相一致。


<!-- ############ SLIDE BREAK ############# -->
# [Central American sequencing shows geographically-clustered transmission中美洲的测序结果表明，病毒传播根据地理聚类](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map,entropy&f_country=Belize,Costa%20Rica,Guatemala,Jamaica,Mexico,Panama&p=grid&transmissions=hide)

There has been limited sequencing from Central America, especially over the past two months, which restricts the inferences we can draw about the epidemic. From the genomes that have been shared, we see geographic clustering of SARS-CoV-2 genomes.
中美洲的序列相对有限，尤其是在过去的两个月内，限制了我们能对疫情所能做的推论。从已公开的基因组中，我们看到了新冠病毒基因组按照地理位置所聚集在一起。

Toward the bottom of the tree in clade 19B, we see a cluster of transmission in Panama starting in mid-February. Several later sequences in Panama from June and July nest in with this cluster, suggesting there's continued local transmission of this virus genotype in the country.
在19B这一支的底部，我们看到巴拿马的一个从二月中旬就开始的传播链。巴拿马的几条近期的六月和七月的序列处于这一簇中，表明病毒的这个基因型在该国持续本地传播。

In Mexico, we also see clear geographic clustering of transmission through May. Without more recent sequencing, we cannot make inferences about the epidemic in later months.
在墨西哥，我们也看到了清晰的在地理上的聚集，在五月中的传播。没有更近的测序数据的话，我们不能对之后的几个月的疫情进行推论。

In the center of the tree, there is a cluster of cases in Baja California (in light blue). These cases were likely imported from California, USA (green branches on the tree) in March. This inferred importation is consistent with known travel links between the neighboring locations although we should be cautious about interpreting inferred transmission locations given sparse sequencing.
在树的中部，在北下加利福尼亚州（浅蓝色）有一簇样本。这些样本很有可能是由美国的加利福尼亚州（绿色的分支）在三月输入的。这起推断的输入事件符合已知的旅行关系，在这两个相邻的地区，虽然我们应该对于解读对于传播地区的推断保持谨慎，因为测序量稀少。


<!-- ############ SLIDE BREAK ############# -->
# [结语](https://nextstrain.org/ncov/global/2020-08-11?d=map)

As the pandemic reaches its eighth month of global circulation, we can now see distinct changes over time in the picture painted by viral genetics, largely determined by changing behaviour.
随着新冠病毒的全球大流行进入第八个月，我们现在可以看到疫情随着时间发生了显著的变化，而病毒的遗传学为我们描绘了这样一个图景，这样的变化很大程度上是由人们的行为变化所决定的。

Multiple early transmissions to the USA, Oceania, Europe, and across Asia, were initially incredibly well-mixed, as our global travel patterns distributed the virus incredibly effectively. Soon afterwards, diverse introductions to South America and Africa, often from Europe and North America, seeded local epidemics there.
在美国、大洋洲、欧洲和亚洲各地，早期的多起传播事件，起初是难以想象地混杂的，我们的全球旅行，以惊人的效率把病毒散布到了各地。之后很快，多样的病毒被输入到南美洲和非洲，常常是来自欧洲和北美洲，在那里撒下了本地传播的种子。


As the scale of the viral spread and severity of COVID-19 became apparent, travel ground to a halt in much of the world. After this point, we can see a distinct shift to local transmission during 'lockdowns' and the most severe travel restrictions. One outcome of this is that we can now sometimes better identify the source for viruses, as local epidemics have in some cases become more genetically distinct. In the USA, the absence of strict domestic travel has helped maintain well-mixed epidemics between states.

随着病毒传播的规模和新冠病情的恶劣程度逐步清晰，在全球的大部分地区，旅行都渐渐停止了。在这一点之后，我们可以看到一个明显的转变，在“封城”和最严格的旅行限令期间向本地传播的转变。这其中的一个后果是，我们现在有时可以更好地识别病毒的来源，因为在一些情况下，本地疫情的病毒变得在遗传上更加独特了。在美国，由于缺少严格的国内旅行限制，各州的病毒序列仍然充分混杂在一起。

Borders are now re-opening and travel has resumed, though not nearly to pre-pandemic levels. This, combined with the lag time from when samples are taken to when they are available publicly, means we only see a few signs of between-country mixing. In general, recent samples tend to continue to cluster with past sequences from the same country, indicating continued transmission of previously circulating variants. 
现在，各国正在逐步打开边境，恢复旅行，虽然还完全比不上疫情前的程度。这样的做法，加上延迟的时间，从采样到序列发布所需要的时间，意味着我们只看到一些国家间传播的标志。总体上，近期的样本倾向于继续与同一国家之前的样本相聚类，表明之前的病毒还在当地持续传播。

Unfortunately, many countries have seen a rise in cases in the last few weeks, usually associated with reopening. As the Northern Hemisphere prepares to move into autumn and colder weather, further reopening, and school resuming, we must remain vigilant about rising case counts. As winter progresses in the Southern Hemisphere, we see worrying signs that seasonality could indeed lead to more trouble containing transmission - Australia's initial success with the virus has been dampened by recent outbreaks. Continuing to scale up Test, Trace, and Isolate, careful hand-hygiene, and conscientious mask-wearing can help keep our societies as open as possible while we continue to battle SARS-CoV-2.
很遗憾，在过去的几周中，很多国家都看到了病例数的重新增长，通常是与疫情后的重启有关。随着北半球准备进入秋冬天气，进一步的重启，开学，我们必须对上涨的病例数保持警惕。随着南半球入冬，我们看到令人担忧的迹象，季节确实会对控制病毒传播带来更多困难——一开始控制疫情非常成功的澳大利亚，最近也遭遇了又一轮疫情爆发。继续扩大检测范围，对病例进行追踪和隔离，认真洗手，自觉带好口罩，可以让我们在与新冠病毒继续战斗的同事，尽可能地保持我们的社会生活。

<!-- ############ SLIDE BREAK ############# -->
# [科学贡献人员](https://nextstrain.org/ncov/global/2020-08-11?d=tree&c=author)

我们要感谢参与此次疫情研究的所有科学家所做的令人惊叹和及时的工作。只有通过基因组数据和元数据的快速共享，才有可能进行这样的分析。
**我们鼓励您点击“探索数据（Explore the Data Yourself）”，然后下拉页面，查看完整的作者列表；单条序列的作者也可以通过在树上选中该序列来查看。** 
我们也感谢 GISAID 提供了上传和共享这些数据的平台。

