# android
心肺复苏训练器App的设计与实现

app目录:android 的app，低功耗蓝牙模块,sqlite 嵌入式数据库
        android studio软件

train目录:服务端, mysql 数据库,应用服务器tomcat
       eclippse软件

用户在训练器上进行训练，通过低功耗蓝牙与Android设备数据交互，保存数据到sqlite，Android 设备向服务器提交训练的数据,保存到mysql
