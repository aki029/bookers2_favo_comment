# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Bookers2
ユーザー認証機能、閲覧機能、投稿機能、編集機能があります。

## Details
バリデーションはbefore_actionを用いています。
いいね後の赤色と、カーソルを合わせたときの色の変化のために、追加でstylesheet_link_tagを設定しapplication.cssを読み込んでいます。

### Changed
configure_permitted_parametersの内容を変更しました。
deviseのviewファイルをform_withヘルパーに変更しました。