# Infection Spread

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryouy/simulations/blob/main/simulations/infection-spread/infection_simulation.ipynb)

2次元平面で球がランダムに移動し、赤い球との接触で感染が広がるシミュレーションです。初期状態では1個が赤、残りは白です。

## Animation

![Infection simulation](outputs/infection.gif)

GIFはColabの最後のセルでGitHubにアップロードすると、このREADMEに自動表示されます。**初回実行前は画像が表示されません。** 再実行時は同じパスのGIFを更新します。

## Outputs

- `outputs/infection.gif` — アニメーション
- `outputs/infection_curve.png` — 感染数の推移
- `outputs/infection_counts.csv` — 時系列データ
- `outputs/settings.json` — 実行設定

## Run

Colabでノートブックを開き、全セルを順番に実行します。GitHubに出力する場合はColab Secretsの `GITHUB_TOKEN` に、このリポジトリのContents読み書き権限を付与してください。MP4は生成しません。

注：衝突は各ステップ終了時の重なりで判定します。移動中のすり抜けは検出しません。
