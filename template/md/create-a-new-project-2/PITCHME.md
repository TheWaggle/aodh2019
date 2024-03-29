---?color=#3A8FB7
@snap[breadcrumbs-wrap bluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/)
@olend
@snapend

@snap[west headline]
## Phoenix<br>プロジェクトの作成
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
@olend
@snapend

### @css[slide-title](Phoenix プロジェクトの作成)

@snap[slide-contents]

@box[rounded box-style](Phoenix を利用してWebプロジェクトを作成します。)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- [プロジェクトの作成](#/20)
- [フォルダの移動](#/22)
- [データベースの作成](#/24)
- [アプリケーションの起動](#/26)
- [Webサイトの確認](#/28)
- [アプリケーションの終了](#/30)
@olend
@snapend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [1. プロジェクトの作成](#/)
@olend
@snapend

@snap[west headline]
## @color[white](プロジェクトの作成)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [1. プロジェクトの作成](#/)
@olend
@snapend

### @css[slide-title](プロジェクトの作成)

@snap[slide-contents]

@box[rounded box-style](**CUI**を使って、プロジェクトのフォルダ構成と<br>必要なソースコードを生成します。)

@snap[left-column]
@ol[numberlist numberlist-color4](false)
- mix phx.new aodhmap
- Y
@olend
@snapend

@snap[right-column]
@snap[gist-box half-gist-box]

@gist[elixir zoom-07](yuki-thewaggle/6d480567461a24e96aeceb52a17e5764)

@[1](プロジェクトを生成します)
@[50](関連する必要物のインストールを許可します)

@snapend
@snapend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [2. フォルダの移動](#/)
@olend
@snapend

@snap[west headline]
## @color[white](フォルダの移動)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [2. フォルダの移動](#/)
@olend
@snapend

### @css[slide-title](フォルダの移動)

@snap[slide-contents]

@box[rounded box-style](**CUI**を使って、<br>プロジェクトのフォルダに移動します。)

@snap[left-column]
@ol[numberlist numberlist-color4](false)
- cd aodhmap
@olend
@snapend

@snap[right-column]
@snap[gist-box half-gist-box]

@gist[r zoom-10](Yoosuke/11ca063670bff4bf628c10eeb8dcfd35)

@[1](aodhmapに移動します)

@snapend
@snapend

@snapend


---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [3. データベースの作成](#/)
@olend
@snapend

@snap[west headline]
## @color[white](データベースの作成)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [3. データベースの作成](#/)
@olend
@snapend

### @css[slide-title](データベースの作成)

@snap[slide-contents]

@box[rounded box-style](**CUI**を使って、<br>データを保存するための機能を作成します。)

@snap[left-column]
@ol[numberlist numberlist-color4](false)
- mix ecto.create
@olend
@snapend

@snap[right-column]
@snap[gist-box half-gist-box]

@gist[r zoom-09](yuki-thewaggle/72816aa21b6f9fc214197d8ba3218cef)

@[1](リポジトリ「保管場所」用のストレージを作成します)
@[3-5](このようなメッセージが出てきたら成功です。)

@snapend
@snapend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [4. アプリケーションの起動](#/)
@olend
@snapend

@snap[west headline]
## @color[white](アプリケーションの<br>起動)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [4. アプリケーションの起動](#/)
@olend
@snapend

### @css[slide-title](アプリケーションの起動)

@snap[slide-contents]

@box[rounded box-style](**CUI**を使って、サーバーを実行して<br>アプリケーションを起動します。)

@snap[left-column]
@ol[numberlist numberlist-color4](false)
- mix phx.server
@olend
@snapend

@snap[right-column]
@snap[gist-box half-gist-box]

@gist[r zoom-07](yuki-thewaggle/cbe24972628ae0f1f0a2d5bec6943f41)

@[1](サーバーを起動します)

@snapend
@snapend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [5. Webサイトの確認](#/)
@olend
@snapend

@snap[west headline]
## @color[white](Webサイトの確認)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [5. Webサイトの確認](#/)
@olend
@snapend

### @css[slide-title](Webサイトの確認)

@snap[slide-contents]

@box[rounded box-style](**Webブラウザー**を使って、アプリケーションが起動して<br>Webサイトが見られるようになったことを確認します。)

@snap[left-column]
@ol[numberlist numberlist-color4](true)
- Firefox を立ち上げます。
- <span class="not-selectable">URLに</span><br><u>http://localhost:4000</u><br><span class="not-selectable">を貼り付けて開きます。</span>
- 画像のようなページが表示されます。
@olend
@snapend

@snap[right-column]
@snap[imagebox]
@img[](template/img/create-a-new-project/5-localhost.png)
@snapend
@snapend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [6. アプリケーションの終了](#/)
@olend
@snapend

@snap[west headline]
## @color[white](アプリケーションの<br>終了)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/3)
- [2. Phoenix プロジェクト](#/18)
- [6. アプリケーションの終了](#/)
@olend
@snapend

### @css[slide-title](アプリケーションの終了)

@snap[slide-contents]

@box[rounded box-style](**CUI**を使って、<br>起動しているアプリケーションを終了します。)

@ol[numberlist numberlist-color4](true)
- Windowsの場合は「**Ctrl + C**」を2回入力します。
- Macの場合は「**control + C**」を2回入力します。
- アプリケーションが終了します。
@olend


@snapend
