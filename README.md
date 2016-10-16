# 设备维修系统
##一、ER图
![ER](images/ER图 .jpg)
##二、Axure设计原型
[Axure原型图](设备保养原型.rp)
##三、Data数据
####（1）[保养记录表](数据/设备保养系统模型_equipmentmaintain.sql)  
![data1.jpg](images/data1.jpg)  

####（2）[检修报告表](数据/设备保养系统模型_examinereport.sql)  
![data3.jpg](images/data3.jpg)  

####（3）[维修消耗表](数据/设备保养系统模型_equipmentneedfix.sql)  
![data2.jpg](images/data2.jpg)  

####（4）[预警表](数据/设备保养系统模型_warning.sql)  
![data4.jpg](images/data4.jpg)

##四、SQL查询语句及截图
SELECT 设备类别,距离下次保养天数 FROM 设备保养系统模型.warning;
![select.jpg](images/select.jpg)
