# 接続で TLS を使う

接続の設定に利用される最初のパケットが到着するとすぐに、通信の開始者はセキュアレイヤーにおけるハンドシェイクのセットアップを開始する crypto フレームを送信します。

セキュリティレイヤーは TLS 1.3 セキュリティが用いられています。

TLS を使用せずに QUIC コネクションを行う方法はありません。プロトコルの硬直化を防ぐためにQUIC はプロトコルレベルでミドルボックスによる通信の改ざんが難しくなるように設計されています。
