# ⚠️ このリポジトリは旧版です
## 現在は軽量化・機能改善を行った最新版「RoboSports Assist」を開発しています
## 最新版はこちら
# Repository：
## https://github.com/ecleaire/Tennis-Assist-Web
# Web App：  
# 大会 審判用

# https://ecleaire.github.io/Tennis-Assist-Web/

# 選手 練習用 / general

# https://ecleaire.github.io/Tennis-Assist-Web/general/

---

> [!IMPORTANT]
> 本リポジトリは、Godot Web Export ベースで開発していた旧版アーカイブです。
> 現在は TypeScript + Vite ベースの Web 版へ移行しています。
>
> 最新版では、
>
> * 初期読み込み速度改善
> * スマートフォン動作改善
> * 軽量化
> * UI改善
> * Google Apps Script 連携強化
>
> などを行っています。

---

# WRO RoboSports Assist

![Godot](https://img.shields.io/badge/Godot-4.6.2-478CBF?logo=godotengine&logoColor=white)
![Web](https://img.shields.io/badge/Platform-Web-2ea44f)
![PWA](https://img.shields.io/badge/PWA-Supported-8A2BE2)
![Offline](https://img.shields.io/badge/Offline-Supported-orange)
---
WRO RoboSports Double Tennis の大会運営・選手の練習をサポートする Godot 製アプリです。

選手は本番さながらの練習環境を構築でき、大会スタッフや審判はタイマー管理から試合記録・集計までをタブレット、PC、スマートフォン上で行えます。

タイマー、ボール配置ランダマイザー、試合記録、ルール確認、ニュース、リンク集などの機能をブラウザ上で利用できます。初回起動時は少し時間がかかる場合があります。

## 公開URL

https://ecleaire.github.io/Tennis-Assist-Public/
GitHub Pages で公開しています。
## 搭載機能

- 試合タイマー
- ボール配置ランダマイザー
- 試合記録
- 集計機能
- チーム管理
- ルールビューア
- ニュース
- リンク集
- PWA / オフライン対応

## 各機能の詳細

### 試合タイマー

- 1:00〜2:00 のランダム試合時間を生成
- 1秒、5秒、10秒単位、手動指定でのランダム設定
- 開始・一時停止・終了・リセットに対応
- 試合中のコールド 10 秒カウント、オーバーボールの 5 秒カウント機能
- 全画面表示に対応
- 記録モードから開始した試合は、タイマー終了後に記録入力へ連携

### ボール配置ランダマイザー

- RoboSports Double Tennis のボール配置をランダム生成
- オレンジボール・紫ボールの配置をフィールド上に表示
- 試合前の配置準備に利用可能
- ホーム画面ではタイマーと並べた二画面表示に対応
- 縦画面ではコートを縦向き表示に切り替え

### 試合記録

- 試合進行の補助
- チームを選択して 3 マッチ構成の試合を管理
- 各マッチの終了理由、得点、勝敗、違反数を記録
- 公式試合・練習試合の履歴を保存
- マッチ結果、試合結果を CSV 形式でエクスポート可能
- CSV インポートに対応
- アプリ内で対戦履歴を閲覧可能
- 誤操作防止の確認表示に対応

### 集計機能

- チーム別の試合数、勝敗、勝率を表示
- 本日・今週・今月の期間切り替えに対応
- チーム別の違反数などを確認可能

### チーム管理

- アプリ内でチームリストを編集可能
- 各端末のファイルシステムからチームリストを読み込み可能
- CSV 形式のチームリストに対応

### ルールビューア

- ルール項目を章ごとに閲覧
- キーワード検索に対応
- 公式ルール、翻訳版、Q&A へのリンクを用意

### ニュース

- Q&A 更新情報や競技情報を表示
- カテゴリ別に絞り込み可能

### リンク集

- WRO 公式サイト、各予選会公式サイト、ルール資料などへのショートカット

### PWA / オフライン対応

- iPad、スマートフォン、PC のブラウザからアプリ形式でホーム画面に追加可能
- 一度読み込んだ後は、オフライン環境でも起動可能
- 更新時は Service Worker のキャッシュを切り替えて新バージョンへ更新

## 今後のアップデート予定

- 音声ガイド機能の追加
- UI 改善
- PC / Android アプリ版の公開

## 開発環境

- Godot 4.6.2
- GDScript
- GitHub Pages


## フィードバック / バグ報告

バグや不具合、表示崩れや誤動作などを発見した場合は、Issues よりご報告いただけますと幸いです。

機能提案や改善案、運営向けアイデアなども Discussions にて歓迎しています。

## ライセンス / クレジット
### 使用素材
 #### 本アプリでは、以下の素晴らしい素材を利用しています。公開してくださっている制作者の皆さまに心より感謝いたします。
- Noto Sans JP（日本語フォント）  
  公式サイト: https://fonts.google.com/share?selection.family=Noto+Sans+JP:wght@100..900  
- DSEG（7セグメントフォント）  
　タイマー表示に使用しています。  
　公式サイト: https://www.keshikan.net/fonts.html  
　GitHub: https://github.com/keshikan/DSEG  
- 効果音ラボ（システム音声・効果音）  
　案内音声やシステム効果音の一部に使用しています。  
　公式サイト: https://soundeffect-lab.info/
 
- WRO、RoboSports、競技ルールに関する正式な情報は WRO 公式サイトを参照してください。  
 
- 開発支援: OpenAI ChatGPT / Codex  
 
- Godot Engine License  
　This game uses Godot Engine, available under the following license:  

　Copyright (c) 2014-present Godot Engine contributors.  
　Copyright (c) 2007-2014 Juan Linietsky, Ariel Manzur.  

　Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, 　　　　publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  

　The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  

　THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  

---

# Thank you

最後まで README をご覧いただき、ありがとうございます。  
このプロジェクトが RoboSports Double Tennis に関わる選手・審判・大会運営の皆さまのお役に立てれば幸いです。  
バグ報告や改善提案はもちろん、「こんな機能があると便利」といったアイデアも歓迎しています。  

皆さまからのフィードバックをもとに、これからも継続して改善・開発を進めていきます。  

