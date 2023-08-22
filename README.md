# アクエディ4拡張 変数名CSV出力ツール <!-- omit in toc -->

## 目次 <!-- omit in toc -->
- [概要](#概要)
- [使用方法](#使用方法)
  - [ダウンロード](#ダウンロード)
  - [解凍](#解凍)
  - [ステージファイル読込](#ステージファイル読込)
    - [GUIの場合](#guiの場合)
    - [コマンドプロンプトの場合](#コマンドプロンプトの場合)
- [動作環境](#動作環境)
- [注意事項](#注意事項)
- [スペシャルサンクス](#スペシャルサンクス)
- [作者](#作者)
- [更新履歴](#更新履歴)


## 概要
- 本ソフトはアントン様制作の「アクションエディター4」(現在は公式配布終了)のエディター内で使用する変数の管理の効率化を目指すことを目的とした、ステージ変数名の一覧をCSVファイルに出力するためのソフトです。
- 本ソフトを使用すると、アクションエディター4で作成されたステージファイルの変数名の一覧をCSVファイルに出力できます。
- 出力されたCSVファイルを表計算ソフトなどに取り込むことで、アクションエディター4とは別の画面で変数名を確認することができ、変数の管理を従来より効率的に行うことが期待できます。

## 使用方法
### ダウンロード
- [このリンク](https://github.com/Kata-3/AE4Ex-out-csv-variable-names/tags)をクリックします。
- ダウンロードしたいバージョンを選択します。
- 「Source code」をクリックします。
- ダウンロードされるまで待ちます。
### 解凍
- ダウンロードしたファイルを解凍します。
   - 解凍したフォルダの中にある「AE4Ex_OutCsv_v`***`」(`***`はバージョン名(「`.`」無し))が本体です。
### ステージファイル読込
#### GUIの場合
- ステージファイルを選択します。(複数選択可)
- 本体の中にあるファイル「AE4Ex_OutCsv.exe」にドラッグ&ドロップします。
#### コマンドプロンプトの場合
- 実行ファイル「AE4Ex_OutCsv.exe」のパスを入力し、半角スペースを入力し、入力ファイルのパスを入力します。
   - 入力ファイルが複数ある場合は、各パスの間に半角スペースを入力します。
- Enterキーを押します。
- 実行ファイルと同じ場所にフォルダ「out」が作成され、その中にCSVファイルが作成されるまで待ちます。
- 詳細は「ReadMe.txt」を参照してください。

## 動作環境
- OS：Windows10
- 端末：日本向けPC
- アクションエディター4のバージョン：10.20

## 注意事項
- 本ソフトの使用により何らかのトラブルが発生しても作者は一切の責任を負いかねます。
- 他のバージョンのアクションエディター4などにより作成されたファイルは対応いたしません(未定義動作となります)。
- 本ソフトや入力ファイルのパスにマルチバイト文字列(漢字など)を含む場合、失敗する場合がございます。
  - ファイルパスにマルチバイト文字列が含まれないようにしてください。
    - 相対パスで指定
    - ファイルを移動
    - リネーム

## スペシャルサンクス
本ソフトの制作において、以下のプログラムを使用させて頂きました。

- Tatu 様
  - [アクエディ4のファイルを開いて表示するコード](https://tatu-oa.itch.io/ae4-file-open-code)
 
## 作者
- 作成者：かた三郎
  - [本ソフトのリポジトリ](https://github.com/Kata-3/AE4Ex-out-csv-variable-names)
  - [トップページ](https://kata-3.github.io/)
  - [X(旧Twitter)](https://twitter.com/ryu_chankyou01)
 
## 更新履歴
- [Ver.1.0.0](https://github.com/Kata-3/AE4Ex-out-csv-variable-names/releases/tag/Ver.1.0.0)
  - 初版公開