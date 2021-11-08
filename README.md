# list.jsとjekyllによる静的な図書館関係本リストのテスト

## サンプルサイトURL
https://maedaak.github.io/listjs_jikyll-test/

## 概要
List.jsのHTML内検索機能を使った書誌検索サンプルページである。<br>
書誌リストTSVをHTML中に埋め込むにあたり、GitHub Pagesの静的サイトジェネレーターJekyllを使用した。

## サンプルデータ
NACSIS-CATの総合目録データベースの書誌情報(CC-BY)を使用している。
そのままだとRDFでありJekyllで処理できないため、大学図書館員のための図書館システム開発練習用データ( https://mbc.dl.itc.u-tokyo.ac.jp/data4librarysystem/ )の図書書誌TSVから、先頭１万件を抽出して使用した。

## 流用方法
以下の資料に記載している。
- https://github.com/maedaak/listjs_jikyll-test/blob/main/doc/Easy_Web_Bibliographic_List_rev.pdf

## HTMLテンプレート
- Jekeyllを使用している。
