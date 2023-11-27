# 概要
redirect_slashes=Falseオプションが機能するかどうかを確認する最小限のFastAPIアプリケーション

# 環境
- fastapi 0.104.1
- starlette 0.27.0
- uvicorn 0.24.0.post1

# インストール
- `git clone https://github.com/KamijoKeiko/minimal_fastapi_for_trailing_slash.git`
- `cd minimumFastApiProject`
- `pip install fastapi==0.104.1 uvicorn`

# 起動
`uvicorn main:app --host 127.0.0.1 --port 7000`

# 参考
- FastAPIのプルリクエスト[#3432](https://github.com/tiangolo/fastapi/pull/3432)（redirect_slashesオプションに関する変更）
- https://github.com/tiangolo/fastapi/pull/5392 (参考の参考)
- FastAPI公式ドキュメントの[FastAPI](https://fastapi.tiangolo.com/ja/reference/fastapi/?h=redirect_slashes#fastapi.FastAPI--example)（redirect_slashesの使い方）
- [FastAPIリリースノート](https://fastapi.tiangolo.com/release-notes/)
