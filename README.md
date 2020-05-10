# インストール
TODO: 以下のコマンドを叩くだけでClientがローカルマシンに作成されるようにしたい
```bash
docker run -p 8926:8926 -v $(pwd)/dbflute_<プロジェクト名>:/app/dbflute__<プロジェクト名> dbflute/dbflute-intro:latest
```