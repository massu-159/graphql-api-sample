# graphql-api-sample
GraphQLとApollo-serverを学習したアウトプットサンプル。

REST-APIとの違いを理解。(単一のエンドポイント、型定義、...)

Apolloserver, ApolloClient, ...

urlはこちら
https://github.com/massu-159/graphql-api-sample

GraphQL公式は[こちら](https://graphql.org/)

## 目次
1. 環境構築
2. アプリケーションの仕様

## 1. 環境構築

`backend`と`frontend`でそれぞれのディレクトリで環境構築

### 1-1. ライブラリ インストール

```
npm install

または

yarn
```

### 1-2. アプリケーション実行

```
npm run dev

または

yarn dev
```

## 2. アプリケーションの仕様

### 2-1. 仕様
- GraphQL
  - data一覧表示

### 2-2. 構成技術
- front
  - react : 18.2.0
  - react-dom : 18.2.0
  - @apollo/client : 3.7.1
  - @apollo/react-hooks : 4.0.0
  - apollo-boost : 0.4.9
  - graphql : 15.8.0

- back (dev)
  - apollo-server : 3.11.1
  - graphql : 16.6.0