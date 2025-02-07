# OP-GSP-Image-Stitching
ipynbファイルのコードブロックを順番に実行してください。

.ipynbファイルへのリンク : https://colab.research.google.com/drive/1pMSp0h_dl3HAfo5FmeG8zF_G-L_yJuMI#scrollTo=6_LddleqX7DQ

コードのテストに使用したデータセットの画像がレポにありますので、ダウンロードしてコードをテストしてください。希望の画像を colab ファイルにアップロードし、メイン関数の最初の2行のコードを以下のように更新します：

img1 = cv2.imread(「/path/to/image1.jpg」, cv2.IMREAD_GRAYSCALE)

img2 = cv2.imread(「/path/to/image2.jpg」, cv2.IMREAD_GRAYSCALE).

隣り合う画像は，互いに交差する番号を名前として持ちます（例： 0001.jpg と 0002.jpg）．このようなファイルは、つなぎ合わせることができます。

OP-GSPのオーバーラップ比は、これらの画像ではうまく機能しませんが、画像が撮影された角度のせいだと思われます。

#hline

# OP-GSP-Image-Stitching
Please execute code blocks in the ipynb file in order. 

Link to the .ipynb file : https://colab.research.google.com/drive/1pMSp0h_dl3HAfo5FmeG8zF_G-L_yJuMI#scrollTo=6_LddleqX7DQ

Some images from the dataset I used to test the code can be found in the repo, please download it to test the code. Upload your desired images to your colab files and update the first two lines of code in the main function as follows:

img1 = cv2.imread("/path/to/image1.jpg", cv2.IMREAD_GRAYSCALE)

img2 = cv2.imread("/path/to/image2.jpg", cv2.IMREAD_GRAYSCALE)

Adjacent images have consective numbers for names (Ex: 0001.jpg and 0002.jpg). Files like this can be stitched together.

The OP-GSP overlap ratio does not work well with these images, I suspect it is because of the angle the images are taken from.
