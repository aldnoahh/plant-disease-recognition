# plant-disease-recognition
PDR based on modified PlantVillage Dataset


About the dataset:
This is modified version of PlantVillage Dataset.
This dataset has been modified to work with data generators of Keras library.
The annotations has been modified so that labelling is easier. 
The train-test split is set at 85:15.
Link for modified dataset: https://drive.google.com/file/d/1Mj6wsKBZN2ycAyyIMs2lI361deuCJqBI/view?usp=sharing

Description:
There 5 ipython notebooks that are aimed at recognizing plant diseases. There is one notebook each for VGG19, Xception, InceptionV3, ResNet105V2, and EfficientNetB7. Additionally, to the pretrained models, the following layers have been added: 1 Batch normalization layer, 1 Dense layers of 512 nodes, and 1 Dense layer for softmax classification.

Keys for alternate annotations:

key= {'00': 'Apple___Apple_scab', '01': 'Apple___Black_rot', '02': 'Apple___Cedar_apple_rust', '03': 'Apple___healthy', '04': 'Blueberry___healthy', '05': 'Cherry_(including_sour)___Powdery_mildew', '06': 'Cherry_(including_sour)___healthy', '07': 'Corn_(maize)___Cercospora_leaf_spot Gray_leaf_spot', '08': 'Corn_(maize)___Common_rust_', '09': 'Corn_(maize)___Northern_Leaf_Blight', '10': 'Corn_(maize)___healthy', '11': 'Grape___Black_rot', '12': 'Grape___Esca_(Black_Measles)', '13': 'Grape___Leaf_blight_(Isariopsis_Leaf_Spot)', '14': 'Grape___healthy', '15': 'Orange___Haunglongbing_(Citrus_greening)', '16': 'Peach___Bacterial_spot', '17': 'Peach___healthy', '18': 'Pepper,_bell___Bacterial_spot', '19': 'Pepper,_bell___healthy', '20': 'Potato___Early_blight', '21': 'Potato___Late_blight', '22': 'Potato___healthy', '23': 'Raspberry___healthy', '24': 'Soybean___healthy', '25': 'Squash___Powdery_mildew', '26': 'Strawberry___Leaf_scorch', '27': 'Strawberry___healthy', '28': 'Tomato___Bacterial_spot', '29': 'Tomato___Early_blight', '30': 'Tomato___Late_blight', '31': 'Tomato___Leaf_Mold', '32': 'Tomato___Septoria_leaf_spot', '33': 'Tomato___Spider_mites Two-spotted_spider_mite', '34': 'Tomato___Target_Spot', '35': 'Tomato___Tomato_Yellow_Leaf_Curl_Virus', '36': 'Tomato___Tomato_mosaic_virus', '37': 'Tomato___healthy'}

plantvillage dataset

No. of sample, belonging to total 38 classes. 85:15 split for Train:Test.
Train: 46141 images
Test:  8162 images

(Time using colab GPU)

|      DNN	       | No. of layers | Code Available |      Average Time per epoch       |
|------------------|---------------|----------------|-----------------------------------|
|1. vgg19		 |	 26	     |	Yes	    |  766 seconds OR   12 min 46 sec   |
|2. xception	 |     136	     |      Yes       |                                   |
|3. inception v3   |     315       |      Yes       |                                   |
|4. resnet 152 v2	 |	 568       |      Yes	    |	 1167 seconds  OR  19 min 27 sec  |
|5. efficientnetb7 |     817       |      Yes       |    	                            |


Target Epochs for each DNN: 100 Epoch

H5 files will be added later.

(Futher Details will be added.)
