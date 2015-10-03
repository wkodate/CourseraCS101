# Digital Images

### Introduction to Digital Images

https://class.coursera.org/cs101-selfservice/wiki/view?page=image1

* 画像は小さな正方形のpixelsで構成されており、各pixelは正方形でとても小さい
* RGB(Red, Green Blue)の組み合わせで色をつくる
* RGBExplorer https://class.coursera.org/cs101-selfservice/wiki/view?page=image-rgb-explorer
* red, green, blueを全部255でwhite, 全部0でblack
* コンピュータにおいて画像や音楽やビデオなどのデータは、全て小さなたくさんの数で表される

### Image Code

https://class.coursera.org/cs101-selfservice/wiki/view?page=image2

* 画像の大きさを変更したり色を変更したり

### For Loop

https://class.coursera.org/cs101-selfservice/wiki/view?page=image3

* for-loopを使って画像の各ピクセルのRGBを変更する例
* for-loopを使うことによって繰り返し処理を簡単なコードで機械的に実行できる

### Expressions

https://class.coursera.org/cs101-selfservice/wiki/view?page=image4

* 取得した画像のピクセルにいくつかの値を掛けて、式で表す例

### Puzzles

https://class.coursera.org/cs101-selfservice/wiki/view?page=image5

* 見えない画像をRGBを変化させて見えるようにする

### Grayscale

https://class.coursera.org/cs101-selfservice/wiki/view?page=image6

* それぞれのpixelのRGBの平均を各RGBにセットすると画像をグレースケールにできる

### If Logic

https://class.coursera.org/cs101-selfservice/wiki/view?page=image7

* 条件に合わせて処理をする
* 画像の赤を別の色に変更したい場合、Rが一定以上の条件だと白も含まれてしまう
→RGBの平均(×1.0~2.0)よりRが大きいときの条件を使う

### Bluescreen

https://class.coursera.org/cs101-selfservice/wiki/view?page=image8

* 画像(image)と背景画像(back)を組み合わせる
* imageのピクセルをループさせて、RGBを検出
* imageのRGBが特定の条件(Rが平均*1.2より大きいなど)にマッチした座標において、imageのRGBをbackのRGBに置き換える
