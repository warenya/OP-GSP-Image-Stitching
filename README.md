# OP-GSP-Image-Stitching
ipynbファイルのコードブロックを順番に実行してください。

既に実行されたバージョンのipynbファイルはこちら : https://colab.research.google.com/drive/1pMSp0h_dl3HAfo5FmeG8zF_G-L_yJuMI#scrollTo=6_LddleqX7DQ にあります。

コードのテストに使用したデータセットはレポにあります。目的の画像を colab ファイルにアップロードし、メイン関数の最初の2行を以下のように更新します：

img1 = cv2.imread(「/path/to/image1.jpg」, cv2.IMREAD_GRAYSCALE)

img2 = cv2.imread(「/path/to/image2.jpg」, cv2.IMREAD_GRAYSCALE).
#hline
# OP-GSP-Image-Stitching
Please execute code blocks in the ipynb file in order. 

An already executed version of the ipynb file can be found here : https://colab.research.google.com/drive/1pMSp0h_dl3HAfo5FmeG8zF_G-L_yJuMI#scrollTo=6_LddleqX7DQ

The dataset I used to test the code can be found in the repo, please download it to test the code. Upload your desired images to your colab files and update the first two lines of code in the main function as follows:

img1 = cv2.imread("/path/to/image1.jpg", cv2.IMREAD_GRAYSCALE)

img2 = cv2.imread("/path/to/image2.jpg", cv2.IMREAD_GRAYSCALE)
