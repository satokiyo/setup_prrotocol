# setup

## windows

- ﾌﾟﾗｲﾊﾞｼー設定

歯車→プライバシー→全般→アクティビティの履歴

- Microsoft IME

設定（A/あ）→学習と辞書→オフ

- 最近開いた項目

歯車→個人用設定→スタート→最近開いた項目OFF

- wsl

- windowsターミナルインストール

- Ubuntu起動して、プロパティ→編集オプション→貼り付けを有効化

- installs

  - git（WSLonly、GitWindows不要。二重管理しないため。GitconfigをWSL、DOCKERで設定）
  - kubectl
  - minikube
  - docker
  - vscode
   - settings.jsonに追記。自動フォーマットが効かない場合、flake8とblackをインストールし、settings.jsonにPATHを追加する。
     "editor.formatOnSave": true,
     "editor.defaultFormatter": "esbenp.prettier-vscode",
     "python.formatting.provider": "black",
     "[python]": {
       "editor.defaultFormatter": null,
     },  
  - python3(WSL) https://pythonlinks.python.jp/ja/index.html https://www.python.jp/install/ubuntu/index.html
  - $ sudo apt update
$ sudo apt install build-essential libbz2-dev libdb-dev \
  libreadline-dev libffi-dev libgdbm-dev liblzma-dev \
  libncursesw5-dev libsqlite3-dev libssl-dev \
  zlib1g-dev uuid-dev tk-dev
  →　./configure　→　make　→　make　install
  - -> python3で起動するバージョンはmake　install、それ以外はmake　altinstall
- Golang
- Git configを共通で設定
- teraterm 
- winmerge

[参考](https://blog.katsubemakito.net/git/git-config-1st)
