# wmt_lvgl_study
My LVGL study

## Working  
* https://github.com/weimingtom/luban-lite_fork  
* https://github.com/weimingtom/lvgl_android_port  
* TODO, https://github.com/weimingtom/luban-lite_fork_tools_vs2013  
* https://github.com/weimingtom/wt32sc01

## TODO：
* 请有时间补充一下工具链信息  
* 研究一下https://gitee.com/mFlying/ssd2xx-demo  
* https://github.com/weimingtom/wmt_ai_study/blob/master/gui_001.md  
* port OneWatch  
* st77903_demo.7z  
* https://gitee.com/lai-shanhai/esp32-s3-lvgl-ec11-st7789    
* OLED-Menu.rar
* lvgldemo_android_v2.rar  
SDL1 android ref: VideoProject_v2_play_audio_success.7z  
SDL? ref: VideoProject.rar  
* https://github.com/paulsykes/Pinetime
* https://github.com/ck-telecom/pinetime
* https://github.com/arteeh/pinetime/tree/v1
* https://github.com/search?q=app_weather.c&type=code
* https://github.com/Emeryth/sma-q2-oss/blob/master/app/app_weather.c
* (TODO) dino, ESP32C3_1.90Inch.zip   
* TODO
```
novel press
F:\12_old_old_yingpan3\novel-press

cii20
F:\12_old_old_yingpan3\cii

gtk dfb
F:\12_old_old_yingpan\linux_resource_backup\gtk-linux

directfb
F:\12_old_old_yingpan\linux_resource_backup\ubuntu20121205

framebuffer
F:\12_old_old_yingpan\linux_resource_backup\ubuntu20121205\fb_study
linux, fb
F:\12_old_old_yingpan\linux_resource_backup\gtk\system\temp

fdb  
* F:\12_old_old_yingpan3\fdb_mod

PDF阅读器分tab
MuPDF Example
baidupan：mupdf111a_v2.rar
mupdf111a.apk

不拆SoC，不用X光机，利用已知IO探测未知的IO连接情况  
https://whycan.com/t_5486.html

milk-v duo soft spi
showbmp_milkv_v2_img.tar.gz
showbmp_milkv_v1_basic.tar.gz
软spi接线方法：showbmp_milkv_v2_img_pin.txt
我知道为什么我之前交叉编译milk-v duo的hello运行会不成功——因为它需要配置正确的march和mabi参数。。。详细见milkv-duo/duo-examples的envsetup.sh。奇怪的是，如果是静态编译的话居然可以不加这些参数。可能加了这些march参数，用算能官网的工具链大概也是可以的吧（它也带了一个musl的工具链）
如果图片不存在，img(bmp）版会崩溃（段错误）
用milk-v duo软SPI驱动1.44寸屏st7735（非ips）效果如下，跟luckfox pico一样，软spi会很慢。另外，不知道为什么，tf卡要带电重插，可能要往tf卡上方用拇指向下（向板面）压一下，否则引导会失败（提示tf卡挂载失败）。virtualbox挂载tf卡写入交叉编译文件，旧固件复制elf文件不需要sudo，但新固件需要，我这里用旧固件20230616，但用的交叉工具链是duo-sdk-v1.2.0（需要指定march mcpu等）。对应的sysfs文件号对应针脚图我自己写了一份。全部用右侧排针

key input
ssd2xx-demo-master.zip\ssd2xx-demo-master\7.gpio\gpio_test_input
https://gitee.com/mFlying/ssd2xx-demo/blob/master/7.gpio/gpio_test_input/main.c
http://doc.industio.com/docs/ido-som2d0x-start/ido-som2d0x-start-1ctpju1ek2b27
https://github.com/OpenNuvoton/NUC970_Linux_Applications/blob/master/demos/gpio/gpio_demo.c
https://github.com/OpenNuvoton/NUC980_Linux_Applications/blob/master/demos/gpio/gpio_demo.c
https://github.com/OpenNuvoton/N32905_Linux_Applications/blob/master/gpio/gpio.c
https://github.com/OpenNuvoton/N32926_Linux_Applications/blob/master/gpio/gpio.c

znzpi

未上传移动硬盘中的龙芯派相关文件，太大了
硬盘:/loongson_upload


https://github.com/wiringX/wiringX
https://milkv.io/zh/docs/duo/application-development/wiringx#准备开发环境
目前已知的类Arduino的Linux BSP SDK，不完全收录（有些板代码不集中）：（1）第一梯队：树莓派的wiringpi，NanoPi的WiringNP和matrix，香橙派的wiringOP，香蕉派的BPI-WiringPi。（2）第二梯队：嵌入式Linux接口开发技术的v3s bsp，龙芯派的Loongson-Smartloong-V2.0和OpenLoongsonLib1c和Ls1bTest，ssd202d的ssd2xx-demo，Tinker board（RK3288）的GPIO_API_for_C.zip（3）第三梯队：vocore2的mem.zip

https://forum.walnutpi.com/t/topic/74
sudo apt-get install nestopia
https://github.com/0ldsk00l/nestopia
https://sourceforge.net/projects/nestopiaue/files/1.52/nestopia_1.52.0-win32.zip/download
http://0ldsk00l.ca/nestopia/

```
* TODO

## 小志掌机研究, GAMEPI20掌机研究    
* lv_port_linux_frame_buffer_xiaozhi_v1.tar.gz  
* work_gamepi_v3.7z
* https://wiki.sipeed.com/soft/Lichee/zh/Zero-Doc/Drive/GPIO_file.html  
不需要，因为小志掌机用的是gpio-keys驱动，被/dev/input/event1键盘设备占用  

## dino  
* wio rp2040, waveshare 2 inch 320x240 st7789, circuitpython:  
dino_v2_2inch_wio_rp2040_success_important.rar   
* dino arduino port  
dino_twatch2020v3_v7_success.rar  
dino_twatch2020v3_v8_faster.rar  
* (IMP, TODO) dino, ESP32C3_1.90Inch.zip
* https://github.com/weimingtom/dino_twatch2020v3  

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
* https://github.com/chuxin520922/SmallDesktopDisplay  
* https://github.com/SmallDesktopDisplay-team/SmallDesktopDisplay  
* https://github.com/yangwu91/SmallDesktopDisplay-ESP32  

## arduino 旋转太空人 天气时钟源码来啦 esp8266  
* SmallDesktopDisplay ???  

## esp32-weather-clock-idf, like SDD  
* https://github.com/amwyyyy/esp32-weather-clock-idf  

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
* ref:
SDL1 android ref: VideoProject_v2_play_audio_success.7z
SDL? ref: VideoProject.rar  

## csky port  
* csky_v2_success.tar.gz  

## Mangopi MQ or Sipeed LicheeRV Dock, Allwinner D1 / D1s / F133-A port  
* https://gitee.com/RCSN/lv_port_linux_frame_buffer_mq_d1s  
* lvgl_demo_v5.tar.gz  
* (toolchain) Xuantie-900-gcc-linux-5.10.4-glibc-x86_64-V2.2.4-20211227.tar.gz  

## LicheeRV 86 panel  
* lv_port_linux_frame_buffer_licheerv_panel_v1.tar.gz  
* (toolchain) Xuantie-900-gcc-linux-5.10.4-glibc-x86_64-V2.2.4-20211227.tar.gz  

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

## (IMP) PineTime  
* https://github.com/InfiniTimeOrg/InfiniTime  
* https://wiki.pine64.org/index.php/PineTime
* (IMP, old version, with preview photo) https://github.com/paulsykes/Pinetime
* https://www.pine64.org/pinetime/
* (IMP, UI design) https://github.com/arteeh/pinetime
* https://github.com/search?q=app_heartrate&type=code
* https://github.com/search?q=lvgl+app_menu+language%3AC&type=code  
* (IMP, zephyr) https://github.com/ck-telecom/pinetime
* ST7789, 240 * 240, https://github.com/paulsykes/Pinetime/blob/master/doc/PinetimeStubWithNrf52DK.md
* search baidupan, work_infinitime_v1_sim.tar.gz
* search baidupan, work_pinetime_v1.tar.gz
* https://github.com/joaquimorg/PineTime40
* https://wiki.pine64.org/index.php/PineTime
* https://wiki.pine64.org/wiki/PineTime_Development
* burn:  
```
用nRF52 DK（nrf52832）和中景园7脚st7789 240方形屏幕搭建的PineTime模拟效果，如下，  
比较简单（暂时不知道怎么切换其他功能）。烧录方法是（可以不接DETECT到地和按钮），  
同时烧录pinetime-app.hex和s132_nrf52_6.1.1_softdevice.hex即可。  
app会从0x26000开始烧录，而软设备会同时包含mbr分区，从0x0跳到0x26000，  
如图橙色和蓝色是mbr和软设备，绿色是app分区  
```

## zepp os  
* https://github.com/zepp-health/zeppos-samples  

## picoclock  
* https://www.waveshare.net/wiki/RP2040-LCD-1.28  
* https://github.com/dawigit/picoclock  

## OpenWatch  
* https://www.eetree.cn/project/detail/152  
* https://github.com/Open-Smartwatch/open-smartwatch-os  
* Paul’s 3D Things  
* https://open-smartwatch.github.io  

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

## (TODO) 3.5寸IPS TYPEC副屏机箱  
* Wall.rar  
* OpenHardwareMonitor  
* https://github.com/openhardwaremonitor/openhardwaremonitor  
* (TODO) 做一个类似的可以传输像素的上位机  

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
* (not good) LVGL 8.2.0, 梁山派LVGL移植RGB-480x800_v0.7z    
* https://lckfb.com/docs/lspi_rgb_mcu_lcd_ex/#/屏幕扩展板资料下载  
* https://lckfb.com/project/detail/lspi_rgb_mcu_lcd_ex  
* 梁山派屏幕代码.zip  
* (this work) liangshan-lvgl_v1_success.rar
* (not good) LSPi_RGB_LVGL8_DEMO.zip  
* (not good) LSPi_RGB_LVGL8_DEMO-450版.zip
* 【游戏机扩展板】资料, 游戏机扩展板屏幕采用了SPI通讯的240*280像素的1.69寸IPS高清圆角屏幕。  
https://lceda001.feishu.cn/wiki/H9adw4sgriCUuakDPYEc83kInqC
* 屏幕扩展版: https://lceda001.feishu.cn/wiki/K8axwug8uiTdFDkZfcocdlZanve  
* RGB屏幕: https://lceda001.feishu.cn/wiki/PoX9w07gfikAI7kaj6ecTmH3nZM  

## QF ZERO V2 智能手表终端 (closed source)  
* QF_ZERO_V2_V1_0_0.zip  
* https://oshwhub.com/dhx233/esp32_s3_watch
* (SquareLine smart watch demo, Windows emulator) lvgl_demo_watch_code_blocks.zip  

## esp32_monitor  

## HPM6750  
* ebf_hpm6750_code_20230331.zip\lv_demo_widgets\lv_demo_widgets\middleware\littlevgl   
* https://doc.embedfire.com/products/link/zh/latest/mcu/hpmicro/ebf_hpm6750.html  

## nes-lvgl-rtt  
* https://github.com/greedyhao/nes-lvgl-rtt  

## vocore2 sdl(?) lvgl  
* https://github.com/Vonger/vocore2/tree/master/utils/lvgl-fb-demo  
* https://vocore.io/screen.html  
* http://vonger.cn/misc/screen/lvgldemo.zip  
* http://vonger.cn/misc/screen/20200927.bin.xz  
* https://vocore.io/screen-notouch.html  
* see https://vocore.io/v2u.html  
see https://vonger.cn/misc/screen/  
see https://vonger.cn/misc/screen/20200628.touch.bin.xz  
```
1. use PC wireless connect to your VoCore hotspot, open browser view 192.168.1.1 or 192.168.61.1 (I use 61.1).  
2. LuCI console using username: root, password: vocore,  
3. select "System" -> "Backup/Flash Firmware"   
4. uncheck 'keep settting', and "Flash Image". choose 20200628.touch.bin  
5. after flashing, will auto start running /root/demo, it's a LVGL demo program  
```

## (old record) vocore2 lvgl demo, not work (see upper)      
* 5寸屏用v2u(vocore2开发板白色立方体)没跑通，可能要自己编译或者分辨率没对上，反正没点亮  
* toolchain.tar.bz2  
* lvgldemo.zip  
* fbusb.vocore2.ko  
* vodisp和lvgldemo无法运行, vodisp提示libusb so缺少, demo运行没有显示（分辨率不对？）      
* 解决  
```
我搞明白怎么用vocore2运行LVGL例子和驱动usb屏幕，之前失败其实是因为fbusb.ko的
驱动程序不兼容（因为需要和内核版本完全一样才能正确运行），
所以要么重新编译内核或者重新编译驱动程序。然后我想起其实可以通过wifi来刷固件，
然后找了一下，发现有个touch固件自带fbusb驱动和LVGL，刷完就可以看到LVGL例子
（开机启动，不需要insmod）。具体效果略，因为触摸比较卡顿，可能和屏幕速度
或者mt7628主频低有关，也许作者不想明说

（更旧的记录）
vocore的LVGL示例代码，对比起mangopi mq的LVGL示例代码，似乎都是7.0的lvgldemo，
但改动较大，有些代码莫名地改了，跟原版不同，但好处是可以似乎可以隐藏控制台光标。
至今没办法跑在vocore2开发板方块上，但可以通过修改（一些修改）跑在荔枝派zero上，
所以如果想省事，建议还是用mq的lvgldemo去改，vocore版的奇怪改动太多了
```


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
* (?) https://github.com/u-blox/ubxlib  
* (nrf52833 dk, ncs 2.2.0) ZSWatch_v1_v2_run_success.rar     
* (zephyr display demo, nrf52833 dk, ncs 2.2.0, with or without LVGL)  
gc9a01a_zephyr_driver_app_v7_lvgl.rar  
* (nrf5340 dk, ncs 2.3.0) ZSWatch_v2_v5_succss_no_sleep_touch.7z
* (nrf5340 dk, ncs 2.3.0) ZSWatch_v2b_v1_success.7z  
* (zephyr display demo, nrf5340 dk, ncs 2.3.0)  
gc9a01a_zephyr_driver_app230_run_success.rar
* nrf52833 pins to GC9A01, SPI1    
```
//MISO P1.08
//MOSI P0.30
//SCK P0.31
//CS0 P0.16	
---
//GND: GND
//VCC: VDD
//SCL: P0.31
//SDA: P0.30
//RES: P0.03
//DC:  P1.00
//CS: P0.16 -> P1.03
//BLK: P0.26
```
* nrf5340 pins to GC9A01, SPI4    
```
//MISO P1.14
//MOSI P1.13
//SCK P1.15
//CS0 P0.06
---
//GND: GND
//VCC: VDD
//SCL: P1.15
//SDA: P1.13
//RES: P0.25
//DC:  P0.07
//CS:  P0.06 -> P1.03
//BLK: P1.06->VCC (waveshare version touch round screen is high)
```
* https://docs.zephyrproject.org/latest/boards/arm/ubx_evkninab4_nrf52833/doc/index.html  
* https://docs.zephyrproject.org/latest/boards/arm/nrf5340dk_nrf5340/doc/index.html  
* https://docs.zephyrproject.org/latest/boards/arm/nrf52833dk_nrf52833/doc/index.html  

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
* T-QT, Anti-aliased_Clock, like TFT_eSPI_Clock  
* https://github.com/Xinyuan-LilyGO/T-QT/blob/main/lib/TFT_eSPI/examples/Smooth%20Graphics/Anti-aliased_Clock/Anti-aliased_Clock.ino  

## e_ink_word_card_2in13, 单词卡  
* https://github.com/zhushengji/e_ink_word_card_2in13  
* https://www.bilibili.com/video/BV1SU4y1Z7PC/  
* https://oshwhub.com/zhushengji/213-mo-shui-ping-dan-ci-ka-tf-ban-ben  

## smart-word-esp32  
* https://gitee.com/BenBuYikk/smart-word-esp32  

## ESP32S3_86盒开发板_带触摸  
* https://oshwhub.com/myzhazha/esp32s3_86-kai-fa-ban  
* https://github.com/TAMCTec/gt911-arduino  
* 1.3版本demo.zip  

## ESP32-S3-RGB-Panel, 86盒, wywy  
* https://github.com/W00ng/ESP32-S3-RGB-Panel  
* https://github.com/W00ng/ESP32-S3-RGB-Panel/blob/square-screen/examples/mp3_player/main/ui_audio.c  
* https://github.com/W00ng/ESP32-S3-RGB-Panel/blob/square-screen/examples/lvgl_demo/main/main.c  

## ESP32_Display_development_board  
* https://github.com/HazemBenAmmar/ESP32_Display_development_board  

## rgb_panel  
* https://github.com/espressif/esp-idf/tree/master/examples/peripherals/lcd/rgb_panel  
* https://blog.csdn.net/ami82/article/details/123106350  

## esp32s3_lilygo_8bit_parallel_display_lvgl  
* https://github.com/UsefulElectronics/esp32s3_lilygo_8bit_parallel_display_lvgl  
* https://forum.lvgl.io/t/lilygo-t-display-s3/10638  
* https://github.com/Makerfabs/Makerfabs-ESP32-S3-Parallel-TFT-with-Touch/tree/main/example  

## makerfabs  
* https://www.makerfabs.com/esp32-s3-parallel-tft-with-touch-ili9488.html  
* https://github.com/Makerfabs/Makerfabs-ESP32-S3-Parallel-TFT-with-Touch/tree/main/example  
* https://github.com/radiosound-com/makerfabs-parallel-tft-lvgl-lgfx/tree/master/main  

## T-RGB  
* https://github.com/Xinyuan-LilyGO/T-RGB/blob/main/examples/factory/factory.ino  

## EspMon, with openhardwaremonitor    
* https://www.codeproject.com/Articles/5343526/EspMon-A-simple-PC-hardware-monitor-using-a-T-Disp  
* https://github.com/codewitch-honey-crisis/EspMon_TDisplayS3/tree/master  
* https://github.com/yltsa/EspMon_TDisplayS3--black-screen-/blob/main/src/ui.c  
* https://github.com/codewitch-honey-crisis/EspMon/blob/master/EspMon.cs  
* https://github.com/openhardwaremonitor/openhardwaremonitor  

## widora spi screen    
* https://widora.cn/ips  

## sipeed m1s  
* https://blog.csdn.net/weixin_43810563/article/details/128276764  

## retro-esp32  
* https://github.com/retro-esp32  

## esplay, esplay micro  
* https://github.com/pebri86/esplay_micro_hardware  
* https://github.com/pebri86/esplay-retro-emulation  
* https://github.com/pebri86/esplay-base-firmware  
* https://github.com/pebri86/esplay-micro-firmware-collections  

## EVUE  
* https://scriptiot.gitee.io/evue_doc/#/zh-cn/evue_explore  
* https://www.codercto.com/a/119710.html  
* https://github.com/scriptiot/evm/releases/download/v2.0/evuesimulator-windows-v2.0.zip  

## 学了3天的littleVGL做了一个手表, OneWatch, STM32F411    
* https://www.bilibili.com/video/av757399659  
* search baidupan, OneWatch.rar  
* nucleo f411re: OneWatch_Soft_f411re_v1.rar  
* f411ceu6: OneWatch_Soft_v1_success_缺面包板接线图.rar  

## sinlinx v3s, 800x480 touch screen lvgl_demo       
* lv_port_linux_frame_buffer_sinlinx_v3s_v1.tar.gz  
```
$ mkdir /mnt/mmc
$ mount /dev/mmcblk0p1 /mnt/mmc
$ ls /mnt/mmc
$ cd /mnt/mmc
$ ps
$ kill -KILL 124
$ dd if=/dev/zero of=/dev/fb0 bs=3200 count=480
$ ./lvgl_demo_sinlinx_v3s
```
* (toolchain) sinlinx-v3s-sdk_20200824_buildroot_out_host.tar.gz  
```
$ cd sinlinx-v3s-sdk
$ ./build.sh buildroot
(then get toolchain under buildroot/out/host/bin)
```
* 评测  
```
我入手了sinlinx的v3s开发板，5寸屏800分辨率，试过跑LVGL非常流畅，
不过这个板有一些不太方便的地方：交叉工具链可能需要buildroot编译获取，
这比较花时间；调试串口UART0需要另外找USB-TTL转换工具连，而且可能会接触不好
（没提供线缆连接调试串口）；u口不能供电（host u口），但四线串口可以供电，
或者用提供的供电电源线；用的是nand flash，由于用Qt导致剩余空间不够
（可以用tf卡扩展或者nfs），启动速度不够快（因为这个板支持无线联网），
支持的接口多，但开发板较大；触摸屏效果不错，但跑Qt可能触摸不太流畅
（可能因为控件小不好按），但LVGL是足够流畅
```
* 图片轮播
```
用sinlinx v3s开发板运行lvgldemo的效果如下。触摸屏分辨率800，5寸，非ips，所以斜角会变色。
代码不是我写的，来源于lv_port_linux_frame_buffer_mq_d1s，如果要显示图片那个效果，
需要把main函数里面的setup_ui放到lv_demo_widgets前面，注释掉lv_demo_widgets。
我认为很流畅，非常顺手，当然这个板开发起来也不是很方便，要频繁切换tf卡（我是通过tf卡运行程序）
```
* 工具链需要编译buildroot, 不要用external-toolchain那个工具链，会运行不了（c库so不对）  
sinlinx-v3s-sdk_20200824_buildroot_out_host.tar.gz  
```
$ cd sinlinx-v3s-sdk
$ ./build.sh buildroot
(then get toolchain under buildroot/out/host/bin)
ubuntu140432
don't use this gcc: #CC = /home/wmt/work_sinlinx/sinlinx-v3s-sdk/tools/external-toolchain/bin/arm-linux-gnueabi-gcc
use this gcc: CC = /home/wmt/work_sinlinx/sinlinx-v3s-sdk/buildroot/out/host/bin/arm-buildroot-linux-gnueabihf-gcc
```

## M1S Dock  
* 评测    
```
简单评价一下sipeed的M1S Dock开发板
（1）发热感人（如果用来实时图像处理）
（2）有一个类似的M0P，也是博流，但屏幕更大
（3）U盘烧录很方便，但按下reset松开然后松开两侧按钮时，松开两侧要慢一拍，不能太快，
否则会看不到烧录U盘，而是看到另一个U盘，而这个非烧录用的U盘居然可以存文件的
（3）实在不知道怎么用串口烧录，现在没跑通
（4）出厂的程序不知道为什么接OTG线后不运行，需要按一下reset按钮才会真正运行
（5）出厂的屏幕屏线和摄影都已经是安装好（粘住底板），不能拆（难拆）
（6）还没试编译，可能比较麻烦，但有提供预先编译的固件
（7）研究Linux可能不太好（驱动不全），因为K210已经可以跑Linux，
而这个有多个烧录核心，可能不太有普遍研究价值（比较另类）
```

## STM32 N-Watch开源项目 浅谈原理（一）菜单及动画部分  
* https://www.bilibili.com/video/BV1wT411o71X  
* WATCH.zip  

## squareline  
* Smartwatch_sdl2_ubuntu1404_v1.tar.gz  

## Gui Guider  
* GUI-Guider-Projects.7z  

## open-watch  
* https://github.com/SMotlaq/open-watch    
* https://github.com/SMotlaq/open-watch/blob/master/open-watch-firmware/my_watch_software/Src/main.c  
* openwatch_v5_run_success.rar  

## 富芮坤fr8008gp lvgl  
* https://blog.csdn.net/cheng___yi/article/details/128633517  
* st7789v 240x280  
* fr8000-master_v1_run_lvgl_success.rar  
* fr8000_lvgl_watch_240x280-master_v1_run_success.rar  

## OV-Watch  
* https://github.com/No-Chicken/OV-Watch_V1.1  

## haasui  
* https://haas.iot.aliyun.com/haasui-doc/demo-clock  
* https://gitee.com/yocop/smart_panel_lvgl  

## LCDwiki 1.28inch IPS Module  
* http://www.lcdwiki.com/zh/1.28inch_IPS_Module  
* https://robot-jp.com/wiki/index.php/%E3%83%A1%E3%82%A4%E3%83%B3%E3%83%9A%E3%83%BC%E3%82%B8  

## Music Player  
* https://www.instructables.com/Design-Music-Player-UI-With-LVGL/  

## 瑞萨 renesas DA1470x watch demo  
* https://github.com/dialog-semiconductor/BLE_SDK10_DA1470x_examples  
* https://github.com/dialog-semiconductor/BLE_SDK10_DA1470x_examples/tree/main/features/watch_demo_lvgl/ui  
* https://lpccs-docs.renesas.com/DA1470x/UM-B-155_DA1470x-Graphics-Framework-GUI/8-Watch%20Demo%20Application/watch_demo.html
* DA14706-00HZDEVKT-P Energy DA14706 Development  

## NXP RT595 watch demo  
* https://www.nxp.com/video/smart-watch-demo-running-on-an-i-mx-rt595-evk:SMARTWDEMO  
* https://info.cranksoftware.com/platforms/demo-images/nxp/imx-rt500  
* https://www.cranksoftware.com/platforms/demo-images/nxp  
* https://community.nxp.com/t5/i-MX-RT/Smartwatch-GUI-Demo-Images-for-the-NXP-i-MX-RT500/m-p/1305591  

## 20 Beautiful Examples of SmartWatch UI  
* https://inspirationfeed.com/smartwatches/   

## Makerfabs, ESP32-S3 Round SPI 1.28" TFT with Touch  
* https://github.com/Makerfabs/ESP32-S3-Round-SPI-TFT-with-Touch-1.28/blob/main/example/clock/clock.ino  
* https://www.makerfabs.com/esp32-s3-round-spi-tft-with-touch-1-28-inch.html  
* https://www.makerfabs.com/open-smartwatch.html  

## M5Stampラウンド液晶モジュール  
* https://github.com/urukakanko/M5Stamp_round_lcd  

## RsPicoラウンド液晶モジュール  
* https://github.com/urukakanko/RsPico_round_lcd/blob/main/RsPico_round_lcd_ClockSample/RsPico_round_lcd_ClockSample.ino  

## ラウンド液晶モジュール for XIAO RP2040（組立キット）  
* https://github.com/urukakanko/XIAO_Round_LCD/blob/main/xiao2040_round_clockSample/xiao2040_round_clockSample.ino  

## ESP32 ScreenShotReceiver  
* https://github.com/lovyan03/ESP32_ScreenShotReceiver  

## NesCat  
* https://github.com/stivcen01/NesCat1.0_ESP32/tree/main/EXAMPLES/_NESemulator  

## gitee  
* https://gitee.com/Xh1024/smart-watch-dial/blob/master/watch/watch.7z  
LVGL windows mingw  
* https://gitee.com/rieo/xzx_stm32/blob/master/code/jiaju/USER/main.c  
* https://gitee.com/serendipityO_O/watch/blob/master/健康监测智能手表（STM32F4主控）/Future_Watch_V2.0省赛.zip  

## Casio F91-W watch    
* https://pars41.github.io/casio-digital-watch/  
* https://github.com/kjs452/casio  
* https://github.com/adamfratino/casio-watch  
* https://github.com/Interaction-Magic/casio-watch-prototyper  
* https://watch.interactionmagic.com  
* Sensor Watch, A hackable ARM Cortex M0+ upgrade for a classic Casio wristwatch  
https://www.crowdsupply.com/oddly-specific-objects/sensor-watch  
https://github.com/joeycastillo/Sensor-Watch  

## 百问网, SetTime   
* https://gitee.com/weidongshan/lv_100ask_linux_desktop/blob/master/lv_100ask_app/src/imx6ull_app/imx6ull_set_time/src/set_time.c  
* 【lvgl项目开发】IMX6ULL Linux LVGL GUI V2.0效果演示，基于lvgl8.1开源并且有lvgl教程 littleVGL  
https://www.bilibili.com/video/BV1nT4y1R7rz  
* https://github.com/100askTeam/lv_100ask_linux_desktop/blob/master/lv_100ask_app/src/imx6ull_app/imx6ull_set_time/src/set_time.c  

## fr5086  
* https://gitee.com/freqchip/fr5080-dsp/blob/master/fr5080_user_code_xip/src/components/module/gui/lv_gui_app/lv_obj_test.c  
* https://gitee.com/freqchip/fr5080-dsp/blob/master/fr5080_user_code_xip/src/example/main.c  

## Android  
* https://github.com/dodola/BubbleCloudView  

## HTML5  
* https://github.com/wanlong1234567/html5-apple-watch-clock-face  

## esp8266-smartwatch  
* https://github.com/Jeija/esp8266-smartwatch  

## sma-q2-oss  
* https://emeryth.net/sma-q2-open-source-smartwatch/  
* https://github.com/Emeryth/sma-q2-oss  

## lempo_smart_watch  
* https://github.com/elmot/lempo_smart_watch  

## mutantW_V1  
* https://mutantc.gitlab.io/mutantW_V1.html  
* https://gitlab.com/mutantC/mutantw-v1/-/tree/main/  

## Bangle.js 2 is a Hackable, Open Source Smartwatch  
* https://www.omgubuntu.co.uk/2021/09/bangle-js-2-is-a-hackable-open-source-smartwatch-that-runs-javascript  

## DA14580, 【开源教程8】疯壳·开源蓝牙心率防水运动手环-三轴计步伐  
* https://blog.csdn.net/efans_Mike/article/details/126545676  
* https://www.bilibili.com/video/av845131734/  
* 【开源】疯壳BLE蓝牙DA14580开发板1-1整板测试  
* 四合一健康智能手表  
* https://www.fengke.club/goods/96  

## DA14580, csdn  
* 鬼斧神工智能穿戴开源制作—可编程手环，可实现任何功能  
* https://download.csdn.net/download/ZCY5202015/13747537  
* 蓝牙DA14580智能手环开发教程  
* https://download.csdn.net/download/fengkesz/9861218  

## DA14580  
* https://www.renesas.com/us/en/general-parts/da14580-smartbond-bluetooth-low-energy-42-soc#design_development   
* https://github.com/dialog-semiconductor/BLE_SDK6_examples  

## mbed, smart watch  
* https://os.mbed.com/users/kewlsrini/notebook/smart-watch/  
* https://os.mbed.com/users/nsloth/code/Smart_Watch_4180_Final_Design//file/65e1d74a137c/main.cpp/  

## 【开源】ESP32智能手环  
* https://www.bilibili.com/video/BV1it4y1s7AY  
* https://github.com/lpeydb/ESP32-SmartBand  
* https://gitee.com/lpeydb/ESP32-SmartBand  

## 自制ESP32智能手表Open Smartwatch  
* https://www.bilibili.com/video/BV14F411g7V3  
* https://github.com/Open-Smartwatch/open-smartwatch-os  

## Let's make Smartwatch ESP32  
* https://www.bilibili.com/video/BV1EA4y1Z7To  
* https://github.com/VolosR/watchESP  

## SmartBracelet - 拆除便宜的Dialog DA14580智能手环  
* https://github.com/melka/SmartBracelet  
* https://www.nuomiphp.com/github/zh/600afe4949768d2c76177926.html  

## 21ic, 【N32G430开发板试用】智能手表功能演示样机  
* https://bbs.21ic.com/icview-3241354-1-1.html  

## FarSightWatch, JZ4775    
* http://download.hqyj.com/download/pdf/Android_DIY.pdf  
* http://www.fsdev.com.cn/products/index3.htm  

## SmartBand, STM32L053  
* https://github.com/westzhao13/SmartBand  

## duband  
* https://github.com/baiduwearable/duband  
* 百度智能手环开源项目资料.rar  
* 百度智能手环方案开源(含源码，原理图，APP，通信协议等)  
* https://blog.csdn.net/whik1194/article/details/85270812
* (???) https://github.com/sommer78/HeartRate/tree/master/wrist-rom-master-code
* 智能手环，基于Nordic公司nRF51822芯片开发，芯片集成BLE蓝牙4.0协议。使用LIS3DH作为加速度传感器，进行运动和睡眠监测.rar
https://download.csdn.net/download/luoqiaosheng/11045020  

## cherrypi  
* http://wiki.lcmaker.com/index.php?title=首页  

## 智能手环(STM32F411)  
* https://github.com/XR-bin/STM32-Practice_project/blob/master/智能手环/智能手环(STM32F411)/USER/test.c  

## 姿态手环  
* https://github.com/ActivePeter/2020_TI_competion_question_A/tree/main/%E5%A7%BF%E6%80%81%E6%89%8B%E7%8E%AF  

## WatchX  
* https://github.com/FASTSHIFT/WatchX  
* https://github.com/FASTSHIFT/WatchX-II  
* https://gitee.com/laocaile/WatchX  

## Chronio  
* https://github.com/CoretechR/Chronio  

## Twantch  
* https://github.com/tianxiaohuahua/Twantch  

## LilyGo-HeartRate-Kit  
* https://github.com/Xinyuan-LilyGO/LilyGo-HeartRate-Kit  

## ESP-32_GC9A01_JPG  
* https://github.com/Myzhazha/ESP-32_GC9A01_JPG  
* https://github.com/Myzhazha/ESP-32_GC9A01_JPG/tree/main/Clock_Demo/SmallDesktopDisplay  

## esp32 smart watch  
* (IMP) https://github.com/Circuit-Digest/ESP32-SmartWatch  
* https://download.csdn.net/download/tianqiquan/87740944  
* https://github.com/Minergabe/TTGO-ESP32-T-display-smart-watch  
* https://github.com/Bellafaire/ESP32-Smart-Watch  

## phase, nrf52840  
* https://github.com/carlfriess/phase  

## 杰理, AC701N手表开发板    
* BR28-watch-SDK, ac701n_watch_release_v1.0.0    
* https://gitee.com/Jieli-Tech/fw-AC79_AIoT_SDK/tree/release/AC79NN_SDK_V1.1.0/ui_project  

## esp8266 deauther  
* https://github.com/SpacehuhnTech/esp8266_deauther/releases  
* https://dstike.com/collections/all/deauther#MainContent  
* https://deauther.com/docs/buy  
* https://blog.lanweihong.com/posts/18040/  

## (TODO) 矽创ST77903使用DEMO，环境STM32H743 + RT-THREAD + LVGL + QSPI + ST77903  
* st77903_demo.7z\st77903_demo\stm32h743-sitronix-qspi\applications\lvgl  
* st77903_demo.7z  
* https://download.csdn.net/download/sainty07/87263609  
* https://blog.csdn.net/sainty07/article/details/115422444  
* https://blog.csdn.net/sainty07/article/details/115428136  
* https://github.com/wirano/st77903_demo  

## (TODO) ESP32-C3-LCDkit, 圆形屏, 1.28 inch, 240 x 240, gc9a01     
* https://docs.espressif.com/projects/espressif-esp-dev-kits/zh_CN/latest/esp32c3/esp32-c3-lcdkit/user_guide.html  
* https://github.com/espressif/esp-dev-kits/tree/master/esp32-c3-lcdkit/examples/knob_panel
* https://www.bilibili.com/read/cv22603801  
* https://gitee.com/lai-shanhai/esp32-s3-lvgl-ec11-st7789
* https://github.com/espressif/esp-bsp/tree/master/esp32_c3_lcdkit  

## (TODO) 基于STM32的OLED多级菜单项目（简化版智能手表）  
* https://blog.csdn.net/black_sneak/article/details/126442559  
* https://download.csdn.net/download/black_sneak/86469358  
* OLED-Menu.rar, dino game    

## 健康手表  
* https://github.com/Nuozhihui/Health_watch_STM32  

## AsteroidOS  
* https://github.com/AsteroidOS/asteroid  
* http://asteroidos.org/  

## ESP32-2424S012 development board, LVGL smartwatch  
* 1.28inch_ESP32-2424S012.zip  
* 1.28inch_ESP32-2424S012.zip\1.28inch_ESP32-2424S012\1-Demo\Demo_Arduino\1_1_Factory_samples\Factory_samples  

## (IMP) OM6621PG  
* 手表资料.7z

## (?) RTL8762D  
* https://github.com/ART-Badge/SDK/blob/main/bsp_for_art-badge/libraries/src/app/wristband/lcd_driver/lcd_st7789_240.c  
* https://github.com/ART-Badge/SDK/blob/main/bsp_for_art-badge/libraries/src/app/wristband/firmware/wristband_sim.py

## 瑞昱小蜜蜂RTL8762A的Bee1 SDK  
* https://github.com/sommer78/HeartRate/tree/master/Bee1_SDK_1.1.11894.12638
* https://github.com/sommer78/HeartRate/tree/master/RTL8762  
* Bee1_SDK_1.0.7291.zip  
* Bee1_SDK_Release2.zip  
* baidupan, RTL8762 小蜜蜂 BLE 开发板简介 V0.1  
* (IMP, nrf51822 wrist-rom) https://github.com/sommer78/HeartRate/tree/master/wrist-rom-master-code  

## guix smart watch  
* https://github.com/azure-rtos/guix/tree/master/samples/demo_guix_smart_watch
* https://www.renesas.com/eu/en/video/smart-watch-demo-using-renesas-synergy-guix

## WCH Wristband, 基于CH582M芯片设计的智能手环Demo  
* https://gitee.com/rvmcu/wch-wristband  
* st7735

## CC2541DB, csdn, 智能手环CC2541  
* FUN(BLE4.0)5-15.zip
* https://download.csdn.net/download/yuanwiner/9843244  

## (IMP, diff from duband ?) nrf51822, csdn, with OLED  
* L91_M_815.zip
* https://download.csdn.net/download/qq_28132841/10649279

## 基于STM32的可穿戴手环设计_基于stm32的智能手环, csdn, STM32F411CEUx  
* Project_Hand_Ring+完整版.rar  
* https://download.csdn.net/download/qq_37150405/85040299  

## limitless_wristband  
* https://gitee.com/daierjidetubage/limitless_wristband  
* nRF5_SDK_12.3.0_d7731ad.zip  
* limitless_wristband-master.zip  

## 小安派的LVGL天气站  
* https://docs.ai-thinker.com/eyes  
* 小安派的LVGL天气站（小电视天气），似乎是开源的，基于安信可的BL616无线模块，  
所以很可能要在Linux下开发（工具链应该是risc-v的），  
软件基于GuiGuider，故可以在Windows下模拟运行，大概效果是这样子  
（当然和86盒差不多，可以点击wifi按钮设置网络） ​​​  
* 小安派eyes天气站.zip, with GuiGuider Windows emulator   
* https://github.com/Ai-Thinker-Open/Ai-Pi_Eeys
* https://github.com/Ai-Thinker-Open/Ai-Pi_Eeys/tree/AiPi-Eyes_Weather
* Ai-Pi_Eeys_weather
* 小安派eyes天气站.zip, 小安派eyes天气站.zip\GuiGuider\M6x_Eyes\lvgl-simulator\build\bin\simulator.exe  

## 小安派, aipi dsl watch  
* https://docs.ai-thinker.com/dsl
* https://aithinker.blog.csdn.net/article/details/131547823  
* https://github.com/Ai-Thinker-Open/AiPi-Open-Kits
* https://github.com/Ai-Thinker-Open/AiPi-Open-Kits/tree/master/AiPi-DSL_Watch
* search aipi-dsl-watch_1.28_flash.zip  

## ESP32S3 GC9A01 LVGL Smart Watch  
* https://github.com/UsefulElectronics/esp32s3-gc9a01-lvgl
* https://www.youtube.com/watch?v=Td08fweKXwY  

## nRF52-Smartwatch  
* https://github.com/FleshdeckTV/nRF52-Smartwatch  

## BLE-Watch  
* https://github.com/CharlesDias/BLE-Watch  

## Micro ESP8266一体开发板 微型桌面时钟  
* https://gitee.com/davis-xu/esp8266_-lua_-day-time_-micor  

## qpaperOS  
* https://github.com/qewer33/qpaperOS

## 树莓派音乐播放器, raspberry pi music player, st7789 python    
* https://github.com/u-geek/AOIDE_KAZOO
* https://github.com/u-geek/st7789-python/tree/master/examples
* may be not open source ???  

## T-Display-S3 NES  
* https://github.com/Xinyuan-LilyGO/T-Display-S3/tree/main/example/nes  
* nes_td3s_v2_run_roms.rar  

## fbtft setup, ILI9341-Orange-Pi-Zero  
* https://github.com/headHUB/ILI9341-Orange-Pi-Zero
* search con2fbmap in bing  

## v853 lvgl NES  
* https://www.aw-ol.com/downloads?cat=18  
* https://v853.docs.aw-ol.com/gui/lvgl_demo_2048/  
* https://v853.docs.aw-ol.com/gui/lvgl_nes/  
* https://gitee.com/weidongshan/lv_lib_100ask/tree/master/src/lv_100ask_nes  
* https://blog.csdn.net/qq_35181236/article/details/126020797  
* https://blog.51cto.com/u_13800193/6268770  
* Melis4.0(D1s):4.测试笔记 - 内嵌的显示命令  

## (????TODO) R128 按键，oled  
* https://www.aw-ol.com/downloads?cat=24

## DaFit Magic 3 Smartwatch, nrf  
* https://github.com/atc1441/Magic3_DaFit  

## ? 可能和lilygo屏幕开发板有关的游戏和时钟  
https://github.com/search?q=lilygo+game&type=repositories  
https://github.com/search?q=lilygo%20t-display&type=repositories  
https://github.com/qewer33/qlock-os  

## (TODO) 优感手表, nrf52840, 魔改成ili9341显示（原版不是），注释掉大部分传感器代码   
* smart-watch_top_v4_ili9341.7z  
* 待补充原来的gitee网址  
* https://gitee.com/in_drama/smart-watch    
* smart-watch_top_v1_build_success.7z  

## qt_nes  
* https://gitee.com/Embedfire/ebf_linux_qt_nes?_from=gitee_search  
* https://github.com/nejidev/arm-NES-linux  

## (TODO, 待整理) qt nes  
https://whycan.com/t_7253.html  
qt4-NES4_5_512_480_640_480.7z  
qt4-NES4_5_512_480_640_480_try_high_speed.7z  
https://whycan.com/t_5312.html  
https://github.com/nejidev/arm-NES-linux  
work_qt4_v1_right_color.7z  
qt_nes_whycan_v1.7z  
qt4-nes2_v1_success_ubuntu14_qt4_qws.tar.gz  
https://bbs.aw-ol.com/topic/4208/qt-驅動-rgb-565-顔色不對  
search baidupan, src.zip  

## gamepi20_drivers    
https://github.com/darrenliew96/gamepi20_drivers  

## （TODO） ESPLAY_MICRO_资料_esplay

## ESP32-Watch  
https://gitee.com/liuzewen/ESP32-Watch/tree/master/1.hardware/ESP32手表V2.0  

## InfoNES-1, SDL  
https://www.elecfans.com/d/1906954.html  
https://github.com/qinyunti/InfoNES-1  
cd src/SDL; make  

## directfb  
https://blog.csdn.net/jxgz_leo/article/details/77543906  
https://gitee.com/todoassert/directfb  

## sdl android dummy  
sdl_v3_compile_pass.tar.gz  

## lvgl android  
* lvgldemo_v2_lvgl_android_draw_success.7z  
* ffmpeg player  
VideoProject_v2_play_audio_success(1).7z  

## fbviewer   
http://bbs.sunsili.com/embedded/202212/00000407.html  
root@MaixLinux:~# fbviewer haoran.jpg -f  

## fbviewer, fbv    
http://www.taodudu.cc/news/show-2612635.html?action=onClick  
fbviewer Yuzuki.jpg  
https://blog.csdn.net/weixin_43094346/article/details/123088068  
https://en.wiki.sipeed.com/soft/Lichee/zh/Lichee-RV/contribution/Dual_screen_display/Dual_screen_display.html  
https://www.gloomyghost.com/live/20220131.aspx  

## fbv  
https://linuxtoy.org/archives/fbv-framebuffer-img-viewer.html  
2011-08-23 · By cheer_xiao · Posted in Apps · 0 Comments  
fbv 是一款基于 framebuffer 的图片查看器，可以在真正的终端下查看 png/gif/jpeg/bmp 图片。  
使用说明书：  
1. 安装 fbv。  
2. 按 Ctrl-Alt-F1~F6 中的某一个键切换到终端，登录。  
3. fbv /path/to/image  
4. 键盘操作：  
5. 如果图片太大，使用 F 切换原大小/适合屏幕。  
6. 如果图片太大，也使用方向键或者 WAXD 滚动。  
7. M 和 N 是旋转。  
8. 如果给定了多个文件，, 和 . 是翻页。  
9. Q 是退出。  
10. 更多操作请自行摸索……欢迎补充 ^_^  
Arch 用户使用 pacman -S fbv 安装。其它发行版请补充。  
PS. fbv 似乎只有一个临时的官方首页，在这里。源码库在这里。  
Tagged as fbv, framebuffer · Edit on GitHub  
http://www.eclis.ch/fbv/  
http://repo.or.cz/w/fbv.git  
http://bbs.eeworld.com.cn/thread-1197990-1-1.html  
..\tina-d1-h\repo\package\utils\fbviewer  

## fbviewer  
https://bbs.aw-ol.com/topic/2530/游戏引擎第一步-d1跑tinygl?_=1694505904441&lang=zh-CN  
https://bbs.aw-ol.com/topic/547/求教-关于tina-linux-sdk代码架构问题/3?lang=zh-CN  
https://gitee.com/YJHmath/image-transmission-d1-tina/tree/master  
https://bbs.aw-ol.com/topic/395/mcu通过以太网-udp-发送图片到哪吒开发板进行处理?_=1694506083079&lang=zh-CN  
https://bbs.aw-ol.com/search?term=fbviewer&in=titlesposts&matchWords=all&sortBy=relevance&sortDirection=desc&showAs=posts  

## fc模拟器  
* https://gitee.com/weidongshan/esp32_100ask_project/tree/master/lib/nofrendo/src   

## directfb  
https://www.cnblogs.com/274914765qq/p/4358088.html  
DirectFB编程  
http://hk.aiuxian.com/article/p-gyjqrxlr-dq.html  
https://blog.csdn.net/zzb2760715357/article/details/125731327  
基于开发板 香橙派 Orange Pi PC PLUS 的 SDL 2交叉编译 ，并运行demo程序  
https://www.misuland.com/news/3691885099445387748  
https://blog.csdn.net/u012075739/article/details/25030029  
https://blog.csdn.net/kof98765/article/details/18264859  
DirectFB简介  
https://blog.csdn.net/GMstart/article/details/6693628   
Get DirectFB 1.2.* running on Ubuntu 9.04 (with multi app support)  
https://blog.csdn.net/ishuang/article/details/83470190  


## D213ECV lvgl_demo v7  
* 测试d213开发板（D213ECV）的lvgl_demo v7，效果如下（代码出处：RCSN/lv_port_linux_frame_buffer_mq_d1s），这电容触摸屏还是不错。结论（1）没有自带fbset，只能目测1024*600，触摸屏/dev/input/event0（2）剩余空间不足，需要复制到/dev/shm下执行（内存执行）（3）还是会有一定的发热量，比自带的测试程序要热  
* lv_port_linux_frame_buffer_d213.tar.gz  
* lv_port_linux_frame_buffer_d213_img.tar.gz  

## (TODO) sololinker-a lvgl_demo v7     
* lv_port_linux_frame_buffer_sololinker_img.tar.gz  
* lv_port_linux_frame_buffer_sololinker.tar.gz  
* 在sololinker-a上运行lvgl_demo v7的效果。工具链用luckfox的，分辨率填480和480，颜色深度填32，显示和触摸设备填/dev/fb0和/dev/input/event0。代码出处：RCSN/lv_port_linux_frame_buffer_mq_d1s，略加修改 （补注：上次说关闭程序会黑屏，但我自己编译的lvgl_demo关闭的话仍然会停留在当前画面）  
