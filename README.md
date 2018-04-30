# Assignment 1
## Image Decryption by a Single-Layer Neural Network 
***

 * 用PIL將圖片讀入
 
 * 將圖片轉存到NUMPY ARRAY
 
 * 藉由訓練資料取得公式所需值
 
 * 輸入Empire取得結果
 
 
###  parameters

* MaxIterlimit : epoch次數， 5

* ε : e

* weights : 使用numpy的random

* α : lerningrate，0.00001

* learningrate 為 0.00001時一個epoch之後 weight的值也沒有在變化了


### 解密圖片 Eprime 之後

| Eprime          | Eprime - Decrypted |
| :-------------: |:---------------:|
| ![Eprime](https://github.com/bill41708/ML2018_410421225/blob/master/ML2018_410421225/Eprime.png) | ![result](https://github.com/bill41708/ML2018_410421225/blob/master/ML2018_410421225/result.png) |


## Weight 結果
```
W1 = 0.24914331
W2 = 0.6613819
W3 = 0.08923953
```

## 心得
一開始還不太確定如何實作，經過理解後，其實只要把參數公式等等設定好，在看著哪裡有錯誤一步一步修改就完成了。過程比想像中的好玩，沒有那麼的沉悶，對各種型態的變數細節也有比較清楚的了解，如果有錯誤就會導致程式出錯。讓我對機器學習也有更深的理解。
