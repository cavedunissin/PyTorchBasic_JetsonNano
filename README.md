# Pytorch深度學習框架X NVIDIA JetsonNano應用-線性回歸與實作

![image](media\gif\linear_regression_Adam.gif)

| 作者 | Chia-Chun, Chang |
| ---- | ---|
| 所屬單位  | Cavedu 教育團隊 |
| 開發日期  | 10908 |
| 文章連結  | https://www.rs-online.com/designspark/pytorchx-nvidia-jetsonnano-cn |

___

## 介紹
深度學習的框架有很多種，Tensorflow、PyTorch、Mxnet、Theano等等的，其中最大眾的算是Google的Tensorflow，但還有一大部分的使用者是透過PyTorch來開發深度學習，今天我們就來介紹並使用PyTorch這款深度學習套件並且使用torch做個簡單的線性回歸；這篇文章的對象是對於深度學習已經稍微有點概念想自己建構神經網路模型的人。
___

## 目錄

* 參考
* 前言、介紹
* 安裝
* 基礎函式
    *	張量
    *	生成張量
    *	從Numpy轉換成Tensor
    *	將Tensor 放入GPU以及提取成Numpy
    *	合併、朔形、最大值、維度相加
    *	PyTorch的Autograd
        * 計算圖 (Computation graphs)
        * PyTorch的Auto grad framework
        * PyTorch凍結權重
* 實作：線性回歸 (Linear Regression)
* 結語





