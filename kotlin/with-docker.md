# Docker上で動かす

## [Docker イメージで Amazon Corretto 8 の使用を開始する](https://docs.aws.amazon.com/ja_jp/corretto/latest/corretto-8-ug/docker-install.html)を参考に「Amazon Corretto 11」を動かしてみる

  ```bash
  $ docker container run -it amazoncorretto:11
  bash-4.2# java -version
  openjdk version "11.0.8" 2020-07-14 LTS
  OpenJDK Runtime Environment Corretto-11.0.8.10.1   (build 11.0.8+10-LTS)
  OpenJDK 64-Bit Server VM Corretto-11.0.8.10.1   (build 11.0.8+10-LTS, mixed mode)
  bash-4.2#
  ```