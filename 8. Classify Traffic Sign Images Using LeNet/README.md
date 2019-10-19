In this case study, we have been provided with images of traffic signs and the goal is to train a Deep Network to classify them.

---

Dataset information:
  - The dataset contains 43 different classes of images.
  - The network used is called LeNet that was presented by Yann LeCun http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf
  - Citation J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011. @inproceedings{Stallkamp-IJCNN-2011, author = {Johannes Stallkamp and Marc Schlipsing and Jan Salmen and Christian Igel}, booktitle = {IEEE International Joint Conference on Neural Networks}, title = {The {G}erman {T}raffic {S}ign {R}ecognition {B}enchmark: A multi-class classification competition}, year = {2011}, pages = {1453--1460} }
  - Classes:
    - ( 0, b'Speed limit (20km/h)') 
    - ( 1, b'Speed limit (30km/h)')
    - ( 2, b'Speed limit (50km/h)') 
    - ( 3, b'Speed limit (60km/h)')
    - ( 4, b'Speed limit (70km/h)') 
    - ( 5, b'Speed limit (80km/h)')
    - ( 6, b'End of speed limit (80km/h)') 
    - ( 7, b'Speed limit (100km/h)')
    - ( 8, b'Speed limit (120km/h)') 
    - ( 9, b'No passing')
    - (10, b'No passing for vehicles over 3.5 metric tons')
    - (11, b'Right-of-way at the next intersection') 
    - (12, b'Priority road')
    - (13, b'Yield') (14, b'Stop') 
    - (15, b'No vehicles')
    - (16, b'Vehicles over 3.5 metric tons prohibited') 
    - (17, b'No entry')
    - (18, b'General caution') 
    - (19, b'Dangerous curve to the left')
    - (20, b'Dangerous curve to the right') 
    - (21, b'Double curve')
    - (22, b'Bumpy road') 
    - (23, b'Slippery road')
    - (24, b'Road narrows on the right') 
    - (25, b'Road work')
    - (26, b'Traffic signals') 
    - (27, b'Pedestrians') 
    - (28, b'Children crossing')
    - (29, b'Bicycles crossing') 
    - (30, b'Beware of ice/snow')
    - (31, b'Wild animals crossing')
    - (32, b'End of all speed and passing limits') 
    - (33, b'Turn right ahead')
    - (34, b'Turn left ahead') 
    - (35, b'Ahead only') 
    - (36, b'Go straight or right')
    - (37, b'Go straight or left') 
    - (38, b'Keep right') 
    - (39, b'Keep left')
    - (40, b'Roundabout mandatory') 
    - (41, b'End of no passing')
    - (42, b'End of no passing by vehicles over 3.5 metric tons')

---


This is an image classification class using LeNet architecture
