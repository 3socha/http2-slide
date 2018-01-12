# HTTP/2 の話
## f TECH MEETUP #1 LT
## 2018/1/13
## so

---

## `$ whoami`

![so](img/so.png)

* so (野田 奏 @ Fenrir Inc, [@3socha](https://twitter.com/3socha))
* インフラエンジニア (AWS/Azure)
* シェル芸

---

## 何故今更 HTTP/2

- 2012/12 SPDY を元に IETF ワーキンググループでドラフト公開
- 2015/02 IETF で仕様として承認
- 2015/05 RFC 7540 として正式に文書化

>>>

- 2015/09 Nginx 1.9.5 で HTTP/2 サポート
- 2015/10 Apache 2.4.17 で HTTP/2 サポート (mod_http2)

>>>

- 2016/04 Let's Encrypt が正式サービス化
- (HTTP/2 は TLS がほぼ必須)

>>>

- 2016/01 ACM がリリース、AWS で使える TLS 証明書の発行が可能に
- 2016/09 AWS CloudFront が HTTP/2 対応
- 2016/12 AWS で HTTP/2 対応の L7 ロードバランサ (ALB) 発表
- 2017/12 ACM で DNS 検証による TLS 証明書発行が可能に

>>>

## HTTP/2 が AWS で使いやすくなったので！

---

## HTTP/2 概要

---

## HTTP/2 で何が嬉しいのか

---

## Reverse Proxy と HTTP/2

---

## まとめ

---

## 参考

---

## おまけ

- HTTP/2 の日本語情報が多くて嬉しい
- 仕様策定段階で、日本の HTTP/2 コミュニティの活動が活発で、様々な実装が作られた
- RFC 7540 の末尾に謝辞が書かれてる
