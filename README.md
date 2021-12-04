# low-light-object-detection-using-pretrained-model-and-image-enhancement
1. please use Ubuntu 18.04 LTS and mxnet with CPU mode.
2. the experiments conducted use Gluon CV model Z00
3. please also install OpenCV and Skimage to successfully run the experiments
4. This is also contains a custom created low light dataset with 125 images
5. The research suite is used to understand the performance and speed of object detection models for low light and the effect when subjected to imageenhancement techniques
6. the experiment contains three pretrained models YOLO,SSD and Faster RCNN which use COCO weights
7. The experiment suite implements three image enhancement techniques Gama Correction,Histogram Equalization and MinMax Contrast strectching
8. the metric used is mAP and IOU and prediction time used in ms
9. change the IOU threshold default is 0.5 
10. the Annotations are maintained in COCO format and the results of the experiments are stored in the dataframe that can be exported csv
