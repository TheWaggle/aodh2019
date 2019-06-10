---?color=#3A8FB7
@snap[breadcrumbs-wrap bluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [12. ページ遷移の追加](#/)
@olend
@snapend

@snap[west headline]
## ページ遷移の追加
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [12. ページ遷移の追加](#/)
@olend
@snapend

### @css[slide-title](ページ遷移の追加)

@snap[slide-contents]

@box[rounded box-style](Dbモジュールを利用した表示)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- [ナビバーへの追加](#/)
@olend
@snapend

@snap[right-column]
@img[goal-image to-center](template/img/Page-transition-13/nav-bar.png)
@snapend

@snapend


---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [12. ページ遷移の追加](#/)
- [1. マップの追加](#/)
@olend
@snapend

@snap[west headline]
## @color[white](ナビバーへの追加)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [12. ページ遷移の追加](#/)
- [1. ナビバーへの追加](#/)
@olend
@snapend

### @css[slide-title](ナビバーへの追加)

@snap[slide-contents]

@box[rounded box-style](**Visual Stdio Code** を利用します。```lib/aedmap_web/templates/layout/app.html.eex```を開きます。)

@ol[numberlist numberlist-color2](false)
- 下記のタグを探します。
- ```<li><a href="https://hexdocs.pm/phoenix/overview.html">Get Started</a></li>```
- 見つけたタグの下に以下を追加します。
- ```<li><%= link "HOME", to: Routes.page_path(@conn, :index) %></li>```
- ```<li><%= link "データ入力", to: Routes.location_path(@conn, :index) %></li>```

@olend

@snapend
