---?color=#3A8FB7
@snap[breadcrumbs-wrap bluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
@olend
@snapend

@snap[west headline]
## DBからのData取得
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
@olend
@snapend

### @css[slide-title](DBからのData取得)

@snap[slide-contents]

@box[rounded box-style](Ectoを利用してDBからDataを取得します。)

@snap[left-column]
@ol[numberlist numberlist-color2](false)
- [Ectoを利用したDataの取得](#/)
- [取得されたDataの確認](#/)
- [DB取得のモジュール開発準備](#/)
- [DB取得のモジュール開発](#/)
- [recompile](#/)
- [columnとrowを対にする](#/)
@olend
@snapend

@snap[right-column]
@ol[numberlist numberlist-color2 start-7](false)
- [Map型へ変換](#/)
- [連続してMap型へ変換](#/)
- [to_map関数の追加](#/)
- [to_map関数の動作確認](#/)
@olend
@snapend

@snapend


---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [1. Ectoを利用したDataの取得](#/)
@olend
@snapend

@snap[west headline]
## @color[white](Ectoを利用した<br>Dataの取得)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [1. Ectoを利用したDataの取得](#/)
@olend
@snapend

### @css[slide-title](Ectoを利用したDataの取得)

@snap[slide-contents]

@box[rounded box-style](**CUI** を利用します。Ecto.Adapters.SQL.queryを利用してDataを取得します。)

@fa[external-link]
[Ecto.Adapters.SQL](https://hexdocs.pm/ecto/2.2.8/Ecto.Adapters.SQL.html#query/4)

@ol[numberlist numberlist-color2](false)
- ```Ecto.Adapters.SQL.query( Aedmap.Repo  ,"SELECT * FROM locations", [])```
- 上記のコマンドをコピーしてCUIにペーストします。
- ```{ status, struct }```というタプル型のデータが返ってきます。
@olend

@snapend


---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [2. 取得されたDataの確認](#/)
@olend
@snapend

@snap[west headline]
## @color[white](取得された<br>Dataの確認)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [2. 取得されたDataの確認](#/)
@olend
@snapend

### @css[slide-title](取得されたDataの確認)

@snap[slide-contents]

@box[rounded box-style](**CUI** を利用します。取得したDataの構造体を確認します。)

@snap[gist-box half-gist-box]
@gist[elixir zoom-09](Yoosuke/32b8b3d1d4cb5ffba23c93fffd1219d6)
@snapend

@[1](```:ok```というステータスが返ってきています。)
@[2](```%Postgrex.Result```という構造体の形式でDataが取得されています。)
@[3](```columns:```には、テーブルのカラムに関するデータが入っています。)
@[9-14](```rows:```には、テーブルのロウに関するデータがリスト型で入っています。)

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [3. DB取得のモジュール開発準備](#/)
@olend
@snapend

@snap[west headline]
## @color[white](DB取得の<br>モジュール開発準備)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [3. DB取得のモジュール開発準備](#/)
@olend
@snapend

### @css[slide-title](DB取得のモジュール開発準備)

@snap[slide-contents]

@box[rounded box-style](**Visual Studio Code** を利用します。lib/util/db.exを作ります。)

@snap[left-column]

@ul[numberlist numberlist-color2](false)
- ```lib/util/```の作成
- ```util/db.ex```ファイルの作成
@ulend

@snapend

@snap[right-column]
@img[goal-image to-center](template/img/DB-operation/Visual_Studio_Code.png)
@snapend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [4. DB取得のモジュール開発](#/)
@olend
@snapend

@snap[west headline]
## @color[white](DB取得の<br>モジュール開発)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [4. DB取得のモジュール開発](#/)
@olend
@snapend

### @css[slide-title](DB取得のモジュール開発)

@snap[slide-contents]

@box[rounded box-style](**Visual Studio Code** を利用します。)

@snap[gist-box half-gist-box]
@gist[js zoom-09](Yoosuke/ae11d619278417963e971972ba791278)
@snapend

@[1](```Db```というモジュール名で作成します。)
@[2](```query```という関数名で、sqlを引数にとります。)
@[3](```case 何々 do```で返って来た値と比較します。)
@[4](ステータスに```:ok```が返って来たら、resultを返します。)
@[5](```:error```が返って来たらエラーメッセージを返します。)

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [5. recompile](#/)
@olend
@snapend

@snap[west headline]
## @color[white](recompile)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [5. recompile](#/)
@olend
@snapend

### @css[slide-title](recompile)

@snap[slide-contents]

@box[rounded box-style](**CUI** を利用します。コンソール画面から、recompileします。)

@ol[numberlist numberlist-color2](false)
- ```recompile```を入力
- ```:ok```と表示されていれば成功
- ```data = Db.query("SELECT * FROM locations")```を入力
- dataに構造体のデータが束縛
- 構造体のデータは、.key名でデータを取得
- data.columnsを入力
- data.rowsを入力
@olend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [6. columnとrowを対にする](#/)
@olend
@snapend

@snap[west headline]
## @color[white](columnと<br>rowを対にする)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [6. columnとrowを対にする](#/)
@olend
@snapend

### @css[slide-title](columnとrowを対にする)

@snap[slide-contents]

@box[rounded box-style](**CUI** を利用します。List.zip([[1,2],[3,4]])の形の引数を渡すと　[{1, 3}, {2, 4}] のようなタプルを保持したリストを返してくれます。)

@ol[numberlist numberlist-color2](false)
- ```[head | tail ] = data.rows```を入力
- ```List.zip([data.columns, head])```を入力
@olend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [7. Map型へ変換](#/)
@olend
@snapend

@snap[west headline]
## @color[white](Map型へ変換)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [7. Map型へ変換](#/)
@olend
@snapend

### @css[slide-title](Map型へ変換)

@snap[slide-contents]

@box[rounded box-style](**CUI** を利用します。Map型にするには、Enum.intoを利用します。第一引数に、リスト、第２引数に %{} を入れる事で、Map型に変換した値が返ってきます。)

@ol[numberlist numberlist-color2](false)
- ```Enum.into(List.zip([data.columns, head]), %{})```を入力
@olend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [8. 連続してMap型へ変換](#/)
@olend
@snapend

@snap[west headline]
## @color[white](連続して<br>Map型へ変換)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [8. 連続してMap型へ変換](#/)
@olend
@snapend

### @css[slide-title](連続してMap型へ変換)

@snap[slide-contents]

@box[rounded box-style](**CUI** を利用します。Enum.map（リスト、処理） 第１引数にリストを入れ、第二引数に処理を書きます。<br>例：Enum.map（[1,2,3], fn x -> x * 2 end ）<br>結果：[2, 4, 6])

@ol[numberlist numberlist-color2](false)
- ```Enum.map(data.rows, fn row -> Enum.into(List.zip([data.columns, row]), %{}) end )```を入力
@olend

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [9. to_map関数の追加](#/)
@olend
@snapend

@snap[west headline]
## @color[white](to_map関数の追加)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [9. to_map関数の追加](#/)
@olend
@snapend

### @css[slide-title](to_map関数の追加)

@snap[slide-contents]

@box[rounded box-style](**Visual Studio Code** を利用します。lib/util/db.exにto_map関数を追記します。)

@snap[gist-box half-gist-box]
@gist[js zoom-09](Yoosuke/ea077d7a6e8a3eb980d537e91e0e00f2)
@snapend

@[5-8](```list_to_tuple```という関数名でEnum.mapの第２引数に入れる関数の作成)
@[1-3](```to_map```という関数名で、Db.queryで取得した値を引数にとる関数の作成)
@[1,5](```def```と```defp```の違い、defはモジュールの外から利用可能defpは不可)

@snapend

---?color=#77B6D4
@snap[breadcrumbs-wrap lightbluescale]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [10. to_map関数の動作確認](#/)
@olend
@snapend

@snap[west headline]
## @color[white](to_map関数<br>の動作確認)
@snapend

---
@snap[breadcrumbs-wrap]
@ol[breadcrumbs](false)
- [ハンズオン講習会の流れ](#/2)
- [10. DBからのData取得](#/)
- [10. to_map関数の動作確認](#/)
@olend
@snapend

### @css[slide-title](to_map関数の動作確認)

@snap[slide-contents]

@box[rounded box-style](**CUI** を利用します。コンソールでrecompileしてDb.to_mapの動作確認をします。)

@ol[numberlist numberlist-color2](false)
- ```data = Db.query("SELECT * FROM locations")```
- ```results = Db.to_map(data)```
@olend


@snapend