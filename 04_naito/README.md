AJACS越後：塩基配列解析のためのデータベース・ウェブツールとCRISPRガイドRNA設計
---------------

ライフサイエンス統合データベースセンター（DBCLS）  
内藤 雄樹（[自己紹介](http://researchmap.jp/meso_cacase/)）  
2018年6月27日 統合データベース講習会 AJACS越後  
新潟大学理学部マルチメディア教室

  - [スライドPDF](AJACS69_04_naito.pdf)

講習で紹介するデータベースやウェブツールへのリンクです。

#### NCBI ####

![スクリーンショット](http://data.dbcls.jp/~meso/img/ncbi_600.png
"スクリーンショット")

  - NCBI - http://www.ncbi.nlm.nih.gov/

#### NCBI BLAST ####

![スクリーンショット](http://data.dbcls.jp/~meso/img/ncbiblast_600.png
"スクリーンショット")

  - NCBI BLAST - http://www.ncbi.nlm.nih.gov/BLAST

#### UCSC BLAT ####

![スクリーンショット](http://data.dbcls.jp/~meso/img/BLAT.png
"スクリーンショット")

  - UCSC BLAT - https://genome.ucsc.edu/cgi-bin/hgBlat
  - 配列を探してみよう - tgaatgaagacgatcgactcaaattcacagctccacaggatggaattcttcttaacaaagctcgacaattcgga （線虫）
  - 統合TVによる解説動画
    - [高速アラインメントツールBLATをプライマー設計支援ツールとして使い倒す2009](http://togotv.dbcls.jp/ja/20090619.html)

#### UCSCゲノムブラウザ ####

![スクリーンショット](http://data.dbcls.jp/~meso/img/867440539.png
"スクリーンショット")

  - UCSCゲノムブラウザ – https://genome.ucsc.edu/cgi-bin/hgTracks
  - 統合TVによる解説動画
    - [UCSC Genome Browserの使い方〜基本編](http://togotv.dbcls.jp/ja/20091113.html)
    - [UCSC Genome Browserの使い方〜表示編](http://togotv.dbcls.jp/ja/20091126.html)
    - [UCSC Genome Browser の使い方〜アノテーショントラック編〜](http://togotv.dbcls.jp/ja/20100722.html)
    - [UCSC Genome Browserの使い方〜wig形式のファイルをトラックとして追加する〜](http://togotv.dbcls.jp/ja/20120116.html)
    - [UCSC Genome Browserの使い方〜表示+ENCODE編〜 2012](http://togotv.dbcls.jp/ja/20120528.html)
    - [UCSC genome browserの使い方～配列取得編～2013](http://togotv.dbcls.jp/ja/20131113.html)


#### 統合遺伝子検索GGRNA ####

![スクリーンショット](http://data.dbcls.jp/~meso/img/GGRNA.v2.jpg
"スクリーンショット")

  - 統合遺伝子検索GGRNA – http://GGRNA.dbcls.jp/
  - 統合TVによる解説動画
    - [GGRNAで遺伝子をGoogleのように検索する](http://togotv.dbcls.jp/ja/20120124.html)
  - ヒトのnanogを検索 – http://GGRNA.dbcls.jp/hs/nanog
  - Accession番号から検索 –  http://GGRNA.dbcls.jp/NM_003380
  - 塩基配列から検索
    - 14bp – http://GGRNA.dbcls.jp/hs/caagaagagattgc
    - 11bp – http://GGRNA.dbcls.jp/hs/caagaagagat
    - 8bp – http://GGRNA.dbcls.jp/hs/caagaaga
  - アミノ酸配列から検索 – http://GGRNA.dbcls.jp/SEHPL+MTCQSC
  - PCRプライマー検索 – http://GGRNA.dbcls.jp/hs/seq%3aagctcattactttatcagtgca+comp%3atgacgtattcactcttctggtt
  - マイクロアレイのプローブ検索 – http://GGRNA.dbcls.jp/1552311_a_at

#### 高速配列検索GGGenome ####

![スクリーンショット](http://data.dbcls.jp/~meso/img/GGGenome_screen2.png
"スクリーンショット")

- 高速配列検索GGGenome – http://GGGenome.dbcls.jp/
  - 統合TVによる解説動画
    - [高速配列検索 GGGenome《ゲゲゲノム》の使い方](http://togotv.dbcls.jp/ja/20131025.html)
    - [GGGenome《ゲゲゲノム》で転写因子結合サイトを検索してゲノムブラウザに表示する](http://togotv.dbcls.jp/ja/20150721.html)
  - ミスマッチやギャップを含む検索 – http://GGGenome.dbcls.jp/hg19/2/TTCACTGACAACATTGAGTA
  - コマンドラインから塩基配列検索
```
% curl -s 'http://GGGenome.dbcls.jp/hg38/TTCATTGACAACATT.bed' ← コマンドラインからゲゲゲノム検索
track name=GGGenome description="GGGenome matches"
chr1	82996792	82996807	.	0	+
chr2	160366603	160366618	.	0	+
chr3	15248282	15248297	.	0	+
chr3	84570693	84570708	.	0	+
chr4	16133027	16133042	.	0	+
chr4	62165421	62165436	.	0	+
chr4	148912065	148912080	.	0	+
chr4	165800997	165801012	.	0	+
chr6	61998310	61998325	.	0	+
chr7	3524040	3524055	.	0	+
chr8	31498628	31498643	.	0	+
chr11	24472483	24472498	.	0	+
chr13	84191411	84191426	.	0	+
chr18	29571723	29571738	.	0	+
chr19	41061360	41061375	.	0	+
chr2	196213135	196213150	.	0	-
chr3	57200490	57200505	.	0	-
chr3	97360477	97360492	.	0	-
chr5	9759390	9759405	.	0	-
chr7	34118948	34118963	.	0	-
chr7	78722087	78722102	.	0	-
chr12	79107513	79107528	.	0	-
chr19	40892286	40892301	.	0	-
% curl -s 'http://GGGenome.dbcls.jp/hg38/TTCATTGACAACATT.bed'| wc ← 行数をカウント
      24     142     728
% curl -s 'http://GGGenome.dbcls.jp/hg38/TTCATTGACAACATT.bed'| grep chr8 ← これを含む行を絞り込み
chr8	31498628	31498643	.	0	+
```
  - 表計算ソフトで塩基配列検索
    - [Googleスプレッドシート](https://docs.google.com/spreadsheet/ccc?key=0AqoKv30zqpDbdHJpSFI1SzJOZmxjVkYzUXByMFhrWWc&usp=sharing#gid=0) を参照
  - 検索結果をゲノムブラウザ上に表示
    1. UCSCゲノムブラウザ (http://genome.ucsc.edu/cgi-bin/hgTracks)
    2. 「add custom tracks」ボタン
    3. 「http://GGGenome.dbcls.jp/hg19/(検索したい配列).bed」と入力

#### CRISPR設計ウェブサーバCRISPRdirect ####

![スクリーンショット](http://data.dbcls.jp/~meso/img/CRISPRscreen.png
"スクリーンショット")

  - CRISPRdirect - http://crispr.dbcls.jp/
  - 統合TVによる解説動画
    - [CRISPRdirectを使ってCRISPR/Cas法のガイドRNA配列を設計する](http://togotv.dbcls.jp/ja/20140412.html)

#### 参考：各生物種のゲノム ####

  - NCBI Genome - https://www.ncbi.nlm.nih.gov/genome/browse/
  - Ensembl Genomes - http://ensemblgenomes.org/
    - 昆虫はEnsembl Metazoa - http://metazoa.ensembl.org/
    - 植物はEnsembl Plants - http://plants.ensembl.org/

#### おまけ：研究に役立つウェブツール ####

  - siRNA設計ツールsiDirect - http://siDirect2.RNAi.jp/
  - 統合TVによる解説動画
    - [siDirectでsiRNAを設計する2011](http://togotv.dbcls.jp/ja/20110606.html)
    - [siDirectのオプションを使いこなす & shRNAを設計する](http://togotv.dbcls.jp/ja/20110712.html)

![スクリーンショット](http://data.dbcls.jp/~meso/img/siDirect_top.jpg
"スクリーンショット")

  - テキスト比較ツール difff《ﾃﾞｭﾌﾌ》(http://difff.jp/)
  - 統合TVによる解説動画
    - [difff《ﾃﾞｭﾌﾌ》を使って文章の変更箇所を調べる](http://togotv.dbcls.jp/ja/20130828.html)

![スクリーンショット](http://data.dbcls.jp/~meso/img/difff6.png
"スクリーンショット")

  - Wolfram Alpha (https://www.wolframalpha.com/)
  - 統合TVによる解説動画
    - [WolframAlphaを使い倒す](http://togotv.dbcls.jp/ja/20090626.html)
    - [Wolfram Alpha を高機能関数電卓として使う その1:基本操作編](http://togotv.dbcls.jp/ja/20140404.html)
    - [Wolfram Alpha を高機能関数電卓として使う その2:数式入力編](http://togotv.dbcls.jp/ja/20140604.html)
    - [Wolfram Alpha を高機能関数電卓として使う その3:微分・積分・方程式編](http://togotv.dbcls.jp/ja/20140717.html)

![スクリーンショット](http://data.dbcls.jp/~meso/img/Wolframalpha1.png
"スクリーンショット")

![スクリーンショット](http://data.dbcls.jp/~meso/img/Wolframalpha2.png
"スクリーンショット")

  - TogoDB (http://togodb.org/)
  - 統合TVによる解説動画
    - [TogoDBの使い方 自分のデータベースを作る](http://togotv.dbcls.jp/ja/20100807.html)

![スクリーンショット](http://data.dbcls.jp/~meso/img/TogoDB.png
"スクリーンショット")

  - 研究者の情報を調べるためのツール
    - 研究成果から
      - 日本の博士論文をさがす CiNii Dissertations - http://ci.nii.ac.jp/d/
      - 特許情報プラットフォーム J-PlatPat - https://www.j-platpat.inpit.go.jp/
    - 研究資金から
      - 科研費採択課題 KAKEN - https://kaken.nii.ac.jp/
      - 日本の研究.com - https://research-er.jp/
    - 本人が発信する情報から
      - researchmap - http://researchmap.jp/
      - Facebook - https://www.facebook.com/
      - Twitter - https://twitter.com/

  - 参考:『[今日から使える! データベース・ウェブツール 達人になるための実践ガイド100](https://www.yodosha.co.jp/jikkenigaku/book/9784758103435/)』実験医学増刊 2014年12月発行

![スクリーンショット](http://data.dbcls.jp/~meso/img/B2uOQ3eCIAAFX9A.png
"スクリーンショット")
