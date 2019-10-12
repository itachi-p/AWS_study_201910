##### 書籍「さわって学ぶクラウドインフラ Amazon Web Service 基礎からのネットワーク＆サーバー構築」（2017改訂版）に沿って進める

###### Chapter1〜9、及びAppendix A,Bの流れに従い、AWS EC2上にWordpressサーバを構築し、ブログを開設する。

上記の一連の作業を通し、（**一旦Docker他を排した最小構成で**）以下についての理解を深める。
- ネットワーク構築
- サーバー構築
- HTTTP/HTTPS
- リクエスト/レスポンス
- TCP/IP (/UDP)
- ファイアウォール
- サブネットマスク
- 名前解決
- NATゲートウェイ

- 書籍に従い、WebサーバとしてはNginxではなくApacheを使用する。
- DBはMySQL(5.7)

### 目次

1. システム構築をインフラから始めるには
2. ネットワークを構築する
3. サーバーを構築する
4. Webサーバーソフトをインストールする
5. HTTPの動きを確認する
6. プライベートサブネットを構築する
7. NATを構築する
8. DBを用いたブログシステムの構築
9. TCP/IPによる通信の仕組みを理解する
10. Appendix-A パケットキャプチャで通信を覗いてみる
11. Appendix-B ネットワークの管理・運用とトラブルシューティング

##### ネットワーク関連コマンド
`ping`, `traceroute`, `telnet`, `nslookup`, `dig`
