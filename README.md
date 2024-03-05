# Java-learning

1.#### 日期

import java.util.Date;

getTime（）表示的是到时间原点的毫秒数

d1.getTime()=System.currentTimeMillis()

###### 日期转字符串

| y 代表年           |
| :----------------- |
| M 代表月           |
| d 代表日           |
| H 代表24进制的小时 |
| h 代表12进制的小时 |
| m 代表分钟         |
| s 代表秒           |
| S 代表毫秒         |

import` `java.text.SimpleDateFormat;

sdf.format(d);//返回值是String

###### 字符串转日期

importjava.text.ParseException;

sdf.parse(str); 需要用try-catch包围
##### [日期排序例题](https://how2j.cn/k/date/date-format/348.html#)
##### [ Java 8引入了java.time 包](https://how2j.cn/k/date/date-format/348.html#)


