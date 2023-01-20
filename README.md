# Object-Detection
Contains : Adversarial training on MNIST data, YOLO, SOLO, Faster-RCNN, and Mask-RCNN

Displayed below are the relevant plots and results from different algorithms implemented.

## Train and validation accuracy and loss plots for adversarial training on the MNIST dataset
<img src="https://user-images.githubusercontent.com/46754269/203434291-983687ef-860f-4f28-88b7-b3e669fe4134.png" width="500" height="300"><img src="https://user-images.githubusercontent.com/46754269/203434358-3b5faa7f-1fc4-4b73-b186-9154d317831f.png" width="500" height="300">

## YOLO
MAP plot over 10 epochs <br>
<img src="https://user-images.githubusercontent.com/46754269/203435728-edcac7ff-2548-4959-8444-62be08ab69ab.png" width="500" height="300"><br>
Train loss over each epoch <br>
<img src="https://user-images.githubusercontent.com/46754269/203435786-da9d02fe-a2ce-4b7c-9d3c-71b8d190ea3f.png" width="500" height="300"><br>
Ground truths and outputs example <br>
<img src="https://user-images.githubusercontent.com/46754269/203435893-c61db0fe-1b6a-4513-8868-6f38265da5a8.png" width="400" height="300"><img src="https://user-images.githubusercontent.com/46754269/203437956-2f24413e-a33d-4772-be9f-73670953e1dd.png" width="400" height="300"> 

## SOLO
Train categorical and mask loss <br>
<img src="https://user-images.githubusercontent.com/46754269/203440029-a88a843a-7cdc-453c-9793-6b55b4de369b.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/203440065-a7771ff7-2c3b-4291-8c1d-886b5a637998.png" width="400" height="300"> <br>
Total train and validation loss over each epoch <br>
<img src="https://user-images.githubusercontent.com/46754269/203446331-94011ab6-89d0-4d72-a6c8-187c34267bb3.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/203448393-743d5a69-6327-4231-aa04-f1fec7615627.png" width="400" height="300"> <br>
Ground truth at each FPN level example <br>
<img src="https://user-images.githubusercontent.com/46754269/203444295-0f00ea48-9f6b-4890-9eef-cf057072e422.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/203444361-a24cb170-d503-4a2a-8d0f-0c3a816c2c13.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/203444409-cffbc164-8e51-4b55-9b0e-964312ddba5f.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/203444477-859ff165-02ce-48b1-bb74-507a9703266f.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/203444523-2795525c-a540-433c-b677-4d27c72a5591.png" width="400" height="300"> <br>
Output example <br>
<img src="https://user-images.githubusercontent.com/46754269/203448522-bbdb91a1-cc46-4cdf-b65f-85e21b9df0ee.png" width="500" height="300"> 

## Faster-RCNN
Total train and validation loss <br>
<img src="https://user-images.githubusercontent.com/46754269/204712833-87bb2cd6-44ff-460d-a003-83212c0db489.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/204713411-5aed7cb2-1a3b-47b2-875f-8856669d2266.png" width="400" height="300"> <br>
Classifier train and validation loss <br>
<img src="https://user-images.githubusercontent.com/46754269/204713623-a3c2244a-75c8-4660-aadd-61e47fde5254.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/204713548-1c0a5d6a-9239-4f24-b209-cb7f49774f6f.png" width="400" height="300"> <br>
Regressor train and validation loss <br>
<img src="https://user-images.githubusercontent.com/46754269/204713102-1719dcaf-a5f5-4041-9a60-f50247d1da0f.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/204713173-63bb1760-1de2-4141-ab2e-323b70ead9ed.png" width="400" height="300"> <br>
Ground truth examples <br>
<img src="https://user-images.githubusercontent.com/46754269/204713769-417a1b21-8437-4636-83ec-c6eaf7186b5b.png" width="400" height="300">  <img src="https://user-images.githubusercontent.com/46754269/204713794-2c2d67e2-f758-4579-80cd-643bb7c39f35.png" width="400" height="300"> <br>
Output examples <br>
<img src="https://user-images.githubusercontent.com/46754269/204713871-52f241ac-7b3a-4b33-a858-9cb0d106b5c6.png" width="400" height="300"> <img src="https://user-images.githubusercontent.com/46754269/204713929-f93db7f2-8deb-4900-8ddd-3dcfe0746fe0.png" width="400" height="300"> <img src="https://user-images.githubusercontent.com/46754269/204714037-abac0ef3-76fe-4746-ab02-8d97feb5ee96.png" width="400" height="300"> <img src="https://user-images.githubusercontent.com/46754269/204714270-a21a4263-ef25-481f-8c16-648ef8a844b7.png" width="400" height="300">

## Mask-RCNN
Output examples <br>
<img src="https://user-images.githubusercontent.com/46754269/213706186-7943ed90-aa11-4586-a4e0-01795e66a169.png" width="400" height="300"> <img src="https://user-images.githubusercontent.com/46754269/213706244-fe5f11b2-eaf6-469a-adcb-7ffc7800d9d6.png" width="400" height="300"> <img src="https://user-images.githubusercontent.com/46754269/213706295-fc3ab352-3284-4df9-9899-991b100b7b8e.png" width="400" height="300"> <img src="https://user-images.githubusercontent.com/46754269/213706357-a451a220-b321-469e-b2b6-a158dddce2ad.png" width="400" height="300">
