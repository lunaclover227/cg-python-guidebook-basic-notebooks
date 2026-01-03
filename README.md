# 大石泉と学ぶPythonプログラミング 基礎編

「大石泉と学ぶPythonプログラミング 基礎編」の情報をまとめたページです。

## 初版第1刷の記載ミスについて

p222のリスト7.32およびp230のリスト7.39に誤りがあり、先頭に以下の3行を追加する必要がありました。

```
images_list = []
for name in name_results:
    images_list.append(images_dict[name])
```

こちらは本来、p220のリスト7.29に記載のあったコードなのですが、p222で書き換える際に消してはならなかった3行を誤って消してしまった状態で掲載したものになります。申し訳ございませんでした。(再販時に修正予定です)

## お知らせ

現在、演習用ページおよびサンプルコードの追加作業に時間を要しております。申し訳ございません。

先んじて、入力が困難なリスト7.24のコードを下記に示します。既に7章まで進まれた方は以下をコピペしてご利用ください。

```
import random
import cv2
import numpy as np
from pathlib import Path
from google.colab.patches import cv2_imshow

!pip install -q gdown
!gdown --folder "https://drive.google.com/drive/folders/1UUYVZPhpIRNzF9EOVeSziFjedNHiqi88?usp=sharing" -O ./images

```

## 第3章　プログラムの基礎に触れてみよう

### 演習用

- [演習用](https://colab.research.google.com/github/lunaclover227/cg-python-guidebook-basic-notebooks/blob/main/chapter_03/第3章_演習用.ipynb)

### サンプルコード

- [サンプルコード](https://colab.research.google.com/github/lunaclover227/cg-python-guidebook-basic-notebooks/blob/main/chapter_03/第3章_サンプルコード.ipynb)

## 第4章　関数について詳しくなろう

### 演習用

- [演習用](https://colab.research.google.com/github/lunaclover227/cg-python-guidebook-basic-notebooks/blob/main/chapter_04/第4章_演習用.ipynb)

### サンプルコード

- [サンプルコード](https://colab.research.google.com/github/lunaclover227/cg-python-guidebook-basic-notebooks/blob/main/chapter_04/第4章_サンプルコード.ipynb)

## 第5章　複数の値をまとめてみよう

### 演習用

- ~~(1/2(金)追加予定)~~ (1/3(土)追加予定)

### サンプルコード

- ~~(1/2(金)追加予定)~~ (1/3(土)追加予定)

## 第6章　文を使いこなそう

### 演習用

- (1/3(土)追加予定)

### サンプルコード

- (1/3(土)追加予定)

## 第7章　10連ガシャを作ってみよう

### 演習用

- (1/3(土)追加予定)

### サンプルコード

- (1/3(土)追加予定)