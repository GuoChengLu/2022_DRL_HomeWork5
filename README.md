# 2022_DRL_HomeWork5
## 深度強化學習作業5 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GuoChengLu/2022_DRL_HomeWork5/blob/master/DQN%20pytorch%20lightning%20with%20gym.ipynb) [![Result in Drive](https://img.shields.io/badge/Drive-Result-red?style=flat&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/146nGl1lH7iScGDDfJYeyideqma2tpxdj?usp=sharing) [![GitHub](https://img.shields.io/badge/Github-Open%20in%20my%20Github-white?style=flat&logo=github&logoColor=white)](https://github.com/GuoChengLu/2022_DRL_HomeWork5)
## 說明
### 其他branch是我在自己電腦上使用Windows10 & anaconda & gtx1060 的環境實做的。
### 作業內容： 
- 環境：MountainCar-v0
  - 主要是使用Gym中的環境下去做訓練。
- 原因：
  - 經過幾次失敗以後，發現本模型不做修改的話只能訓練acttion是離散式的環境，如果是連續的會無法訓練，例如Car-racing。
  - 使用離散式car-racinng(CarRacingDiscrete-v1)時，用原本的模型參數無法訓練，若是更改會佔用大量資源，colab無法實做，相關結果發布在network-fail-banch這個分支中。
- 使用的訓練方式 - 老師提供的DQN
