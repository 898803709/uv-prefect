# uv-prefect

## install uv
```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

## dictoryを初期化

```
uv init
```

## ライブライをインストール

```
uv add ruff
```

## uvでpythonをinstall

```
uv python install 3.12
```

## 既存のpythonバージョンを確認する

```
uv python list
```

## pythonのバージョン変更
```
 uv python pin 3.12.6 
```

## run a command 
```
uv run prefect server start
```

## サーバーを設定する
```
uv run prefect config set PREFECT_API_URL="http://127.0.0.1:4200/api"
```