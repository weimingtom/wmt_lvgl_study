# wmt_lvgl_study
My LVGL study

## TODO：
* 请有时间补充一下工具链信息  
* 研究一下https://gitee.com/mFlying/ssd2xx-demo  

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

## (TODO) 100ask lvgl doc  
* https://100ask-lvgl-doc.readthedocs.io/zh/latest/  

## 野火-华芯微特 SWM32SRET6, 4.3 inch, 480x272  
* https://doc.embedfire.com/products/link/zh/latest/mcu/synwit/swm32sret6.html  
* (IMP) SWM32S开机综合例程.rar, lvgl v6.1.2 (?), or ebf_swm32s_code_20230324.zip      
* SWM320_Lib-210810.rar  

## 华芯微特带屏幕接口的开发板  
* (has screen interface, SWDM-LQ64-32SRE04, ATK-4342) SWM32SRET6-50-800_480电容触摸液晶屏LCD模块TFTSWDM-LQ64-32SRE_华芯微特  
* (has screen interface, 19S显示开发板 屏驱-SWXS-LQ48-19SCB02, JLT35002A) SWM19SCBT6-50_LQFP48最小系统板_华芯微特  
* (no screen interface) SWM320VET7-LQ100-32101最小系统板_华芯微特  
* (not bought, has screen interface, ATK4342, TFT 4.3) SYNWIT34SVEA3显示开发板 屏驱_华芯微特, SWM34S_demo800×480_HMI030_PC.rar  

## ESP32 LVGL, esp32-2432s028r, 2.8inch_ESP32-2432S028R, esp32, 240x320, ili9341?    
* 2.8inch_ESP32-2432S028R.zip  
* https://qiita.com/sylphy_00/items/77f5b9d5fdba85860d9d  
* http://www.jczn1688.com/zlxz  

## TK032F8004 smart_IoT  
* TK499_LTDC_TK032F8004_LVGL.zip  

## STM32F429IGTx, 适用于野牛开发板的 LittlevGL 的 demo 程序  
* 有 MDK 版本和 VS 模拟器版本  
* https://gitee.com/mzy2364/LittlevGL_Demo  
* 101.LittleVGL GUI SDK资料, LittlevGL 20201231.rar, 开源GUI LittlevGL应用.pdf  

## gd32f450  
* https://gitee.com/tinnu/littlevgl_gd32f450  

## esp32-s2-hmi-devkit-1  
* https://www.espressif.com.cn/zh-hans/solutions/hmi/esp-hmi  
* https://github.com/espressif/esp-dev-kits/tree/master/esp32-s2-hmi-devkit-1/examples/get-started/hello_world  
* https://docs.espressif.com/projects/espressif-esp-dev-kits/en/latest/esp32s2/esp32-s2-hmi-devkit-1/user_guide.html#getting-started  

## ttgo t-watch  
* https://github.com/sharandac/My-TTGO-Watch  
This is factory firmware ???  
see also https://github.com/xvno/my-ttgo-watch  
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
* 简单介绍一下我入手的T-Watch-2020-v3的出厂固件，似乎是开源的，  
二进制固件在TTGO_TWatch_Library的bin目录，源码是在My-TTGO-Watch。  
可能有几个，我下面的截图来源于xvno/my-ttgo-watch，  
实际运行会没有桌面图（黑色），需要自己设置。  
实际效果和这些截图有不同，但大概的布局是差不多的  
* display bmp: ips2_0_esp32_ganyu_twatch_2020_v3.rar  
* display fonts and bmp: ips2_0_esp32_v2_success_twatch_2020_v3.7z  
* fill with rgb: fillScreen_v1_twatch_2020_v3_success.7z  

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

## 桌面天气时钟  

## arduino 旋转太空人 天气时钟源码来啦 esp8266  

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

