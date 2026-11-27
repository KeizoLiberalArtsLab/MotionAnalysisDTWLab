# Motion Analysis DTW Lab powered by Visual3D

[アプリを開く](https://keizoliberalartslab.github.io/MotionAnalysisDTWLab/)

Visual3DのHDF5ファイルから動作波形を読み込み、時間正規化した平均波形をDTWで比較するブラウザアプリです。日本語・English・Italianoに対応しています。

ログイン・APIキー・R・Pythonのインストールは不要です。利用者が選んだ解析ファイルはブラウザ内で処理し、サーバーへ送信しません。

## 操作
1. 基準Aと比較BのVisual3D .h5ファイルを選択します。
2. 試行、信号・成分、EVENT区間、採用周期を選択します。
3. DTWを実行し、波形・コスト・相関を確認します。
4. 必要に応じてCSVと解析設定JSONを保存します。

## 配布物
バージョン1.3.3の単一HTML配布版です。研究データ・元のRコード・開発用ファイルは含めていません。NIST h5wasmのライセンスはLICENSE-h5wasm.txtとHTML内に保持しています。
