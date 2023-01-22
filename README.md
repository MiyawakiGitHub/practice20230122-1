Spring boot + Vue.js + MySql + VS Code + Docker で開発環境を構築する
https://qiita.com/PoKoPoKoTa2ry/items/2f9b54518b8158809192

Vue CLIでプロジェクトを作成する [Vue.js]
https://johobase.com/vue-js-cli-create-project/


1. Dockerfileを作成
- spring
- vue
- mysql

2. 環境のセットアップ
- springのプロジェクトを作成
https://start.spring.io/

- vueのプロジェクト作成

```
cd ***docker-composeが配置されているフォルダ***
docker-compose build
docker-compose up -d
docker exec -it frontend /bin/bash

```

初回構築は時間がかかる
```
vue create .
# 開発者npm
npm run serve
```

確認アドレス
- http://localhost:9000

ターミナル
- docker
- powershell

### コンテナを止める
```
# 
docker-compose down
```

vscodeのセットアップ
- RemoteDevelopment

.devcontainer用の設定ファイルを作成
