# Use_VisionTransFormer
画像データを用意すればそのままVisionTransFormerを使った学習が実施できます。

利用手順

1.ラベル訳した画像をフォルダ毎にわけます。

2.全体のフォルダをzipファイルで圧縮します。

3.「Vision__Transfomer_with_Cross_val.ipynb」を開き、google colaboratoryで開きます。

4. 画面右上の「接続」と表示されているところをクリックし、接続します。

5.画面左のフォルダのマークの部分を開き、そこにzipファイルをドラック&ドロップします。

6.「シフト + エンター」で処理を実行していき、「'解凍するzipファイル'」の欄を該当のzipファイル名に変更します。

7.「%cd 対象フォルダ」の欄を解凍されたzipファイルのフォルダ名に変更します。

8.「シフト + エンター」で処理を実行していくと、AIの学習が進みます。

9.最終的に「数字_model.pth」というファイルが、学習済みのモデルが保存されたファイルになります。

これをダウンロードすることで、フォルダわけした分類方針と同じ方針で画像を分類するAIモデルを利用することが出来ます。


