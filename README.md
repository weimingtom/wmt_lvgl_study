# wmt_lvgl_study
My LVGL study

## work  
* Windows VS2013 port (with FastFireFrame)    
lvgldemo_501_v5_input_pass.rar  
lvgldemo_530_v2_run_success.rar  
lvgldemo_612_v1_success.rar  
lvgldemo_711_v1_success.rar  

* WT32-SC01 (ESP32 wrover) port  
lvgldemo_v3_success_wt32_self_lvgl.rar  
lvgldemo_v4_swap_color.rar  
```
idf version, see esp-idf-4.3_v2_200m.part01.rar  
https://github.com/wireless-tag-com/8ms-esp32    
wt32-sc01-8ms-esp32-main.zip  
```

* Android port  
(NOT DONE) search baidupan, lvgldemo_android_v2.rar  

* csky port  
csky_v2_success.tar.gz  

* Mangopi MQ or Sipeed LicheeRV Dock, Allwinner D1 / D1s / F133-A port  
https://gitee.com/RCSN/lv_port_linux_frame_buffer_mq_d1s  
lvgl_demo_v5.tar.gz  

* Mangopi MQ-Dual, Allwinner T113-S3  
lv_port_linux_frame_buffer_t113_v1.tar.gz  

* ssd202d 7inch    
lv_port_linux_frame_buffer_arm_v1.tar.gz  

* STM32F429I-DISC1, 240x320, LVGL8      
STM32Cube_FW_F4_V1.27.0_v6_lvgl_good_stm32f429i_disc1.rar  
https://github.com/lvgl/lv_port_stm32f429_disco  

* (TODO) ZX3D50CE02S_USRC_4832, ESP32-S3 wrover    
sdk-8ms-esp32-release-2.1_run_ok.rar  
https://gitee.com/qiming-zhixian/sdk-8ms-esp32/tree/release%2F2.1/  
please use 2.1, not 2.2, adapting to the version in https://8ms.xyz/projects/esp32  
install esp-idf-tools-setup-offline-4.4.3.exe  
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

* (TODO) WT32-SC01-PLUS  
https://github.com/Skorpi08/WT32-SC01-PLUS  
https://github.com/dudals-jung/WT32-SC01-PLUS-LVGL-IDF  
https://github.com/WojciechowskiMarek/WT32-SC01-Plus_ESP32-S3_JIngle_Bells  

* d1, nezha    
lv_port_linux_frame_buffer_nezha_d1_hdmi_event3_git.tgz  

* 君正MIPS, 青联X2000, 1024 * 600, from ssd202d version, static link (gcc -static)    
lv_port_linux_frame_buffer_x2000_lvgl_v1.tar.gz  
ABS_MT_POSITION_X define see https://blog.csdn.net/Chuangke_Andy/article/details/122454299  
see lv_drivers/indev/evdev.c  
see https://gitee.com/RCSN/lv_port_linux_frame_buffer_mq_d1s  
```
//see include/uapi/linux/input.h
#ifndef ABS_MT_POSITION_X
#define ABS_MT_POSITION_X 0x35
#endif

#ifndef ABS_MT_POSITION_Y
#define ABS_MT_POSITION_Y 0x36
#endif
```

* f1c200s  
https://github.com/nminaylov/F1C100s_projects  
https://github.com/nminaylov/F1C100s_LVGL  
https://github.com/motoedy/minimal_f1c100s_fb_zlggui  
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

## 芒果派MQ的lvgl_demo源代码出处  
https://bbs.aw-ol.com/topic/303/哪吒d1开发板-lvgl7-源码下载-带git仓库/31?lang=zh-CN  
我似乎找到芒果派MQ的lvgl_demo源代码出处，应该是在这里：《哪吒d1开发板-lvgl7-源码下载-带git仓库》，  
在aw-ol.com的bbs上，有份代码叫lv_port_linux_frame_buffer_nezha_d1_hdmi_event3_git.tgz，  
里面有个文件mouse_img.c就是鼠标光标的图片  
