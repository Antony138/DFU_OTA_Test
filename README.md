# DFU\_OTA_Test
Update device firmware through OTA
##流程
- 1、将固件(ZIP格式)放入firmwares文件夹下；
- 2、发送相应指令使你的硬件进入DFU模式（这个demo没有集成这个指令，因为每款硬件进入DFU模式的指令不一样，是由写固件的人定义的）。在用这个demo进行OTA升级前，可以用LightBlue写入对应的指令使硬件进入DFU模式。
- 3、打开这个demo，会自动选上firmwares文件夹中的固件；
- 4、点击「SELECT DEVICE」按钮，选择进入DFU模式的硬件进行链接；
- 5、返回主界面后，点击upload即可。