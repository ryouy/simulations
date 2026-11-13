# Simulations

Google Colabで実行するPythonシミュレーションのコレクションです。各シミュレーションを独立したディレクトリで管理し、ノートブック・説明・結果をまとめます。

## Simulations

| Simulation | Description | Notebook |
| --- | --- | --- |
| [Infection Spread](simulations/infection-spread/README.md) | 2D particle infection model | [Open in Colab](https://colab.research.google.com/github/ryouy/simulations/blob/main/simulations/infection-spread/infection_simulation.ipynb) |

## Structure

```text
simulations/
└── infection-spread/
    ├── README.md
    ├── infection_simulation.ipynb
    └── outputs/                 # Generated after running Colab
        ├── infection.gif
        ├── infection_curve.png
        ├── infection_counts.csv
        └── settings.json
```

新しいシミュレーションは `simulations/<simulation-name>/` に追加します。各ディレクトリのREADMEに目的・Colabリンク・GIFプレビュー・出力一覧を記載します。

## GitHub output upload

Colab Secretsに `GITHUB_TOKEN` を登録し、対象リポジトリの **Contents: Read and write** 権限を与えてください。各ノートブックのアップロードセルで結果を対応する `outputs/` に保存します。READMEの相対GIFリンクにより、アップロード後はGitHub上に最新アニメーションが表示されます。トークンをコードやコミットに含めないでください。
