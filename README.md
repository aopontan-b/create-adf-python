[クイック スタート:Python を使用してデータ ファクトリとパイプラインを作成する](https://learn.microsoft.com/ja-jp/azure/data-factory/quickstart-create-data-factory-python) 見ながら実際に作成してみる

## セットアップ
ソースコードの取得
```
git clone https://github.com/aopontan-b/create-adf-python.git
cd create-adf-python
```
### 仮想環境の生成
仮想環境を生成するには二つの方法がある

### ターミナルから
仮想環境の生成する
```
python3 -m venv .venv
```

アクティベート
```
# Windows
.venv/Scripts/activate.bat
# Unix, MacOS
source .venv/bin/activate
```

必要なパッケージを全てインストール
```
python -m pip install -r requirements.txt
```

### VS Code上から
1. VSCodeでrequirements.txtを開いて右下の`環境の生成`ボタンをクリック
2. 環境の種類は`Venv`を選択
3. Python インストールは`Python 3.10.6 64-bit /bin/python3`を選択
4. インストールする依存関係は`requirements.txt`を選択
5. `OK`をクリックすると、仮想環境が生成される
6. アクティベートする

## Data Factory の構築
```
python3 datafactory.python
```

## 参考記事
- [クイック スタート:Python を使用してデータ ファクトリとパイプラインを作成する](https://learn.microsoft.com/ja-jp/azure/data-factory/quickstart-create-data-factory-python)