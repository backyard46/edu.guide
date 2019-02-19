# 新人研修等の教育用サンプルコード

IT系企業の新人研修用サンプルコードの内容について、その背景や狙い、概要について説明します。

## 概要

### 目的
ここで説明するサンプルコードは、ソフトウェア開発を行う企業における新人教育で、ITSS研修ロードマップに沿ったプログラミング実習を行う際に利用されることを想定したものです。ITSSではJavaを想定していますが、ここではMicrosoft .NET Frameworkを利用したプログラミング言語 C#を用いています。

### 対象者
本サンプルコードを用いた研修の対象者は以下のような方です。

- 就職までの間にプログラミング言語に触れたことが無い未経験者。
- 簡単なプログラムやExcel VBAのような言語での業務経験はあるものの、工学部や専門学校などでの専門教育を受けたことが無い方。

---
## 実習とサンプルコードの構成
サンプルコードはそれぞれITSS研修ロードマップのカリキュラムに沿って用いる事を想定しています。カリキュラムとしては別途、講義等で各項目に沿った基礎学習を実施することを想定していますので、それぞれに見合った内容の講義を実施した上で利用してください。
以下ではカリキュラムに沿った講義用の実習課題とサンプルプログラムの対応を説明します。

---
### B121: プログラミングの基礎(1)

#### 実習環境構築と基本的な用法説明
この実習では、Visual Studioのインストールや、基本的な使い方について学びます（2019年2月時点で特に教材なし）。

#### データ型と基本的な演算処理

#### 条件分岐
条件分岐について基礎的な学習を終えたあとの実習用課題です。

- [EDU. Trash Day Check（ゴミの日チェックプログラム）](https://gitlab.com/it_education/edu.-trash-day-check)
  - 課題1: ゴミの日通知プログラム
  - 課題2: ゴミの日通知プログラム（強制通知版）
  - 課題3: 変則的なゴミの日への対応
- [EDU. Score Evaluation（点数評価プログラム）](https://gitlab.com/it_education/edu.-score-evaluation)
  - 課題1: 入力されたスコアの評価
  - 課題2: Enterキーが押された時にも評価する
  - 課題3: エラー回避策の実装（対応方法検索含む）

#### 繰り返し
ループ処理について基礎的な学習を終えたあとの実習用課題です。

- [EDU. Loop and Array Sample（足し算と九九の表）](https://gitlab.com/it_education/edu.-loop-and-array-samples)
  - 課題1: 十個の整数足し算
  - 課題2: 九九の表作成
  - 課題3: 九九の表改造、14x14の表にする
  - 課題4: カンマ区切り数字の足し算

#### クラス
クラスの概念や基本的な使い方についての学習を終えた後の実習用課題です。

- [EDU. Bank Accounts（銀行口座管理プログラム）](https://gitlab.com/it_education/edu.-bank-accounts)
  - 課題1: 銀行口座クラス作成
  - 課題2: 口座操作GUI追加
  - 課題3: 残高照会機能追加
  - 課題4: 複数人口座管理機能追加
  - 課題5: 残高不足対応
  - 課題6: コンストラクター作成
  - 課題7: 引数有りコンストラクターの作成

#### 補足: フォーム間情報連携
ここでは、この後の課題等で発生する可能性があるフォームクラス間での情報連携についてサンプルコードを例示、学びます。

- [EDU. Transfer data between forms（フォーム間情報連携サンプル）](https://gitlab.com/it_education/edu.-transfer-data-between-forms)

#### 継承
継承の基本的な使い方についての学習を終えた後の実習用課題です。

- [EDU. Monster Creator and Battle（モンスター対戦シミュレーター）](https://gitlab.com/it_education/edu.-monster-creator-and-battle)

#### インターフェース

- サンプル作成中（2018講義内容を改変してなんとかする）

#### 例外処理
例外処理の基本的な扱いについて学習を終えた後の実習用課題です。

#### 入出力
ファイルの読み書きについて基本的な学習を終えたあとの実習用課題です。

- [EDU. CSV File Read Sample（CSVファイルの読み込み）](https://gitlab.com/it_education/edu.-csv-file-read-sample)
- [EDU. CSV File Read Sample EX（区切り文字指定CSVファイル読み込み、追加課題）](https://gitlab.com/it_education/edu.-csv-file-read-sample-ex)
- [EDU. Specify File Type（ファイル形式識別）](https://gitlab.com/it_education/edu.-specify-file-type)


---
### B241: セキュリティ基礎

#### 不正アクセス
パスワード入力をソフトウェアで突破するサンプルを完成させる実習課題です。ツールさえそろえば、4桁数値の暗証番号がどれくらいで突破できるかを体感します。

- [EDU. Bruteforce Attacker Sample（ブルートフォース攻撃）](https://gitlab.com/it_education/edu.-bruteforce-attacker-sample)

#### ウィルス
簡単なマクロウィルスの例として、PowerPointファイルを開くとメッセージが表示されるサンプルを作り、その容易性と、Microsoft Office側の対応について体験します。

- サンプル作成中

#### セキュアプログラミング
データベースからデータを取得するプログラムの検索条件に不正な文字列を入れることで、SQLインジェクションを起こしてデータの改竄が可能であることを体験します。「例外処理」で使ったプログラムをベースにしています。

- [EDU. Monster Data Viewer（ポケモンデータ閲覧プログラム）](https://gitlab.com/it_education/edu.-monster-data-viewer)

#### 暗号技術、署名、PKI、セキュリティプロトコル
ハッシュ処理を応用した電子署名の作成ツールを使い、改竄有無の確認を体験します。

- [EDU. Digital Sign（電子署名作成プログラム）](https://gitlab.com/it_education/edu.-digital-sign)

