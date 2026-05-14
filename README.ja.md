# echizenkaigan

越前海岸沿いの魅力的な観光スポットを紹介するWebアプリケーションです。越前海岸盛り上げ隊が提供するデータを、インタラクティブな地図上で可視化しています。

## デモ
https://code4fukui.github.io/echizenkaigan/

## 特徴
- 単一のCSVファイルを利用して、インタラクティブな地図上に観光スポットを表示します。
- マーカーをクリックすると、概要、電話番号、定休日などの詳細情報が表示されます。
- カテゴリーごとに異なるアイコン（例: 体験には `taiken.png`、飲食には `eat.png`）を使用し、視覚的にわかりやすく分類しています。
- `<csv-map>` Webコンポーネントを使用した、シンプルな静的HTMLページとして構築されています。

## 使い方
最新のWebブラウザで[デモページ](https://code4fukui.github.io/echizenkaigan/)を開いてください。地図と観光スポットが自動的に読み込まれます。地図上のアイコンをクリックすると、その場所の詳細情報が表示されます。

## データソース
このプロジェクトは、観光スポット情報が記載されたCSVファイルを利用しています。

- **データURL:** [`echizenkaigan-spot.csv`](https://code4fukui.github.io/echizenkaigan/echizenkaigan-spot.csv)
- **主なフィールド:** `名前`、`電話番号`、`カテゴリー`、`icon`、`概要`、`定休日`、および位置座標を示す `geo3x3`。

## 貢献団体・クレジット
- **データ提供:** [越前海岸盛り上げ隊](https://discoverechizen.com/)
- **開発:** [福井工業高等専門学校](https://www.fukui-nct.ac.jp/)
- **アイコン:** [OpenMoji](https://openmoji.org/) – オープンソースの絵文字・アイコンプロジェクト。

## ライセンス
MIT License — 詳細は[LICENSE](LICENSE)を参照してください。
