# WEEKLY人工無脳【第4号】（2018.4.23~4.29）

![eye_catch](./../figs/weekly_jinkoumunou.png)


## 金属ガラス合成にも機械学習

https://gigazine.net/news/20180423-ml-accelerate-matellic-glass/

金属ガラス合成がどれほど難しいものかはわからないが、内容的には、無数の組み合わせが存在する中から現実的な材料の組み合わせを見つけさせる、というものらしい。

おそらく創薬分野の課題と似たような「膨大な組み合わせの中から特定の結合パターンを見つける」みたいな問題だと思うが、パターン認識こそ機械学習の得意分野。このような問題はいろんな業界に転がっているはずなのでこの数年はそういった簡単な問題が解かれる事例がまだまだでてくるはず。

## NECが機械学習の特徴量抽出設計自動化技術で子会社設立。しかし新CEOのTシャツが気になって内容が入ってこない。

https://japan.zdnet.com/article/35118412/

「特徴量の自動抽出」という半信半疑な話だけれど、最近人気と噂の[DataRobot](https://www.datarobot.com/jp/)が提供しているものと同じ方向性のものだと思われれる。

ただ、NECはこれまでもこの技術に関するリリースを継続的に出している。

・[NEC、ビッグデータの高精度な予測分析に必要な期間を従来比1/3に短縮する「特徴量自動設計技術」を開発](https://jpn.nec.com/press/201508/20150818_02.html)（2015年8月18日）

・[NEC、業務システムにおける大規模データ予測を自動化する｢予測分析自動化技術｣を開発](https://jpn.nec.com/press/201612/20161215_06.html)（2016年12月15日）

NECは「[異種混合学習技術](https://jpn.nec.com/ai/analyze/pattern.html)」という手法によって、データサイエンティストが人手で行っていた高度な作業(データの関係性発見、特徴量の抽出・設計から分析モデル作成まで)を高精度に自動化する研究開発を2012年からずっと行っていたらしい。

NECの今回の技術やDataRobotのサービスが、この自動化分野の真打ちとなるかはわからないが、「特徴量の自動抽出」はいつかきっと達成される課題なので今後も注目したい。

ちなみにこの方が変なTシャツ着てるのは今回だけじゃないということもお伝えしておきます。

http://business.nikkeibp.co.jp/atclbdt/15/258684/120900099/



## 8K映像技術はきっと機械学習の良いパートナーになる

http://tech.nikkeibp.co.jp/dm/atcl/feature/15/050200094/042400019/?ST=health&P=2

好評開催中の「[人体展](https://www.kahaku.go.jp/exhibitions/ueno/special/2018/jintai/)」でも8K動画の展示がされていて、「人間の目の解像度的にそんな必要？」って思ったけど、超精細な患部の状況を知りたい医療系画像や、最近医療分野でもバリバリ活躍している機械学習用の画像データとして貴重っぽい。2K画像と8K画像の比較が結構衝撃的なので是非リンク先記事を見て欲しい。

8Kによって「精細によく見える」ことの恩恵は、単純にズームしても画質が粗くならないということだけではなく、”厚そう・薄そう・硬そう・柔らかそう”といった”質感“までが画像から予想できるようになること。人間に予想できるということはもちろん機械的にも識別が可能になるというわけで、「カメラが良くなる」ことの恩恵は計り知れない。

こういった最先端の道具の完備・ネットワーク化を目指した「[次世代手術室SCOT（Smart Cyber Operating Theater: 通称スマート治療室）](http://tech.nikkeibp.co.jp/dm/atcl/feature/15/327441/062100087/?ST=health&P=1)」というものも開発が進んでいる。今後ここに医療用AIが組み込まれることは間違いないので期待しかない。

詳細な学習用画像が深層学習アルゴリズムを進化させる話は[先週号](http://ysdyt.hatenablog.jp/entry/week3)の「コンクリートヒビを自動検知するシステム」にも書いたので興味があればぜひ見てください。

## 新型ゾゾスーツに「違う、そうじゃない」が殺到。しかし技術者たちはにわかに賞賛している模様

https://twitter.com/autani/status/989763786503409665

ゴーリキーとのフライデーがすっぱ抜かれたものの[ナイスコメント](https://www.fashionsnap.com/article/2018-04-26/zozo-maezawa/)で好感度をあげた前澤社長だが、新型ゾゾスーツは不評な模様。剛力にこのダサいスーツを着せられるのかと案の定[イジられている](http://kabumatome.doorblog.jp/archives/65906721.html)。

IT企業がハードウェアを無料でバラ撒いてでも生体情報を取得しようとする姿勢は、データアナリスト達的にはかなり胸熱な展開だったと思う。これこそ真のデータドリブン企業。かく言う自分も、ゾゾスーツ発表直後にソッコーで申し込んだ勢の一人。

今回のネタについていくつか記事を追ってみると、

センサー計測式のゾゾスーツを無料で配布します（かっこいい！） → 製造委託先ではもろもろで製造できず（[40億損失](https://www.wwdjapan.com/607378)） → 画像でマーカーを読み取る形式に変更して自社開発 → ７月までには予約者に届けるね

という流れらしい。そして当初の未来感がすごかったかっこいいスーツから、水玉ドットの新型スーツが出てきたのでみんながっかり…という。

どっちがコケてもいいように新旧スーツは裏で[同時に開発を進めていた](https://www.fashionsnap.com/article/2018-04-27/zozosuit-new/)らしく、ハードウェアを作ることの難しさを感じられる。ちなみに画像でマーカーを読み取る形式は[3億で買い取ったアイデア](https://www.nikkei.com/article/DGXMZO26992020W8A210C1000000/)らしい。

たしかにかっこよさが失われ多少がっかりはしたが、コスト面と必要機能を考えると、わざわざ伸縮センサーのような高価なハードを使わなくても、マーカー形式でも精度良く体型測定できそうである。こちらの動画の最後の方に複数人の測定画像がでてくるが、パッと見でもそれぞれの体型の違いがわかるのでやっぱり問題なさそう。

https://twitter.com/ksasao/status/989842844243279872/video/1

今後は自分のサイズにあった服をオーダーする流れがきっとくるので、ゾゾスーツの人気は間違いなく高まる。そうしたら安価に製造できる新型スーツが良いことは自明。
でもそんなことはみんなわかってるんだ…みんなは「ゾゾスーツ届いた！」といってインスタに写真撮るチャンスを多少なりとも失ったことにがっかりしてるだけだから気にしないでね前澤社長。ゴーリキーとお幸せに…

ちなみに、ダサいダサいと言われる新型スーツだが、ComputerVision勢と[スーツフェチズム勢](https://twitter.com/makotofalcon/status/990422948157640711)からじわじわと好評の声が上がりだしている。冗談抜きで、技術者のお遊びとしてこのスーツからとれるデータでわりとデカいムーブメントくるぞ。zooは決して失敗していない。

## 教師なし学習の波が機械翻訳まできている

http://deeplearning.hatenablog.com/entry/unsupervised_machine_translation

深層学習には膨大なデータが必要、ということは変わらないが、それが「教師あり」なのか「なし」なのかで更に労力は異なる。

労力がかからない教師なし学習で如何に教師あり学習の精度に追いつくか、というのが大きな流れの１つとしてあるが、こと「機械翻訳」のタスクにおいては当然翻訳の答えとなる教師データが必要と考えられていた。
それに対して、教師なし学習でもかなりの精度を出せるようになってきた論文についてくわしく解説してくれているありがたいブログ。（いつもお世話になっています！）ノイズ除去や”逆翻訳”というアイデアをうまく機能させるために「潜在表現空間を共有させる」という一見難しそうなアイデアをうまく説明してくれている。

「コレ考えた人、頭いいなー」と思える、膝を打つような体験に何度も出会えるのがこの進歩の早い分野の一番の魅力かもしれない。

## Qiitaのタイトルに並んでいるだけで笑ってしまうからやめて

https://qiita.com/j_catfish/items/0d36a21b4744aa3e4870

往年の「トリビアの泉」を見ているかのようなワクワクを感じながら読める。可視化一発芸として自分の中でランクインした。


## ドコモの位置情報とDLでタクシーの需要予想

https://cloudplatform-jp.googleblog.com/2018/04/ntt-docomo-ai-taxi-tensorflow.html

ドコモの携帯ネットワークをつかった人口統計情報（つまり位置情報でしょ？）やその他もろもろの変数の合計120次元のデータをstacked denoising autoencoderに突っ込んで、500m四方エリア別の30分後のタクシー需要を95%程度の精度で予測するモデルをtensorflowで作った話。

需要予想モデルはエリアによってDLと自己回帰モデルを切り替えて使うらしい。すべてDLだけでやろうとしないところは正しいやり方だと思うし、実際に社会現象の予想モデルはきっと１つのモデルだけでは説明できないのだと思う。stacked denoising autoencoderを採用した理由はインプットデータのノイズを削減するのが精度を上げるためのキーだったからとのこと。

何はともあれ、社会が便利になるための技術活用は大歓迎。タクシーはともかく、電車の通勤ラッシュもなんとかならんものか…

このプロジェクトはNTTドコモと東京無線と富士通によって行われたそうだが、NTTグループは[corevo](http://www.ntt.co.jp/corevo/)というAIブランドを独自に展開している。おそらく今回のタクシーの話はまた別なのだろうと思うが…