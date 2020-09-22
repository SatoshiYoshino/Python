### Pythonのトレーニング用リポジトリ

#### tensorfrow環境設定
numpy 1.16ではcaffeが動作しないため、numpy 1.15を使いたい場合に対応するtensorflowのバージョンは1.12を使用

TensorFlow 1.12
scikit-learn 0.20.0
XGBoost 0.81
numpy 1.15.4


バージョンを指定したインストールは下記のコマンド
conda install numpy==1.15
conda install tensorflow==1.12


### MeCab設定参考URL
https://murabitoleg.com/mac-mecab/

mecab-ipadic-NEologdのインストール
https://github.com/neologd/mecab-ipadic-neologd/blob/master/README.ja.md

### HomeBrewの最新版をインストールしてから、MeCab設定を行ったらインストールができた
HomeBrewがインストールされていてかつ最新版出ないとMeCab＋mecab-ipadic-neologdがインストールできなかった

neologd/mecab-ipadic-neologd - GitHub
