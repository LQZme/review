# review
复习一些python基础

#### input函数默认是str类型，如果想对输入的数字进行int操作，需要进行强制转化
#### 使用time下的localtime函数获取当前时间，时间日期格式化符号如下:
```
%y 两位数的年份表示（00-99）
%Y 四位数的年份表示（000-9999）
%m 月份（01-12）
%d 月内中的一天（0-31）
%H 24小时制小时数（0-23）
%I 12小时制小时数（01-12）
%M 分钟数（00=59）
%S 秒（00-59）
%a 本地简化星期名称
%A 本地完整星期名称
%b 本地简化的月份名称
%B 本地完整的月份名称
%c 本地相应的日期表示和时间表示
%j 年内的一天（001-366）
%p 本地A.M.或P.M.的等价符
%U 一年中的星期数（00-53）星期天为星期的开始
%w 星期（0-6），星期天为星期的开始
%W 一年中的星期数（00-53）星期一为星期的开始
%x 本地相应的日期表示
%X 本地相应的时间表示
%Z 当前时区的名称
%% %号本身
```

### 字符串
Python strip() 方法用于移除字符串头尾指定的字符（默认为空格或换行符）或字符序列。  
###### 切片操作（列表、元组都适用）
切片的语法格式：[起始:结束:步长]   
包含起始但不包含结束
###### replace（）
replace(old, new, [max])   
将old值替换为new值，[max]可选，替换不超过max次
###### split（）
str.split(str="", num=string.count(str)).  
str -- 分隔符，默认为所有的空字符，包括空格、换行(\n)、制表符(\t)等。  
num -- 分割次数。默认为 -1, 即分隔所有。   
   
     
### 列表
###### 添加
append——向列表添加元素，在末尾添加   
extend——将一个列表中元素全部添加到另外一个列表（后添加到前）  
insert——可以在列表指定位置添加元素  
&emsp;&emsp;insert(位置， 要添加的元素) 
###### 删除
del：根据下标进行删除  
pop：删除最后一个元素  
remove：根据元素的值进行删除  
###### 排序
sort：根据列表元素的值排序   默认从小到大     
&emsp;&emsp;sort(reverse=True) 从大到小  
reverse：对列表元素反向排序  
   
    
### 元组
只有一个元素时，不能直接使用（），需要用（，）来消除歧义   
有一个以上的元素时可以省略括号
###### +操作
和列表的extend是类似的，可以将一个元组的值全部添加到另一个元组  
  
    
  
### 字典
当key值重复时，后面的值会覆盖前面的值  
###### clear——清空字典
