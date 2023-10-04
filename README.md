# Computer_Vision_Brain_Tumor_Detection

This project implements YOLOV8 and Computer Vision to perform Object Detection and Instance Segmentation for Brain Tumors

We decided to exploit the power of Transfer Learning
to develop a supporting tool for early detection of
brain tumor and potentially brain surgery planning
for surgeons and radiologists.

Using a pre-trained YOLO model for object detection and
instance segmentation trained on annotated MRI scans,
with the appropriate hyperparameters tuning allows us to
reach satisfying results in accuracy (75-85%).

Our work is intended to emulate a supporting tool, not a fully
diagnostic one, the final diagnosis and treatment decisions
should be made by experienced healthcare professionals
who integrate the findings with their clinical expertise.

Instructions:

-Build a computer vision use case that can be solved with deep learning, which has a practical
application by solving a real world problem
-Prepare a dataset of images
-Annotate the images
-Apply transfer learning to your already pretrained model (YOLO, U Net, Mask R CNN…) to be able to
handle the new images
-Report on all the training parameters used (epochs, loss function…) and performance measures on
the test dataset
