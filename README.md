# sonarqube-template

本プロジェクトは[SonarQube](https://www.sonarqube.org/)の docker-compose テンプレートプロジェクトです。

## Usage

### サーバ起動

```sh
docker-compose up
```

### Web アクセス

`http://localhost:9000/`にアクセス

### Clean ES Data

(挙動が不安定な場合は)`./clean_sonardata.sh`を実行し、docker コンテナの再作成から実行する。

## other

公式ドキュメントを確認すること。
