# screenrecord
A Screenrecord for Android4.3 Jelly Bean and lower version


```
#capture 2 screens per second, and save them to /sdcard/000/
for /L %%i in (1,0,2) do @adb shell screencap -p /sdcard/000/screen%%i.png & @sleep 500
```


**Requirements**

- Adb installed
- USB debugging mode
- Android version with screencap available
- [FFmpeg](https://www.ffmpeg.org/) or [avconv](https://libav.org/avconv.html)  (convert images to video)
- [sleep](https://github.com/witwall/sleep) for Windows,Linux and Mac OS X already have sleep command
