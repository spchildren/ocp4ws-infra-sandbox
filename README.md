# Red Hat OpenShift 4 ワークショップ <br> -インフラ編-

本ハンズオンは，OpenShift4(以降，OCPまたはOCP4)のインフラ編です。
Kubernetesの運用がOperatorを使うとどう変わるのか，どう便利になるのかを体験頂けます。

## 諸連絡
**OCPクラスター接続情報など (Etherpad) ==>**

## タイムテーブル

|Time|Agenda|Content|
|:---:|:---|:---|
|13:00-13:30|受付||
|13:30-14:00|<講義><br>OCP4 & Operator 概要|OCP4<br>Kubernetes運用 <br>Operator - CRD/Controller|
|14:00-14:20|OCP4クラスター接続確認||
|14:20-14:30|<講義><br>Prometheus Operator|Prometheus<br>Prometheus Operator (CRD)|
|14:30-15:10|<ハンズオン><br>アプリ と Operator 連携||
|15:10-15:20|Break||
|15:20-15:50|<講義><br>Operator<br>開発, 運用, エコシステム|OperatorHub<br>Operator Framework<br>|
|15:50-16:30|<ハンズオン><br>Operator 運用|PostgreSQL Operator<br>Operator Lifecycle Manager<br>|
|16:30-17:00|QA, Closing||

## ハンズオン環境および前提
本ハンズオンは，Kubernetesクラスター(OpenShift)の動作環境としてAWSを使用します。今回は構築済です。

OCPクラスターに対するCLI操作をを行う際は，クライアントPCから **ocコマンド** を使って制御します。GUI操作は，クライアントPCのブラウザ(**Chrome/Firefox推奨**)を使用します。

このため以下の準備を事前に済ませておいてください。
- SSH用ツール (※本日は使いません)
- ブラウザ (Google Chrome or Firefox)

## ハンズオン
**Lab1: [アプリケーション と Operator 連携](Lab1)**

**Lab2: [Operator 運用](Lab2)**