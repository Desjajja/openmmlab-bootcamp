# Balloon Detection and Masking with Mask-RCNN 
## task
Detect balloons after training on a limited dataset. Then use the model to pick out balloons on a given video, reserve their colors and 
turn the rest part of the frames into greyscale images
## file structure
* `20230210_203750.log`: log file of training the model
* `balloon_dataset.zip`: dataset used for training, just balloons and more balloons with annotations
* `color_splash.ipynb`: notebook for model inference and processing the video
* `mask_rcnn_r50_caffe_fpn_mstrain-poy_1x_balloon.py`: custom configurations catering for this task
* `full_config.py`: full configurations including our custom part and its inherit part from the basic config
* `test_video.mp4`: orginal video to be processed
* `out.avi`: final outcome
## Demo
Origin:
![origin](./demo/original.gif)
After process:
![out](./demo/out.gif)
