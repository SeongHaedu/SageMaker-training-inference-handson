# SageMaker Training & Inference の advance Hands-on の会場はこちらです🦊

※ 本ハンズオンは SageMaker Training & Inference の basic Hands-on の続きです。

## Hands-on のスコープ
SageMaker Training Job の定義と実行のハンズオン
- ファイルまたはディレクトリをトレーニングインスタンスに持ち込む編
  - 単一のファイルをトレーニングに持ち込む
  - ディレクトリごとトレーニングに持ち込む
  - 複数のディレクトリをトレーニングに持ち込む
- アーティファクトを S3 に転送する編
- ライブラリを追加する編
- ハイパーパラメータをコードの外部から入力する編

SageMaker Inference endpoint の作成と呼び出しのハンズオン
-  リアルタイム推論
-  サーバーレス推論
-  非同期推論
-  バッチ推論

## Hands-on 開始前の事前準備
1. AWS マネジメントコンソールにて、SageMaker Studio または Notebook instance を立ち上げます。
2. JupyterLab を開き、本 repo を clone します。
3. JupyterLab で 1_sagemaker_training_job.ipynb ファイルを、2_pytorch.ipynb ファイルを開いてください。
