---
title: COVID-19 ゲノム疫学 2020年8月の更新
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
  - Fengjun Zhang
  - Tomoyuki Nezu
  - Takeshi Sato
translatorLinks:
  - https://twitter.com/fengjun_zhang
  - https://twitter.com/tommy_nezy
  - https://github.com/satotake
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-08-11?d=map"
date: "2020 August 14"
abstract: "
現在、世界的に感染が拡大しており、[毎週150万人以上の新たな患者](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports)、総報告数は[1,800万人](https://ourworldindata.org/covid-cases)、[60万人以上の死亡者数](https://ourworldindata.org/covid-deaths)となっています。
\n\n
### 2020年8月2日にWHOがまとめた状況: (https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports)
\n\n
### **\"各国がウイルスの感染を制限するために実施した公衆衛生および社会的対策が緩和されるにつれ、これらの国の多くではクラスタの発生や感染の再発が確認されています。リスクと脆弱性は、脆弱で、資源が少なく、紛争の影響を受けている状況ではさらに拡大しています。\"**
\n\n
### 世界的な SARS-CoV-2ゲノムの配列決定作業は衰えることなく続けられており、このデータをもとに Nextstrain を利用してウイルスの地理的な移動と進化を追跡しています。
現在までに世界の半分の国から75,000以上の配列が公開されていますが、これはこの背後にいる科学者と公衆衛生関係者の驚くべき成果です。
\n\n
### 我々は、分析のために地域と期間が適切に含まれるようにするため、サブサンプリング手法を使用して潜在的なサンプリングバイアスを削除します(これは計算要件にも役立ちます)
\n\n
### ここでは、約4300のゲノムの地理的分布を見ることができます。
各円は個々の国を中心にしており、色は地域を示し、半径はその国のゲノム数に応じて変化します（[Nextstrainでの地図の解釈についてはこちらを参照してください](https://nextstrain.org/docs/visualisation/map-interpretation))
\n\n
### このレポートでは、COVID-19の世界的ななゲノム疫学を幅広く調査し、各世界の地域に固有の更新情報を提供します。
"
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Please add your names & links to the 'translators' section above -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- table of contents slide -->
# [COVID-19 のまとめ](https://nextstrain.org/ncov/global/2020-08-11?d=map)

### 目次
* [世界的な系統群の分布](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [D614Gスパイクの変異](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [アジアの状況](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [オセアニアの状況](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [ヨーロッパの状況](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [南アメリカの状況](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [アフリカの状況](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [北アメリカの状況](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [まとめ](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [著者、提供者など](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Nextstrain Resources
* [START HERE: How to read a phylogeny](https://nextstrain.org/narratives/trees-background/)
* [Previous Situation Reports](https://nextstrain.org/ncov-sit-reps/)
* [Background on coronaviruses](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# 概要

このレポートでは、公開されている COVID-19 ゲノムを分析しました。これらのウイルスのゲノムを相互に比較することにより、COVID-19 が世界中をどのように移動しているか、地域の中でどのように拡散しているかを特徴付けることができます。

- アジアでは 19A および 19B 系統群の割合が高く、20A, 20B および 20C 系統群がヨーロッパおよび北米で優勢です。

- 世界的に見ても、Spikeタンパク質の D614G 置換が目立つようになってきているのがよくわかります。この変異は SARS-CoV-2 の感染を増加させる原因になると考えられています。

- 世界中の SARS-CoV-2 データのリアルタイムでの分析をより適切に表示するために、6つの地域分析と1つの全世界での分析を実行します。これらは毎週更新されます。

- アジアでは感染拡大の初期に国間の感染が多数発生していました。最近では国内での感染が増加しており、これはほとんどの地域で見られる傾向です。

- オセアニアでは、ニュージーランドの症例は、ウイルスの排除に対応する狭い時間帯にとどまっています（今週まで）。オーストラリアの最近の症例数の急増は、少なくともこれまでに共有されたサンプルを見ると、以前の多様性からの症例が緊密にクラスタリングされていることを示しています。

- SARS-CoV-2 はヨーロッパで非常に急速に拡散しました。このため、感染拡大の初期にはヨーロッパのサンプルの混合が激しく、ある場所から別の場所への感染を区別し識別することが困難になりました。最近では渡航制限によってウイルスが制限されるようになったため、特定の国に関連したより明確な亜種が見られるようになりました。

- 他の地域と同様に、南米でも複数の伝播があり、SARS-CoV-2 の既知の多様性のほとんどをカバーしています。渡航制限が行われるようになってからは、遺伝子配列は顕著にクラスター化し始めます。残念ながら、多くの国で進行中の深刻な流行にもかかわらず、より最近の遺伝子配列は容易に入手できません。

- アフリカでも、感染拡大の初期には複数の多様な伝播がありました。その後の渡航制限により、アフリカ諸国間での混合は制限されているようで、ほとんどの配列は同じ国で以前に流通していた多様性に由来しているようです。

- 国内旅行が大幅に制限されていない米国では、異なる画像が示されています。すべての州間の混合と局所的な伝播が見られます。メキシコと中米では、特にカリフォルニア州（米国）とバハ・カリフォルニア州（メキシコ）との間で地理的なクラスタリングが見られます。

```


<!-- ############ SLIDE BREAK ############# -->
# [Worldwide distribution of genetic variants](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

Since its emergence in late 2019, SARS-CoV-2 has diversified into several different co-circulating variants. To facilitate discussion of these variants, we have grouped them into clades which are defined by specific signature mutations.

We currently define 5 major clades (see [this blog post](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming) for details):

* 19A and 19B emerged in Wuhan and dominated the early outbreak.
* 20A emerged out of 19A, dominated the European outbreak in March, and has since spread globally.
* 20B and 20C are large, genetically distinct subclades of 20A.


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


We're now looking at the distribution of these clades across the world (the color now represents clade membership).
You can see that countries in the Asia region have a higher proportion of 19A and 19B (blues) as that variant dominated in the early outbreak.
Europe and North America have a mixture of all clades, but are dominated by 20B and 20C (yellow and orange, respectively).

#### If you have SARS-CoV-2 sequences for which you'd like to know their clade (and estimated position on a phylogenetic tree), we made Nextclade ([clades.nextstrain.org/](https://clades.nextstrain.org/)) which lets you drag-and-drop your FASTA files onto the browser.


<!-- ############ SLIDE BREAK ############# -->
# [The well-publicized D614G Spike Mutation](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

The D614G substitution in the gene coding for the Spike (S) protein has been in the news recently and the topic of much speculation.

Evidence is building that the G variant (yellow in this view) increases infectivity of SARS-CoV-2 _in vitro_ and may have been evolutionarily selected for increased human-to-human transmission ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). However, an increase in infectivity may potentially come at the cost of making the virus more vulnerable to neutralizing antibodies ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

Here we can see that this variant was inferred to have appeared very shortly after the initial zoonosis and subsequently spread around the world.
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
# [ヨーロッパの初期状況](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2は、主にアジアからの直接感染によって、ヨーロッパで急速に広がった。

By the end of February, even though there were just [a few hundred cases](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea) officially reported in Europe, the virus had spread to at least 15 European countries.
2月の終わりまでに、ヨーロッパで公式に報告された例はわずか[数百件](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea)であったにもかかわらず、実際、ウイルスは少なくともヨーロッパの15カ国に広がっていました。

パンデミックの初期にはサンプリングがあまり足りっていなかったことを考えると、SARS-CoV-2は、サンプルが行われてなかった国も含めて、ほぼ確実にヨーロッパのほとんどの地域ですでに流通していたことになります。

<!-- ############ SLIDE BREAK ############# -->
# [ヨーロッパでのロックダウン](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

3月から4月にかけて、ヨーロッパの多くの国が国境を閉鎖し、移動が制限されたり、企業や学校が閉鎖されたりする様々なタイプの「ロックダウン」が行われました。このような制限により、国間の伝播が減少し、ある国の配列がその国の以前の配列と「クラスター」する可能性が高くなると予想されます。

しかし、SARS-CoV-2はすでにヨーロッパ全体で非常に混ざり合っていたため、ウイルスの異なる遺伝型が複数の国で広げていました。ほとんどの国では、ロックダウンの前に、他国からのウイルスに関連した多数の異なる遺伝型がすでに流行していました。 これによって、国境を閉鎖した後も系統図が極めて混ざっていることを意味します（木の上で互いに近くに複数の色があることで示されています）。

それでも、私たちが予測しているような局所的な伝達の兆候がいくつかも見られます。ここでは、フィンランドとスウェーデンは、緑とオレンジ色（上から約1/3）で非常にはっきりとした伝播のクラスターを示し、またスペイン（紺色）は、木の下と上ではっきりとした局所的な伝播を示しています。アイスランド（紫）とスイス（水色）もまた、局所的なクラスターを示しています。

_ヒント：ツリーの左上にある「国」をクリックすると凡例を拡大することができます。_


<!-- ############ SLIDE BREAK ############# -->
# [欧州における最近の配列解析により、局所的な伝播が明らかになり、早期のSARS-CoV-2の伝播についての理解がより深く](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

過去1週間にアップロードされたサンプルだけを調べてみると、2 つの重要なポイントが浮かび上がってきます。

一つ、前にグループにしてたチップ（元々近かったの複数の葉）からミニクラスター（小規模な枝）に発展している傾向が見られます。これは、各国内での伝播が初期の広げた後も引き続き支配することを示しており、このような結果はヨーロッパ全土で導入された様々な規制の産物である可能性も高いでしょう。ウイルスはロックダウン中も遺伝的に多様化し続けましたが、1つの国に限定されている可能性が高く、現階段では他国からの遺伝型をよりよく区別できるようになりました。

同じ国の他のサンプルとより強くリンクするというこの傾向に従わないサンプルもあります。凡例の国の上にカーソルを置くと、その国の木のヒントがハイライトされ、そのようなサンプルを識別するのに役立ちます。例えば、木の中央には、スウェーデンのサンプル（緑）が、より大きなロシアのクラッド（赤）の中に入れ子になっているのが見えます。しかしサンプリングが一部の国で異常に多くことを考えると、この見解に基づいて、国間伝播の結論を過剰に解釈しないように慎重になる必要があります。

二つ、チップの水平方向の間隔に大きな差があり、即ちこの1週間に提出されたサンプルは、3月上旬までのサンプル収集期間を表しています。「古い」ゲノムを配列決定する理由は様々ですが、これらのサンプルは、ウイルスの進化や地理的な移動の理解を埋めるのに役立ちます。


<!-- ############ SLIDE BREAK ############# -->
# [南米の初期状況](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmax=2020-04-15)

南米の最初の SARS-CoV-2 の配列は、2 月下旬から 3 月上旬に由来のもので、ツリー全体に散在しており、複数の導入を示唆している。3月に国際的な旅行が減少したため、いくつかの国で持続的な局所感染の証拠を見ることができます。

ブラジルの（薄緑色の）配列の多くは、2つの大きなクラスター（木の上端付近）の一部であり、この変異体がチリ、ウルグアイ、アルゼンチンへと大陸を移動したことを示す証拠がいくつかあります。

また、コロンビア（オレンジ色）、チリ（ターコイズ色）、ウルグアイ（薄い青色）、アルゼンチン（濃い青色）を含む感染の明確なクラスターが木の中に散在していることがわかります。


<!-- ############ SLIDE BREAK ############# -->
# [南米の最近の状況](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmin=2020-05-01)

残念なことに、南米では SARS-CoV-2 が広く普及し続けていますが、配列の解析が追いついていませんでした。南米大陸の多くの地域で症例数は依然として多いが、5 月以降、5 カ国（ブラジル、エクアドル、ウルグアイ、アルゼンチン、チリ）からのサンプルが68件しか共有されていない。

サンプリングがまばらなために我々の推論は限られているが、多くの場合、これらのより最近のサンプルは、同じ国や他の南米諸国で採取された以前のウィルス遺伝型とリンクしている。このことは、現在流通している品種は、伝染病の初期に導入された品種の子孫であることを示唆しています。

<!-- ############ SLIDE BREAK ############# -->
# [アフリカのSARS-CoV-2](https://nextstrain.org/ncov/africa/2020-08-11?d=tree,map&f_region=Africa&legendOpen&transmissions=hide&p=grid)

南米と同様に、アフリカでもSARS-CoV-2が何度か大陸に導入されており、その多くはヨーロッパからのものと考えられています。これは、アフリカのサンプルがツリー全体に広がっていることで示されています - 同じ国からのサンプルであっても、多様な遺伝型が含まれています。

現在私たちは、アフリカ全土の国々からの配列入手していますが、最近では配列決定の努力が少しずつ低下しているように見えます。
今まで南アフリカから提供されているデータはウィルスの配列でも重要な一部です。


<!-- ############ SLIDE BREAK ############# -->
# [アフリカにおけるクラスタリング](https://nextstrain.org/ncov/africa/2020-08-11?d=tree&f_region=Africa&legendOpen&p=full&f_country=Democratic%20Republic%20of%20the%20Congo,Senegal,South%20Africa)

コンゴ民主共和国、セネガル、南アフリカでは、局所的な感染の明確な兆候が見られ、ツリー内に配列のクラスターとして示されています。
セネガルと南アフリカでは、より最近に採取されたサンプルもあります。
これらのサンプルは一般的に、局所的な伝播が継続していることを予想して、この国の前のウィルスから発展した例です。

我々の結論は非常に偏ったサンプリングによって大きく制限されているため、慎重にならざるを得ませんが、我々が入手したアフリカからの最近のサンプルは、他の場所からの遺伝型の継続的な輸入はほぼないと示唆する。
このことは、世界中に人口移動が制限され続けていることによっての成果と、私たちが考えています。

<!-- ############ SLIDE BREAK ############# -->
# [米国の流行は局所的なものと国内での伝播が混在している](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&p=full)

ここでは、4月15日から現在に至るまでの米国の伝染病のゲノムを示しています。4月中旬、米国の全州が封鎖されていました。[各州はその後、一致しない再開政策を実施して来ました。](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html)

このツリーでは、他の地域のツリーと同様に、時間の経過とともに同系色の先端（ツリーの葉）が群がっていることから、局所的なウイルス感染の例を見ることができます。「Explore the Data Yourself」をクリックして、場所を「Yakima County」選択し、ワシントン州のこの地域への遺伝的に関連したウイルスの導入と感染拡大による明確な例を見ることができます。(同じ結果は[ここ](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&f_location=Yakima%20County&p=grid)をクリックしても見られますが、このページを一時的に閉じてしまいます)。

しかし逆に、ツリー上で木の先端で色が混ざっている状態も、アメリカ国内での一部の感染を示しています。地図上では、米国内の伝播は、少なくとも一部が州間に伸びる伝播ルートからのように見えます。これらの観察結論は、国内旅行の制限が少なく、各州の厳密ではない再開政策と一致しています。


<!-- ############ SLIDE BREAK ############# -->
# [中米の塩基配列決定は地理的にクラスタ化された伝播を示している](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map,entropy&f_country=Belize,Costa%20Rica,Guatemala,Jamaica,Mexico,Panama&p=grid&transmissions=hide)

中米では、特にこの2ヶ月間、限られたシークエンシングしか行われていないため、私達からの伝染病についての推論が限りられてる。共有されたゲノムから、SARS-CoV-2 ゲノムの地理的なクラスタリングが見られる。

クレード 19B のツリーの一番下の方では、2 月中旬からパナマでの感染のクラスタが見られます。6 月と 7 月にパナマで発生したいくつかの後続の配列は、このクラスターの中に入り込んでおり、パナマではこのウイルス遺伝子型の局所的な伝播が継続していることを示唆しています。

メキシコでは、5月までの感染の地理的なクラスタリングが明らかに見られます。より最近のシークエンシングがなければ、それ以降の月の流行についての推論はできません。

ツリーの中央には、バハ・カリフォルニア州での感染者の集団が見られます（水色）。これらの症例は 3 月に米国カリフォルニア州から輸入された可能性が高いです（ツリー上の緑色の枝）。この輸入と推定された事例は、隣接する地域間の既知の旅行リンクと一致していますが、サンプリングがまばらであることを考えると、推定された感染場所の解釈には慎重にならざるを得ません。


<!-- ############ SLIDE BREAK ############# -->
# [まとめ](https://nextstrain.org/ncov/global/2020-08-11?d=map)

パンデミックが世界的な循環のその 8 ヶ月目に達すると、私たちは今、このウイルスの遺伝学によって描かれた絵の中で、主にウィルス生理上の変化に決定される明確な変化を、時間の経過とともに観察ができます。

米国、オセアニア、ヨーロッパ、アジア全域への複数の初期感染は極めて混合されていたことが、私たちのグローバルな旅行パターンが信じられないほど効果的にウイルスを分散していた結果です。その後すぐに、南米やアフリカへの伝染が、しばしばヨーロッパや北米から導入され、そこでの局所的な伝染病の種となりました。

COVID-19 のウイルスの広がりの規模と深刻さが明らかになると、世界の多くの地域で旅行が止まりました。この時点以降、「ロックダウン」と最も厳しい旅行制限の間に、局所的な伝染への明確なシフトが見られるようになりました。この結果の一つは、局所的なウィルスがより遺伝的に区別されるようになったことで、ウイルスの感染源をより正確に特定できるようになったことです。米国では、国内旅行の厳格な制限がないことで、州間の混合伝播が維持されています。

現在、国境は再開され、旅行も再開されていますが、パンデミック前のレベルにまでは達していません。これは、サンプルが採取されてから公開されるまでの時間の遅れと相まって、国家間の混合の兆候がわずかに見られるだけであることを意味しています。一般的に、最近のサンプルは、同じ国の過去の配列とクラスター化し続ける傾向があり、前に流通していた遺伝型の伝播が継続していることを示しています。

残念なことに、多くの国ではここ数週間で症例数が増加しており、通常は再開に関連しています。北半球では、秋に向けて寒さが厳しくなり、更なる再開や学校の再開しつつのため、私たちは症例数の増加に引き続き警戒しなければなりません。南半球では冬が進むにつれ、季節性が感染を食い止めるのにさらなる困難をもたらす可能性があることが懸念されます。オーストラリアのウイルスに対する初期の成功は、最近の流行によって弱まっています。SARS-CoV-2 との戦いを続ける中で、検査、追跡、隔離の規模を拡大し続け、手指の衛生管理に気を配り、きちんとしたマスクの着用を続けることは、私たちの社会を可能な限りオープンに保つのに役立ちます。

<!-- ############ SLIDE BREAK ############# -->
# [分析データのクレジット](https://nextstrain.org/ncov/global/2020-08-11?d=tree&c=author)

私たちはこの感染症流行の中において、関係したすべての科学者による驚くべきタイムリーな研究に謝意を表します。 
この分析は世界中の科学者や医師によるゲノム配列や病例に関するメタデータの共有があって可能になりました。

**「データを自分で調べる」（Explore the Data Yourself）をクリックし、下にスクロールして著者の全リストを表示することをお勧めします。ツリーで遺伝子情報を選択すると、個々の遺伝子情報の作成者を利用できます。**

また、これらのデータをアップロードおよび共有できるプラットフォームを提供してくれた GISAID にも感謝します。
