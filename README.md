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

* (TODO) ZX3D50CE02S_USRC_4832  
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

## 芒果派MQ的lvgl_demo源代码出处  
https://bbs.aw-ol.com/topic/303/哪吒d1开发板-lvgl7-源码下载-带git仓库/31?lang=zh-CN  
我似乎找到芒果派MQ的lvgl_demo源代码出处，应该是在这里：《哪吒d1开发板-lvgl7-源码下载-带git仓库》，  
在aw-ol.com的bbs上，有份代码叫lv_port_linux_frame_buffer_nezha_d1_hdmi_event3_git.tgz，  
里面有个文件mouse_img.c就是鼠标光标的图片  
