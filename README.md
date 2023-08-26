
## ローカルのフォルダをgit管理(リモートリポジトリに追加)する方法
- 以下のコマンドを順に実行する
  - git init
  - git remote add origin git@github.com:diCieL/docker_test.git
  - いつも通りコミットとプッシュを行う。

## よく使うコマンド
docker exec -it sample-db bash
psql -U postgres -d sample_db
docker-compose down

## 参考サイト
- mySQL postgresql コマンド比較
  - https://qiita.com/ka215/items/9557d208ff189a529cb6

- nuxt rails postgre
  - https://blog.cloud-acct.com/posts/u-docker-compose-rails6new/

- postgresql を docker compose する
  - https://qiita.com/ke_suke0215/items/90deba2bf484293000fc

- dockerで立ち上げたpostgresqlを日本語に設定する
  - https://qiita.com/shimizuyuta/items/0e5a3b16c0ce3649a212

- DBの永続化とは
  - https://nishinatoshiharu.com/docker-volume-tutorial/

- postgresの永続化
  - https://qiita.com/snooow/items/04a84193fb6c7076e86f