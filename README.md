# PHP.grammer

PHP の基礎文法を学習するための練習用リポジトリです。

## 概要

制御構文や配列操作、文字列処理など、PHP の基本文法を1ファイルずつ試しながら学んだサンプル集です。あわせて、学んだ文法を使った簡易的な血圧記録アプリの練習実装も含まれています。

## 内容

### 制御構文

- `if1.php` / `if2.php` / `if3.php` — 条件分岐
- `for1.php` 〜 `for4.php` — for 文
- `while1.php` / `while2.php` — while 文
- `foreach.php` / `foreach2.php` — foreach 文

### 配列

- `array1.php` / `array2.php` — 配列の基本操作
- `array_splice.php` — 配列の切り出し・置換

### 文字列・関数

- `str1.php` / `str2.php` — 文字列操作
- `func2.php` — 関数の定義・利用
- `hikaku1.php` — 比較演算
- `htmlspecialchars.php` — HTMLエスケープ処理
- `mktime.php` — 日時操作

### 簡易アプリ

- **血圧記録アプリ(作成中)**
  - 閲覧ページ — 日付・最高血圧・最低血圧・脈拍を一覧表示するテーブル(PHPでDBから出力する想定、現状は未実装)
  - `addform.html`(追加フォーム)へのリンクはあるが、ファイル自体は未作成
- `bbs_simple.php` — 簡易掲示板
- `omikuzi.php` — おみくじプログラム

## 動作環境

PHP が実行できる環境(ローカルサーバーや XAMPP など)で各ファイルを直接実行して動作確認できます。

```bash
php -S localhost:8000
```

## ライセンス

特に指定なし
