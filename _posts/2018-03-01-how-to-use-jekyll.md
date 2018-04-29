---
layout: single
classes:
  - landing
  - dark-theme
title:  "Jekyll設定"
date:   2018-03-01 17:07:45 +0800
categories: 
  - Jekyll
tags:
  - Jekyll
  - Blog
  - GitHub
---

### 基本設定 ###

在terminal輸入以下指令

	~ $ gem install jekyll bundler
	~ $ jekyll new myblog
	~ $ cd myblog
	~/myblog $ bundle exec jekyll serve

 => 瀏覽 http://localhost:4000

-------

### Minimal-Mistakes版面套件設定 ###

本網站套用[Minimal-Mistakes][Minimal-Mistakes]

[Minimal-Mistakes]: https://mmistakes.github.io/minimal-mistakes/

-------

### 部屬至Github ###

使用Github內建的github.io網址

	~/myblog $ git init
	~/myblog $ git add .
	~/myblog $ git commit -m 'init git'

	git remote add origin https://github.com/account/account.github.io.git
	git push -u origin master

新增文章後push至GitHub

	~/myblog $ git add .
	~/myblog $ git commit -m 'add new post'
	~/myblog $ git push -u origin [gh-pages|master]