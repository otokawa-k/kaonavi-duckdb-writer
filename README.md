# Kaonavi DuckDB Writer

## 概要
カオナビのデータをDuckDBに書き込むためのPythonスクリプトです。
[Kaonavi API Executor](https://github.com/otokawa-k/kaonavi-api-executor.git)を使用して、カオナビのAPIからデータを取得し、DuckDBに書き込みます。

## Kaonavi API Executorのインストール
1. GitHub[リリースページ](https://github.com/otokawa-k/kaonavi-api-executor/releases)から最新の.whlファイルをダウンロード

2. ダウンロードしたパッケージのインストール
    ```bash
    uv pip install kaonavi_api_executor-<version>-py3-none-any.whl
    ```

## License
This project is licensed under the [MIT License](./LICENSE).
