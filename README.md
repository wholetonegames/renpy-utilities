# Renpy Utilities

このリポジトリは Ren'Py に有用な様々なファイルをアップロードしています。   
基本的に一覧の下に行くほど複雑で上級者向けになります。   
各ファイルの詳しい説明は、ファイル自体にコメントとして埋め込まれています。   
本リポジトリに含まれるファイルは全てパブリックドメインです。


## keyconf.rpy
マウス・キーボード・ゲームパッドの割り当てを追加・変更するファイルです。

## animation.rpy
様々な transform（画像変換）や transition（画像遷移）を追加・変更するファイルです。

## gallery.rpy
視聴済みの画像や音楽を自動的に検索・追加する、統合型のギャラリーを追加するファイルです。

## _statements.rpy
Ren'Py に新たなステートメント（命令文）を追加します。

## tilemap.rpy
小さな画像を並べて一枚の画像にする Tilemap を追加するファイルです。

## dressup.rpy
多層レイヤーのスプライトを追加するファイルです。   
次の inventory と組み合わせることでドレスアップゲームなども作ることもできます。

## inventory.rpy
アイテムの売買や管理を行う機能を追加するファイルです。   
多少の改変でスキルやクエストなど様々な要素の管理に汎用的に使えます。

## competition.rpy
ターン制のバトルや競技などを行う基本的な枠組を追加するファイルです。   
シンプルなコードで汎用性を重視しているため、実用には改変の必要があります。

## explorer.rpy
２Dマップにイベントを配置する探索型ゲームのフレームワークです。   
RPGからSLGまで様々に使えるように汎用性を高くしてありますが、その分コードは少し複雑になっています。

## crawler.rpy
上の explorer を拡張して疑似３Dダンジョンを探索できるようにします。   
必要最低限のコードしか無いので、面白いゲームにするには色々研究して改変してみてください。   
サンプルを実行するには cave フォルダーの画像をダウンロードして images フォルダーに置く必要があります。
