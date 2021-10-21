
/**********************************************************************
项目名称/Project		: 小电视_天气
程序名称/Program name	: AutoConnect_Weather_Oled
作者/Author		: 一只狍
日期/Date（YYYYMMDD）	: 20200816
程序目的/Purpose		:通过WiFiManager库配置ESP8266连接到互联网
                          		通过ESP8266WebServer库从心知天气获取天气信息
                          		通过U8g2lib库实现OLED显示
______________________________________________________________________
OLED：4pin IIC引脚，正面看，从左到右依次为GND、VCC、SCL、SDA
     OLED  ---  ESP8266
     VCC   ---  3.3V
     GND   ---  G (GND)
     SCL   ---  D1(GPIO5)
     SDA   ---  D2(GPIO4)
***********************************************************************/