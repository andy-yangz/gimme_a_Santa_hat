# Give me a santa hat

给照片加圣诞帽。  
Add Christmas hats to people and cats in photo automatically.
## Getting started
### 文件说明 file structure
`tutorial.ipynb`是主要的程序。 `tutorial.ipynb` is the main program.
`photos/`放着测试照片，和帽子素材。 `photos/` have the test photos and resources of hats.  
`models/`里面放置训练好的模型。 `models/` have the pretrained classifiers.  
`results/`里面放置完成了的图片。 `results/` will have processed photos.  
其他文件是为之后工作做准备。 other files for future work.  
### Prerequisites
```
Python=3.5.0
OpenCV=3.2.0 # For face detection
matplotlib
numpy
Pillow=4.2.1
```

### TODO：
- [] Detect Face pose then change angle of hat
- [] Use Deep Learning Model
