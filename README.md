# GStreamer-Android-Studio-Java
GStreamer環境建置
設備環境:
OS: Windows 10 專業版
Android Studio: 4.0.1
classpath 'com.android.tools.build:gradle:3.1.4'
GStreame SDK : 1.18.4


1.	GStreame 官方網站，下載GStreameSDK
 
點選android Tutorials
 
官方安裝說明
 
點選GStreamer binaries 下載GStreameSDK，這邊點選1.18.4 tarball及Android NDKs used r21
 
GStreameSDK 解壓縮內容
 
建立資料夾命名GStreameSDK，存放至C:\GStreameSDK\1.18.4\
 
Android NDK 
 
2.	下載GStreamer官方範例，點選左邊連結連至GStreame gitlab，並點選gst-doc s
 
下載範例 gst-docs
 
 
3.	載入專案，點選File->New->ImportProject
 
新增gradel.properties
gstAndroidRoot=C\:\\GStreamerSDK\\1.18.4
此路徑為剛下載的GStreamerSDK位置
 
gradel.properties 畫面
 
中間會出現Exception錯誤
修改為->Exception
 
出現GStreamer未能使用，將GStreamer.java複製至專案內
 
複製位置，將所有tutorials1-4資料夾內都複製貼上
 
編譯完成顯示在實機上
 
 
