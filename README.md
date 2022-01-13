# SanFrancisco Crime
- サンフランシスコ警察の2003～2015年のデータセットに対して犯罪を可視化、分類モデルを作成し新しいデータセットに対して、その犯罪が何であるかの予測を行う事が目的
----
- Binderで起動したJupyterでの実行か、自環境のNotebookで実行してください。Githubでは40MBを超えUpdate制限にかかる為表示できません。
  - 自仮想環境下で実行する場合の必要なライブラリ　==　python3.8
    - itertools
    - pytz
    - numpy
    - folium
    - matplotlib.pyplot
    - seaborn 
    - sklearn 
    - pandas 
    - xgboost 
    - yellowbrick

--- 
# DataSet概要
## Data fields

- 日付 -犯罪事件のタイムスタンプ
- カテゴリ -犯罪事件のカテゴリ（train.csvのみ）。これは、予測するターゲット変数です。
- 説明 -犯罪事件の詳細な説明（train.csvのみ）
- DayOfWeek -曜日
- PdDistrict-警察署地区の名前
- 解決-犯罪事件がどのように解決されたか（train.csvのみ）
- 住所-犯罪事件のおおよその 住所
- X-経度
- Y-緯度
