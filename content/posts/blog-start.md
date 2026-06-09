+++
date = '2026-06-09T20:47:18+09:00'
draft = true
title = '「Hugo + GitHub Pagesでブログを1時間以内に立ち上げた話」'
+++

エンジニアをやっていると、いつかブログを作りたいと思いながらずっと先延ばしにしていることがある。今回は思い立ったが吉日で、実際にやってみたら1時間かからずに公開まで漕ぎ着けた。その記録を残しておく。

使ったもの



Hugo（静的サイトジェネレーター）

GitHub Pages（無料ホスティング）

PaperMod（Hugoテーマ）

Git / GitHub Actions（自動デプロイ）



手順の流れ

まずHugoをインストールした。Windowsならwinget install Hugo.Hugo.Extended一発で入る。次にhugo new site myblogでプロジェクトを作成、PaperModをサブモジュールとして追加した。

GitHub側はリポジトリをユーザー名.github.ioという名前で作成し、GitHub ActionsのワークフローファイルをYAMLで書いてpushするだけで自動デプロイが走る設計にした。

デザインはassets/css/extended/custom.cssにCSSを置くだけでPaperModを上書きできる。黒ベースにセピア系のテキストカラーを入れてフィルムっぽい雰囲気にした。

やってみて

思ったより圧倒的に簡単だった。環境構築からデザインの骨格まで1時間以内に終わる。WordPressより軽くて無料で、記事はMarkdownで書けるのでエンジニアには向いている。

これをベースに映画分析を中心としたブログを育てていく予定だ。

