﻿---
lab:
    title: 'Azure バッチ処理参照アーキテクチャ'
    module: 'モジュール 2: Azure バッチ処理参照アーキテクチャ'
---

# DP 201 - Azure Data プラットフォーム ソリューションの設計。
# ラボ 2 - Azure バッチ処理参照アーキテクチャ。

**推定時間**：60 分

**前提条件**：このラボのケース スタディを確認済みであること。

**ラボ ファイル**：このラボのファイル は_Allfiles\Labfiles\Starter\DP-201.2_フォルダにあります。

## ラボの概要

学生達はケース スタディを利用して、Lambda アーキテクチャに関連するビジネス要件と技術要件をバッチ モードの観点から特定します。次に、学生は Enterprise BI ソリューションを設計し、アーキテクチャに自動化を追加します。最後に、学生達はこのようなソリューションをサポートするのに必要なデータ ストアに焦点を当てた AI アーキテクチャを設計してみます 

## ラボの目標
  
このモジュールを終了した後、次のことができるようになります：

1. Azure で Enterprise BI ソリューションを設計する
2. Azure で Enterprise BI ソリューションを自動化する
3. Azure でエンタープライズ グレードの会話ボットを構築する

## シナリオ
  
あなたはアドベンチャーワークスのシニアデータエンジニアです。データのバッチ モード処理を対応するソリューションを構築、設計します。ソリューション アーキテクチャは、すべてのビジネス要件の全体像を考慮し、提案を Word ドキュメントに表示することをお勧めします。

まず、AdventureWorks 要件のどの側面が Lambda アーキテクチャのバッチ モード処理に適合するかを定義します。次に、Azure で Enterprise BI ソリューションのアーキテクチャを提供し、ソリューションを自動化する方法を考えます。AI アーキテクチャの最初のパスも設計します。

このラボの最後には、次の操作が行われます。

1. Azure で Enterprise BI ソリューションを設計する
2. Azure で Enterprise BI ソリューションを自動化する
3. Azure でエンタープライズ グレードの会話ボットを構築する

>**注**：このラボは 2 つの部分に分かれています。これはグループして質問に答えるパート 1 です。各演習のタイミングは、グループの裁量に任せます。ラボ全体は 60 分以内に完了する必要があります。第 2 部分では、講師がラボに関する学習と調査結果についてグループとディスカッションを行います。

>**リソース**：このラボのコース ケース スタディの使用に加えて、[マイクロソフト ドキュメント](https://docs.microsoft.com) [Azure リファレンス アーキテクチャ サイト](https://docs.microsoft.com/ja-jp/azure/architecture/reference-architectures/)および [マイクロソフト カスタマー ストーリー サイト](https://customers.microsoft.com/)などのリソースを使用して、このラボの質問回答の通知に役立ちます。 

## 演習 1：Azure で Enterprise BI ソリューションを設計する

**グループ演習**
  
この演習の主なタスクは次のとおりです。

1. ケース スタディから、AdventureWorks の Enterprise BI ソリューションでデータのバッチ モード処理の一部を形成する要件を特定します。

1. AdventureWorks の Enterprise BI ソリューションを反映した高レベルのアーキテクチャを構築します。

### タスク 1：AdventureWorks のバッチ モード処理要件の一覧表示

1. マシンから **Microsoft Wor** を起動し、ファイル **DP-201-Lab02_Ex01_Ta01.docx** を **Allfiles\Labfiles\Starter\DP-201.2** フォルダから開きます。

1. グループとして、AdventureWorks の Enterprise BI ソリューションの一部となる要件について **15 分間** 説明し、リストを作成します。ケーススタディから証拠を提供する必要があります。

> **結果**：この演習を完了したら、AdventureWorks のセキュリティ要件の表を示す Microsoft Word ドキュメントを作成しました。

### タスク 2：AdventureWorks の Enterprise BI ソリューションを反映した高レベルのアーキテクチャを構築します。

1. マシンから **Microsoft Wor** を起動し、ファイル **DP-201-Lab01_Ex01_Ta02.docx** を **Allfiles\Labfiles\Starter\DP-201.2** フォルダから開きます。
 
1. グループとして、AdventureWorks の Enterprise BI ソリューションの一部となるアーキテクチャについて **20 分間** 議論し、図示します。アイコン フォルダでの png ファイルを使用して、アーキテクチャを構築できます。

> **結果**：この演習を完了したら、AdventureWorks の Enterprise BI ソリューションの一部を形成するアーキテクチャを作成しました。

## 演習 2：Azure で Enterprise BI ソリューションを自動化する

**グループ演習**
  
この演習の主なタスクは次のとおりです。

1. AdventureWorks で Enterprise BI ソリューションの自動化を含めるように、高レベルのアーキテクチャを修正します。

### タスク 1：AdventureWorks で Enterprise BI ソリューションの自動化を含めるように、高レベルのアーキテクチャを修正します。

1. マシンから **Microsoft Wor** を起動し、ファイル **DP-201-Lab01_Ex02_Ta01.docx** を **Allfiles\Labfiles\Starter\DP-201.2** フォルダから開きます。ドキュメントを読み、例を確認します。

1. グループとして、ドキュメント **DP-201-Lab01_Ex01_Ta02.docx** の AdventureWorks の Enterpris BI ソリューションの一部として定義したアーキテクチャを **15 分間** 確認します。データ ファクトリによって自動化されるワークフローに [Data Factory] アイコンを追加します。アイコン フォルダでの png ファイルを使用して、アーキテクチャを構築できます。

> **結果**：この演習を完了したら、AdventureWorks に Enterprise BI ソリューションの自動化を含めたアーキテクチャを修正しました。

## 演習 3：Azure での会話型ボット ソリューション

**グループ演習**
  
この演習の主なタスクは次のとおりです。

1. AdventureWorks で会話型ボット ソリューションの自動化を含めるように、高レベルのアーキテクチャを修正します。

### タスク 1：Azure でエンタープライズ グレードの会話ボットを構築する

1. マシンから **Microsoft Wor** を起動し、ファイル **DP-201-Lab01_Ex03_Ta01.docx** を **Allfiles\Labfiles\Starter\DP-201.2** フォルダから開きます。ドキュメントを読み、例を確認します。

1. グループとして、AdventureWorks の Enterprise グレードの会話型ボットの一部を形成するアーキテクチャについて、 **10 分間** 議論し、図示します。アイコン フォルダでの png ファイルを使用して、アーキテクチャを構築できます。

> **ヒント**：ボットの会話を扱う単純なアーキテクチャのみが必要です。

> **結果**：この演習を完了したら、Azure に Enterprise グレードの会話型ボットを含めたアーキテクチャを作成しました。

## ラボ レビュー

約 60 分後、インストラクターがこの演習の近くに集めます。各グループの調査結果について話し合います。