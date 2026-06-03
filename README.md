# Rails 8 + Tailwind CSS + DaisyUI テンプレート

Rails 8、Tailwind CSS v4、DaisyUI を導入済みのテンプレートです。

新しい Rails アプリを作成する際の初期構築を省略することを目的としています。

## 使用技術

* Ruby
* Rails 8
* Tailwind CSS v4
* DaisyUI
* SQLite3
* Node.js
* mise

## セットアップ手順

### 1. リポジトリをクローン

```bash
git clone <リポジトリURL>
cd <リポジトリ名>
```

### 2. Ruby と Node.js をインストール

`.tool-versions` に記載されたバージョンをインストールします。

```bash
mise install
```

### 3. Gem をインストール

```bash
bundle install
```

### 4. npm パッケージをインストール

```bash
npm install
```

### 5. データベースを作成

```bash
bin/rails db:prepare
```

### 6. アプリケーションを起動

```bash
bin/dev
```

ブラウザで以下にアクセスします。

```text
http://localhost:3000
```

## DaisyUI の動作確認

以下のコードを任意のビューに記述してください。

```erb
<button class="btn btn-primary">
  DaisyUI Test
</button>
```

ボタンがスタイリングされて表示されれば正常に動作しています。

## Tailwind CSS の動作確認

以下のコードを任意のビューに記述してください。

```erb
<h1 class="text-6xl font-bold text-red-500">
  Tailwind OK
</h1>
```

文字が大きく赤色で表示されれば正常です。

## ディレクトリ構成

```text
app/
├── controllers/
├── models/
├── views/
├── helpers/
└── assets/
```

## テンプレートの利用方法

このリポジトリを GitHub の Template Repository として利用できます。

新規プロジェクト作成時は、

1. 「Use this template」をクリック
2. 新しいリポジトリを作成
3. クローンして開発開始

作成したリポジトリをクローン
git clone https://github.com/<ユーザー名>/<リポジトリ名>.git
cd <リポジトリ名>