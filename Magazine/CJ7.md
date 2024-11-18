# 楽しいプログラミング 《最終回》

&emsp;私事で恐縮ですが、まだ当分の間、新しい事を始められなくなってしまいました。となると、「オブジェクト指向入門」を読むのも先送りになります。ネタがありません。そういうわけで、今回のみ＜昔ばなし＞でページを埋めまして、本連載はしばらくお休みさせて頂きます。誠にお恥ずかしい限りです。

## ■ マイコンとの出会い
&emsp;それは、大学受験を目前にして、半ば受験ノイローゼに陥っている頃でした。親父の部屋で、ふと、二冊のマイコン入門書が目にとまりました。一冊は、BASICの入門書。表紙の「StarTrek」の画面、これが私のマイコンとの出会いです。TRS－80のグリーンモニタに浮かんだ凸凹のエンタープライズ号。それには、神秘的な、深くすいこまれるような何かを感じました。そして、初めて「プログラム」というものを見たのです。

	LET　A＝1
	LET　B＝2
	PRINT　A＋B

そんなリストでしたか。
『AとBに値を代入すると、A＋Bを出力する』
「あっ、おもしろい！」と思いました。
それが全ての始まりでした。<br>　二冊目は、TK80の本でした。こちらは何やら難しかった。巻末に8080のコード表が載っていましたっけ。ほとんど理解不能でした。

&emsp;さて、無事合格し、入学祝いにマイコンを買ってもらう事になりました。何がいいのだろう？　MZ、BM、PC。やはりカラーの魅力でPC－8001かな。なにはともあれ大須のアメ横ビルへ。しかし、そこには大きな罠が待ち受けていたのでした。

## ■ H68TR／CTV
&emsp;エスカレータで2Fへ上がった左のお店。店員さんに「PCってどうなの」とか尋ねたのでしょう。答えは意外でした。<br>　「あれはよくない。Z80なんて、命令が汚い。6800の方が断然美しい。日立のH68TRには、そいつがのってる。今度出るカラーボードをつけると、128×96ドットでドット毎に8色出せる。PCは文字単位でしか色がつかん。」
&emsp;私はなるほどと思い、H68TRに決めました。

&emsp;ワンボードマイコン「TK80」をご存じの方は多いでしょう。しかし、日立のトレーニングモジュール「H68TR」は、それを上回る高性能のマイコンです。MPUは6800の1MHz。RAMは標準で1KB。3KBまで増設できます。8セグメントLED付きのコンソールパッドで、アルファベットの入出力が可能です。300ボーのカセットI／Oでプログラムのロード／セーブができます。モニタROMには、1ラインアセンブラまでのっていました。

&emsp;私は、食い入るようにマニュアルを読みました。あのマニュアルはよく出来ていた。そして初めて作ったプログラムが、「モグラたたきゲーム」です。LEDにぴょこぴょこと頭をもたげるモグラを、対応するキーをすばやく押して叩くわけです。あんまり嬉しかったので、御袋を呼んでやらせてみました。訳わかんなさそうでしたが、でも喜んでくれました。<br>　この時わかったのです。自分の作ったもので人が楽しんでくれるって、なんて素晴らしい事なんだろう、と。

&emsp;TRでは、あと「ヒット＆ブロー」（マスターマインドとも言う）とか作りましたか。「SpaceWars」という、だんだん接近してくる敵船の攻撃を左右に避けながら、タイミングを図って攻撃するゲームを作っている途中で、待望のカラーボードが来ました。これは「CTV1」というボードです。しかし、RFモジュレータが全く使い物にならなかったため、結局グリーンモニタを買いました。こんな事なら、カラーにこだわるんじゃなかった。<br>　もちろん、目指すは「インベーダーゲーム」。当時は、だれもが作ろうとしたゲームでしょう。完成した128×96ドットのインベーダーは、キャラクタを使ったどんなインベーダ－より見栄えがしました。ただ、ゲーム自体はあまりおもしろくなかった。<br>　後でわかった事ですが、インベーダーって、最後の一匹になると異様に速くなるんですね。知らなかったなぁ。そう、私はゲーセンに行った事がなかったのです。

&emsp;H68TRにはその後、フルキーボードとBASIC－ROMが発売されましたが、それらは拡張される事はありませんでした。なぜなら、「ベーシックマスター・レベル3」が発売されたからです。

## ■ ベーシックマスター・レベル3
&emsp;それはまさに夢のマシンでした。「究極の8bitMPU」と呼ばれる6809を搭載。640×200ドットで、「ひらがな」まで表示できます。アスキーの紹介記事にのった「ひらがな」の画面写真を、穴のあくほど見つめました。<br>　しかし、なかなか発売されません。仕方が無いので専用カラーモニターを先に購入し、H68CTVに繋げて、カラーのインベーダーで遊んでおりました。そして、暇さえあれば6809の命令コード表を眺めてました。あれはまさしく垂涎もの。今から思うと、本当に胸のときめいたマシンは、これが最初で最後でした。<br>　それにしても、モニターと本体合わせて40数万円、いったいどこからお金が出たのでしょう。貯金を叩いたのか、親父に助けてもらったのか、とんと記憶にありません。

&emsp;レベル3を買って、初めてフルキーボードとBASICに触れました。<br>　今となっては口にするのもはばかられるBASICですが、昔はこれしかなかったのです。1行は長い方がいいとか、良く使う変数は最初に定義するとか、ひたすら高速化のテクを追求しました。読みやすさなんて、思いもよりません。<br>　そして毎度のごとくゲーム作り。「スタートレック」、「平安京エイリアン」、「野球ゲーム」、等々。<br>　「スタートレック」は、自爆シーンをマシン語で書いて雰囲気を盛り上げました。<br>　「平安京エイリアン」は、高速化のため随所にマシン語ルーチンを使ったため、うじゃうじゃ増えた時は見ものでした。<br>　「野球ゲーム」は、弟と二人で燃えました。守備側がテンキー、攻撃側がフルキーで操作しますから、回が終わるごとに席を入れ代わるわけです。間に衝立をおいて、球種が見えないようになんかして。ほんと、白熱しました。対戦型データ野球ゲームの元祖かも知れないな。<br>　そういえば、野球ゲームを作ってる時、一度カセットのロードとセーブを間違えて、消してしまった事がありました。あれはショックだった･･･。だいぶ前のバージョンが残っていたので、そこから作り直しました。それ以来、ソースは大切に保管しています。プログラマにとっては、命より大事なソースです。

&emsp;基本的にゲームは、メインはBASIC、必要な部分のみアセンブラで作りました。純正のアセンブラはとんでもなく使いづらいので、そのうちモニタ、エディタ、アセンブラ、逆アセンブラを一体化した開発ツールを自作しました。これは結構辛かった。その頃から頭使うプログラムは苦手でした。<br>　今考えるとかなり変態的なツールで、しかし、実用的ではありました。<br>　エディタはEdlinライクなポインタ型エディタですが、ラインエディットできます。1行入力する度に、マシン語とラベルの交じった中間言語に変換され、表示の際は、命令やレジスタの種類によってカラフルに色分けされました。Aレジスタは赤、Bレジスタは黄色、ブランチ命令は緑とか。そしてもちろん、総ての処理がオンメモリです。<br>　結局このツールは、FM、S1へと移植され、6809時代の私のメインツールとなるのでした。「統合環境」という意味では、なかなかのものでしたよ。

&emsp;アセンブラの開発システムが整い、それで作った最初のマシン語ゲームが「ギャラクシアン」です。これを作っている時の充実感といったら･･･
&emsp;（絶対に負けないものを作るんだ！）
その堅い決意が、すべてを突き動かしていました。<br>　（明日はこのルーチンを作ろう）
そう思うと、わくわくして眠る間も惜しかった。
完成間近になって、自転車で走っている時、ふと、
&emsp;（これが完成するまでは死ねない･･･）
そんなふうにまで思いました。<br>　とりあえず動くまでに2週間。デバッグとサウンドに2週間。ついに「ギャラクシアン」は完成しました。640×200のドット単位で動き、PSG音源にも対応していますす。BGMは「633爆撃隊」。この戦争映画をもう一度見たい･･･。真に手に汗握る空中戦でした。そういうゲームを作りたかったのです。

&emsp;絶対の自信がありました。そして、プログラムコンテストにも応募しました。

&emsp;ある日のことです。のんびりとマイコン雑誌を読んでいた私は、突如、背筋が凍りつきました。そこには、「ギャラクシーフライ」というゲームが載っていたのです。

## ■ 人との出会い
&emsp;このゲームは、名前こそ違え、紛れもなく「ギャラクシアン」でした。しかも、編隊に戻るとき回転するとあります。私のは回転などしません。しかし、動きはどうやらキャラクタ単位のようです。その点は私の勝ち。でも先を越された事には変わりありません。ショックでした。まさか同じものを作っていた奴がいたとは･･･。<br>　その後、プログラムコンテストの結果が発表されました。私は特選をうけました。「ギャラクシーフライ」は入選でした。そして、東京有楽町のフードセンターで、授賞式が開かれる事になりました。<br>　「ギャラクシーフライ」の作者は、なんと高校の物理の先生でした。現在もPDSの開発や雑誌の投稿で活躍されておられるこの先生は、今の私の、人との繋がりのルートに位置されている方です。もしこの先生が「ギャラクシーフライ」を作らなかったら、今の私はどんなだったでしょう。人の運命とは不思議なものです。<br>　この授賞式で、他にも数名の方と知り合いました。本体だけで和音を演奏させるサウンドドライバーを作った彼。3Dカーレースを作った彼。アメリカ人のための和英辞書を作っておられた、日本語のじょうずなM.スパンさん。皆さん、今どうしておられるのでしょう。

&emsp;その後、幾人かのプログラマと会いましたが、内心は、

&emsp;　（おれよりプログラムの書ける奴はいないな）

などと思い上がっていました。それが完璧に打ちのめされるのは、「スキッパー」というゼビウスタイプのスクロールゲームを見た時です。<br>　これはすごいものでした。スクロールする背景画面とキャラクタ画面を1フレーム毎に切り替えて、むりやり合成します。当然画面はちらつきますが、もともとレベル3のCRTは残光性ですから、見られない事はありません。敵キャラと弾幕が乱舞するこのゲームは、まさしくハードの限界を越えたゲームでした。

&emsp;世の中には本当にとんでもない奴がたくさんいます。私など、人並み以上の力を持ってはいるが、しかし常人にすぎない。そう悟るのは意外とたやすい事でした。才能やセンスがすべての分野では、これはまさしく挫折です。しかし、プログラミングは、テクニックの世界です。積み重ねたノウハウが物を言います。そして、ネタはそれこそ無限にあります。このゲームなら、このツールでは、誰にも負けない。それで十分、私達は誇りを保てるのです。

## ■ そして現在へ
&emsp;結局「ギャラクシアン」が、自作の最後のゲームでした。FM7、S1では、先の開発ツールを移植したのみで、何も作りませんでした。パソコンに対するやみくもの情熱は、この頃すでになくなっていたのかもしれません。むろん、プログラミングそのものは、あいも変わらず楽しいものです。ただ、作りたいネタが浮かばなかったのです。

&emsp;このように大学時代は、まさにパソコンのみで過ぎ去りました。学生時代の友人がいないのは寂しいことですが、結局その時培ったものが、多くの人と知り合うきっかけを生んだのです。<br>　人の輪が広がり、趣味が広がった現在では、作りたいネタは山ほどあります。しかしその分、時間と情熱と集中力が失われてしまいました。すっかり軟弱になってしまった自分を突き動かすもの、それを自ら探し当てねばならないところに、私は来ています。<br>　アマチュアだなぁ･･･。

（雑誌「**PC POWER** 1993年1月号」掲載）
