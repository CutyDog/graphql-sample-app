# README

## references
https://zenn.dev/lilac/books/37bdf5d90b5f9b


* System dependencies
ruby 2.7.4p191
Rails 7.0.4
graphql-rails

* memo
- app/graphql/object_types/*
  - 各テーブルに対応するTypeを定義
- app/graphql/queries/*
  - データ取得クエリをresolveメソッドに定義
- app/graphql/input_types/*
  - mutationの引数の型を定義
- app/graphql/mutations/*
  - データ更新のクエリをresolveメソッドに定義
  - /input_types/* に定義した型を`argument :prams`に指定する
- app/graphql/types/*
  - デフォルトではこのディレクトリ配下にファイルが自動生成される
  - /queries/* にクエリ追加したら、/types/query_type.rb にフィールド追加する
  - /mutations/* にクエリ追加したら、/types/mutation_type.rb にフィールド追加する

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
