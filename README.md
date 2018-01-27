# FontDataAll

# ファイルの説明

## 推論実行用のテストデータ

青空文庫にあった宮沢賢治の小説をキャプチャーしたもの。  
学習用に使用されているフォントとは別のものを使用。  
`predict.py`や`predict_some_snapshot.py`で利用することを想定している。

- `The_Night_of_the_Milky_Way_Train_ch2.PNG`
- `The_Nighthawk_Star_op.PNG`

## 学習・テスト用のデータ

`train.py`で使用することを想定したデータセット。

- ``font_*.bmp``

## 学習・テスト用のデータを自分で作成

以下のマクロを利用すれば違うフォントや文字を利用した自分だけのデータセットを作成できる。  
使用方法はマクロのシート内に記述。

- `フォント画像生成用マクロ.xlsm`
