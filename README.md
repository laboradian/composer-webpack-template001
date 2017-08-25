Composerとwebpackを使った雛形プロジェクト001
===================

Requirements
----------

- PHP 7


Webサーバにアップロードするディレクトリ・ファイル
----------

```
public/   ・・・ドキュメントルート
src-php/  ・・・PHPのソースファイル
vendor/   ・・・PHPの依存パッケージ（Apacheの場合は.htaccessを作成する必要がある）
.htaccess ・・・Apacheの場合に必要（nginxの場合は同様の設定が必要）
.env      ・・・ Webサーバの環境に合わせて手動で作成する
```

- 上記の `.htaccess` はアクセス制御に使用することを目的としている。


参考
-------

- [PHP: PDO - Manual](http://php.net/manual/ja/book.pdo.php)
- [PHPのセキュリティ対策 – ラボラジアン](https://laboradian.com/sec-php/#3_SQL)

