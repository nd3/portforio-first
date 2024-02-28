# portforio-first<!-- omit in toc -->

<div id="top"></div>

## 使用技術一覧<!-- omit in toc -->

<p style="display: inline">
  <!-- フロントエンドのフレームワーク一覧 -->
<img alt="HTML5" src="https://img.shields.io/badge/html5-ffffff?style=for-the-badge&logo=html5">
  <!-- バックエンドのフレームワーク一覧 -->
  <!-- バックエンドの言語一覧 -->
  <!-- ミドルウェア一覧 -->
<img alt="Nginx" src="https://img.shields.io/badge/-Nginx-269539.svg?logo=nginx&style=for-the-badge">
  <!-- インフラ一覧 -->
<img alt="EC2" src="https://img.shields.io/badge/-Amazon%20ec2-232F3E.svg?logo=amazon-ec2&style=for-the-badge">
<img alt="Ubuntu" src="https://img.shields.io/badge/ubuntu-300a24?style=for-the-badge&logo=ubuntu">
  <!-- その他ツール等 -->
<img alt="VSCode" src="https://img.shields.io/badge/vscode-007acc?style=for-the-badge&logo=visual-studio-code">
</p>

## 目次<!-- omit in toc -->

- [1. プロジェクト概要](#1-プロジェクト概要)
- [2. 環境](#2-環境)
- [3. ディレクトリ構成](#3-ディレクトリ構成)
- [4. 開発環境構築](#4-開発環境構築)
- [5. 参考](#5-参考)

## プロジェクト名<!-- omit in toc -->

ポートフォリオのテスト作成

## 1. プロジェクト概要

AWS EC2を用いて自力でWebサーバーを設定し、ポートフォリオページと、設定手順を記したHTMLを配置し、外部公開する。
<p align="right">(<a href="#top">トップへ</a>)</p>

<!-- ## プロジェクト詳細 -->

  <!-- プロジェクト管理をしていればリンクを貼る -->
<!-- <p align="right">(<a href="#top">トップへ</a>)</p> -->

## 2. 環境
<!-- 言語、フレームワーク、ミドルウェア、インフラの一覧とバージョンを記載 -->

| 言語・フレームワーク  | バージョン |
| ------------------ | ---------- |
| Nginx              | 1.18.0     |
| Ubuntu             | 22.04 LTS 64ビット(x86)    |
<p align="right">(<a href="#top">トップへ</a>)</p>

## 3. ディレクトリ構成

<!-- Treeコマンドを使ってディレクトリ構成を記載 -->
<!-- tree -a -I "github-markdown-css|.DS_Store|.git|images_photo" -L 2-->
.<br>
├── .gitignore<br>
├── .vscode<br>
│   └── sftp.json<br>
├── README.md<br>
├── css<br>
│   ├── animation.css<br>
│   ├── github-markdown-light.css<br>
│   └── style.css<br>
├── howto<br>
│   ├── images<br>
│   ├── infra_no1.html<br>
│   └── infra_no1.md<br>
├── images<br>
│   ├── bg.jpg<br>
│   ├── bg.psd<br>
│   ├── bg1.jpg<br>
│   ├── bg2.jpg<br>
│   ├── bg3.jpg<br>
│   ├── bg4.jpg<br>
│   ├── bg_main.jpg<br>
│   ├── logo.png<br>
│   ├── logo.psd<br>
│   ├── logo_pf.png<br>
│   └── logo_pf.xcf<br>
├── index.html<br>
└── js<br>
    └── main.js<br>

<p align="right">(<a href="#top">トップへ</a>)</p>

## 4. 開発環境構築

<http://ec2-15-168-37-255.ap-northeast-3.compute.amazonaws.com/portfolio/first/howto/infra_no1.html>
<p align="right">(<a href="#top">トップへ</a>)</p>

<!-- ## トラブルシューティング -->

## 5. 参考

全プロジェクトで重宝されるイケてるREADMEを作成しよう！(<https://qiita.com/shun198/items/c983c713452c041ef787> 閲覧日:2024-02-28, 更新日:2023-09-30)
