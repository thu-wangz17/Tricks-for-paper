* 设置子图：
```python
fig , ax = plt.subplots(nrows=3, ncols=5)
```

<img src="C:\Users\WangZ\Desktop\Plot-with-Matplotlib-for-paper\figure\v2-725ed5a26cc23afb6d39c01d242e416c_720w.jpg" alt="1" style="zoom:50%;" />

* 紧凑布局(Tight Layout)：

  上图横轴与纵轴的tick会有重叠，因此使用```tight_layout```

  ```python
  fig, ax = plt.subplots(tight_layout=True)
  ```

  ![2](C:\Users\WangZ\Desktop\Plot-with-Matplotlib-for-paper\figure\v2-69c6bfde4c05847870b057fd3c5f9d56_720w.jpg)

* 图中图(Inset)：

  ```python
  ax.plot(x, y)
  inset = plt.axes((.5, .5, .3, .3), facecolor='lightblue')
  inset.plot(x, y, color='r')
  ```

  <img src="C:\Users\WangZ\Desktop\Plot-with-Matplotlib-for-paper\figure\v2-cb707d77a7d0503fdbc6fe20140c2497_720w.jpg" alt="3" style="zoom:50%;" />

* 设定轴的缩放(Scale)：

  可选参数包括```linear```(default),```log```,```symlog```,```logit```

  ```python
  ax.set_yscale('log')
  ```

  <img src="C:\Users\WangZ\Desktop\Plot-with-Matplotlib-for-paper\figure\v2-d40633a32c8c039d656bd92442dbe868_720w.jpg" alt="4" style="zoom:67%;" />

  如图，如果不设置缩放，左图纵轴为线性，缩放后为右图。

以上内容参考https://zhuanlan.zhihu.com/p/118020086