# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...

---

環境構築方法 🛠

1.リポジトリを GitHub からローカル環境にクローンして、フォルダに入ります。
bash git clone https://github.com/username/rails-docker.git cd rails-docker

2.Docker コンテナをビルドして起動します。
docker compose up --build

3.データベースの作成とマイグレーションをします（別ターミナル）。
docker compose exec web rails db:create
docker compose exec web rails db:migrate

4.ブラウザで以下にアクセスして、動作確認をします。
http://localhost:3000

5.Rails アプリの開発環境が整いました。

---
