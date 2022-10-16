# 一、类库



```python
import cv2  # opencv读取的格式是BGR
import matplotlib.pyplot as plt # 绘图工具:matplotli，专门用于画图
import numpy as np # 处理数值计算最为基础的类库，用来存储和处理大型多维矩阵
```

```python
import cv2

def cv_show(name,img):
    cv2.imshow(name,img) # 显示图片 name:窗口的名字, img:opencv读取图像
    cv2.waitKey(0) # 等待时间，毫秒级，0表示任意键终止
    cv2.destroyAllWindows() # 关闭所有窗口
```

# 二、常用基础函数

## 2.1 imread

## 2.2 imshow

## 2.3 imwrite

## 2.4 waitkey

## 2.5 split

## 2.6 merge

## 2.7 边界填充

## 2.8 add

## 2.9 resize



