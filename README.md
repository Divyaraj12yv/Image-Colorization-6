 # Task 6 :-
 # Real-time Multi-Object Colorization with Semantic Segmentation Description:

 🎯 Objective:-
 
 
Segment objects in video frames in real-time using DeepLabV3

Apply different color schemes to each object category

Display the colorized video stream interactively through a GUI


🧠 Model Used :-


Semantic Segmentation Model: DeepLabV3

Backbone: MobileNet / ResNet (depending on config)

Trained on: PASCAL VOC / COCO (supports 20–80+ object classes)


🧠 Model Architecture :-


You can use or fine-tune:

Zhang et al.’s model – Based on classification and regression over color channels in LAB space.

InstColorization – Context-aware deep colorization with instance-level segmentation guidance.


🖥️ GUI Features :-


Upload and preview videos

Switch between camera or file input

Real-time semantic segmentation

Per-object class colorization

Live colorized video display


🙌 Acknowledgments :-


TensorFlow DeepLab

OpenCV for real-time frame handling

PyQt5 for the GUI







 
