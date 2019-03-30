# convert_mnist_data_to_imagefile

mnistのデータをpng画像に変換して保存する

## Description

mnistのファイル(t10k-images.idx3-ubyte、t10k-labels.idx1-ubyte、train-images.idx3-ubyte、train-labels.idx1-ubyte)を読み込んでpng画像に変換します。


## Usage

引数に画像ファイル、ラベルファイル、作成した画像ファイルを保存するディレクトリを指定して、parse_mnist.pyを実行します。

    python parse_mnist.py --image=t10k-images.idx3-ubyte --label=t10k-labels.idx1-ubyte --dir=images

引数dirで指定したディレクトリが作成され、その中にラベルごとのディレクトリが作成されます。
画像ファイルはラベルのディレクトリ内に作成されます。

## Requirement

Python 3.6.7で作成しました。
