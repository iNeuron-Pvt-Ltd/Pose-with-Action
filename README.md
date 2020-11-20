## :running: :walking: :dancer: Pose-With-Action
![pose_with_action](https://user-images.githubusercontent.com/62059604/99776776-5db0de00-2b37-11eb-97e7-b39f53f2d703.gif)

![Untitled design (4)](https://user-images.githubusercontent.com/62059604/99800421-5818bf80-2b5a-11eb-83ad-c0fe6a2d48be.png)

![Untitled design (5)](https://user-images.githubusercontent.com/62059604/99800592-9e6e1e80-2b5a-11eb-8f70-4796dd0ee36a.png)

- This repository represents **" Action Recognition Using Alphapose "**.
- With the help of this project we can detect the human Actions/Activities based on the **Human Pose**.
  
## 📝 Description
- This implemantation is based on official **Alphapose** repository https://github.com/MVIG-SJTU/AlphaPose 
- In this project we have used **Alphapose** and **XGBOOST** for activity recognition.

## ⏳ Dataset
- Download the dataset for custom training
- https://drive.google.com/drive/folders/1CFxvuigTzbnRXUojFeCRozxjUbYiQ8RM?usp=sharing 

## 🏽‍ Download Object Detection Model
- Download the object detection model manually : **yolov3-spp.weights** file from following Drive Link
- https://drive.google.com/file/d/1-dAgUMwN7SH9cRsRie_A78we_5_I0-8L/view?usp=sharing
- Download the weight file and Place it into **" detector/yolo/data/ "** folder.

##  🏽‍ Download Deep Sort weights
- Download the 'Ckpt.t7' model from following Drive Link 
- https://drive.google.com/file/d/1BOF_IxrB3DKfhoZM2nHPLCDU7gQP9fcE/view?usp=sharing
- Download the weight file and put into " **deep_sort/deep_sort/deep/checkpoint/** " folder.

## 🎯 Inference demo
Run :-
```bash
$ python3 head_count.py --source ...

```
- Video:  `--source demo.mp4`
- Webcam:  `--source 0`
- RTSP stream:  `--source rtsp://190.90.111.100/rtplive/jk784600ee04ee3369623556dd`
- HTTP stream:  `--source http://wxyz.abc.net/msdrjpg/demovideo.mjpg`

## Contributors <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25> 
