### nrpeのv2.12ではアクセス許可設定がCIDR表記(xxx.xxx.xxx.xxx/24)では接続できないという問い合わせの調査に使用したリポジトリです。

v2.12とv2.13のソースコードを比較してます。時に使用したリポジトリです。
```
https://github.com/daihiraoka/nrpe/compare/nrpe-2-12...master
```

NRPEのバージョンがv2.12の場合、CIDR表記が実装されていません。次のバージョンのv2.13からCIDR表記は実装されています。
