# uma-grouth-check-app
## pipenv インストール
```
brew install pipenv
```
https://pipenv-ja.readthedocs.io/ja/translate-ja/

## プロジェクトの直下に仮想環境を作る設定
```
## python仮想環境をローカルディレクトリに作成
echo export PIPENV_VENV_IN_PROJECT=true >> ~/.bash_profile
source ~/.bash_profile

## パッケージインストール
pipenv install --dev
```

## Flask起動
```
pipenv run flask run --host 0.0.0.0 --port 8081
```
