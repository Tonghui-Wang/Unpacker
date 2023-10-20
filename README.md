# Unpacker
Automatic Unpacking Machine

Upper_PC：上位机，负责人机交互显示部分。  
基于Knico Green系列7寸触摸屏，使用Kinco Dtools工具进行界面组态编辑。  
  
Lower_PC：下位机，负责底层逻辑处理部分。  
基于VMMORE PC4M系列PAC控制器，使用Codesys V3.5.16工具进行程序逻辑编辑。  
  
Upper_PC和Lower_PC之间，通过Modbus TCP协议进行数据传输。  
