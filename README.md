# real time action recognition
## example

![](http://owvctf4l4.bkt.clouddn.com/ql41i-wgywx.gif)

the video cann't show here, the below are some capture images.
![](http://owvctf4l4.bkt.clouddn.com/video_classification_img1.png)

![](http://owvctf4l4.bkt.clouddn.com/video_classification_img2.png)

## prepare
* tensorflow 1.2+  
* opencv3.x  
* pillow
* scipy
* python3+

## run

```bash
python real_time_c3d.py
```
Two test video provided in test_video.

This code can be run directly use cpu, but it will cause delay.With  **gpu**, it will run real-time recognition very well.

the pretrained model can be downloaded here.[c3d_pretrained_model](https://www.dropbox.com/sh/8wcjrcadx4r31ux/AAAkz3dQ706pPO8ZavrztRCca?dl=0)


## Others
This demo's pretrained model is based on [C3D-tensorflow](https://github.com/hx173149/C3D-tensorflow)
