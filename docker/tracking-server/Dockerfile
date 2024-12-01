FROM python:3.9-slim

WORKDIR /mlapp
# 必要なライブラリをインストール
RUN pip install --no-cache-dir mlflow

# ポート5001を公開
EXPOSE 5001

# MLflowサーバーを起動
ENTRYPOINT ["mlflow", "server", "--host", "0.0.0.0", "--port", "5000"]

