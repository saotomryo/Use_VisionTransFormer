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
  
- English

Once you have the image data, you can start learning with VisionTransFormer as-is.

How to use VisionTransFormer

1. Separate the label-translated images into folders.

Zip the entire folder.

Open "Vision__Transfomer_with_Cross_val.ipynb" and open it in google colaboratory.

Click on the upper right corner of the screen where it says "Connect" to connect.
5. Open the part of the folder symbol on the left side of the screen and drag & drop the zip file there.

6. Execute the process with "Shift + Enter" and change the field "'�zip file to unzip'" to the name of the corresponding zip file.

7. Change the "%cd Target Folder" field to the name of the folder of the extracted zip file.

8. Execute the process with "Shift + Enter" to advance the AI training.

9. Finally, the file "numbers_model.pth" will be the file where the learned model is saved.

By downloading this file, you can use the AI model that classifies images using the same classification policy as the folder classification policy.
