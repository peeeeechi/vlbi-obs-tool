# vlbi-obs-tool

このツールは VLBI 観測における、空間周波数平面（u, v）上で対象天体を観測し続けたときに各基線が描く軌跡 （uv coverage） および 各アンテナにおいて対象天体が観測可能な時間帯を合わせて表示するツールです。
日本の VERA アンテナを想定して作成していますが、自身でアンテナの地理座標（緯度, 経度）, 標高を追加することで任意のアンテナ間の uv coverage の表示も可能です。

アンテナの座標は https://www.miz.nao.ac.jp/content/facilities.html の各観測局のページに記載された情報を引用しています。
また、標高の情報は https://maps.gsi.go.jp/ より、アンテナの座標を入力して取得しています。
