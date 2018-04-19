# 基于Apache POI导出大数据量Excel的实现
### 使用POI导出大数据量Excel Demo

项目分别模拟了10W，100W，1048576（xlsx最大支持行数）条数据，进行一次性Excel导出。


### 测试：
模拟10W条数据，一次性导出用时3秒左右（3736ms）；  
模拟100W条数据，一次性导出用时26秒左右（26381ms）；  
模拟1048576条（xlsx最大支持行数）数据，一次性导出用时27秒左右（27834ms）；  
（测试图例在imgs文件夹内）  

### 数据测试环境
当然，导出速度也和电脑配置相关，以上数据测试环境如下：  
系统：windows 7  
处理器：Inter(R) Core（TM）i5-4590 CPU @ 3.30GHz 3.30GHz  
内存：16 GB  
工具：IntelliJ IDEA  
