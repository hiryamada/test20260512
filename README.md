# test20260512

## 概要
FastAPI を使って `Hello World` を返すシンプルな API を実装したプロジェクトです。

## ディレクトリ構成
- `src/`: API のソースコード
- `tests/`: pytest による単体テスト

## セットアップ
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## 実行方法
以下のコマンドで API サーバーを起動します。

```bash
uvicorn src.main:app --reload
```

起動後、`http://127.0.0.1:8000/` にアクセスすると以下の JSON が返ります。

```json
{"message": "Hello World"}
```

## テスト方法
以下のコマンドで単体テストを実行します。

```bash
pytest
```
