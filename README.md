
# 机器学习纳米学位
# 模型评估与验证
## 实战项目: 预测波士顿房价

### 安装

本项目要求安装 **Python** 和以下 Python 库：

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

你还需要安装软件，才能运行并执行 [Jupyter Notebook](http://ipython.org/notebook.html)

我们建议学员安装 Python  的 [Anaconda](http://continuum.io/downloads) 分发系统，该系统已经包含上述软件包，并且包含项目所需的其他软件包。

### 代码

你可以在 notebook 文件 `boston_housing.ipynb` 中找到代码模板。你还将被要求使用 Python 文件 `visuals.py` 和数据集文件 `housing.csv` 来完成你的任务。我们已经提供了一些初始代码来帮助你开始，你需要补充额外函数来顺利完成本项目。请注意，学员无需更改 `visuals.py` 中的代码。如果你对 notebook 中的可视化文件感兴趣，请随意探索。


### 运行

在终端或命令行窗口中，跳转至最上面的项目目录 `boston_housing/`（包含 README 文件），并运行如下命令：

```bash
ipython notebook boston_housing.ipynb
```  
或者
```bash
jupyter notebook boston_housing.ipynb
```

这将在你的浏览器中打开 Jupyter Notebook 软件和项目文件。

### 数据

修改后的波士顿房屋数据集包含 489 个数据点，每个数据点有 3 个特征。 该数据集是基于[UCI 机器学习库](https://archive.ics.uci.edu/ml/datasets/Housing)中的波士顿房屋数据集进行修改的版本。


**特征**

1.  `RM`: 每个住宅区的平均房间数量
2. `LSTAT`: 被视为处于较低地位的人口百分比
3. `PTRATIO`: 城镇中学生-教师比例 

**目标变量**

4. `MEDV`: 自住房屋的中位值 （median value of owner-occupied homes）