# wmt_lvgl_study
My LVGL study

## TODO：
* 请有时间补充一下工具链信息  
* 研究一下https://gitee.com/mFlying/ssd2xx-demo  
* https://github.com/weimingtom/wmt_ai_study/blob/master/gui_001.md  

## dino  
* wio rp2040, waveshare 2 inch 320x240 st7789, circuitpython:  
dino_v2_2inch_wio_rp2040_success_important.rar   
* dino arduino port  
dino_twatch2020v3_v7_success.rar  
dino_twatch2020v3_v8_faster.rar  

## ttgo t-watch  
* https://github.com/sharandac/My-TTGO-Watch  
This is factory firmware ???  
see also https://github.com/xvno/my-ttgo-watch  
factory firmware, twatch-2020-v3-220531.bin   
https://github.com/Xinyuan-LilyGO/TTGO_TWatch_Library/blob/master/bin/2020-v3/twatch-2020-v3-220531.bin  
* test firmware, 2020-V3_Speaker.bin  
https://github.com/Xinyuan-LilyGO/TTGO_TWatch_Library/blob/master/bin/2020-V3_Speaker.bin  
https://github.com/Xinyuan-LilyGO/TTGO_TWatch_Library/blob/master/examples/UnitTest/HardwareTest/HardwareTest.ino  
https://github.com/jackp803/TTGO_TWatch_Lilbarray/blob/master/examples/UnitTest/HardwareTest/HardwareTest.ino  
Play Audio!  
* https://github.com/Xinyuan-LilyGO/TTGO_TWatch_Library  
* https://t-watch.readthedocs.io/zh_CN/latest/index.html  
* https://t-watch-document-en.readthedocs.io/en/latest/index.html  
* https://www.ui.cn/detail/50032.html  
* https://blog.csdn.net/weixin_42413377/article/details/119258212  
* https://zhuanlan.zhihu.com/p/80828378  
* https://github.com/projetsdiy/T-Watch-Projects  
* https://github.com/lixy123/TTGO_T_Watch_Baidu_Rec  
* https://github.com/spaceAngel/cyberWatch  
* https://github.com/SkUrRiEr/T-Watch2020-BluetoothScan  
T-Watch2020-BluetoothScan.7z  
* 简单介绍一下我入手的T-Watch-2020-v3的出厂固件，似乎是开源的，  
二进制固件在TTGO_TWatch_Library的bin目录，源码是在My-TTGO-Watch。  
可能有几个，我下面的截图来源于xvno/my-ttgo-watch，  
实际运行会没有桌面图（黑色），需要自己设置。  
实际效果和这些截图有不同，但大概的布局是差不多的  
* display bmp: ips2_0_esp32_ganyu_twatch_2020_v3.rar  
* display fonts and bmp: ips2_0_esp32_v2_success_twatch_2020_v3.7z  
* fill with rgb: fillScreen_v1_twatch_2020_v3_success.7z  
* SmallDesktopDisplay ready to port (no wifi, not twatch, only 240 screen and bread board):   
SmallDesktopDisplay_v3_success.rar  
* SmallDesktopDisplay twatch port:   
SmallDesktopDisplay_v5_twatch2020v3.rar  
* dino arduino port  
dino_twatch2020v3_v7_success.rar  
dino_twatch2020v3_v8_faster.rar  
* 微雪代码演示背景图显示  
watchdemo_twatchv3_v1_success.rar  
* round clock from Seeed_Arduino_RoundDisplay  
round_clock_twatchv3_v1.rar  
https://github.com/Seeed-Studio/Seeed_Arduino_RoundDisplay  
* LilyGO-T-Watch-Demo  
https://github.com/lewisxhe/LilyGO-T-Watch-Demo  

## SmallDesktopDisplay_2432S028R, Arduino IDE, Program ROM Flash not enough (for NodeMCU-32S and st7789 ips 240x240)    
* Board: ESP32 Dev Module  
* Partition Scheme: Huge APP (3MB No OTA/1MB SPIFFS)   
* SmallDesktopDisplay_v4.rar  
* 4_11_SmallDesktopDisplay.rar  

## (origin) ESP8266wifi天气时间站  
* SD²固件V1.2.zip  
* https://oshwhub.com/wo-niu-ke-ji/ESP8266wifitian-qi-shi-jian-zhan  

## 桌面天气时钟  
* 1.33寸ESP12F-8266创意智能复古迷你手工麦金塔WIFI桌面天气时钟  
* search baidupan, A MIni 资料  
* SmallDesktopDisplay  

## arduino 旋转太空人 天气时钟源码来啦 esp8266  
* SmallDesktopDisplay ???  

## Windows VS2013 port (with FastFireFrame)    
* lvgldemo_501_v5_input_pass.rar  
* lvgldemo_530_v2_run_success.rar  
* lvgldemo_612_v1_success.rar  
* lvgldemo_711_v1_success.rar  

## WT32-SC01 (ESP32 wrover) port  
* lvgldemo_v3_success_wt32_self_lvgl.rar  
* lvgldemo_v4_swap_color.rar  
```
idf version, see esp-idf-4.3_v2_200m.part01.rar  
https://github.com/wireless-tag-com/8ms-esp32    
wt32-sc01-8ms-esp32-main.zip  
```

## (TODO) ZX3D50CE02S_USRC_4832, ESP32-S3 wrover    
* sdk-8ms-esp32-release-2.1_run_ok.rar  
* https://gitee.com/qiming-zhixian/sdk-8ms-esp32/tree/release%2F2.1/  
* please use 2.1, not 2.2, adapting to the version in https://8ms.xyz/projects/esp32  
* install esp-idf-tools-setup-offline-4.4.3.exe  
```
(cd to sdk-8ms-esp32-release-2.1)  
idf.py set-target esp32s3  
(copy config\ZX3D50CE02S_USRC_4832\lib*.a->components\xxx\*.a)  
(copy config\ZX3D50CE02S_USRC_4832\sdkconfig to top)  
(get source.zip from my 8ms online project menu, download source, see https://8ms.xyz/projects/esp32)  
(unzip source.zip to components\qmsd_ui, remove origin files)  
idf.py fullclean  
idf.py menuconfig  
q (or ESC)  
idf.py build  
idf.py flash  
```

## (TODO) WT32-SC01-PLUS  
* https://github.com/Skorpi08/WT32-SC01-PLUS  
* https://github.com/dudals-jung/WT32-SC01-PLUS-LVGL-IDF  
* https://github.com/WojciechowskiMarek/WT32-SC01-Plus_ESP32-S3_JIngle_Bells  
* https://github.com/FCam1/SC01_Plus_HMI_example  

## Android port  
* (NOT DONE) search baidupan, lvgldemo_android_v2.rar  

## csky port  
* csky_v2_success.tar.gz  

## Mangopi MQ or Sipeed LicheeRV Dock, Allwinner D1 / D1s / F133-A port  
* https://gitee.com/RCSN/lv_port_linux_frame_buffer_mq_d1s  
* lvgl_demo_v5.tar.gz  

## Mangopi MQ-Dual, Allwinner T113-S3  
* lv_port_linux_frame_buffer_t113_v1.tar.gz  

## d1, nezha    
* lv_port_linux_frame_buffer_nezha_d1_hdmi_event3_git.tgz  
* (toolchain:) Xuantie-900-gcc-linux-5.10.4-glibc-x86_64-V2.2.4-20211227.tar.gz  
* (d1s, SDL) SDL-1.2.15_makefile_v7_keyboard_failed.tar.gz  

## 芒果派MQ的lvgl_demo源代码出处  
https://bbs.aw-ol.com/topic/303/哪吒d1开发板-lvgl7-源码下载-带git仓库/31?lang=zh-CN  
我似乎找到芒果派MQ的lvgl_demo源代码出处，应该是在这里：《哪吒d1开发板-lvgl7-源码下载-带git仓库》，  
在aw-ol.com的bbs上，有份代码叫lv_port_linux_frame_buffer_nezha_d1_hdmi_event3_git.tgz，  
里面有个文件mouse_img.c就是鼠标光标的图片  

## ssd202d 7inch   
* search baidupan, lv_port_linux_frame_buffer_arm_v1.tar.gz  
* for IDO_SBC2D07  
* 工具链：gcc-arm-8.2-2018.08-x86_64-arm-linux-gnueabihf.tar.gz  
http://doc.industio.com/docs/ido-sbc2d06/ido-sbc2d06-1cu14t7bq11de  
好像是和树莓派的arm-linux-gnueabihf-gcc交叉工具链通用，  
甚至可以直接把树莓派3b上gcc编译出来的elf搬过来运行  

## ssd202d lvgl 7.10   
* https://github.com/caszhao/ssd_lvgl  
* LVGL7.10-linux_framebuffer-SSD202-TEVET-PACK-20210223.tar  
* SSD20X直接编译lvgl7.10带双缓（附源码）  
* https://whycan.com/t_6043.html  
* for IDO_SBC2D07 ???  

## ssd202d ido-lvgl8.2, 1024x600   
* 虽然是用于IDO-SBC2D06 (Purple Pi R1 ???), 但实际上可能也只是for IDO_SBC2D07
* 很可能也是7寸屏或转接成7寸屏，看配置是1024x600，不确定  
* https://github.com/industio/ido-lvgl8.2  
* http://doc.industio.com/docs/ido-sbc2d06/ido-sbc2d06-1duplsnvbelfj  
* /home/ronnie/work3/ssd201/gcc-arm-8.2-2018.08-x86_64-arm-linux-gnueabihf/bin/arm-linux-gnueabihf-gcc  

## (TODO) ssd202d demo   
* https://gitee.com/mFlying/ssd2xx-demo/tree/master/4.littlevgl  

## STM32F429I-DISC1, 240x320, LVGL8      
* STM32Cube_FW_F4_V1.27.0_v6_lvgl_good_stm32f429i_disc1.rar  
* https://github.com/lvgl/lv_port_stm32f429_disco  
* https://github.com/app-z/stm32f429_ili9341  

## 君正MIPS, 青联X2000, 1024 * 600, from ssd202d version, static link (gcc -static)    
* lv_port_linux_frame_buffer_x2000_lvgl_v1.tar.gz  
* ABS_MT_POSITION_X define see https://blog.csdn.net/Chuangke_Andy/article/details/122454299  
* see lv_drivers/indev/evdev.c  
* see https://gitee.com/RCSN/lv_port_linux_frame_buffer_mq_d1s  
```
//see include/uapi/linux/input.h
#ifndef ABS_MT_POSITION_X
#define ABS_MT_POSITION_X 0x35
#endif

#ifndef ABS_MT_POSITION_Y
#define ABS_MT_POSITION_Y 0x36
#endif
```
* 工具链（因为libc对不上，需要-static静态编译）：gcc-4.3-ls232/bin/mipsel-linux-gcc  

## f1c200s lcd_test.bin    
* https://github.com/nminaylov/F1C100s_projects  
* https://github.com/nminaylov/F1C100s_LVGL  
* https://github.com/motoedy/minimal_f1c100s_fb_zlggui  
```
fatload mmc 0:1 80000000 firmware.bin  
go 80000000  
```
```
2021-7-30  
昨天试了一下，把f1c200s的u-boot的sd卡运行模式跑通了（fatload命令），  
不过nand flash的引导方法仍然没有头绪。fatload有个几个缺点，  
是要先保证tf卡是FAT文件系统，这个可能有点坑，因为可能会提示缺分区表  
（我是拿PSP2000去格式化TF卡），其次，需要先引导到u-boot，  
这里有个技巧，就是先按住BOOT按钮reset进入FEL，  
然后通过from-fel-to-dfu.bat进入DFU模式，  
而其实所谓的DFU模式就是U-BOOT，只不过会卡住等待，  
这时候在串口控制台按Ctrl+C中断即可回到U-BOOT命令行，  
然后通过fatload mmc 0:1 80000000 lcd_test.bin
和go 80000000即可运行（参考nminaylov/F1C100s_projects），  
我更想知道能否用类似的方法引导nand flash的代码，  
如果可以的话就可以解决nand引导问题
```
* from-fel-to-dfu, see mpi-r-tools.zip  
* see https://mangopi.org/f1c_flashrom  
* see https://wiki.dfrobot.com.cn/_SKU_DFR0780_MangoPi-R3  
* git clone https://github.com/Icenowy/sunxi-tools.git -b f1c100s-spiflash  
* https://github.com/Icenowy/sunxi-tools/tree/f1c100s-spiflash  
```
sudo apt install gcc-arm-none-eabi

用PSP格式化FAT文件系统的tf卡，把lcd_test.bin复制到tf卡上

>from-fel-to-dfu.bat
(ttyS) Ctrl+C
=> help
=> fatload mmc 0:1 80000000 lcd_test.bin
=> go 80000000

sunxi-fel -p spiflash-write 0x000000 simple_loader.bin
sunxi-fel -p spiflash-write 0x10000 lcd_test.bin

(x) dfu-util -s 0x000000 -D simple_loader.bin
(x) dfu-util -s 0x010000 -D lcd_test.bin
```
* lcd_test.bin see F1C100s_projects-master_v1.tar.gz\F1C100s_projects-master\_tools_\mksunxi  
* lcd_test.bin see F1C100s_projects-master_v1.tar.gz\F1C100s_projects-master\lcd_test\build  
* search baidupan, F1C100s_projects-master_v1.tar.gz  
* ? use DiskGenius401Pro  

## (TODO) 智能虚拟电子研发室, f1c200s  
* search F1C200s_V1_2_1.zip  
* (转载，不是我做的）F1C200S裸机MDK+LVGL+GT911电容屏（从网上RTX+EMWIN例程上改的有BUG）  
(转载，不是我做的）最近做了一块F1C200S的板子，驱动800x480分辨率的电容屏，  
好不容易在网上找了一个MDK的RTX+EMWIN例程在这基础上改  
成无系统+LVGL+GT911电容屏  
see https://whycan.com/t_7187.html  
* F1C200S串口屏板, 立创电路图    
https://oshwhub.com/lg508612189/f1c200s-chuan-kou-ping-ban  

## F1C100S_Linux lvgl, F1C100S/F1C200S系统构建    
* (origin) https://github.com/huanghl365/LittlevGL  
* (origin) https://github.com/huanghl365/LittlevGL/blob/master/Doc/03.F1C100S_Linux/F1C100S_Linux.md  
* (dead) https://littlevgl.readthedocs.io/en/latest/Doc/03.F1C100S_Linux/F1C100S_Linux.html    

## 小淘气, f1c200s    
* F1C100S_keil开发文件，较大的那个压缩包里面有（有两个，小的那个是在csdn下载的，大的那个是在闲鱼买的）  

## (TODO) 100ask lvgl doc  
* https://100ask-lvgl-doc.readthedocs.io/zh/latest/  

## 野火-华芯微特 SWM32SRET6, 4.3 inch, 480x272  
* https://doc.embedfire.com/products/link/zh/latest/mcu/synwit/swm32sret6.html  
* (IMP) SWM32S开机综合例程.rar, lvgl v6.1.2 (?), or ebf_swm32s_code_20230324.zip      
* SWM320_Lib-210810.rar  

## 华芯微特带屏幕接口的开发板, 有各种不同UI库（不限于LVGL）的移植模板  
* (has screen interface, SWDM-LQ64-32SRE04, ATK-4342) SWM32SRET6-50-800_480电容触摸液晶屏LCD模块TFTSWDM-LQ64-32SRE_华芯微特  
* (has screen interface, 19S显示开发板 屏驱-SWXS-LQ48-19SCB02, JLT35002A) SWM19SCBT6-50_LQFP48最小系统板_华芯微特  
* (no screen interface) SWM320VET7-LQ100-32101最小系统板_华芯微特  
* (not bought, has screen interface, ATK4342, TFT 4.3) SYNWIT34SVEA3显示开发板 屏驱_华芯微特, SWM34S_demo800×480_HMI030_PC.rar  

## ESP32 LVGL, esp32-2432s028r, 2.8inch_ESP32-2432S028R, esp32, 240x320, ili9341?    
* 2.8inch_ESP32-2432S028R.zip  
* https://qiita.com/sylphy_00/items/77f5b9d5fdba85860d9d  
* http://www.jczn1688.com/zlxz  

## TK032F8004 smart_IoT, TKM32F499    
* TK499_LTDC_TK032F8004_LVGL.zip  

## STM32F429IGTx, 适用于野牛开发板的 LittlevGL 的 demo 程序  
* 有 MDK 版本和 VS 模拟器版本  
* https://gitee.com/mzy2364/LittlevGL_Demo  
* 101.LittleVGL GUI SDK资料, LittlevGL 20201231.rar, 开源GUI LittlevGL应用.pdf  
* Bison-Board, 野牛开发板, 野牛STM32F429手持机/开发板/工控/HMI    
* 出自：野火swm32/01.SYNWIT技术应用资料/00.其它公用资料/101.LittleVGL GUI SDK资料  

## gd32f450  
* https://gitee.com/tinnu/littlevgl_gd32f450  

## esp32-s2-hmi-devkit-1  
* https://www.espressif.com.cn/zh-hans/solutions/hmi/esp-hmi  
* https://github.com/espressif/esp-dev-kits/tree/master/esp32-s2-hmi-devkit-1/examples/get-started/hello_world  
* https://docs.espressif.com/projects/espressif-esp-dev-kits/en/latest/esp32s2/esp32-s2-hmi-devkit-1/user_guide.html#getting-started  

## watchio  
* https://github.com/eggfly/WatchIO  

## watchx  
* https://github.com/FASTSHIFT/WatchX  

## watchy  
* https://github.com/sqfmi/Watchy  

## PineTime  
* https://github.com/InfiniTimeOrg/InfiniTime  

## zepp os  
* https://github.com/zepp-health/zeppos-samples  

## picoclock  
* https://www.waveshare.net/wiki/RP2040-LCD-1.28  
* https://github.com/dawigit/picoclock  

## OpenWatch  
* https://www.eetree.cn/project/detail/152  
* https://github.com/Open-Smartwatch/open-smartwatch-os  

## N|Watch  
* https://github.com/Soysauce007/WatchX-Nwatch-stm32  
* https://blog.zakkemble.net/diy-digital-wristwatch/  
* https://github.com/ZakKemble/NWatch  
## ESP32墨水屏开发板_4寸_北京物联网开发  

## win10_idd_xfz1986_usb_graphic_driver_display  
* https://github.com/chuanjinpang/win10_idd_xfz1986_usb_graphic_driver_display  

## waft (with wasm???)    
* https://www.yuque.com/waft/docs/pv8ktt  
* https://chuangke.aliyun.com/waft  
* https://wiki.sipeed.com/hardware/zh/lichee/RV/86_panel.html  
* npm i waft-cli -g  

## haasui, 阿里云智显系列/智显面板ASP-80/AIoT小程序框架引擎/8寸触摸屏  
* 阿里云智能硬件官方旗舰店  
* https://www.yuque.com/wcye0k/haasui/lqwximddosvrr4yi  
* https://www.yuque.com/wcye0k/haasui/lytxwk#ncO5O  
* haas-ui-simulator-mac-v2.zip  
* haasui-simulator-windows-64.zip  
* https://www.yuque.com/wcye0k/haasui/lytxwk#ncO5O  
* sudo apt-get install libsdl2-dev  
* haas-ui-simulator-ubuntu.zip  
* sudo cnpm i aiot-vue-cli -g   

## Pico-RGB-Matrix-P3-64x32  
* https://www.waveshare.net/wiki/Pico-RGB-Matrix-P3-64x32  

## 1.28inch LCD Module  
* https://www.waveshare.net/wiki/1.28inch_LCD_Module  

## T-Wristband  
* https://github.com/yacubovvs/CubOS  
* https://github.com/Xinyuan-LilyGO/T-Wristband  
* https://github.com/Xinyuan-LilyGO/LilyGo-T-Wristband/tree/master/examples/T-Wristband-MAX30208  
* https://github.com/Xinyuan-LilyGO/LilyGo-T-Wristband-NRF52  

## HaaS EDU k1  
* https://github.com/alibaba/AliOS-Things/blob/dev_3.1.0_haas/application/example/edu_demo/k1_apps/aircraftBattle/aircraftBattle.c  
* https://github.com/weimingtom/AliOS-Things/tree/dev_3.1.0_haas  
* https://haas.iot.aliyun.com/haasapi/index.html#/Python/docs/zh-CN/startup/HaaS_EDU_K1_startup  

## lvgldemo  
* search baidupan, lvgldemo_v4_run_success.rar

## LittlevGL, LVGL  
* Light and Versatile Embedded Graphics Library  
* https://littlevgl.com

## lvgl esp32  
* https://github.com/lvgl/lv_port_esp32
* https://github.com/wireless-tag-cn/lv_port_esp32

## 荔枝派
* https://wiki.sipeed.com/soft/Lichee/zh/Nano-Doc-Backup/application/littlevgl.html  
(old, not available) http://nano.lichee.pro/application/littlevgl.html  
see https://github.com/STRfarfar/sipeed_wiki/blob/master/docs/soft/LicheeOS/Nano-Doc-Backup/application/littlevgl.rst  
see https://github.com/Lichee-Pi/Nano-Doc-Backup/blob/master/application/littlevgl.rst  
see https://github.com/Lichee-Pi/Lichee-Nano-Doc-us-english/blob/master/application/littlevgl.rst  
* https://github.com/littlevgl/lvgl
* https://github.com/littlevgl/lv_drivers
* https://github.com/littlevgl/lv_examples

## maixduino  
* see maixduino examples  

## framebuffer LVGL    
* https://blog.lvgl.io/2018-01-03/linux_fb  
* https://github.com/lvgl/lv_port_linux_frame_buffer  
* https://blog.csdn.net/tq384998430/article/details/96841247  

## Omega2 Dash  
* https://onion.io/omega2-dash-guide/  
* https://github.com/OnionIoT/lv_micropython  
* https://github.com/OnionIoT/Omega2-Dash/blob/master/demo/littlev-demo/main.c  
* 实际上对于LVGL，即使不使用编辑器和代码生成器技术，也可以玩，  
那就是把官方的例子拿来魔改，例如这个：  
OnionIoT/Omega2-Dash/blob/master/demo/littlev-demo/main.c  
它应该是把一个名叫lv_test_theme_2的方法拿来演示，  
但我认为这样非常好看（图转自onion.io/omega2-dash-guide）  


## TL2855_2082-2121  
* https://github.com/dwcsunshine/TL2855_2082-2121  

## f1c_nonos  
* https://github.com/minilogic/f1c_nonos  

## f1c100s_boot  
* https://github.com/Saoskywalker/f1c100s_boot  
* https://github.com/Saoskywalker/micropython_for_f1c100s  
* https://github.com/hcly/f1c100s  

## gsm-weather-esp32s3-esp-idf5.0, (ESP32桌面看台)gsm-weather-esp32s3版本  
* https://gitee.com/gsm-wheather-project/gsm-weather-esp32s3-esp-idf5.0  
* https://gitee.com/gsm-wheather-project  
* https://www.bilibili.com/video/BV1VU4y1v7VD/  

## Footleg/arduino/T-Watch-2000  
* https://github.com/Footleg/arduino/tree/master/T-Watch-2000  
* https://www.bilibili.com/video/BV1QV411m7SX/  
* LilyGo TWatch 2020 Arduino Framework 老外T-Watch的框架(中英字幕)  

## 如何优雅地用micropython下一个代码雨？  
* https://blog.csdn.net/jd3096/article/details/125354986  

## 副屏制作, HellGateMonitor    
* https://github.com/Hotakus/HellGateMonitor  

## 3.5寸IPS TYPEC副屏机箱  
* Wall.rar  

## ESP32-S2 副屏  
* https://github.com/chuanjinpang/win10_idd_xfz1986_usb_graphic_driver_display  
* https://oshwhub.com/an_ye/cube-415_-zhuo-mian-fu-ping  

## 小方屏时钟（Lite）程序, NXEZ Cube 小方屏 T1/T1 DHT10 定制套件 ESP8266 天气时钟 OLED  
* https://make.quwj.com/project/231  
* https://github.com/nxez/cube-clock-lite  

## BL618, m0pdock  
* https://github.com/bouffalolab/bouffalo_sdk/tree/master/examples/lvgl/demos  
* https://github.com/sipeed/M0P_BL618_examples/blob/main/sipeed_support/examples/m0pdock/pt/src/pt.c  
* https://wiki.sipeed.com/m0p  

## k210 maixduino lvgl  
* https://github.com/lvgl/lv_port_maixduino  
* https://github.com/sipeed/Maixduino/tree/master/libraries  
* https://github.com/lvgl/lv_port_maixduino/tree/6bcae290e53020bd4abbc089fd483635df3b0a3d  

## M1s DOCK 开发板, BL808 RISC-V Linux     
* https://gitee.com/Sipeed/M1s_BL808_example/blob/main/c906_app/lvgl_demo/main.c  
* https://wiki.sipeed.com/hardware/zh/maix/m1s/m1s_dock.html  
* https://wiki.sipeed.com/m1s  
* https://github.com/sipeed/M1s_BL808_Linux_SDK  
* https://github.com/bouffalolab/bouffalo_sdk  
* https://gitee.com/sipeed/M1s_BL808_example  
* https://gitee.com/sipeed/M1s_BL808_SDK  

## ART-Pi, stm32h750    
* https://art-pi.gitee.io/website/  
* https://blog.csdn.net/weixin_37127273/article/details/110134225  
* https://blog.csdn.net/qq_43610430/article/details/120152946  
* https://gitee.com/mirrors/ART-Pi/tree/master/tools/firmware  
* https://blog.csdn.net/toopoo/article/details/113105148  
* https://github.com/luhuadong/FCTC-ART-Pi-Code  
* 

## lvgl_demo_music  
* https://github.com/RT-Thread-packages/lv_demo_music  

## ES32 SDK, Eastsoft东软载波, ES32F36xx  
* https://www.essemi.com/index/product/detail?id=799  
* 嵌入式软件, ES32_SDK 1.20  
* LVGL 6.0.0, ES32_SDK.zip, ES32_SDK_V1.12/Middlewares/Third_Party/lvgl_V6.0  
* LVGL 8.3.3, ES32_SDK-V1.20.7z\ES32_SDK-V1.20\ES32_SDK-V1.20\Middlewares\Third_Party\lvgl  

## NUC  
* LVGL-v8.3.4 : https://github.com/OpenNuvoton/LVGL_NUMAKER-HMI-N9H30/tree/master/packages/LVGL-v8.3.4  
* LVGL 5.1.1: https://github.com/OpenNuvoton/AliOS-Things/tree/numicro/3rdparty/experimental/gui/littlevGL  
* https://github.com/luhuadong/NuMaker-N9H30-Player    

## 梁山派, GD32F470ZGT6    
* https://blog.csdn.net/qq_51930953/article/details/129313750  
* LVGL 8.2.0, 梁山派LVGL移植RGB-480x800_v0.7z    
* https://lckfb.com/docs/lspi_rgb_mcu_lcd_ex/#/屏幕扩展板资料下载  
* https://lckfb.com/project/detail/lspi_rgb_mcu_lcd_ex  
* 梁山派屏幕代码.zip  
* liangshan-lvgl_v1_success.rar  

## QF ZERO V2 智能手表终端 (closed source)  
* QF_ZERO_V2_V1_0_0.zip  
* https://oshwhub.com/dhx233/esp32_s3_watch  

## esp32_monitor  

## HPM6750  
* ebf_hpm6750_code_20230331.zip\lv_demo_widgets\lv_demo_widgets\middleware\littlevgl   
* https://doc.embedfire.com/products/link/zh/latest/mcu/hpmicro/ebf_hpm6750.html  

## nes-lvgl-rtt  
* https://github.com/greedyhao/nes-lvgl-rtt  

## vocore2 sdl lvgl  
* https://github.com/Vonger/vocore2/tree/master/utils/lvgl-fb-demo  
* https://vocore.io/screen.html  
* http://vonger.cn/misc/screen/lvgldemo.zip  
* http://vonger.cn/misc/screen/20200927.bin.xz  
* https://vocore.io/screen-notouch.html  

## minipad  
* https://gitee.com/Jumping99/minipad  
* https://www.bilibili.com/video/BV1Yo4y1w7qs  

## mangopi tina lvgl packages  
* https://github.com/mangopi-sbc/tina-package/tree/main/gui/littlevgl-8  
* https://github.com/mangopi-sbc/tina-package/tree/main/gui/littlevgl-6  

## flutter-embedded-linux  
* https://github.com/sony/flutter-embedded-linux  
* https://github.com/sony/flutter-elinux  

## 诛仙剑C-SKY  
* csky_v2_success.tar.gz  
* csky-linux-gcc: csky-linux-tools-x86_64-glibc-linux-4.9.25-20170522.tar.gz  
* usb.img  

## a33 lvgl  
* 用a33-vstar开发板运行lvgl_demo（lvgl v7），热量还可以（不是很厉害），  
fb0 800 480，dev input event2对应鼠标。触摸屏输入还不行，  
以后再想办法（可以移动但不可以点击）。偷懒没有编译evtest，  
只是通过getevent查询输入设备  
* lv_port_linux_frame_buffer_arm_a33_v1.tar.gz  

## melis orange  
* https://github.com/Tina-Linux/d1s-melis/tree/master/emodules/mod_orange/GUI  
* https://github.com/Tina-Linux/d1s-melis/blob/master/livedesk/beetles/sun20iw1_app/apps/app_root/app_root_scene.c  
* https://github.com/yilanjueding123/quanzhiwork  

## 哔哩哔哩小电视  
* https://gitee.com/wangpeng25/the-little-bili-tv  

## ESP_MASTER  
* https://github.com/Kevincoooool/ESP_MASTER  

## LicheeRV dock hdmi, etc/rc.d/S99tinatest, waft_app, waftapps/app_wifi.wasm  
* LicheeRV_Tina_dock_hdmi_8723ds.img  

## 荔枝派zero, licheepi zero, with touch screen      
* (TODO, not done) lv_port_linux_frame_buffer_licheezero_v2_input.tar.gz, see below another vocore version     
* (new lvgl demo, using vocore2 version, no console cursor)    
lvgldemo.zip  
lvgldemo_v1_licheepizero_from_vocore2.tar.gz  
demo  
* (gcc toolchain) gcc-linaro-6.3.1-2017.05-i686_arm-linux-gnueabihf.tar.xz  
* (linux rom, need written with mount under virtualbox ubuntu 1404) Zero_pub_V0.3.gz  
* (evtest) evtest-master_v1_zero.tar.gz  
* (burn tools) Win32DiskImager-1.0.0-binary.zip  
* (touch screen) CJ050QGH50-05442Y-01 2023-01-03, FOG-050QGH113-40, 5inch touch screen, bought from sipeed    
* lv_port_linux_frame_buffer例子, 显示控制台的白色方块光标, 不太好看      
```
用Win32DiskImager-1.0.0-binary烧录tf卡Zero_pub_V0.3.gz/test.img
接usb（供电和虚拟网卡？），并且需要另外用FT232接UART0调试串口115200-8-1-none-none，u口非串口
针脚图：https://wiki.sipeed.com/soft/Lichee/zh/Zero-Doc/Start/intro_cn.html
屏线向上，左上9和左上10是UART0-TX，UART0-RX，右上7是GND
密码：root/licheepi

tf卡挂载在ubuntu下修改（virtualbox选择读卡器USB设备连接）
$ ls /media/wmt/
$ sudo ls /media/wmt/50641143-6315-449a-b9e6-d8fe8b4d75aa/root/
$ sudo cp /media/wmt/50641143-6315-449a-b9e6-d8fe8b4d75aa/root/demo demomod

工具链：
https://releases.linaro.org/components/toolchain/binaries/6.3-2017.05/arm-linux-gnueabihf/
gcc-linaro-6.3.1-2017.05-x86_64_arm-linux-gnueabihf.tar.xz
gcc-linaro-6.3.1-2017.05-i686_arm-linux-gnueabihf.tar.xz
use ubuntu140432, i686

测试ev
https://blog.csdn.net/phmatthaus/article/details/127748541
$ ls /dev/input
$ cat /proc/bus/input/devices 
$ cat /dev/input/event1
event0是键盘，event1是触摸屏？

测试lvgl_demo
记录5寸触摸屏型号：CJ050QGH50，FOG-050QGH113-40
lv_drv_conf.h
EVDEV_CALIBRATE
#  define EVDEV_CALIBRATE         0               /*Scale and offset the touchscreen coordinates by using maximum and minimum values for each axis*/
#  if EVDEV_CALIBRATE
#    define EVDEV_HOR_MIN   3800                    /*If EVDEV_XXX_MIN > EVDEV_XXX_MAX the XXX axis is automatically inverted*/
#    define EVDEV_HOR_MAX   200
#    define EVDEV_VER_MIN   200
#    define EVDEV_VER_MAX   3800
#  endif  /*EVDEV_SCALE*/
```
* vocore例子, 可以不显示控制台的光标  

## RT595  
* https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt595-evaluation-kit:MIMXRT595-EVK  

## watch  
* https://blog.csdn.net/StarEmbedded/article/details/105751357  
STM32F413-DISCOVERY  
* https://github.com/Open-Smartwatch/open-smartwatch-os  
* https://github.com/lxydiy/lvgl-watch   
* https://github.com/STMicroelectronics/STM32CubeG0/blob/master/Projects/STM32G0C1E-EV/Demonstrations/Modules/calendar/app_calendar.c  

## LVGL_Watchface  
* https://github.com/moononournation/LVGL_Watchface  
* https://www.instructables.com/Design-Watch-Face-With-LVGL/  
* https://www.hackster.io/news/chen-liang-s-smart-arduino-watch-faces-are-built-with-lvgl-and-squareline-studio-125a84c86c8f  

## ZSWatch  
* https://github.com/jakkra/ZSWatch  

## waveshare 1.28 inch watch, demo bg picture    
* https://www.waveshare.com/wiki/RP2040-LCD-1.28  
* RP2040-LCD-1.28.zip\RP2040-LCD-1.28\c\examples\ImageData.c  
* https://www.waveshare.com/wiki/1.28inch_Touch_LCD  
* 1.28inch_Touch_LCD_RPI.zip\1.28inch_Touch_LCD_RPI\c\pic\LCD_1inch28_1.bmp  
* 1.28inch_Touch_LCD_RPI.zip\1.28inch_Touch_LCD_RPI\c\examples\image.c  
* https://www.waveshare.net/wiki/1.28inch_LCD_Module  
* LCD_Module_code.zip\RaspberryPi\python\pic   
* https://www.waveshare.net/wiki/1.28inch_Touch_LCD  
* 1.28inch_Touch_LCD_Demo.zip\1.28inch_Touch_LCD_Demo\RPI\python\pic  
* 转换后的图片和字体，微雪示例中自带的背景图, picmodpng和font    

## (touch not good) LicheeRV Dock 800 480 screen extention board    
* not good, 触摸屏屏线接口没用, 暂时不知道怎么触摸  
* test 800x480 screen    
```
/usr/bin/waft_app /waftapps/app_wifi.wasm
dfbdump
dfbshow
dfbshow /usr/share/directfb-examples/dfblogo.png
dfbshow /root/sipeed.png
/usr/bin/waft_app /root/render_example.wasm
/usr/bin/waft_app /root/render_example_d1_allwin.wasm
```
* LicheeRV_Tina_dock_800480_8723ds.img有启动画面  
* LicheeRV_Tina_800480.7z无启动画面，但可以显示800x480  
* 屏幕扩展板，虽然有触摸口，都不支持触摸屏（最好用mangopi或者licheerv 86盒）  
* 注意屏线都是金属向上  
* (burn tools) PhoenixCard.zip, V4.2.8    

## vocore2 lvgl demo, not work    
* 5寸屏用v2u(vocore2开发板白色立方体)没跑通，可能要自己编译或者分辨率没对上，反正没点亮  
* toolchain.tar.bz2  
* lvgldemo.zip  
* fbusb.vocore2.ko  
* vodisp和lvgldemo无法运行, vodisp提示libusb so缺少, demo运行没有显示（分辨率不对？）      

## (touch screen good) 芒果派MQ（非R版）
* (firmware) tina_d1-mangopi_mq_rgb800x480_gt9xx_uart0_可能修复了某些显示屏问题_2021-12-24.7z  
* (burn tools) phoenixcard4.2.8.zip  
* 自带启动LVGL例子 
* (not good firmware for touch) mq-r-f133-rtl8189fs-5113-dns-uart0.zip  
* (not good firmware, color strange) tina_d1-mangopi_mq_rgb800x480_gt9xx_uart0_20211214.img  
* (touch screen) bought from mangopi, 5inch, 800x480, XJW050-GQ 2022.11.21, F500G4024-Q01, STC911-19, gt911  

## Seeed_Arduino_RoundDisplay  
* https://github.com/Bodmer/TFT_eSPI/blob/master/examples/320%20x%20240/TFT_Clock/TFT_Clock.ino  
* https://github.com/Bodmer/TFT_eSPI/tree/master/examples/Sprite/Animated_dial  
* https://wiki.seeedstudio.com/XIAO-RP2040-with-Arduino/#software-setup  
* https://www.sohu.com/a/659807701_121124373  
* https://github.com/Seeed-Studio/Seeed_Arduino_RoundDisplay  
* https://github.com/Seeed-Studio/Seeed_Arduino_RoundDisplay/blob/main/examples/TFT_eSPI_Clock/TFT_eSPI_Clock.ino  

## e_ink_word_card_2in13, 单词卡  
* https://github.com/zhushengji/e_ink_word_card_2in13  
* https://www.bilibili.com/video/BV1SU4y1Z7PC/  
* https://oshwhub.com/zhushengji/213-mo-shui-ping-dan-ci-ka-tf-ban-ben  

## smart-word-esp32  
* https://gitee.com/BenBuYikk/smart-word-esp32  


