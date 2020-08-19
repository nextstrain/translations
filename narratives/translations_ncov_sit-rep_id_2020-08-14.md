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
### **\"Ketika negara-negara telah melonggarkan kesehatan masyarakat dan tindakan sosial, yang diterapkan untuk membatasi penularan virus beberapa negara ini mengamati klaster atau kebangkitan kasus. Risiko dan kerentanan semakin besar di wilayah yang rapuh, bersumber daya rendah, dan terpengaruh konflik.\"**
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
# [Keadaan terdahulu di Eropa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&dmax=2020-02-29&dmin=2020-01-03&f_country=Belgium,Denmark,Finland,France,Germany,Greece,Iceland,Italy,Netherlands,Norway,Spain,Sweden,Switzerland,United%20Kingdom,Austria&transmissions=hide)

SARS-CoV-2 menyebar cepat di Eropa, sepertinya terutama melalui penularan langsung dari Asia.

Pada akhir Pebruari, meskipun hanya terdapat [beberapa ratus kasus](https://www.ecdc.europa.eu/en/cases-2019-ncov-eueea) yang resmi dilaporkan di Eropa, si virus telah menyebar setidaknya ke 15 negara Eropa.

Mengingat bahwa penyampelan hanya sedikit dilakukan pada masa awal pandemik, SARS-CoV-2 dipastikan telah beredar meluas di Eropa, termasuk negara-negara yang kami tidak memiliki sampelnya.


<!-- ############ SLIDE BREAK ############# -->
# [Penguncian di Eropa](https://nextstrain.org/ncov/europe/2020-08-10?d=tree,map&f_region=Europe&p=grid&legendOpen&transmissions=hide&dmax=2020-04-28&dmin=2020-03-01&f_country=Finland,Iceland,Spain,Sweden,Switzerland)

Sepanjang Maret dan April banyak negara Eropa menutup perbatasannya, dan banyak yang menerapkan beragam tipe 'penguncian' yang membatasi pergerakan dan menutup sekolah dan usaha. Kita berharap pembatasan ini menurunkan penularan antarnegara, sehingga kita akan melihat sekuens dari suatu negara akan seklaster dengan sekuens sebelumnya dari negara tersebut.

Namun, SARS-CoV-2 telah sangat bercampur di seantero Eropa sehingga varian yang berbeda dari si virus telah beredar melintasi banyak negara. Kebanyakan negara memiliki varian berbeda beredar sebelum penguncian yang berhubungan dengan virus yang beredar di negara lain. Ini artinya gambar filogenetik tetap tercampur bahkan setelah perbatasan ditutup (ditunjukkan dengan berbagai warna yang berdekatan satu sama lain dalam pohon).

Namun demikian, kita dapat melihat beberapa tanda penularan lokal seperti yang kita duga. Di sini, Finlandia dan Swedia memiliki klaster penularan yang sangat berbeda berwarna hijau dan jingga (sekitar 1/3 dari atas), sementara Spanyol (biru tua) menunjukkan penularan lokal berbeda di bawah dan atas pohon. Islandia (ungu) dan Switzerland (biru muda) juga menunjukkan klaster penularan lokal.

_Petunjuk: Anda dapat memperbesar Keterangan dengan mengklik 'Country' pada kiri atas pohon!_


<!-- ############ SLIDE BREAK ############# -->
# [Sekuens baru Eropa menyorot penularan lokal dan memperkaya pemahaman tentang penyebaran SARS-CoV-2 terdahulu](https://nextstrain.org/ncov/europe/2020-08-10?d=tree&f_recency=3-7%20days%20ago,New,1-2%20days%20ago&f_region=Europe&p=full&legendOpen)

Memeriksa hanya sampel yang diunggah sepekan terakhir menyorot dua hal penting.

Pertama, kita dapat malihat kecenderungan pengelompokan ujung ke klaster kecil. Ini menandakan bahwa penularan dalam negeri terus mendominasi - sepertinya hasil dari beragam peraturan yang diterapkan di Eropa. Si virus terus berkembang secara genetik saat penguncian, namun lebih cenderung terbatas di satu negara, artinya kita dapat lebih membedakan 'varian' lokal dari yang di negara lain.

Beberapa sampel tidak mengikuti pola ini. Melayangkan di atas suatu negara pada keterangan gambar menyorot ujung pada pohon dari negara itu dan akan membantu mengenali sampel semacam itu. Sebagai contoh, di tengah pohon, kita dapat melihat beberapa sampel Swedia (hijau) bersarang di dalam klad Rusia yang lebih besar (merah).
Mengingat besarnya sub-penyampelan, kita harus tetap berhati-hati untuk tidak membuat penafsiran berlebihan terhadap dugaan penularan antarnegara dari pandangan ini.

Kedua, kita dapat melihat bahwa ujungnya memiliki perbedaan besar pada ruang horizontal -- bahwa sampel yang dikirimkan pada pekan terakhir mewakili rentang waktu pengumpulan sampel yang melebar hingga awal Maret.
Alasan untuk merunut sekuens genom "lama" beragam, namun sampel-sampel ini membantu untuk mengisi pemahaman kita tentang evolusi virus dan pergerakan geografis.


<!-- ############ SLIDE BREAK ############# -->
# [Keadaan terdahulu di Amerika Selatan](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmax=2020-04-15)

Sekuens SARS-CoV-2 Amerika Selatan pertama yang berasal dari akhir Pebruari dan awal Maret terpencar di dalam pohon, mengesankan banyak introduksi. Saat perjalanan internasional menurun pada Maret, kita dapat melihat bukti penularan lokal yang tertahan di beberapa negara.

Banyak dari sekuens Brazil (hijau muda) merupakan bagian dari dua klaster besar (dekat puncak pohon), dengan beberapa bukti bahwa varian ini juga bergerak di seantero benua ke Chili, Uruguay, dan Argentina.

Kita juga dapat klaster penularan yang berbeda meliputi Kolombia (jingga), Chili (pirus), Uruguay (biru muda), dan Argentina (biru tua) terpencar di seluruh pohon.


<!-- ############ SLIDE BREAK ############# -->
# [Keadaan lebih baru di Amerika Selatan](https://nextstrain.org/ncov/south-america/2020-08-10?d=tree&f_region=South%20America&p=full&legendOpen&dmin=2020-05-01)

Sayangnya, sementara SARS-CoV-2 terus menyebar luas di Amerika Selatan, pemeriksaan sekuens belum terkejar. Meski kasus tetap tinggi hampir di seantero benua, hanya 68 sampel dari 5 negara (Brazil, Ekuador, Uruguay, Argentina, & Chili) telah dibagikan sejak Mei.

Meski inferensi kita terbatas oleh penyampelan yang jarang, dalam banyak kasus sampel-sampel yang lebih baru ini bersarang dalam keragaman terdahulu yang tersampel di negara yang sama, atau negara Amerika Selatan lainnya. Ini menyarankan varian-varian yang beredar kini merupakan turunan dari yang diintroduksi di awal pandemik.


<!-- ############ SLIDE BREAK ############# -->
# [SARS-CoV-2 di Afrika](https://nextstrain.org/ncov/africa/2020-08-11?d=tree,map&f_region=Africa&legendOpen&transmissions=hide&p=grid)

Sebagaimana Amerika Selatan, Afrika mengalami beberapa introduksi SARS-CoV-2 ke benua tersebut, kebanyakan sepertinya dari Eropa. Ini ditunjukkan oleh terpencarnya sampel Afrika dalam pohon - bahkan sampel dari negara yang sama mencakup varian yang beragam.

Kita kini memiliki sekuens dari negara-negara Afrika sepanjang epidemik, meski usaha pengumpulan sekuens tampak menurun belakangan ini.
Afrika Selatan menyumbang proporsi yang besar dalam pengumpulan sekuens.


<!-- ############ SLIDE BREAK ############# -->
# [Pengklasteran di Afrika](https://nextstrain.org/ncov/africa/2020-08-11?d=tree&f_region=Africa&legendOpen&p=full&f_country=Democratic%20Republic%20of%20the%20Congo,Senegal,South%20Africa)

Di Kongo, Senegal, dan Afrika Selatan, kita dapat melihat dengan jelas adanya penularan lokal, ditunjukkan sebagai klaster sekuens dalam pohon.
Dari Senegal dan Afrika Selatan, kita juga memiliki sampel yang didapatkan baru-baru ini.
Sampel-sampel ini umumnya masuk ke dalam keragaman terdahulu di negaranya, sebagaimana kita duga dari kelanjutan penularan lokal.

Namun, kita harus berhati-hati dalam menyimpulkan karena keterbatasan penyampelan yang dapat menimbulkan bias, sampel belakangan dari Afrika yang kita miliki tidak menunjukkan berlanjutnya importasi varian dari luar.
Temuan ini cenderung mencerminkan berlanjutnya pembatasan pergerakan secara global.


<!-- ############ SLIDE BREAK ############# -->
# [Epidemik AS adalah campuran dari penularan lokal dan dalam negeri](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&p=full)

Di sini kami menunjukkan genom dari epidemik AS sejak 15 April hingga kini. Pada pertengahan April, dilakukan penguncian di seluruh negara bagian AS. [Masing-masing negara bagian kemudian menerapkan berbagai kebijakan pembukaan kembali](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html).

Pada pohon ini, sebagaimana pohon di wilayah lain, kita melihat contoh penularan lokal virus sebagaimana ditunjukkan oleh pengklasteran ujung sewarna sepanjang waktu. Jika diklik, "Explore the Data Yourself", dan menapis lokasi ke Yakima County, dapat terlihat contoh yang jelas introduksi dan pertumbuhan virus yang berkerabat secara genetik ke wilayah Negara Bagian Washington ini. (Anda juga dapat [klik di sini](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map&dmin=2020-04-15&f_country=USA&f_location=Yakima%20County&p=grid), namun akan meninggalkan naratif.)

Akan tetapi, pada pohon, kita juga melihat penularan dalam negeri seantero AS seperti yang ditunjukkan oleh campuran warna pada ujung pohon. Pada peta, penularan dalam negeri terlihat seperti garis penularan yang memanjang antarnegara bagian. Observasi ini konsisten dengan beberapa pembatasan bepergian domestik dan kebijakan pembukaan kembali negara bagian.


<!-- ############ SLIDE BREAK ############# -->
# [Sekuens Amerika Tengah menunjukkan penularan terklaster geografis](https://nextstrain.org/ncov/north-america/2020-08-11?d=tree,map,entropy&f_country=Belize,Costa%20Rica,Guatemala,Jamaica,Mexico,Panama&p=grid&transmissions=hide)

Sekuens dari Amerika Tengah masih sangat terbatas, terutama dua bulan terakhir, sehingga membatasi penafsiran yang dapat ditarik mengenai epidemik ini. Dari genom yang telah dipublikasi, kita melihat pengklasteran geografis genom SARS-CoV-2.

Melalui dasar pohon di klad 19B, kita melihat klaster penularan di Panama mulai pertengahan Pebruari. Beberapa sekuens berikutnya dari bulan Juni dan Juli bersarang di klaster ini, menandakan kelanjutan penularan lokal genotipe virus ini di negeri tersebut.

Di Meksiko, kita juga melihat pengklasteran geografis penularan hingga bulan Mei. Tanpa sekuens baru, kita tidak dapat membaca epidemik pada bulan-bulan berikutnya di negeri ini.

Di tengah pohon, terdapat klaster kasus di Baja California (biru muda). Kasus ini sepertinya diimpor dari Kalifornia, AS (cabang hijau pada pohon) pada bulan Maret. Penafsiran importasi ini selaras dengan lalu-lintas perjalanan antara kedua wilayah bertetangga ini meskipun kita harus berhati-hati dalam penafsiran ini karena sekuens yang kurang memadai.


<!-- ############ SLIDE BREAK ############# -->
# [Rangkuman penutup](https://nextstrain.org/ncov/global/2020-08-11?d=map)

Saat pandemi mencapai delapan bulan sirkulasi global, kini kita dapat melihat perubahan yang berbeda sepanjang waktu dalam gambar yang diwarnai dengan genetika virus, sebagian besar ditentukan oleh perubahan perilaku.

Penularan awal bertubi ke AS, Oseania, Eropa, dan seantero Asia, awalnya bercampur, pola perjalanan global menyebarkan virus dengan sangat efektif. Segera setelahnya, beragam introduksi ke Amerika Selatan dan Afrika, kebanyakan dari Eropa dan Amerika Utawa, telah menyemai epidemi lokal.

Ketika skala penyebaran virus dan keparahan COVID-19 menjadi jelas, perjalanan terhenti di sebagian besar dunia. Setelah ini, kita dapat melihat pergeseran berbeda ke penularan lokal saat 'penguncian' dan pembatasan bepergian. Satu hasil dari pembatasan ini adalah kini kita dapat lebih mengenali sumber virus, ketika epidemi lokal dalam beberapa kasus telah berubah secara genetik. Di AS, ketiadaan pembatasan perjalanan domestik 'berhasil membantu' mempertahankan percampuran epidemi antarnegara bagian.

Perbatasan kini telah dibuka kembali dan perjalanan telah diperbolehkan, meski belum menyamai kadar sebelum pandemi. Hal ini ditambah jeda waktu antara penyampelan dan ketersediaan sekuens secara publik, kita hanya melihat sedikit tanda percampuran antarnegara. Secara umum, sampel-sampel baru cenderung terus berklaster dengan sekuens terdahulu dari negeri yang sama, menunjukkan berlanjutnya penularan varian yang sudah ada sebelumnya. 

Sayangnya, banyak negara menemukan peningkatan kasus dalam beberapa pekan terakhir, mengikuti pengendoran pembatasan. Ketika Hemisfer Utara akan menghadapi musim gugur dan cuaca yang mendingin, pembukaan lebih lanjut, dan pembukaan sekolah, kita harus tetap waspada terhadap peningkatan angka kasus. Saat musim dingin berlanjut di Hemisfer Selatan, kita melihat tanda mengkhawatirkan karena kemungkinan peningkatan penularan - keberhasilan Australia di awal kini teredam oleh wabah baru-baru ini. Melanjutkian peningkatan jumlah pemeriksaan, pelacakan, dan isolasi, menjaga kebersihan tangan, dan pemakaian masker secara benar dapat membantu masyarakat kita seterbuka mungkin sementara memerangi SARS-CoV-2.

<!-- ############ SLIDE BREAK ############# -->
# [Kredit ilmiah](https://nextstrain.org/ncov/global/2020-08-11?d=tree&c=author)

Kami menyampaikan penghargaan karya luar biasa dan menguras waktu yang telah dilakukan oleh para ilmuwan yang menggeluti wabah ini.
Hanya melalui berbagi cepat data genomik dan metadata analisis seperti ini dapat dilakukan.

**Kami mendorong anda untuk mengklik 'Explore the Data Yourself' dan gulir ke bawah untuk melihat daftar lengkap penulis; penulis setiap sekuens dapat dilihat dengan memilih sekuensnya pada pohon.**

Kami juga menyampaikan penghargaan kepada GISAID yang telah menyediakan platform yang memungkinkan data-data ini diunggah dan dibagikan.
