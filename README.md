# Generative-Adversarial-Network-GAN-
![Generated Images](img/GAN.png?raw=True)

# GAN的運作模式 :
  GAN 區分為兩個 Network，分別是Discriminator Network 以及 Generator Network，Generator Network的功用在於偽造虛擬的Data，而Discriminator Network 則用於區分真實Data與虛擬Data，也就是說當Gernerator Network創造出來的Data完美到讓Discriminator Network無法分辨出誰真誰假，就可能完美的模擬出真正Data分布的model 

## 專案目標&環境
  該專案目標為讓Generator Network 創造手寫數字圖片，其中使用的資料庫為MNIST手寫辨識資料庫，使用的神經網路Framework為Tensorflow

## 結果
![Generated Images](result/loss_rate.png?raw=True)
  該圖片為1000次iteration的訓練過程中，Generator Network & Discrimiantor Network 的loss rate
  
![Generated Images](result/result_2.png?raw=True) 
  該圖片為Generator Network 產生的手寫數字圖片(第一列為Generator Network的初始資料N)
  
