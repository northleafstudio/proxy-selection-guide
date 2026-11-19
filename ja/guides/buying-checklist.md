# プロキシプランを買う前の短い確認リスト

このリストは Northleaf Studio が公開しています。Northleaf Studio は [ProxyVendors](https://proxyvendors.com/ja/) も運営しています。同じ運営者による補足資料であり、無関係な第三者による推薦ではありません。事業者の現行の料金ページ、規約、小さな試用に当てて使ってください。対象のサイトでプランが必ず動くという保証はありません。

## 言語

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- **日本語**
- [Português](../../pt/guides/buying-checklist.md)
- [한국어](../../ko/guides/buying-checklist.md)
- [اردو](../../ur/guides/buying-checklist.md)
- [Bahasa Indonesia](../../id/guides/buying-checklist.md)
- [Türkçe](../../tr/guides/buying-checklist.md)
- [العربية](../../ar/guides/buying-checklist.md)
- [Polski](../../pl/guides/buying-checklist.md)
- [Italiano](../../it/guides/buying-checklist.md)
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- [Tiếng Việt](../../vi/guides/buying-checklist.md)
- [Русский](../../ru/guides/buying-checklist.md)

## 1. 作業を書き、その後でネットワークを選ぶ

出口にさせたいことを書きます。長いログイン、地域を指定した公開データ、大量のリクエスト、モバイル事業者でのテストなどです。それを[プロキシの種類](./proxy-types.md)にあるネットワークの種類、つまり住宅、データセンター、ISP、モバイルに対応させます。トップページと料金ページで開始価格や国の数が違う場合は両方を記録し、実際に買う段階にはどちらが当てはまるか尋ねてください。

## 2. セッションの動きを確認する

同じ出口を数分、数時間、契約期間のあいだ保つ必要があるのか、リクエストごとに出口を変えるのかを決めます。スティッキーまたは固定の時間、それが切れる条件、落ちた IP が置き換わるかを確認します。公式文書が二つの保持時間を示すことがあります。事業者が確認するまでは、未確定として扱ってください。

## 3. プロトコルと認証を確認する

HTTPS サイト向けの [HTTP CONNECT](https://proxyvendors.com/ja/glossary/http-connect) を含む HTTP は、[SOCKS5](https://proxyvendors.com/ja/glossary/socks5) と同じではありません。住宅製品には HTTP と HTTPS しか扱わないものがあります。SOCKS5、または SOCKS5 経由の UDP が必要なら、製品とクライアントの両方が対応しているか確認します。入口のホスト、ポート、認証方法を確認します。ユーザー名とパスワード、IP 許可リスト、またはその両方です。CONNECT 中の 407 はプロキシからの応答です。このステータスは Proxy Authentication Required を意味します。プロキシが認証を求めているか、受け取った認証を受け入れなかったということです。トンネルは確立されておらず、対象サイトはそのリクエストを見ていません。

## 4. 実際の費用を足す

見出しの単価だけで判断しないでください。最低購入量、パックの有効期限、超過料金、再試行で無駄になる量、細かい指定の追加料金、消費税、自動チャージや自動更新を記録します。見出しの価格は大量購入の段階のもので、最初に買うパックの価格ではないことがあります。試用にカードが必要で自動チャージが有効になる場合は、始める前に切るかどうかを決めてください。

## 5. 試用、返金、利用条件を読む

試用の量と期間、返金できる期間、利用上限、返金にネットワーク障害の記録が必要かを確認します。本人確認や KYC、銀行や政府サイトなどの禁止区分、固定または専用製品の公正利用の上限も見てください。入手元やコンプライアンスが重要なら、宣伝文だけに頼らず、事業者に文書を求めてください。

## 6. ネットワークを調べ、それから試す

特定の通信事業者が必要なら、[ASN ターゲティング](https://proxyvendors.com/ja/glossary/asn) に対応しているか、使える出口がないときに何が起きるかを確認します。その後、小さな実作業を行います。対象から有効な応答が返るか、セッションが切れるか、地域は正確か、実際に消費したトラフィックはどれだけかです。接続したあとは [IP チェック](https://proxyvendors.com/ja/ip-check) で、公開 IP、組織、ASN を購入した製品と照合し、DNS と WebRTC の経路も重要ならその検査も実行します。

そのあとで、購入量を決めてください。

— Northleaf Studio
