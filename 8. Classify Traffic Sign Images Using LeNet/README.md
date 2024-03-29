In this case study, we have been provided with images of traffic signs and the goal is to train a Deep Network to classify them.

---

Dataset information:
  - The dataset contains 43 different classes of images.
  - The network used is called LeNet that was presented by Yann LeCun http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf
  - Citation J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011. @inproceedings{Stallkamp-IJCNN-2011, author = {Johannes Stallkamp and Marc Schlipsing and Jan Salmen and Christian Igel}, booktitle = {IEEE International Joint Conference on Neural Networks}, title = {The {G}erman {T}raffic {S}ign {R}ecognition {B}enchmark: A multi-class classification competition}, year = {2011}, pages = {1453--1460} }
  - Classes:
    - ( 0, 'Speed limit (20km/h)') 
    - ( 1, 'Speed limit (30km/h)')
    - ( 2, 'Speed limit (50km/h)') 
    - ( 3, 'Speed limit (60km/h)')
    - ( 4, 'Speed limit (70km/h)') 
    - ( 5, 'Speed limit (80km/h)')
    - ( 6, 'End of speed limit (80km/h)') 
    - ( 7, 'Speed limit (100km/h)')
    - ( 8, 'Speed limit (120km/h)') 
    - ( 9, 'No passing')
    - (10, 'No passing for vehicles over 3.5 metric tons')
    - (11, 'Right-of-way at the next intersection') 
    - (12, 'Priority road')
    - (13, 'Yield') (14, b'Stop') 
    - (15, 'No vehicles')
    - (16, 'Vehicles over 3.5 metric tons prohibited') 
    - (17, 'No entry')
    - (18, 'General caution') 
    - (19, 'Dangerous curve to the left')
    - (20, 'Dangerous curve to the right') 
    - (21, 'Double curve')
    - (22, 'Bumpy road') 
    - (23, 'Slippery road')
    - (24, 'Road narrows on the right') 
    - (25, 'Road work')
    - (26, 'Traffic signals') 
    - (27, 'Pedestrians') 
    - (28, 'Children crossing')
    - (29, 'Bicycles crossing') 
    - (30, 'Beware of ice/snow')
    - (31, 'Wild animals crossing')
    - (32, 'End of all speed and passing limits') 
    - (33, 'Turn right ahead')
    - (34, 'Turn left ahead') 
    - (35, 'Ahead only') 
    - (36, 'Go straight or right')
    - (37, 'Go straight or left') 
    - (38, 'Keep right') 
    - (39, 'Keep left')
    - (40, 'Roundabout mandatory') 
    - (41, 'End of no passing')
    - (42, 'End of no passing by vehicles over 3.5 metric tons')

---


This is an image classification class using LeNet architecture

---

Sample predictions

![SamplePrediction-SignClassification](signClassificationSample.JPG)
