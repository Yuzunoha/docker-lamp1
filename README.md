# docker-lamp1


## 使い方
- 起動
  ```
  docker-compose up -d --build
  ```
- mysqlコンテナにログイン
  ```
  docker-compose exec mysql bash
  ```


## メモ
- htdocsに生徒のリポジトリをcloneする
- mysqlvolumeに後述のsqlファイルを格納してmysqlコンテナに渡す
- 生徒にphpmyadminでsqlファイルを出力してリポジトリに含めてもらう
  - 出力の際カスタムオプションでDB生成から出力してもらう
- php.iniも提供を受けた方がよいかも知れない


## 参考
- [PHP+MySQL+ApacheでさくっとDocker開発立ち上げる][link1]


[link1]:https://qiita.com/wakanayoshizawa/items/9ed771842a4e4b05efb5