# ComputerVisionBasics
Basic examples of image classification and object detection. This demonstrates basic proficiency and useful tidbits that can be applied to other projects.

1) Image classification using the Kaggle Petal to the Metal example.
	* Use TF record format for efficient memory usage.
	* Use albumentations for efficient image augmentation.
	* Result: >92% F1 score on Kaggle.
2) Object detection using YOLO with a bounding box widget.
	* Have a handy bounding box widget so you can label a data set from scratch if necessary.
	* Learn how to configure YOLO and work through dependency mismatches in order to get up and running.
	* Result: basic implemenation of a state of the art YOLO (v5) object detection model. Identify, localize and count objects in an image for various applications (logistics, security, military, ecology, industrial, etc.). Basic benchmark level performance in Kaggle Great Barrier Reef competition (train and test 86% precision, 74% recall, mAP50-95 of 43%).