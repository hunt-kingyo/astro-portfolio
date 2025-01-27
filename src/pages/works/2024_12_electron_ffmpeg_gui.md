---
layout: ../../layouts/MarkdownLayout.astro
title: "ElectronとFFmpegを用いた動画変換ソフトウェアの開発"
from: "2024/05"
to: "2024/12"
description: "ソフトウェア開発"
---
## 概要

ElectronやReact、FFmpegを用いて動画のコーデックを変換するソフトウェアを開発しました。

![開発したソフトウェア](/assets/app_image.jpg)

## ソースコード

https://github.com/hunt-kingyo/electron-ffmpeg-gui

## 主な機能
- 複数ファイルの選択・エンコード
- コーデックの選択
- コーデックごとのオプションの指定
- コンテナフォーマット / 拡張子の指定
- ファイル名へのサフィックス[^4]の追加
- 出力先フォルダの指定
- 実行中のログの表示する

## 技術スタック
- 言語：TypeScript
- フレームワーク：Electron
- フロントエンドライブラリ：React, Material UI
- その他のライブラリ：ffmpeg-static, fluent-ffmpeg