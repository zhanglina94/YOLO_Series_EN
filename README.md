# YOLO_series

<h2>YOLOV1</h2>
Advantages of YOLO v1

- The speed is very fast, the processing speed can reach 45fps, and its fast version (with smaller network) can even reach 155fps.
- Training and prediction can be performed end-to-end, which is very simple.

Disadvantages of YOLO v1

- Accuracy is not high enough
- The detection effect is not good for small objects and close objetcs

<h2>YOLOV2</h2>
Compared with the v1 version, YOLOv2 has improved in three aspects: more accurate prediction (Better), faster speed (Faster), and more recognition objects (Stronger) on the basis of continuing to maintain the processing speed. Among them, recognizing more objects is to expand to be able to detect 9000 different objects, called YOLO9000.

yoloV2 proposed the **Darknet-19** (with 19 convolutional layers and 5 MaxPooling layers) network structure as a feature extraction network. DarkNet-19 is smaller than VGG-16, and **the accuracy is not weaker than VGG-16**, but the amount of floating point operations is reduced to about **⅕** to ensure faster operation speed.


<h2>YOLOV3</h2>

YOLOv3 has significantly improved the accuracy of small objects detection.

<h2>YOLOV4</h2>
YOLO V4 is a major update of the YOLO series. **Its AP and FPS on the COCO dataset have increased by 10% and 12%**, respectively.

YOLO v4 summarizes most of the detection techniques, and then screens, arranges and combines, and experiments (ablation study) which methods are effective. In general, Yolov4 does not create new improvements, but uses a large number of objects detection techniques.

<h2>YOLOV5</h2>


<h2>YOLOV6</h2>
<h2>YOLOV7</h2>
<h2>YOLOV8</h2>

<h2>Summary</h2>
In daily work,YOLOV5 is fast than YOLOv7,YOLOV7 ACC is more high.
