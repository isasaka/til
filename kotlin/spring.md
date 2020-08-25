# Spring

## 参考資料

### 公式ドキュメント

- [英語](https://spring.io/)
- [日本語訳](https://spring.pleiades.io/)
  - [Spring Boot を使用する](https://spring.pleiades.io/spring-boot/docs/current/reference/html/using-spring-boot.html)
  - [Docker で Spring Boot 日本語](https://spring.pleiades.io/guides/gs/spring-boot-docker/)
  - [Spring Boot と Kotlin を使用した Web アプリケーションの構築](https://spring.pleiades.io/guides/tutorials/spring-boot-kotlin/)

### 参考サイト

- [ドメイン駆動設計のための Spring の上手な使い方](https://www.slideshare.net/masuda220/spring-82650951)
- [Java と Spring Boot でドメイン駆動開発 〜レイヤーとモジュール分割編〜](https://qiita.com/sei40kr/items/da8e067287151c0a31c6)
  - > 実装知識を含んだレポジトリのインスタンスはどこで初期化するのか
- [ボトムアップドメイン駆動設計](https://nrslib.com/bottomup-ddd/)
- [「実践ドメイン駆動設計」を読んだので、実際にDDDで設計して作ってみた！](https://qiita.com/APPLE4869/items/d210ddc2cb1bfeea9338)
  - 「ユースケース図」「ロバストネス分析」を使った設計
- [JIG](https://github.com/dddjava/jig)
  - バイトコード（classファイル）から一覧やダイアグラムを出力
  - バイトコードが対象なので、JVM言語であれば主要機能は動作する
- [業務でSpring Bootを半年間使ってみて思ったこと](https://engineering.linecorp.com/ja/blog/spring-boot-job-report/)
  - DIの使用例
- [さくっと理解するSpring bootの仕組み](https://www.slideshare.net/OgawaTakeshi/spring-boot-71285225)
  - `Spring` と `Spring Boot` の関係
  - `Spring Boot` が改善する開発プロセス
- [SpringBoot + Kotlin + Docker を使ってみる](https://qiita.com/qphsmt/items/10520fa92c06df022ef7)
- [Spring Bootで始める簡単Webプロジェクト～ひな型の作成からWeb APIの実装まで](https://codezine.jp/article/detail/11380)
- [Groovyを知らない人のためのbuild.gradle読み書き入門](https://qiita.com/opengl-8080/items/a0bb31fb20cb6505188b)
- [Kotlin × Spring Boot で REST API サンプルアプリケーション作ってみた。](https://qiita.com/yusuke_dev/items/79c980ff7002d68f9aa5)

### SpringBoot + Kotlin + Docker を使ってみる

#### 開発環境構築

```bash
$ # gradle
$ brew install gradle
$ gradle -v

Welcome to Gradle 6.6!

Here are the highlights of this release:
 - Experimental build configuration caching
 - Built-in conventions for handling credentials
 - Java compilation supports --release flag

For more details see https://docs.gradle.org/6.6/release-notes.html


------------------------------------------------------------
Gradle 6.6
------------------------------------------------------------

Build time:   2020-08-10 22:06:19 UTC
Revision:     d119144684a0c301aea027b79857815659e431b9

Kotlin:       1.3.72
Groovy:       2.5.12
Ant:          Apache Ant(TM) version 1.10.8 compiled on May 10 2020
JVM:          14.0.1 (Oracle Corporation 14.0.1+14)
OS:           Mac OS X 10.15.6 x86_64

$ # java
$ java -version
openjdk version "14.0.2" 2020-07-14
OpenJDK Runtime Environment (build 14.0.2+12-46)
OpenJDK 64-Bit Server VM (build 14.0.2+12-46, mixed mode, sharing)
$
$ # docker
$ docker -v
/usr/local/bin/gradle
$
```