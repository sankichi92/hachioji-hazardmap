# 八王子市ハザードマップ

東京都八王子市の Web ハザードマップです。\
[市区町村ハザードマップテンプレート](https://github.com/sankichi92/shikuchoson-hazardmap-template)（[`655f547`](https://github.com/sankichi92/shikuchoson-hazardmap-template/tree/655f54701fa6928a98f0c8580c2132d70078879b)）を用いて作成しました。

## 使い方

### CSV ファイルをアップロードしてカスタムレイヤを追加する

1. 作成したリポジトリの [`csv`](./csv) をクリックして内容を表示する
2. 「Add files」→「Upload files」から CSV ファイルをアップロード、変更内容に名前をつけて「Commit changes」ボタンを押す

詳細: https://docs.github.com/ja/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

#### CSV のフォーマットについて

CSV ファイルは必ず `name`（名前）、`lat`（緯度）、`lon`（経度）のカラム（列）を持つ必要があります。
さらに、これらのカラム以外も追加でき、地図上のアイコンをクリックしたときに合わせて表示されます。
また、ファイル名先頭の `01-` は地図上での表示順を決めるために使われ、数字自体は地図上に表示されません。

### 画像をアップロードして地図の左下に表示する

CSV 同様、[`images`](./images) 以下に画像をアップロードすれば、地図の左下に表示されるようになります。
