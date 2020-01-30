# 1st-DL-CVMarathon
+ opencv安裝，於conda terminal 中打
```
pip install opencv-python
```

+ tensorflow安裝，注意cuda版本裝10.0即可，10.2會找不到DLL，一切都要匹配。[教學文章](https://medium.com/@rick.huang1609/window-10%E5%AE%89%E8%A3%9Dtensorflow-gpu%E4%B8%A6%E5%9C%A8jupyter-notebook%E5%92%8Cspyder%E9%81%8B%E8%A1%8C-221bb4707dbd)

+ anaconda安裝法，[教學文章](https://allen108108.github.io/blog/2019/10/07/Tensorflow%202.0%20-%20GPU%E7%9A%84%E5%AE%89%E8%A3%9D%E5%8F%8A%E7%A2%BA%E8%AA%8D%20(%20Win%2010%20)/)
這裡注意一下cudnn7.6.0會預設搭配cudatoolkit10.1，[參照](https://developer.nvidia.com/cudnn)7.6訓練速度快很多，可能配合tensorflow2.1比較適合
(未測試)
