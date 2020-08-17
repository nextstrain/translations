---
title: Pemutakhiran Agustus 2020 mengenai epidemiologi genomik COVID-19
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
  - Erwin Sentausa
  - Iskandar Adnan
translatorLinks:
  - https://www.linkedin.com/in/sentausa
  - https://twitter.com/wikidisastra
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-08-11?d=map"
date: "14 Agustus 2020"
abstract: "
Pandemik saat ini menyebar luas ke seluruh dunia, dengan lebih dari [1,5 juta kasus baru tiap pekan](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports) dan jumlah kasus terlaporkan [18 juta](https://ourworldindata.org/covid-cases) serta [600.000 kematian](https://ourworldindata.org/covid-deaths).
\n\n
### Keadaan [dirangkum oleh WHO pada 2 Agustus 2020](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports):
\n\n
### **\"As countries have eased public health and social measures, implemented to limit transmission of the virus, a number of these countries have observed clusters or resurgences of cases. Risks and vulnerabilities are further magnified in fragile, low-resource and conflict-affected settings.\"**
\n\n
### Pembacaan sekuens genom SARS-CoV-2 di dunia terus berlanjut, dan dengan data ini kami menggunakan Nextstrain untuk melacak pergerakan geografis dan evolusi si virus.
Terkini, terdapat lebih dari 75.000 sekuens dibagikan untuk umum dari separuh negara-negara di dunia - warisan luar biasa bagi para ilmuwan dan pejabat kesehatan masyarakat di belakangnya.
\n\n
### Kami menggunakan pendekatan subsampling untuk menyingkirkan potensi bias sampling untuk memastikan bahwa wilayah dan periode-waktu ditautan secara memadai untuk analisis.
(Ini juga membantu untuk persyaratan komputasi.)
\n\n
### Di sini anda dapat melihat sebaran geografis ~4300 genom.
Tiap lingkaran berpusat pada negara masing-masing, warna menandakan wilayah, dan radius sebanding dengan jumlah genom dari negara tersebut ([lihat di sini untuk bantuan penafsiran peta dalam Nextstrain](https://nextstrain.org/docs/visualisation/map-interpretation)).
\n\n
### Dalam laporan ini, kami menguji epidemiologi genomik global COVID-19 secara luas dan menyediakan pemutakhiran spesifik untuk tiap wilayah dunia.
"
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Please add your names & links to the 'translators' section above -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->


<!-- ############ SLIDE BREAK ############# -->
<!-- table of contents slide -->
# [Ringkasan COVID-19](https://nextstrain.org/ncov/global/2020-08-11?d=map)

### Daftar isi
* [Penyebaran klad global](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=2)
* [Mutasi 'Spike' D614G](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=3)
* [Keadaan di Asia](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=5)
* [Keadaan di Oseania](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=7)
* [Keadaan di Eropa](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=10)
* [Keadaan di Amerika Selatan](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=13)
* [Keadaan di Afrika](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=15)
* [Keadaan di Amerika Utara](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=17)
* [Ringkasan penutup](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=19)
* [Kredit](https://nextstrain.org/narratives/ncov/sit-rep/2020-08-14?n=20)

#### Sumber Daya Nextstrain
* [START HERE: How to read a phylogeny](https://nextstrain.org/narratives/trees-background/)
* [Previous Situation Reports](https://nextstrain.org/ncov-sit-reps/)
* [Background on coronaviruses](https://nextstrain.org/help/coronavirus/human-CoV)

<!-- This is the right-side text -->
```auspiceMainDisplayMarkdown

# Ringkasan Eksekutif

Dalam laporan ini, kami menganalisis genom SARS-CoV-2 terbagi umum. Dengan membandingkan genom-genom virus ini, kami dapat mengkarakterisasi bagaimana COVID-19 bergerak ke seluruh dunia dan menyebar secara lokal.

- Asia memiliki proporsi klad 19A & 19B lebih tinggi, sedangkan klad 20A, 20B & 20C mendominasi Eropa & Amerika Utara.

- Secara global, kami dapat secara jernih melihat bangkitnya keunggulan substitusi D614G dalam protein 'spike'. Varian ini dihipotesiskan menjadi penyebab peningkatan penularan SARS-CoV-2.

- Untuk menampilkan lebih baik bangun 'real-time' data SARS-CoV-2 di seluruh dunia, kami menjalankan 6 bangun regional dan 1 bangun global, yang dimutakhirkan setiap pekan.

- Di Asia, terdapat banyak penularan antar-negara di wilayah yang terpapar awal dalam pandemik. Yang lebih baru, kami melihat pergerakan ke dalam-negeri, suatu tren yang terlihat di kebanyakan wilayah.

- Di Oseania, kasus Selandia Baru tertangani dalam tempo yang singkat, berhubungan dengan pembasmian virusnya (hingga pekan ini). Australia's recent surge in cases shows up, at least in the samples shared so far, as tightly clustering cases coming from previously circulating diversity.

- SARS-CoV-2 menyebar sangat cepat di Eropa - si virus sepertinya telah ditularkan di banyak negara sebelum disadari. Ini mengakibatkan percampuran berat sampel Eropa di awal pandemik, menjadikannya sulit untuk membedakan dan mengenali introduksi dari satu tempat ke tempat lain. Lebih baru-baru ini, kami dapat melihat varian yang berbeda yang berkaitan dengan negara tertentu, karena virus terkurung akibat pembatasan/pelarangan bepergian.

- Sebagaimana wilayah lainnya, Amerika Selatan mengalami banyak introduksi, maliputi hampir semua keragaman SARS-CoV-2 yang diketahui. Setelah pembatasan bepergian, pengklasteran sekuens lebih terlihat. Sayangnya, kendati epidemik yang parah masih berlangsung di banyak negara, sekuens lebih baru belum tersedia.

- Afrika juga mengalami introduksi yang banyak dan beragam di awal pandemik. Pembatasan bepergian kemudian membatasi percampuran antarnegara Afrika, dengan kebanyakan sekuens sepertinya berasal dari keragaman yang bersirkulasi lebih awal di negara yang sama.

- Gambaran berbeda ditunjukkan di AS, di mana perjalanan domestik tidak banyak dibatasi: kami melihat percampuran di sluruh negara bagian, begitu pula penularan lokal. Di Meksiko & Amerika Tengah, kami melihat contoh pengklasteran geografis dalam penularan, khususnya antara Kalifornia (AS) & Baha Kalifornia (Meksiko).

```


<!-- ############ SLIDE BREAK ############# -->
# [Sebaran sejagat varian genetik](https://nextstrain.org/ncov/global/2020-08-11?c=clade_membership&d=map&r=color)

Sejak kemunculannya pada akhir 2019, SARS-CoV-2 telah terpecah menjadi beberapa varian yang beredar bersamaan. Untuk mewadahi diskusi varian ini, kami telah mengelompokkannya ke dalam klad-klad yang ditentukan oleh mutasi penciri spesifik.

Saat ini kami menentukan 5 klad mayor (lihat [this blog post](https://nextstrain.org/blog/2020-06-02-SARSCoV2-clade-naming) untuk lebih rinci):

* 19A dan 19B muncul di Wuhan dan mendominasi di awal wabah.
* 20A muncul dari 19A, mendominasi wabah Eropa bulan Maret, dan kemudian menyebar secara global.
* 20B dan 20C adalah subklad dari 20A yang secara genetik berbeda.


<svg viewBox="0 0 120 80">
<g transform="translate(-77.7 -164.8)"><circle cx="177.3" cy="172.6" r="2.6" fill="#e8ce4b"></circle><circle cx="177.3" cy="183.2" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="193.8" r="2.6" fill="#ff923a"></circle><circle cx="177.3" cy="204.4" r="2.6" fill="#a8d66e"></circle><circle cx="177.3" cy="215" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="236.1" r="2.6" fill="#4c87e8"></circle><circle cx="177.3" cy="225.6" r="2.6" fill="#6ec2b2"></circle><path fill="none" stroke="#a8d66e" d="M129.6 172.6h-5.2v31.8h52.9"></path><path fill="none" stroke="#e8ce4b" stroke-width="1.005" d="M129.6 172.6h47.7"></path><path fill="none" stroke="#a8d66e" d="M177.3 183.2h-53"></path><path fill="none" stroke="#ff923a" d="M177.3 193.8h-47.7"></path><path fill="none" stroke="#4c87e8" d="M177.3 236.1H92.6v-47.6h26.5"></path><path fill="none" stroke="#6ec2b2" d="M177.3 225.6H97.9"></path><path fill="none" stroke="#4c87e8" d="M177.3 215H92.6"></path><path fill="none" stroke="#a8d66e" d="M129.6 193.8h-5.2m0-5.3H119"></path><path fill="none" stroke="#4c87e8" d="M97.9 225.6h-5.3m0-15.9h-5.3"></path><text style="line-height: 1.25;" x="76.7" y="207" fill="#4c87e8" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="76.7" y="207">19A</tspan></text><text style="line-height: 1.25;" x="95.3" y="222.9" fill="#6ec2b2" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="95.3" y="222.9">19B</tspan></text><text style="line-height: 1.25;" x="108.5" y="185.9" fill="#a8d66e" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="108.5" y="185.9">20A</tspan></text><text style="line-height: 1.25;" x="127" y="191.2" fill="#ff923a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="191.2">20C</tspan></text><text style="line-height: 1.25;" x="127" y="170" fill="#e5cb4a" stroke-width="0.3" font-family="sans-serif" font-size="7.1" font-weight="400" letter-spacing="0" word-spacing="0"><tspan x="127" y="170">20B</tspan></text></g>
</svg>


Kini kami mengamati sebaran klad-klad ini di seluruh dunia (warna kini mewakili keanggotaan klad).
Anda dapat melihat bahwa negara-negara di wilayah Asia memiliki proporsi 19A dan 19B yang lebih besar (biru) sebagai varian yang mendomonasi saat awal wabah.
Eropa dan Amerika Utara memiliki campuran seluruh klad, namun didominasi 20B dan 20C (kuning dan jingga, berturut-turut).

#### Jika anda memiliki sekuens SARS-CoV-2 yang ingin diketahui kladnya (dan perkiraan letaknya dalam pohon filogenetik), kami telah membuat Nextclade ([clades.nextstrain.org/](https://clades.nextstrain.org/)) yang memungkinkan anda seret-dan-lepas berkas FASTA anda ke dalam penjelajah.


<!-- ############ SLIDE BREAK ############# -->
# [Mutasi 'Spike' D614G yang terpublikasi dengan baik](https://nextstrain.org/ncov/global/2020-08-11?c=gt-S_614&d=tree,map&r=region&transmissions=hide&legendOpen)

Substitusi D614G pada gen yang menyandi protein 'Spike' (S) baru-baru ini telah diberitakan dan menimbulkan banyak spekulasi.

Bukti-bukti menunjukkan bahwa varian G (kuning dalam tampilan ini) meningkatkan infektivitas SARS-CoV-2 _in vitro_ dan mungkin secara evolusioner terpilih untuk peningkatan penularan manusia ke manusia ([Korber et al.](https://www.cell.com/cell/pdf/S0092-8674(20)30820-5.pdf), [Zhang et al.](https://www.biorxiv.org/content/10.1101/2020.06.12.148726v1.full), [Yurkovetskiy et al.](https://www.biorxiv.org/content/10.1101/2020.07.04.187757v2), [Daniloski et al.](https://www.biorxiv.org/content/10.1101/2020.06.14.151357v2), [Volz et al.](https://www.medrxiv.org/content/10.1101/2020.07.31.20166082v1)). Namun, peningkatan infektivitas dapat berpotensi untuk mengakibatkan si virus lebih rentan terhadap antibodi penetral ([Weissman et al.](https://www.medrxiv.org/content/10.1101/2020.07.22.20159905v1)).

Di sini kita dapat melihat bahwa varian ini disimpulkan muncul segera setelah zoonosis awal dan kemudian menyebar ke seuruh dunia.
Pada Juli, varian 614G terdapat pada mayoritas virus yang beredar sejagat. Sejak awal kemunculannya, substitusi telah muncul berkali-kali dan berreversi ke varian 614D.
Tak ada bukti bahwa substitusi dan reversi ini telah menghasilkan rantai penularan yang sinambung.


<!-- ############ SLIDE BREAK ############# -->
# [Menganalisis bentukan regional terpisah](https://nextstrain.org/ncov/global/2020-08-11?&c=num_date&d=map&r=region&legendOpen&transmissions=show)

Berhubung terdapat terlalu banyak genom untuk ditampilkan dalam pohon tunggal, kami menyediakan analisis regional untuk enam wilayah yang ditampilkan di sini, di samping bentukan global utama.
Ini memungkinkan kira untuk fokus pada keragaman dalam wilayah, sementara memilih sampel di luar wilayah yang tepat, sehingga kami dapat menjaga gambaran seluruh penularan antarwilayah sepanjang waktu - sebagaimana dapat kita lihat pada layar ini!

Pada layar berikutnya kami akan menyediakan gambaran masing-masing wilayah tersebut dengan berpindah ke dataset terkait. (Ini fitur baru dalam Nextstrain Narratives!)

Inventaris lengkap bangunan yang kami dan pihak lain kelola tersedia di [nextstrain.org/sars-cov-2](https://nextstrain.org/sars-cov-2/).

<!-- ############ SLIDE BREAK ############# -->
# [Keadaan Asia pra-Juni](https://nextstrain.org/ncov/asia/2020-08-11?dmax=2020-06-01&d=map&f_region=Asia&legendOpen)

Jika kita menguji keadaan Asia dari genom yang terkumpul sebelum Juni 2020, kita melihat tanda sekaligus penularan luas dalam-Asia dan penularan ke dan dari belahan dunia lain.

#### Menafsirkan garis dan warna

Di sini hanya negara-negara Asia yang diwarnai, sedangkan wilayah lainnya dikelabukan.
Warna tiap garis penularan (garis antarlingkaran) mewakili tempat asal, oleh karena itu seluruh garis **berwarna** mewakili penularan yang berasal dari suatu negara dalam Asia (dalam contoh ini).

#### Penularan ke Asia

Ini menampilkan bahwa banyak dari penularan yang melibatkan negara Asia dan non-Asia merupakan importasi ke Asia (garis kelabu).
Terutama yang disebutkan dalam tampilan ini adalah penularan dari Eropa ke Asia (meskipun garis-garisnya kalihatan seperti datang dari Jerman, titik ini mewakili seluruh Eropa). Namun, kita harus hati-hati mengenai magaimana penafsiran kita terkadap kesimpulan penularan ini, karena pengaruh besar bias penyampelan (dan kita memiliki sampel dari Eropa jauh lebih banyak daripada wilayah lain).


<!-- ############ SLIDE BREAK ############# -->
# [Keadaan Asia setelah 1 Juni](https://nextstrain.org/ncov/asia/2020-08-11?d=tree,map&dmin=2020-06-01&f_region=Asia&legendOpen&p=grid)

Mengamati genom yang tersampel setelah 1 Juni (yaitu dua bulan terakhir), kita melihat bahwa penyampelan didominasi oleh lebih sedikit negara.
Ini membatasi kesimpulan yang bisa kita tarik, namun sepertinya kita memiliki penularan antarnegara yang lebih sedikit.

Ini juga terbukti saat kita mengamati filogeninya, di mana kita memiliki pengelompokan genom monofiletik (di bagian pohon yang sama) besar dari Singapura (kuning) dan Bangladesh (biru muda).

Data ini konsisten dengan berkurangnya perjalanan internasional dan pengaturan yang lebih ketat.


<!-- ############ SLIDE BREAK ############# -->
# [Ikhtisar Oseania](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree,map&f_region=Oceania&legendOpen&p=grid&transmissions=hide)

Di sini kita dapat menjelajahi ~790 genom dari Australia dan Selandia Baru dengan tambahan ~1100 sekuens untuk menyediakan konteks global.
Hanya sampel dari Australia dan Selandia Baru yang diwarnai.

Anda dapat melihat bahwa sampel-sampel ini tersebar di seluruh pohon, menandakan bahwa Oseania telah terpapar ke (kebanyakan) keragaman genomik SARS-CoV-2 yang teramati.

Mayoritas sampel Selandia Baru (biru, ungu, hijau) datang dari kelompok temporal ketat pada Maret dan April, sebagai hasil dari strategi pengendalian yang berhasil dilakukan oleh pemerintah Selandia Baru. Sementara negara ini kembali ke kehidupan yang relatif normal, perbatasan masih tertutup untuk seluruh warga negara asing untuk membatasi kemungkinan masuknya kembali si virus. Warga negara yang kembali harus dikarantina selama 14 hari sebelum masuk.

Pekan ini, pemerintah Selandia Baru mengumumkan empat kasus baru penularan komunitas yang tidak dapat dihubungkan dengan kasus yang datang. Pemeriksaan genetik diharapkan bisa membantu menyingkap bagaimana SARS-CoV-2 menerobos pengendalian yang ketat -- lebih lanjut di bawah!

_PETUNJUK: jika mengarahkan tetikus di atas lingkaran pada peta, anda dapat melihat kiat yang relevan pada pohon yang disorot!_


<!-- ############ SLIDE BREAK ############# -->
# [Kebangkitan di Australia](https://nextstrain.org/ncov/oceania/2020-08-11?d=tree&dmin=2019-12-29&f_country=Australia&label=clade:20B&p=grid&transmissions=hide&legendOpen)

Australia, dan negara bagian Victoria (ibukota: Melbourne), ditunjukkan dengan warna jingga, telah menyaksikan kemunculan kembali kasus COVID-19 dan baru-baru ini telah menerapkan tindakan kesehatan masyarakat lebih jauh untuk berusaha mengatasi peningkatan ini.

Genom terbaru ini tampaknya merupakan subklad dari 20B (kembali ke layar sebelumnya untuk melihat bagaimana klad 20B cocok dengan filogeni keseluruhan).
Tanggal dan pengklasteran baru ini merupakan tanda dari wabah lokal.

Kita dapat melihat pengklasteran serupa pada sekuens dari New South Wales yang juga mengalami peningkatan kasus baru-baru ini.


<!-- ############ SLIDE BREAK ############# -->
# [Kasus baru terdeteksi di Selandia Baru pekan ini](https://nextstrain.org/ncov/oceania/2020-08-11?c=gt-nuc_10097,23731&d=tree)

Selandia Baru telah melaporkan lebih dari 100 hari tanpa penularan komunitas sebelum mendeteksi kasus pekan ini.
Klaster kini telah menyebar ke sekitar 30 kasus yang diketahui (saat publikasi), terutama berpusat di kota terbesar, Auckland.

Sumbernya belum diketahui, namun para ilmuwan telah telah mendapatkan sekuens isolat dan melaporkan bahwa virus ini termasuk ke dalam garis keturunan pangolin B1.1.1; sehingga sementara genomnya belum diumumkan mereka di sini masuk dalam wilayah berwarna biru.
Garis keturunan ini berasal dari Eropa, namun kemudian terpantau di wilayah-wilayah lain di seluruh dunia.


<!-- ############ SLIDE BREAK ############# -->
# [Situasi terdahulu di Eropa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 menyebar cepat di Eropa, sepertinya terutama melalui penularan langsung dari Asia.

Pada akhir Pebruari, meskipun hanya terdapat [beberapa ratus kasus](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea) yang resmi dilaporkan di Eropa, si virus telah menyebar setidaknya ke 15 negara Eropa.

Mengingat bahwa penyampelan hanya sedikit dilakukan pada masa awal pandemik, SARS-CoV-2 dipastikan telah beredar meluas di Eropa, termasuk negara-negara yang kami tidak memiliki sampelnya.


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
# [Kredit ilmiah](https://nextstrain.org/ncov/global/2020-08-11?d=tree&c=author)

Kami menyampaikan penghargaan karya luar biasa dan menguras waktu yang telah dilakukan oleh para ilmuwan yang menggeluti wabah ini.
Hanya melalui berbagi cepat data genomik dan metadata analisis seperti ini dapat dilakukan.

**Kami mendorong anda untuk mengklik 'Explore the Data Yourself' dan gulir ke bawah untuk melihat daftar lengkap penulis; penulis setiap sekuens dapat dilihat dengan memilih sekuensnya pada pohon.**

Kami juga menyampaikan penghargaan kepada GISAID yang telah menyediakan platform yang memungkinkan data-data ini diunggah dan dibagikan.
