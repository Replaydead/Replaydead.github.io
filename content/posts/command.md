+++
date = '2026-06-09T20:52:06+09:00'
draft = true
title = 'Hugoでよく使うコマンド一覧'
+++

Hugo日常コマンド

\# 新規記事作成

hugo new content posts/記事名.md



\# ローカルサーバー起動（下書き含む）

hugo server --buildDrafts



\# ローカルサーバー起動（公開記事のみ）

hugo server

Git日常コマンド

\# 変更を全部ステージング

git add .



\# コミット

git commit -m "コメント"



\# 本番に反映

git push

記事の公開/非公開

\# 下書き（本番に出ない）

draft = true



\# 公開

draft = false

流れとしては



hugo new content で記事ファイル作成

メモ帳で編集

hugo server --buildDrafts でローカル確認

git add . → git commit → git push で本番反映



