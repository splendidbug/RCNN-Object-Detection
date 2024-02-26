## Fast RCNN based object detection on video and image files.

![airport_mask_rcnn_out_pyonline-video-cutter com-ezgif com-video-to-gif-converter](https://github.com/splendidbug/RCNN-Object-Detection/assets/48771895/1e5e49aa-157b-4f87-b508-0a1a4363619c)

### Download the necessary weights and files.

Fast RCNN download:

`wget http://download.tensorflow.org/models/object_detection/mask_rcnn_inception_v2_coco_2018_01_28.tar.gz`
`tar zxvf mask_rcnn_inception_v2_coco_2018_01_28.tar.gz`

Install requirements:

`pip install requirements.txt`

**Dependencies**
- Opencv

### Usage

`data` folder contains input image and video

Image: `python yolo.py --image=data\zebra.jpg`

Video: `python3 mask_rcnn.py --video=data\airport.mp4`

An output file is generated in data folder with marked objects. The output is also shown live as the frames are processed
