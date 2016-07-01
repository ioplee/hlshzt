http://localhost:8080/shzt/service/cmd/_command?deviceID=device50&status=134&code=01
红外透传接口
deviceID 设备ID
用于读取设备

status 设备状态 红外设备对应的是指令码,这里是86和88的10进制读数 分别为134 和136
代表着学习模式和正式模式

code 代表红外节点保存的100个指令区域
1-90