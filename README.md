# compornent（共通部品）

## イメージ画像
<img width="412" alt="image" src="https://user-images.githubusercontent.com/99580997/161290895-27564dc0-6451-4e70-aabd-1a778e4abf25.png">


## 概要

- カード（アスペクト比を固定して画像の縦横比を保つ方法）※aspect-ratio: 4/3;を使用したケース
- `aspect-ratio: 4/3;`を使用してアスペクト比を維持する。
- 
- `.card {`
- `display: inline-block;`
- `width: rem(375);`
- `aspect-ratio: 4/3;`
- `background-color: #f00;`
- `overflow: hidden;`
- `}`
- 
- https://www.notion.so/000_web-component-index-c4b399010bf342e9b4e2ed516cf9c730

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- xxx

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> card をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="757" alt="image" src="https://user-images.githubusercontent.com/99580997/161290973-877c5d7d-2b54-4f04-a0c5-38a598c52a54.png">


## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="950" alt="image" src="https://user-images.githubusercontent.com/99580997/161291030-8e43eb8e-c172-4baf-ae8f-c8700032f4cb.png">


## portfolio url:

- https://c-0045.wtb.cfbx.jp/

## 参考にしたサイト

- アスペクト比をもっと簡単に設定する方法`(aspect-ratio: 4/3;)`
- https://ryu-webstudy.com/2021/10/28/aspect/
- css translate の使い方！transform の translate の３ D 移動
- https://owl-view.com/css/2579/

## 更新履歴

- 2022/4/2 初版 作成完了(カード（アスペクト比を固定して画像の縦横比を保つ方法）※aspect-ratio: 4/3;を使用したケース)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
