---?color=#3A8FB7
@snap[breadcrumbs-wrap bluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [13. その他のJSライブラリ](#/)
@olend
@snapend

@snap[west headline]
## その他のJSライブラリ
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [13. その他のJSライブラリ](#/)
@olend
@snapend

### @css[slide-title](その他のJSライブラリ)

@snap[slide-contents]

@box[rounded box-style](自分の位置情報を取得できるJavaScript API、leaflet.jsの地図に情報を追加できるTurf.js)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- [GeoLocation API](#/)
- [turf.jsの紹介](#/)
@olend
@snapend

@snap[right-column]
@img[goal-image to-center](template/img/Page-transition-13/mylocation.png)
@snapend

@snapend


---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [13. その他のJSライブラリ](#/)
- [1. GeoLocation API](#/)
@olend
@snapend

@snap[west headline]
## @color[white](GeoLocation API)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [13. その他のJSライブラリ](#/)
- [1. GeoLocation API](#/)
@olend
@snapend

### @css[slide-title](GeoLocation API)

@snap[slide-contents]

@box[rounded box-style](**Visual Stdio Code** を利用します。```lib/aedmap_web/templates/page/index.html.eex```を開きます。)

@snap[gist-box half-gist-box]
@gist[elixir zoom-08](Yoosuke/d56848eecd50e14924cf2be6f8d6b1d1)
@snapend

@ol[numberlist numberlist-color2](false)
- 上記のコードを貼り付けて動きを確認しましょう。
- 詳しくはリンク先を参照してください。[MDN Geolocaiton](https://developer.mozilla.org/ja/docs/Web/API/Geolocation/Using_geolocation)
@olend



@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [13. その他のJSライブラリ](#/)
- [2. turf.jsの紹介](#/)
@olend
@snapend

@snap[west headline]
## @color[white](turf.jsの紹介)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [13. その他のJSライブラリ](#/)
- [2. turf.jsの紹介](#/)
@olend
@snapend

### @css[slide-title](turf.jsの紹介)

@snap[slide-contents]

@box[rounded box-style](**Visual Stdio Code** を利用します。先ほどコピーしたプログラムで、２点間の距離を算出していた箇所がturf.jsを利用しています。)

@ol[numberlist numberlist-color2](false)
- ```var to =  turf.point([latitude, longitude]);```
- ```var from = turf.point([緯度,経度]);```
- ```var options = {units: 'kilometers'};```
- ```var distance = turf.distance(from, to, options);```
- [TURF](http://turfjs.org/)他にも色々なライブラリがあります。

@olend

@snapend
