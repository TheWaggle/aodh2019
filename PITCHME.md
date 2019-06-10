---?color=#3A8FB7

@snap[headline]

@snap[byline headline-detail color4]
@size[0.75em](GEOSPATIAL Hackers Program Hands-on)
@snapend

# オープンデータを<br>利用して<br>地図アプリを作ろう!
@snapend

---?image=template/img/me-background.jpeg&size=cover

### @css[me-title](自己紹介)

@snap[me]

@img[avatar-image](template/img/yosukenakao.me.png)

@snap[me-detail]

[YOSUKE NAKAO.me](https://www.yosukenakao.me/)<br>
@fa[twitter-square]()[@YOSUKENAKAO](https://twitter.com/yosukenakao)

@snapend

@snapend

---
### @css[slide-title](本日のゴールイメージ)

@snap[slide-contents]
@img[goal-image to-center](template/img/finish.png)
@snapend

---
### @css[slide-title](ハンズオン講習会の流れ)

@snap[slide-contents]

@ol[numberlist numberlist-color1](false)
- 基礎知識			@css[detail-comment](Webの仕組みやプログラミングに必要な知識を学ぶ)
- Phoenix プロジェクト	@css[detail-comment](Phoenix を利用して Elixir のWebプロジェクトを設定する)
- Elixirモジュールの追加　@css[detail-comment](hexにあるモジュールを追加する)
- REPLを利用した開発　@css[detail-comment](REPLによるコードを試しながら開発する)
- APIの利用 @css[detail-comment](AEDオープンデータプラットフォームを利用してAPIをGetする)
- 外部データの取得と抽出 @css[detail-comment](オープンデータを取得する)
- 抽出データのWebページ表示 @css[detail-comment](抽出したデータをWebに表示する)
- 地図のWebページ表示 @css[detail-comment](leafletjsを利用する)
- 地点データの追加 @css[detail-comment](データを追加する)
- DBからのData取得 @css[detail-comment](DataBaseからDataを取得する)
- 地図にDataの反映　@css[detail-comment](位置情報を登録してWebに表示する)
- ページ遷移の追加　@css[detail-comment](ページのリンクを追加する)
- その他のJSライブラリ	@css[detail-comment](Geolocation APIやTURF.jsライブラリの紹介)
@olend

@snapend

---?include=template/md/basic-knowlede-webgis-1/PITCHME.md

---?include=template/md/create-a-new-project-2/PITCHME.md

---?include=template/md/add-modules-3/PITCHME.md

---?include=template/md/how-to-test-Elixir-project-4/PITCHME.md

---?include=template/md/external-API-5/PITCHME.md


---?include=template/md/external-API-data-7/PITCHME.md

---?include=template/md/display-data-on-web-page-8/PITCHME.md

---?include=template/md/display-map-on-web-page-9/PITCHME.md

---?include=template/md/add-location-data-10/PITCHME.md

---?include=template/md/DB-operation-11/PITCHME.md

---?include=template/md/map-view-12/PITCHME.md

---?include=template/md/Page-transition-13/PITCHME.md

---?include=template/md/other-14/PITCHME.md

---
### @css[slide-title](サンプルコード)

今回作った[SampleCode](https://github.com/TheWaggle/GeoHack_sampleCode.git)はこちらです。

---
### @css[slide-title](Excelから関数型言語マスター)

@ol[numberlist numberlist-color2](false)
- [1回目：データ行の”並べ替え”と”絞り込み”](https://qiita.com/piacere_ex/items/6714e1440e3f25fb46a1)
- [2回目：データ列の”抽出”、”Web表示”](https://qiita.com/piacere_ex/items/b7787580fce5f148242f)
- [3回目：WebにDBデータ表示【PostgreSQL or MySQL編】](https://qiita.com/piacere_ex/items/a7558adc6856e3577dc6)
- [4回目：Webに外部APIデータ表示](https://
qiita.com/piacere_ex/items/4c212615a4eb699dd109)
- [5回目：Webにグラフ表示](https://qiita.com/piacere_ex/items/290b76b76d5ff8e019bf)
- [6回目： Vue.js＋内部API（表示編）](https://qiita.com/piacere_ex/items/50d847170291c41fef64)
- [7回目： Vue.js＋内部API（更新編）](https://qiita.com/piacere_ex/items/7cd1162ce6d66a334a07)
- [Elixir CSVデータを取り込んで表示する方法](https://qiita.com/Yoosuke/items/3d2b0f9c9b9d1a4e491a)
@olend

---?color=#3A8FB7

@snap[headline]

@snap[byline headline-detail color4]
@size[1em](ありがとうございました。)
@snapend
