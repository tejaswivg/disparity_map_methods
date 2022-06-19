1. stereoSGBM from opencv
```
python .\stereo_match.py 
```
2. PSMnet 

a. Clone the repository https://github.com/JiaRenChang/PSMNet

b. download model weights (kitti2015)
then use resized 'Preethi' images

and then run 

```
python Test_img.py --loadmodel C:\Users\Tejaswi\Downloads\pretrained_model_KITTI2015.tar --leftimg .\View1.png --rightimg .\View2.png
```

as indicated here:

https://github.com/JiaRenChang/PSMNet#test-on-your-own-stereo-pair

this generates the disparity image in the same directory
