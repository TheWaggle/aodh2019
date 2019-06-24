---?color=#3A8FB7
@snap[breadcrumbs-wrap bluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
@olend
@snapend

@snap[west headline]
## Here APIの利用
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
@olend
@snapend

### @css[slide-title](Here APIの利用)

@snap[slide-contents]

@box[rounded box-style](ブラウザ を使ってDeveloper登録をします。)

@ol[numberlist numberlist-color2](false)
- [Hereとは](#/)
- [Location for Developers](#/)
- [Location for Developersとは](#/)
- [JavaScript API code sample](#/)
- [確認](#/)
@olend

@snapend
---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [1. Hereとは](#/)
@olend
@snapend

@snap[west headline]
## @color[white](Hereとは)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [1. Hereとは](#/)
@olend
@snapend

### @css[slide-title](Hereとは)

@snap[slide-contents]
@snap[quote-wrap]

@quote[<ul><li>Hereは、地図サービスの提供会社の一つ<li>開発者に向けた３つのサービスがある</li><li>Open Location Platform</li><li>クラウドベースの位置管理サービス「HERE XYZ」</li><li>Developer Portal</li></ul>](https://www.here.com/)

@snapend
@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [2. Developer Portal](#/)
@olend
@snapend

@snap[west headline]
## @color[white](Developer Portal)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [2. Developer Portal](#/)
@olend
@snapend

### @css[slide-title smaller-font](Developer Portal)

@snap[slide-contents]
@img[goal-image to-center](template/img/here-api/developer-api.png)

@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [2. Developer Portal](#/)
@olend
@snapend

### @css[slide-title smaller-font](地図表示のAPIを提供)

  @snap[slide-contents]
  @img[goal-image to-center](template/img/here-api/here-map.png)

  @snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [2. Developer Portal](#/)
@olend
@snapend

### @css[slide-title smallest-font](Developer Portalとは)

@snap[slide-contents]

@box[rounded box-style](今回は<u>[Deceloper Portal](https://developer.here.com/?cid=www.here.com-main_menu)</u>のJavaScriptライブラリを利用します。<br>これは、地図表示を設置できるAPIです。)

@ol[numberlist numberlist-color4](false)
- Webブラウザーを使って、<u>https://developer.here.com/?cid=www.here.com-main_menu</u>にアクセスします。
- 画面上部のメニューから **GET STARTED FOR FREE** をクリックします。
- 新規アカウントを作成します。
- 利用規約に同意するにチェックをします。
- 登録したMailアドレスにhereのメールが届いてるので、リンクをクリックしてConfirmedします。
@olend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [3. App IDとApp Codeの取得](#/)
@olend
@snapend

@snap[west headline]
## @color[white](App IDと<br/>App Codeの取得)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [3. App IDとApp Codeの取得](#/)
@olend
@snapend

### @css[slide-title](App IDとApp Codeの取得)

@snap[slide-contents]

@box[rounded box-style]( **Webブラウザー** から 「JAVASCRIPT/REST」のApp IDを取得します)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- [App IDと App Codeの取得](#/)
@olend
@snapend

@snap[right-column]
@img[goal-image to-center](template/img/here-api/app-id.png)
@snapend

@snapend
---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [3. App IDとApp Codeの取得](#/)
@olend
@snapend

### @css[slide-title](App IDとApp Codeの取得)

@snap[slide-contents]

@box[rounded box-style]( **Webブラウザー** から取得したApp IDとApp Codeのメモをしておきます。)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- [App IDと App Codeの取得](#/)
@olend
@snapend

@snap[right-column]
@img[goal-image to-center](template/img/here-api/code_id.png)
@snapend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [4. JavaScript Code Sampleの利用](#/)
@olend
@snapend

@snap[west headline]
## @color[white](JavaScript Code<br/> Sampleの利用)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [4. JavaScript Code Sampleの利用](#/)
@olend
@snapend

### @css[slide-title smallest-font](JavaScript Code Sampleの利用)

@snap[slide-contents]

@box[rounded box-style](今回は<u>[Maps API for JavaScript](https://developer.here.com/api-explorer/maps-js/v3.0)</u>のJS+HTMLのサンプルコードを利用します。<br>これは、地図表示を設置できるAPIの例です。)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- Webブラウザーを使って、<u>https://developer.here.com/api-explorer/maps-js/v3.0</u>にアクセスします。
- JS+HTMLのタブを開き、記載されているコードをコピーします。
@olend
@snapend

@snap[right-column]
@img[goal-image to-center](template/img/here-api/jscode.png)
@snapend

@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [4. JavaScript Code Sampleの利用](#/)
@olend
@snapend

### @css[slide-title smallest-font](JavaScript Code Sampleの利用)

@snap[slide-contents]

@box[rounded box-style]( **Visual Studio Code** を使います。index.html.eexにコピーした内容を貼り付けます。)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- Visual Studio Codeを使って、コピーしたコードをindex.html.eexに貼り付けします。
@olend
@snapend

@snap[right-column]
@img[goal-image to-center](template/img/here-api/res.png)
@snapend


@snapend
---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [5. 応用](#/)
@olend
@snapend

@snap[west headline]
## @color[white](応用)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [14. Here APIの利用](#/)
- [5. 応用](#/)
@olend
@snapend

### @css[slide-title](確認)

@snap[slide-contents]

@box[rounded box-style](**Webブラウザー** を使って、<br>マーカーを表示する方法を調べます。)

@snap[left-column]
@ol[numberlist numberlist-color4](false)
- マーカー表示の例が乗っているページです。<br><u>@size[0.7em](https://developer.here.com/api-explorer/maps-js/v3.0/markers/markers-on-the-map)</u>
- 右のコードは、DataBaseにある緯度経度を表示する応用例です。
@olend
@snapend

@snap[right-column]
@snap[gist-box half-gist-box]

@gist[json zoom-06](Yoosuke/88450cbf931b336eae6261c14ff0e101)

@[0](上記をindex.html.eexにコピーして利用します。)
@[1](上記のコードは、現在日本の地図には対応していません。)

@snapend
@snapend

@snapend
