# screencast-tools for Fedora Linux
## Fedora Linux 一些有用的螢幕錄製工具

### 1. 畫面錄影
* [simplescreenrecorder](https://www.maartenbaert.be/simplescreenrecorder/)

  ```
  # sudo dnf install -y simplescreenrecorder
  ```
### 2. 顯示滑鼠位置
* [bDMZ 滑鼠指標](https://www.gnome-look.org/p/999801/)

  ```
  # tar xvfz 160115-bDMZT.tar.gz
  # mv bDMZT/* ~/.icons
  
  # vim ~/.config/compiz/compizconfig/Default.ini
  [core]
  as_cursor_theme = ybDMZ                                                                         
  
  # vim ~/.config/gtk-3.0/settings.ini
  [Settings]
  gtk-cursor-theme-name=ybDMZ
  
  # vim ~/.gtkrc-2.0
  gtk-cursor-theme-name="ybDMZ"
  ```
* [Compiz Showmouse 外掛](http://wiki.compiz.org/Plugins/Showmouse)

### 3. 顯示鍵盤輸入
* [screenkey](https://www.thregr.org/~wavexx/software/screenkey/)

  ```
  # sudo dnf install -y screenkey
  ```

### 4. 自動字幕
* [Closed Captioning OBS Plugin](https://github.com/ratwithacompiler/OBS-captions-plugin)
* [subtitle-plugin-obs](https://github.com/devneto/subtitle-plugin-obs)
* [Live Captioning](https://github.com/MidCamp/live-captioning)
* [Open-as-Popup for Google Chrome](https://chrome.google.com/webstore/detail/open-as-popup/ncppfjladdkdaemaghochfikpmghbcpc)
* [pyTranscriber](https://github.com/raryelcostasouza/pyTranscriber)

  ```
  # cd pyTranscriber
  # python main.py
  ```

### 5. 聲音降噪
* [NoiseTorch](https://github.com/lawl/NoiseTorch)
* [module-echo-cancel for PulseAudio](https://www.freedesktop.org/wiki/Software/PulseAudio/Documentation/User/Modules/#module-echo-cancel)

### 6. 影片裁剪
* [Avidemux](http://www.avidemux.org/)

  ```
  # sudo dnf install -y avidemux
  ```
  
### 7. 字幕編輯
* [Gnome Subtitles](https://gnomesubtitles.org/)

  ```
  # sudo dnf install -y gnome-subtitles
  ```
  ```
  # ffmpeg -i MakeCode剪刀石頭布.mp4 -preset ultrafast -vf "subtitles=MakeCode剪刀石頭布.srt:force_style='FontName=GenSenRounded TW,FontSize=24'" output.mp4
  ```
* [繁體中文免費字型列表](https://zi-hi.com/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87%E5%85%8D%E8%B2%BB%E5%AD%97%E5%9E%8B%E5%88%97%E8%A1%A8)
  
## 行動裝置相關工具
### 1. Android 螢幕投影
* [scrcpy](https://github.com/Genymobile/scrcpy)

  ```
  # scrcpy -m 1920
  ```
  
* [Scrcpy AppImage](https://github.com/srevinsaju/scrcpy-appimage)

### 2. 手機相機當電腦鏡頭
* [DroidCam for PC](https://play.google.com/store/apps/details?id=com.dev47apps.droidcam)
* [DroidCam for Linux](https://www.dev47apps.com/droidcam/linux/)

### 3. Webcam 特效
* [Webcamoid](https://webcamoid.github.io/)
* [v4l2loopback](https://github.com/umlaeute/v4l2loopback)

  ```
  # sudo dnf install -y v4l2loopback
  ```

### 4. 程式教學平台
* [Code.org](https://code.org/)
* [MakeCode for micro:bit](https://makecode.microbit.org/)
* [PictoBlox](https://thestempedia.com/product/pictoblox/)
