# Curriculum Vitae
日本語版は[こちら](./README.md)。

## My Information

|SNS etc.|links|
|---|-----|
|Facebook|[Toshihiro Tamura](https://www.facebook.com/toshihiro.tamura.75)|
|LinkedIn|[Toshihiro Tamura](https://www.linkedin.com/in/toshihiro-tamura-75743914a)|
|Qiita|[neriudon](https://qiita.com/neriudon)|
|GitHub|[neriudon](https://github.com/neriudon)|
|Blog|[neriudon workshop](http://neriudon.blogspot.com/)|

## Skills
### Languages
#### Programing Languages
- Java
  - 1.4 ~ 8
    - simurations, data mining, web applications, Android applications, embedded applications to MFP and etc.
- Groovy
  - mainly using for Spock which is testing library
- C
  - just studying at Univ. and teach it to the students as a TA
- HTML
- CSS
  - beginner level
- JSON
  - design and implement REST API, using in programs by Jackson library
- XML
  - using in programs by JAXB and communicate with SOAP protocol
- Kotlin
  - now studying  

#### Communication
- Japanese
  - native
- English
  - easy conversation
  - read documents

### Frameworks
- TERASOLUNA Server Framework for Java (5.x)
  - Spring Framework
    - Spring MVC
    - Spring Security
  - and frameworks supported by TERASOLUNA
- Spring Integration
  - http
  - tcp

### Others
- OS
  - Windows
    - XP ~ 10
      - 普段から利用している。
  - Mac OS
    - 5年程度使用していた。
  - Linux
    - 資料を見ながら環境構築ができる。
- Code Management
  - Git
    - GitHub
    - GitLab
    - GitBucket
    - Tools
      - Source Tree
    - ブランチ戦略
      - GitHub Flow
      - Git Flow
  - Subversion
- Task Management
  - Redmine
- 品質管理
  - SonarCube
- CI
  - Jenkins
- Build tools
  - Maven
  - Gradle
- Text Editor
  - Atom
  - Sublime Text3
  - Sakura Editor
- Markup Languages
  - Markdown
  - AsciiDoc
- IDE
  - Eclipse
  - STS
  - NetBeans
- Database
  - H2
  - MySQL
  - SQLite
  - PostgreSQL
  - Oracle
- O/R Mapper
  - MyBatis3
- GUI
  - JavaFX
- AP Servers
  - Tomcat
    - 8.0~
  - JBoss
    - EAP6.x, EAP7.x
  - Wildfly
    - 10
  - WebLogic
    - 12
- Office
  - Word
  - Excel
  - Power Point
  - Visio
- 開発手順
  - ウォーターフォール
  - スクラム（２週間のスプリントを３ヶ月間）

## 強み
- 自分が面白そうと感じたことに関しては行動力があります。
- これまでのバックエンドの経験を活かします！

## 関心があるもの
- Chat Bot(Twitter 4j + Google Apps Engineでbot運用経験あり)
- FinTech

## 資格
- 基本情報技術者
- アロマテラピー２級

## 職務経歴
### 平成２１年　４月～平成２５年１０月：学校法人H（アルバイト）
#### TA（Teach Assistant）
JavaやC言語によるプログラミング演習、Webアプリケーション、Androidアプリケーション開発やデータマイニングなど様々な講義の資料作成や、講義内での学生サポート、出席管理、講義の代行などをおこなった。

### 平成２４年　９月～平成２５年１１月：株式会社A（アルバイト）
#### アプリ開発及び市場調査
phpによるSNSサイトの構築、Android向けのライブラリ・SNSアプリ開発の他、流行のブラウザゲームやスマートフォン向けアプリの仕様や特徴、課金要素等をレポートにまとめて報告した。

### 平成２７年　１月～平成２７年９月：株式会社J
#### カスタマーサポート
営業先リストの作成、書類整理、お客様からの問い合わせメールの対応をおこなった（非技術職）。

### 平成２７年　９月～平成２７年１２月：株式会社H
#### サイト作成及びスマートフォンアプリ開発
HTMLやCSS、Bootstrapを使った自社サイトのコーディング、Ruby on Railsによる自社の求人サービスの運用、Android SDKを使って建設事業者向けの足場点検アプリ`ASSET 足場安心簡単チェック`を開発した。
アプリ開発では、自分を含め2名で担当し、タスクをRedmineで管理し、コミュニケーションツールにはSlackを使っていた。
納期が短く、Androidアプリ開発に関する知識が少なかったため、テストを十分にできなかったが、なんとかリリースすることができた。

### 平成２８年　３月～　：N株式会社
1ヶ月の研修期間の後、株式会社Nの協力会社として案件に参画。

#### 研修（平成２８年　３月）
上司が常駐しているN社でTERASOLUNAの研修を受けた。
TERASOLUNAは、N社が提供するSpringを中心としたオープンソースソフトウェアを組み合わせたフレームワークで、開発に必要なライブラリの設定が予めされている、3つのレイヤで構成されているため依存関係が分かりやすい等の特徴がある。
研修ではまずガイドラインを読んで概要について学び、チュートリアルを参考に簡単なTodoアプリケーションを作成した。その後、レビューを受けながら入力チェックやアカウント管理等の機能を追加した。

#### 某求人サイトのシステム更改案件（平成２８年　４月～平成２８年　１０月）
古いバージョンのJavaで実装されていて、かつDBが複数の求人サイトで共有されているR社のシステムを
- Java 8ベースの実装にリプレース
- 共有されたDBをサービスごとに分離
- DBアクセスをSpring BootをもとにAPI化する

案件。以下のタスクをおこなった。

##### 応募APIのテストとID取得のAPI作成
Spring Bootを使ってAPI化された応募処理のテストコードをGroovyで書かれたテストライブラリSpockで作成し、応募内容がDBに反映されているか、不正な値を入力したときに想定しているエラーが起こるか検証した。
また応募時に必要なIDを採番するAPIの実装とテストもおこなった。

##### 効果情報参照APIの作成
掲載されている求人のPV数や応募数を集計するAPIの設計書を作成し、それをもとにSpring Bootで実装し、Spockで単体テスト・内部結合テスト・外部結合テストコードを作成し検証した。

##### DBアクセスAPIの単体テストとサイト側の改修
Spring Bootを使ってAPI化されたDBアクセスのテストコードをSpockで作成し検証した。4月からのテストコードを書いていた経験を生かし、工期は短かったものの依頼された分のテストを実施できた。

##### DB分離の結合テストの障害対応
結合テストで発見されたバグが、どこで起きたのかをログから解析し、API側とサイト側どちらに原因があるのかを判定し、サイト側に原因があればコードの改修をおこなった。

##### DB分離の強化テスト実施
システム間テストで漏れていた項目のテストを実施した。改修をおこなった部分が既存と同じ挙動になるかの比較を慎重におこない、リリース前に致命的なバグを発見することができた。

#### TERASOLUNAの保守案件（平成２８年　１１月～平成２９年　７月）
TERASOLUNA 5.3.0.RELEASEをリリースする案件。以下のタスクをおこなった。

##### Spring Frameworkやその他のOSSのバージョンアップに伴う動作検証
ベースとなっているSpring Frameworkのバージョンを4.2.xから4.3.xへ。また、その他OSSのバージョンを上げることによりガイドラインで記述している内容と動作が変わっていないか、既存の機能テストで問題ないかと調査した。
動作検証では、自分でAPサーバ、DBサーバ、メールサーバ、JMSサーバのVMを構築して、Jenkinsを使ってテストのビルドをした。
使用したサーバは以下の通り。

|種類|サーバ名|
|---|--------|
|APサーバ|Tomcat, JBoss, WebLogic, WebSphere|
|DBサーバ|H2, PostgreSQL, Oracle, DB2|
|メールサーバ|Postfix + Dovecot|
|JMSサーバ|Apache MQ, WebSphere MQ|

この中でも、特にJBossの動作検証を任され、モジュールの依存関係やJBoss EAP6.xとJBoss EAP 7.xの動作の違いについて力を入れ、[JBoss EAP 7を利用する際の注意点](https://github.com/terasolunaorg/terasoluna-gfw/wiki/JBoss7_ja)を執筆した。

##### 既存の機能テストの改修
平成２９年３月にTERASOLUNA 5.3.0.RELEASEをリリースしたあとは、既存の機能テストでタイミングによって失敗するようなテストケースの改修をおこなった。
その際、どのような状況でテストが失敗するのか、またどのように改善すれば必ず成功するようにできるかを調査し、任されたテストケースのタイミング問題を解決しただけでなく、テストの実行時間の短縮も実現できた。

#### 金融関連の改修案件（平成２９年　７月～現在）
##### Spring IntegrationによるPOC
現行のC++で実装された金融関連のシステムを、Javaに改修するにあたり、どのような課題があるか調査するために約3カ月に渡ってPOCを実施した。POCでは、２週間毎に目的を設定したスクラム開発をおこなった。フレームワークとしてTERASOLUNA 5.3.0.RELEASEとSpring Integrationを使用し、主にTCP通信の処理に力を入れた。最後には、TERASOLUNA 5.3.0.RELEASEとSpring Integrationの機能で実現できるかどうか、実現できない場合はどのような作りこみが必要になるかを発表した。

##### サンプル開発の設計
改修にどの程度のコストがかかるかを調査するために、現行のシステムの一部をサンプルとして取り上げ、外部システムとの連携に必要な入出力などの基本設計から、データ構造、プロパティ値、マスタデータなどの詳細設計まで実施した。

##### AP基盤として部品作成
サンプル開発に必要な機能で業務に依存しないもの（入力チェック・ログ出力・例外ハンドリングなど）を実装した。ただ実装するだけでなく、品質管理のためにSocarCubeを使い、コードの改善・カバレッジの向上を続けた。

##### コードレビュー
サンプルの開発者のコードが設計通りに実装されているかをレビューし、必要に応じて設計書へフィードバックを実施した。

## 特記事項
就労にあたり、いくつか条件があります。詳しくはLinkedInでお問い合わせください。
