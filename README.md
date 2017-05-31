# 初赛：（5月18日-6月13日）
## 扬中市高新区1000多家企业用电预测

### 准备工作

这个项目需要安装**Python 2.7**和以下的Python函数库：

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

你还需要安装一个软件，以运行和编辑[ipynb](http://jupyter.org/)文件。



### 编码

代码在`tianchi_power.ipynb`文件中给出。

### 运行

在终端或命令行窗口中，选定`tianchi_power/`的目录下（包含此README文件），运行下方的命令：

```jupyter notebook tianchi_power.ipynb```

这样就能够启动jupyter notebook软件，并在你的浏览器中打开文件。

### Data

竞赛数据

本次竞赛主要数据源为企业用电量表Tianchi_power，我们抽取了扬中市高新区的1000多家企业的用电量（数据进行了脱敏），包括企业ID（匿名化处理），日期和用电量。具体字段如下表：
Tianchi_power
https://tianchi.aliyun.com/competition/information.htm?spm=5176.100067.5678.2.YmMR7U&raceId=231602
参赛者可以参考其他外部数据，比如天气、经济数据等。

**特征**

1. `record_date`: 日期
2. `user_id`: 企业id


**目标变量**

4. `power_consumption`: 用电量