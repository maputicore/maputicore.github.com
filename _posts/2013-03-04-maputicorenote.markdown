---
layout: post
title: grailsコマンドの備忘録
date: 2013-03-04
category : programing
---

###サーバーの起動

	grails run-app -Dserver.port=※※※

※※※は任意の番号

任意のポート番号にしないと,apacheと共存させるときとかに困る

###サーバーの停止

	grails stop-app

こちらはポート番号とか不要。
でも勝手に強制終了するとあとが面倒。