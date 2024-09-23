c---
title: "個別要素法ライブラリYadeをDocker環境で構築する"
emoji: "📘"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["Yade", "Docker", "地盤", "シミュレーション", "個別要素法"]
published: false
---

# はじめに
Yadeは、個別要素法（DEM）を用いた粒子シミュレーションを行うためのライブラリです。YadeはPythonで記述されており、Pythonのスクリプトを用いてシミュレーションを行うことができます。また、Yadeは、多くの物理モデルやアルゴリズムを提供しており、様々な問題に対してシミュレーションを行うことができます。

この記事では、YadeをDocker環境で構築する方法について説明します。Dockerを用いることで、Yadeの環境構築を簡単に行うことができます。
今回対象とする環境は以下のとおりです。

- OS: Ubuntu 22.04
- Docker Desktop: 4.25.2
- Yade: 2022.01a
- PC: MacBook Pro (Apple Silicon)

基本的な流れとしては、Yadeの公式HPに記載されている方法に従っていきます。

@[card](https://yade-dem.org/doc/installation.html)

# Docker Desktopのインストール

# 