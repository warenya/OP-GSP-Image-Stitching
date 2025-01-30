# OP-GSP-Image-Stitching
ipynbファイルのコードブロックを順番に実行してください。

既に実行されたバージョンのipynbファイルはこちら : https://colab.research.google.com/drive/1pMSp0h_dl3HAfo5FmeG8zF_G-L_yJuMI#scrollTo=6_LddleqX7DQ にあります。

コードをテストするために使用したデータセットからの画像がいくつかレポにあります。希望の画像をcolabファイルにアップロードし、メイン関数の最初の2行のコードを以下のように更新します：

img1 = cv2.imread(「/path/to/image1.jpg」, cv2.IMREAD_GRAYSCALE)

img2 = cv2.imread(「/path/to/image2.jpg」, cv2.IMREAD_GRAYSCALE).

現在、画像の合成に問題があります。せっかく特徴点が特定されても、つなぎ合わせることで不要な変形が起きてしまうのだ。これは、実際のデータではなく、ダミーの座標とデータをテストに使用したためだと思われる。

#hline

# OP-GSP-Image-Stitching
Please execute code blocks in the ipynb file in order. 

An already executed version of the ipynb file can be found here : https://colab.research.google.com/drive/1pMSp0h_dl3HAfo5FmeG8zF_G-L_yJuMI#scrollTo=6_LddleqX7DQ

Some images from the dataset I used to test the code can be found in the repo, please download it to test the code. Upload your desired images to your colab files and update the first two lines of code in the main function as follows:

img1 = cv2.imread("/path/to/image1.jpg", cv2.IMREAD_GRAYSCALE)

img2 = cv2.imread("/path/to/image2.jpg", cv2.IMREAD_GRAYSCALE)

There is currently an issue with combining images. Even though feature points are identified well, stitching causes unwanted deformation. I suspect this is because dummy coordinates and data was used for the test instead of actual data.
