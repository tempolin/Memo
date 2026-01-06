# ペットボトル認識Webアプリ 要件

## ゴール
- ブラウザ上で動作
- 端末内で完結（映像を外部送信しない）
- ペットボトル（bottle）を検出

## 機能
- ボタン押下でカメラ開始
- 開始/終了を同一ボタンでトグル
- 終了時にカメラを解放（全track停止）
- 背面カメラ優先
- 検出結果を枠＋スコア表示

## 非機能
- HTTPS 前提
- 軽量（低解像度＋推論間隔制御）

## 対応環境
- iOS Safari（Chrome等も同等）
- Android Chrome / Firefox
- PC Chrome / Edge / Firefox
- Meta Quest Browser
