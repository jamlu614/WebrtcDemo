# metaRTCDemo
集成metartc7.0去qt操作界面的app服务，流媒体服务器是srs的demo,demo是linux x86平台  

srs流媒体服务器地址设置  
在根目录/yangpush/VideoPush.h,修改string m_url = "http://175.178.181.116:1985/rtc/v1/whip/?app=live&stream=livestream" 变量  

编译与运行  

方法一、用vscode打开,编译后把yang_config.ini配置文件放在build目录下即可运行  

方法二、cmake命令编译  
在项目根目录下依次执行  
mkdir build  
cd build  
cmake ..  
cp ../yang_config.ini .(注意不要把.省略)  
./rtcApp  
命令后运行
