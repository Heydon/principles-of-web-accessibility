# ウェブアクセシビリティの原則（[Principles Of Web Accessibility](https://github.com/Heydon/principles-of-web-accessibility) 日本語訳）

_ウェブアクセシビリティへのアプローチに関するハイレベルな指針となる原則。_

* [完璧主義は敵](#完璧主義は敵)
* [はじめからアクセシブルに、さもなくば死を](#はじめからアクセシブルにさもなくば死を)
* [同等であることが最重要](#同等であることが最重要)
* [実装を考慮したデザイン](#実装を考慮したデザイン)
* [まずは構造から](#まずは構造から)
* [言葉を大切に](#言葉を大切に)
* [ツールをペルソナにしてはならない](#ツールをペルソナにしてはならない)
* [少ないことは、少ないだけ（でもそれでいい）](#少ないことは少ないだけでもそれでいい)
* [報酬を得よう](#報酬を得よう)
* [魚ではなく、釣り方を](#魚ではなく釣り方を)
* [見せかけのパフォーマンスに価値なし](#見せかけのパフォーマンスに価値なし)
* [悪は腐るに任せよう](#悪は腐るに任せよう)

## 完璧主義は敵

100%アクセシブルなモノは存在しないし、存在しえない。自分の提供するモノが完全にアクセシブルであると主張する人は、嘘つきであるか、アクセシビリティを理解していないか、あるいはその両方である。まあ両方だろう。可能なかぎりアクセシビリティを高めたのであれば、100％アクセシブルなモノでなくてもOKだ。与えられた制約の範囲内で、出来ることをやる。もし制約が理不尽であれば、まずそれを変える努力をすべきだ。アクセシビリティに取り組むにあたって、自分よりもふさわしい人が他にいるのではないか、と思うかもしれない。しかし、あなたには出来る。そこにいない（そもそも存在しない）アクセシビリティの救世主に仕事を任せてはならない。 

## はじめからアクセシブルに、さもなくば死を

アクセシビリティは、本質的に言うと、プラグインやアドオンのように後から追加できるものでも、ユーザーの同意を得て初めて機能するものでもない。インタフェースにアクセシビリティを有効にするオプションがある時点で、それはすでにアクセシブルとは言えない。低コントラストのスイッチが「高コントラスト」をオンにする仕組み？ゲームオーバーだ。はっきり言って、アクセシビリティオーバーレイソフトウェアは機能しないし、機能することはあり得ない。アクセシブルでない何かの上にアクセシビリティ関連のものを追加しても、本質的な問題は解決されない。そのようなサードパーティの介入者たちが提供する個々の機能は、重要ではない。後付けのアクセシビリティという考え方にはなんとしてでも抵抗すべきだ。アクセシビリティのないMinimum Viable Product（MVP、実用最小限の製品）は——最小限でさえも——実用的とは言えない 

## 同等であることが最重要

重要なのは、より望ましい体験や十分に良い体験を提供することではない。異なる人々の間で同等の体験を保証することこそが本質である。インターフェースが人によって障壁となったり、ならなかったりする状況は避けるべきだが、どうしても複雑なインターフェースや、本質的に難解なコンテンツがあることも事実だ。誰が何に興味を持ち、あるいは誰が何に対処できるか、あなたに選ぶ権利はない。画像がジョークとして機能するなら、代替テキストでオチを先に明かしたり、なぜ面白いのかを説明するのではなく、別の手段で同じジョークを伝える必要がある。そのジョークがある人にとって不快に感じられたり、理解されなかったりしても、それはアクセシビリティの問題ではなく、包括性の欠如に起因するものといえる。

## 実装を考慮したデザイン

形態は機能に従うべきであるとされている。しかし、ほとんどの組織では、まずデザイン（ビジュアライズ）を行い、次に開発が行われる。デザインフェーズでは、純粋にグラフィカルな表現の検討に終始するにとどまり、実装に関する多くの疑問には答えられないままとなる。その結果、開発者はユーザビリティよりもグラフィックの視覚的な再現を優先させるようになる。ドラッグアンドドロップのインターフェースは、キーボードで操作ができる必要がある。つまり、ボタンが備わっているべきことを意味する。これらのボタンは、当然「デザイン」に含まれなくてはならない。あなたはアクセシビリティの実践者として、早い段階でかつ概念的なレベルから貢献すべきである。なぜなら、形態が機能に従うべきものであると同様に、機能はアクセシブルでなければならないからだ。

## まずは構造から

不適切な構造のインターフェースが、形式上はWCAGを満たすことがある。適切な構造で、直感的でもあるインターフェースが、WCAGの複数の基準を満たさないこともある。おそらく、ほとんどの人にとって、よりアクセシブルなインターフェースは後者のほうである。自動アクセシビリティツールは、個々のエラーを検出することには非常に優れているが、それだけだ。これらは診断の役には立つかもしれないが、必要なのは全体的な視点である。人々に混乱や圧倒をもたらすものは何か? 人々がつまずくのはどこか？ 根本的な構造を見直さなければならないのに、個々の達成基準をひとつひとつ潰していくような無駄な時間を費やしてはならない。

## 言葉を大切に

ウェブアクセシビリティの多くの部分は、テキストラベルの提供に関するものである。ボタン、リンク、入力フィールドにはすべてラベルが必要である。ページタイトルや見出しも重要なラベルの一種である。ステータスメッセージは、状態をラベル付けするために必要不可欠なものである。ラベルを付けさえすれば、自動アクセシビリティテストツールを黙らせることはできるかもしれないが、真に重要なのはラベルの文言である。優れたライティングは自動化できない。AIはあなたの意図を予測できない。ライティングや編集のスキルを磨くか、または優れたライターや編集者をあなたのラベル検討のプロセスに参加させるべきである。

## ツールをペルソナにしてはならない

能力が多様であるのと同じく、障害もまた多様である。様々なスクリーンリーダーの利用者は、様々なニーズや好みを満たすために、様々な状況において、様々な理由で、様々な方法で、様々なスクリーンリーダーを使用している。そもそも、スクリーンリーダーを使っていない場合もある。スクリーンリーダー利用者や、そのふるまいを正確に表せるペルソナは存在しない。全スクリーンリーダー利用者を代表できる人は存在しない。だから、スクリーンリーダー利用者（あるいは実際には存在しない画一的なユーザー層）を前提にデザインしてはならない。スクリーンリーダーの機能を支え、活かすようにデザインしよう。人間は定量化できないし、すべきでもない。しかし、入力と出力は定量化できるし、実際にされている。

## 少ないことは、少ないだけ（でもそれでいい）

「少ないことは豊かなことだ（less is more）」という格言は正しくない。少ないことは単に少ないだけであり、それだけで良いことである。過剰なインターフェース開発は、他の誰かがやっているか、それができると証明するためだけに行われている。止めよう。多くのことを行えば行うほど、そしてアウトプットが複雑になればなるほど、失敗する可能性が高くなる。単にエラーや故障を引き起こすだけでなく、もっと重要なこととして、理解を妨げてしまう。多くの場合、ほとんどのコンポーネントは単にコンテンツであるべきだ。コンテンツをボタンの後ろに隠すべき状況はめったにない。見出し、段落、リストをアクセシブルであってもタブインターフェースに変えることは強化ではない。それは自慢する権利を伴った劣化だ。

## 報酬を得よう

アクセシビリティに対する情熱を搾取されないように。他の仕事と同様に、無償でやる人が増えるほど、その価値は低く見られてしまう。アクセシビリティの仕事は、オプションでも、趣味でも、優しさでもない。健全なインターフェースデザインの基盤である。給与を受け取り、働く中でアクセシビリティに取り組んでいるのであれば、それは正式に役割の一部として定義されるべきである。アクセシビリティの仕事も、他の仕事と同様に、正当に評価され、報酬が支払われなければならない。「アクセシビリティはみんなの仕事」となると、結局誰の仕事でもなくなってしまう。その美辞麗句には要注意。

## 魚ではなく、釣り方を

アクセシブルな製品やインターフェースの設計は、それを実現する組織やコミュニティの在り方を設計することから始まる。今アクセシブルな成果を提供することができたとして、それを明日誰がそれをするのか。明日は誰が、あるいは何が、それを元に戻せるか。 アクセシブルな設計とはフロントエンドに精通した開発者で構成されたフロントエンドチームを作ることかもしれない。アクセシブルな出力ができないCMSを廃止することかもしれない。コンテンツを適切に構造化する方法を編集スタッフに説明することかもしれない。もしあなたが自分自身で、自分一人でアクセシビリティの課題に対応しようとしているのであれば、その効果はすぐに薄れていくだろう。 

## 見せかけのパフォーマンスに価値なし

企業は、実際にアクセシビリティに取り組むことよりも、取り組んでいるように見せることを優先しがちである。アクセシビリティの専門家を雇いながら、必要なリソースを与えない。障害者を対象とした調査を委託しながら、フィードバックを真剣に受け止めようとしない。監査には金を払うが、その勧告には従わない。色のコントラストを評価する必要があると言いながら、自分たちの神聖なブランドに関わる色には一切変更を加えようとしない。もし、本当に変化を起こしたいのであれば、パフォーマンスではなく実践を求めるべきだ。

## 悪は腐るに任せよう

あなたは、もともと搾取的で中毒性のある製品、憎悪や誤った情報を売買する製品、あるいはただ世界をより悪くするだけの製品に、携わる機会があるだろう。このような類の製品と、それらを生み出す狂気じみた企業は、なんだかんだ言いながら、変革に強く抵抗する。救いようのないものを救おうとして、自分を犠牲にしてはならない。彼らの失敗を自分の失敗にしてはいけない。あなたの評判とメンタルヘルスを守ろう。世の中には、アクセシブルでないものがあふれている。そもそも存在する価値のある製品のために、理解のある人々と共に働くことを優先しよう。

## クレジット

### 日本語訳

- 太田 良典（[@bakera](https://x.com/bakera) / 弁護士ドットコム株式会社）
- 大山 奥人（[@okuto_oyama](https://x.com/okuto_oyama) / 株式会社Schoo）
- 坂巻 舞羽（[@mt_dew2](https://x.com/mt_dew2)）
- 杉吉 真奈（[@manasugiyoshi](https://x.com/manasugiyoshi)）
- 高井 実（[@debiru_R](https://x.com/debiru_R)）
- 田中 泰斗（[@taitotnk](https://x.com/taitotnk)）
- 田中 美和（[@miwa11y](https://x.com/miwa11y)）
- 土屋 一彦（[@caztcha](https://x.com/caztcha) / Accessible & Usable）
- 羽馬 直樹（[@naohaba70](https://x.com/naohaba70) / 株式会社コドモン）
- 守谷 絵美（[@emim](https://x.com/emim)）
- 山崎 規弘（[@chuff_chuff09](https://x.com/chuff_chuff09)）
- 植木 真（[@makoto_ueki](https://x.com/makoto_ueki) / 株式会社インフォアクシア）

### レビュー

- 石丸 治樹（[@hrism2](https://x.com/hrism2) / 株式会社ストックラボ, 株式会社Tety）
- 伊藤 芳浩（[@ItouYoshihiro](https://x.com/ItouYoshihiro) / NPO法人インフォメーションギャップバスター)
- そめ（[@_tsmd](https://x.com/_tsmd)）
- YUTO（[@TravelYuto](https://x.com/TravelYuto) / 株式会社Penetrator）
