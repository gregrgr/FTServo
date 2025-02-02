| 库/SDK                              | 解释/Explanation                           | FEETECH Serail servo | 环境/Surroundings                      |
| ---------------------------------- | ---------------------------------------- | -------------------- | ------------------------------------ |
| SCServoCL_keil_f103_220106.7z      | SCSCL舵机SDK/SCSCL servo SDK               | SCS                  | 支持STM32F103芯片/support STM32F103 Chip |
| SCServoCL_keil_f405_220330.7z      | SCSCL舵机SDK/SCSCL servo SDK               | SCS                  | 支持STM32F405芯片/support STM32F405 chip |
| SMServoBCL_keil_f103_220329.7z     | SMS/STS系列舵机SDK/SMS/STS serial servo SDK  | SMSBL/SMSCL/STS      | 支持STM32F103芯片/support STM32F103 chip |
| SMServoBCL_keil_f405_220329.7z     | SMS/STS系列舵机SDK/SMS/STS serial servo SDK  | SMSBL/SMSCL/STS      | 支持STM32F405芯片/support STM32F405 chip |
| SMServoBCL_keil_f405_hal_220330.7z | SMS/STS系列舵机hal库SDK/SMS/STS serial servo hal library SDK | SMSBL/SMSCL/STS      | 支持STM32F405芯片/support STM32F405 chip |
| SCServo_Linux_220329.7z            | Linux舵机SDK/Linux servoSDK                | SCSCL/SMSBL/SMSCL/STS      | Linux                                |
| SCServoDemo_vs_2008_200724.7z      | vs2008(VC++)舵机SDK/vs2008(VC++) servo SDK | SCSCL/SMSBL/SMSCL/STS      | VC++                                 |
| SCServo_Python_220415.7z           | Python舵机SDK/Python servo SDK             | SCSCL/SMSBL/SMSCL/STS      | Python                               |
| SCServo_Arduino_220524.7z          | Arduino舵机SDK/Arduino servo SDK           | SCSCL/SMSBL/SMSCL/STS      | Arduino                              |
| ModbusRtu_Arduino_211016.7z        | Modbus rtu舵机SDK/Modbus rtu servo SDK     | SMSBLMD/SMSCLMD      | Arduino                              |

SCServoCL_keil_f103_220106.7z  
1、stm32f103 keil sdk增加总线切换延时  
2、SDK读超时使用指令计数方法替换系统定时器(不占用系统定时器)   

SCServoCL_keil_f405_220330.7z  
1、stm32f405 keil sdk增加总线切换延时  
2、SDK读超时使用指令计数方法替换系统定时器(不占用系统定时器)    

SMServoBCL_keil_f103_220329.7z  
1、stm32f103 keil sdk增加同步读功能  
2、stm32f103 keil sdk增加总线切换延时

SMServoBCL_keil_f405_220329.7z  
1、stm32f405 keil sdk增加同步读功能  
2、stm32f405 keil sdk增加总线切换延时  
3、SDK读超时使用指令计数方法替换系统定时器(不占用系统定时器)

SMServoBCL_keil_f405_hal_220330.7z  
1、stm32f405 keil hal sdk增加同步读功能  
2、stm32f405 keil hal sdk增加总线切换延时 

SCServo_Linux_220329.7z  
1、linux sdk增加同步读功能  
2、增加SMS_STS类，同时兼容两个系列舵机  
3、example例子SMSBL与SMSCL类改成SMS_STS类应用实例  
4、修正调试输出信息格式与错误  

SCServo_Arduino_220524.7z  
1、Arduino sdk增加同步读功能  
2、增加恢复舵机默认参数功能  
3、修复通信超时不稳定问题  

SCServo_Python_220415.7z  
1、增加sms_sts类(SMS/STS舵机)与scscl类(SCS舵机)  
2、优化同步读稳定性  