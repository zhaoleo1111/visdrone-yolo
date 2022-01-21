# visdrone-yolo
visdrone      
Code is based on https://github.com/AlexeyAB/darknet.git  
weights: https://drive.google.com/file/d/1b1xwtV7c1RcQFg9qWC4ccoXj_NEhheiR/view?usp=sharing  
For AP50:`./darknet detector map test.data yolov3.cfg yolov3.weights -iou_thresh 0.50 -points 101`   
For AP75:`./darknet detector map test.data yolov3.cfg yolov3.weights -iou_thresh 0.75 -points 101`    
The tensorrt code: https://github.com/enazoe/yolo-tensorrt.git     
