---?color=#3A8FB7
@snap[breadcrumbs-wrap bluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/0)
@olend
@snapend

@snap[west headline]
## 基礎知識
@snapend


---

@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/0)
@olend
@snapend

### @css[slide-title](基礎知識)

@snap[slide-contents]

@box[rounded box-style](Webの仕組みやプログラミングに必要な知識を学びます。)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- [Webとは](#/6)
- [Webページとは](#/7)
- [HTMLとは](#/8)
- [HTMLの書き方](#/9)
- [CSSとは](#/10)
- [CSSの書き方](#/11)
@olend
@snapend


@snap[right-column]
@ol[numberlist numberlist-color2 start-7](false)
- [JavaScriptとは](#/12)
- [JavaScriptの書き方](#/13)
- [Webの仕組み](#/14)
- [Elixirとは](#/15)
- [フレームワークとは](#/16)
- [型とは](#/17)
@olend
@snapend

@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [1. Webとは]()
@olend
@snapend

### @css[slide-title](Webとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>World Wide **Web**（WWW、ワールド・ワイド・ウェブ）</li><li>Web（ウェブ）とも呼ばれる</li><li>「**インターネット**」という表現が<br>ワールド・ワイド・ウェブを指す場合もある</li><li>**世界中に張り巡らしたような、文書間のつながり**</li></ul>](https://ja.wikipedia.org/wiki/World_Wide_Web)

@quote[Webにおける情報の基礎的な単位は**ページ**<br>（Webページ、ウェブページ）](http://e-words.jp/w/Web.html)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [2. Webページとは]()
@olend
@snapend

### @css[slide-title](Webページとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>ウェブ上にあり、ウェブブラウザで閲覧可能なページ単位の文書</li><li>**HTML**（またはXHTML）と **スタイルシート**、画像データで構成</li><li>ウェブブラウザを使用して閲覧されることが一般的</li><li>**JavaScript** などのスクリプト言語を使って<br>ウェブページに動作をもたる場合がある</li></ul>](https://ja.wikipedia.org/wiki/ウェブページ)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [3. HTMLとは]()
@olend
@snapend

### @css[slide-title](HTMLとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[**H**yper **T**ext **M**arkup **L**anguage（ハイパーテキスト マークアップ ランゲージ、HTML（エイチティーエムエル））](https://ja.wikipedia.org/wiki/HyperText_Markup_Language)

@quote[**ハイパーテキスト**：<br>複数の文書（テキスト）を相互に関連付け、結び付ける仕組み](https://ja.wikipedia.org/wiki/ハイパーテキスト)


@quote[**マークアップ言語**：<br>視覚表現や文章構造などを記述するための形式言語](https://ja.wikipedia.org/wiki/マークアップ言語)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [4. HTMLの書き方]()
@olend
@snapend

### @css[slide-title](HTMLの書き方)

@snap[slide-contents]
@snap[code-contents]

@snap[gist-box ]
@gist[js zoom-8](Yoosuke/b59c57e544ef5f1273c41b3f332cddb9)
@snapend

@[1-2](「&lt;html&gt;」「&lt;head&gt;」などを タグ と呼びます。)
@[0](タグを利用して文書の構造や意味などを記述（マークアップ）していきます。)
@[6,12](&lt;body&gt;内容&lt;/body&gt; のように、タグで囲んで内容を記述をしていきます。)
@[8](&lt;div id="section"&gt; のように、タグの中にid="id名をつける事ができます。")

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [5. CSSとは]()
@olend
@snapend

### @css[slide-title](CSSとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>**C**ascading **S**tyle **S**heets（CSS、<br>カスケーディング・スタイル・シート）</li><li>HTMLの要素をどのように修飾（表示）するかを指示する</li><li>文書の構造と体裁を分離させる<br>という理念を実現する為に提唱された**スタイルシート**の一つ</li></ul>](https://ja.wikipedia.org/wiki/Cascading_Style_Sheets)

@quote[**スタイルシート**：<br>構造化文書などにおける表示形式を制御するしくみ](https://ja.wikipedia.org/wiki/スタイルシート)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [6. CSSの書き方]()
@olend
@snapend

### @css[slide-title](CSSの書き方)

@snap[slide-contents]
@snap[code-contents]

@snap[gist-box half-gist-box]
@gist[js zoom-9](Yoosuke/d205b0cd2ada1ac3e8eb0dbe06e312d5)
@snapend


@[0](（適応する対象を指定します）{<br><span></span>（スタイルの種類を選びます）:（値を設定します）;<br>})
@[1](タグ名で適応範囲を指定しています。この例では、divタグのid=sectionの場所を適応範囲として指定しています。)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [7. JavaScriptとは]()
@olend
@snapend

### @css[slide-title](JavaScriptとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>JavaScript（ジャバスクリプト）</li><li>主にWebページに組み込まれたプログラムを<br>Webブラウザ上で実行するために用いられる**プログラミング言語**</li><li>HTMLファイル内に埋め込まれて記述</li></ul>](https://ja.wikipedia.org/wiki/JavaScript)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [8. JavaScriptの書き方]()
@olend
@snapend

### @css[slide-title](JavaScriptの書き方)

@snap[slide-contents]
@snap[code-contents]


@snap[gist-box half-gist-box]
@gist[js zoom-15](Yoosuke/59f42cf61fdb5b3600e6965ab966e6f2)
@snapend

@[1](```<script></script>```のタグの間にJavascriptを書きます。)
@[2](varを使ってnameという変数を宣言しています。　= は代入演算子といって、 "YOSUKE"という文字列を変数nameに代入しています。)
@[3](console.log(name)は、console.log()という関数に変数nameを引数として入れる事でconsoleのlogにYOSUKEが表示されます。)


@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [9. Webの仕組み]()
@olend
@snapend

### @css[slide-title](Webの仕組み)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>ウェブページのコピーが<br>**サーバー** から **クライアント** にダウンロードされ、<br>ユーザーのウェブブラウザーに表示されます</li><li>**サーバー**：<br>ウェブページ、サイト、アプリを保存しているコンピューター</li><li>**クライアント**：<br>インターネットに接続された<br>コンピューターやスマートフォンなどのデバイス</li></ul>](https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [10. Elixirとは]()
@olend
@snapend

### @css[slide-title](Elixirとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>Elixir（エリクサー）</li><li>プログラミング言語</li><li>高い基本性能、書きやすい高生産性</li><li>１つのマシン内で数十万のプロセスが同時に動作</li><li>コードを短く/速く/メンテナンスしやすくするスタイル</li><li>開発用ツールセットが用意されています<ul><li>ビルドツール「 **mix（ミックス）**」</li></ul></li><li>Web<a href="#/">**フレームワーク**</a>「 **Phoenix（フェニックス）**」が人気</li></ul>](https://www.ossnews.jp/oss_info/Elixir)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [11. フレームワークとは]()
@olend
@snapend

### @css[slide-title](フレームワークとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>汎用的な機能や基本的な制御構造をまとめた**半完成品**</li><li>開発者がコードを記述して機能を追加、拡張する</li></ul>](http://e-words.jp/w/フレームワーク.html)

@snapend
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [1. 基礎知識](#/4)
- [12. 型とは]()
@olend
@snapend

### @css[slide-title](型とは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>データ（値）の種類に関する分類<ul><li>0, 1, 2, -42 といったような値は整数型</li><li>"foo", "Hello" といったような値は文字列型</li></ul></li></ul>](https://ja.m.wikipedia.org/wiki/データ型)

@snapend
@snapend



