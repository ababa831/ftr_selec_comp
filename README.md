# 特徴量選択ツールを色々使ってみる

これから色々追加していく予定

## Boruta導入方法

以下のコマンド打てばOK

```
$ pip install git+https://github.com/scikit-learn-contrib/boruta_py.git
```

あとは，Pythonコードに

```
from boruta import BorutaPy
```

をインポートして，[サンプルコード](https://github.com/ababa893/ftr_selec_comp/blob/master/boruta.ipynb)のように使うだけ．

## 参考

- [ランダムフォレストと検定を用いた特徴量選択手法 Boruta](https://aotamasaki.hatenablog.com/entry/2019/01/05/195813)

- [sklearn.feature_selection による特徴量選択](https://qiita.com/rockhopper/items/a68ceb3248f2b3a41c89)
