# my-monitoring-system-2
my-monitoring-system 2版

- いつかやりたい用

```bash
# 構想
ネットワーク
　・cilium: ネットワーク制御
  　- hubble: メトリクス
　・istio: トレース、サービスメッシュ、ネットワーク制御
収集
　・otelcol: ログ、メトリクス、トレース
集積
　・minio: オブジェクトストレージ
　・mimir: メトリクスストレージ
　・loki: ログストレージ
バックエンド
　・tempo: トレース管理
　・prometheus: メトリクス管理、メトリクス
ポータル
　・backstage
クラスタートレース?プロファイリング
　・pixie: トレース?プロファイリング
プロファイリング
　・pyroscope: プロファイル、ebpf
セキュリティ
　・Falco ※暫定
エラー監視
　・sentry
```
