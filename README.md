# 期末專題：生成對抗網路 (Wasserstein GAN with NumPy) 
GAN 是近年來最熱門的深度學習模型之一，通過兩個神經網路互相對抗的方式進行學習，被廣泛應用於圖像生成與修復、樣本擴增等領域。Wasserstein GAN 則是它的改良版本，能有效地解決 Vanilla GAN 在結構上的缺陷（詳見附錄）。此專題的目的是從理論出發，以 NumPy 實作模型架構與 backpropagation 最佳化算法，完整重現 WGAN 模型。此專題的模型在測試中展現出基本的學習能力，能夠生成 MNIST 與 fashion MNIST 數據集的圖片。
## 附錄
### DNN 深度神經
[DNN 原理（一）](https://coomerbot.github.io/test/neural_network%20(3).pdf)  
[DNN 原理（二）](https://coomerbot.github.io/test/neural_network_2%20(2).pdf)  
[DNN 原理（三）](https://coomerbot.github.io/test/neural_network_3%20(2).pdf)  
### GAN 生成對抗
[GAN 原理](https://coomerbot.github.io/test/gan%20(2).pdf)  
[WGAN 原理](https://coomerbot.github.io/test/wgan%20(1).pdf)
