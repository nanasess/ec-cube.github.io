---
layout: default
title: EC-CUBE開発ドキュメント・マニュアル
keywords: このサイトについて, QuickStart
tags: [quickstart]
sidebar: home_sidebar
permalink: /
---

# {{page.title}}

 EC-CUBEの開発ドキュメント（マニュアル）サイトです。    
 EC-CUBEのインストール方法、開発ガイドラインや要素技術の概念、本体開発やプラグイン開発のチュートリアル、Cookbookなどの情報を提供しています。  
 ドキュメントへの追記、記載内容の修正についてはEC-CUBE本体と同様に[GitHub](https://github.com/EC-CUBE/ec-cube.github.io/){:target="_blank"
}で受け付けております。

運用者向けには以下のサイトをご覧ください。

+ [EC-CUBE 3運用マニュアル（株式会社クロスキューブ様）](https://www.xross-cube.com/service/ec-cube%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA/eccube3-manual/){:target="_blank"}
+ [EC-CUBE 3管理・運用 マニュアル（株式会社シロハチ様）](https://www.shiro8.net/manual/v30x/){:target="_blank"}

## Quick Start

+ [インストールの前に] (こんなコンセプトで開発されているよ的な。 Introduction)
+ [システム要件](/quickstart_requirement)

### インストール方法

+ [インストール方法](/quickstart_install)
	- [本番環境]
	- [開発環境の構築](/guideline_development)
		- [Docker コンテナ]

### 設定ガイド
+ 設定ファイル
	- [設定ファイルの概要](/spec_config)
	- [doctrine_cacheの設定](/spec_doctrine-cache)
	- [セッションハンドラの設定](/spec_session-handler)
	- [ログ出力設定](/guideline_log)
++ [プロキシサーバの設定](/quickstart_proxy)
++ [urlからhtmlを無くす手順](/quickstart_remove-html)

### バージョンアップガイド

+ [バージョンアップ方法](/quickstart_update)

## 開発ガイド

+ [EC-CUBE 3の利用技術](/guideline_architecture)
+ [コーディング規約](/guideline_coding-style)
+ [開発の補助:デバッグ・Tips](/guideline_tips)
+ [コマンドラインインターフェイス]
+ [パフォーマンス](/spec_performance)
+ [実験的実装](/spec_experimental)

### 本体の仕様

+ [ディレクトリ構成](/spec_directory-structure)
+ [機能一覧](https://github.com/EC-CUBE/eccube3-doc/blob/master/feature_list.xls){:target="_blank"}
+ [テーブル・ER図](https://github.com/EC-CUBE/eccube3-doc/tree/master/ER-D){:target="_blank"}
+ [結合試験項目書](https://github.com/EC-CUBE/eccube3-doc/tree/master/IntegrationTest){:target="_blank"}
+ [APIリファレンス](/api-specifications/master/index.html){:target="_blank"}
+ 機能仕様
	- [複数配送](/spec_multi-shipping)
	- [税率設定](/spec_tax)


### Web API仕様

+ [Web API β版 プラグインスタートアップガイド](/api_startup-guide)
+ [Web API 開発指針](/api_policy)
+ [Web API認証(Authorization)ガイド](/api_authorization)

## デザインカスタマイズ

+ [デザインテンプレートの基礎](/design_template)
+ [デザインのフレーム構成](/design_default-frame)
+ [フォームレイアウトの変更](/design_form)
+ [ブロックの利用](/design_block)
+ [例:GoogleAnalyticsタグの設置](/design_analyticsbloc)

## 本体のカスタマイズ

+ [カスタマイズ指針](/customize_policy)
	- [イベントハンドラ]
	- [PurchaseFlow]
+ [例:会員管理へ項目の追加](/customize_example-adminadd)
+ [例:のしオプション追加]

## プラグイン開発

(目次に全部載せる必要ないと思う)

+ [プラグインの導入方法](/plugin_install)
+ [プラグイン導入時のトラブルシューティング](/plugin_troubleshooting)
+ プラグイン機構の仕様
	- [プラグイン仕様書](http://downloads.ec-cube.net/src/manual/v3/plugin.pdf){:target="_blank"}
+ プラグインの開発方法
+ [app/console向けプラグイン](/plugin_console-plugin)
+ プラグインベストプラクティス

+ [オーナーズストアへの公開](http://www.ec-cube.net/plugin/){:target="_blank"}

## Translations

翻訳ガイド

## Cookbook

こんな感じのやつ
http://docs.sylius.org/en/latest/cookbook/index.html

## Testing Guide

ユニットテスト、 Codeception の使い方

## 本体開発に参加する

+ [開発作業全体概要](/collaboration_workflow)
+ [Gitを用いた開発手順](/collaboration_githubflow)
+ [マイグレーションガイド](/collaboration_migration)
+ [外部Componentの利用](/collaboration_component)

## Supporters

EC-CUBEは以下のサポートを受けています。

+ [JetBrains](https://www.jetbrains.com/)  
[![JetBrains](/images/logo_JetBrains_4.png)](https://www.jetbrains.com/){:target="_blank"}  

+ [SAKURA internet](https://www.sakura.ad.jp/)  
[![SAKURA internet](/images/3-1-2line-rgb-whiteback.png)](https://www.sakura.ad.jp/){:target="_blank"}  
