---

title:  "Python图像二值化+Matlab导出Excel点阵数据+Excel重绘"
date:   2019-04-06 16:4:04
author: Mine4ever
#categories: Jekyll update
tags: 图像处理 Python Matlab Excel

---
### 二值化
* Python

### 数据提取
* Matlab
{% highlight matlab %}
>> data=imread('E:\ycycy\fig\7-2-binary.png');              %读取图片
>> xlswrite('E:\ycycy\fig\write2Excel.xlsx',data);          %导出数据到excel

{% endhighlight %}

### Excel
* 格式->列宽->2.5
* 将True全部替换成空：格式->替换->替换内容(True-> )->全部替换
* 条件格式->新建规则->只为包含以下内容的单元格设置格式:无空值->格式->填充:黑色

### 参考：
* [如何用Matlab在Excel上画二次图](https://www.bilibili.com/video/av28790093?from=search&seid=1089115841263066107)
