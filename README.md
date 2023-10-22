## 使用版本
* python == 3.6
* tensorflow == 1.14


## 数据集准备
```
├── dataset
   └── selfie2anime
       ├── trainA
           ├── xxx.jpg
           ├── yyy.png
           └── ...
       ├── trainB
           ├── zzz.jpg
           ├── www.png
           └── ...
       ├── testA
           ├── aaa.jpg 
           ├── bbb.png
           └── ...
       └── testB
           ├── ccc.jpg 
           ├── ddd.png
           └── ...
```

### 训练
```
> python main.py --dataset selfie2anime
```
* If the memory of gpu is **not sufficient**, set `--light` to **True**
  * But it may **not** perform well


### 测试
```
> python main.py --dataset selfie2anime --phase test
```

### 结果
<div align="center">
  <img src = 'user_study.png' width = '738px' height = '187px'>
</div>


## 参考github
* https://github.com/FIFALUO/UGATIT