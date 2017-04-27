---
layout: post
category: jekyll
date: 2017-04-27
title: Jekyll学習
---
[翻訳サイト](http://jekyllrb-ja.github.io/)などを読みながらJekyllの学習を進めます。備忘のためメモします。

## ディレクトリ構成
_drafts postsに出力しない。  
_site 生成されたサイトはデフォルトでここに置かれる。.gitignoreファイルに追加した。  
cssやimageフォルダ そのまま生成したサイトにコピーされる。  

## ビルドコマンドオプション
LSI 関連postsの索引を作成する。ビルドに時間がかかるらしい。  

## 未解決
以下の処理でCloud9上でJekyllを動かせるらしいが、Not Foundとなってしまう。  
`jekyll serve --host $IP --port $PORT --baseurl ''`