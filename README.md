# COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans
COVID-19 Detection based on Chest X-rays and CT Scans using four Transfer Learning algorithms: VGG16, ResNet50, InceptionV3, Xception. The models were trained for 500 epochs on around 1000 Chest X-rays and around 750 CT Scan images on Google Colab GPU. After training, the accuracies acheived for the model are as follows:
<pre>
                InceptionV3  VGG16   ResNet50   Xception
Chest X-rays    96%          94%      83%       92%

CT Scans        93%          93%      80%       95%
</pre>
A Flask App was later developed wherein user can upload Chest X-rays or CT Scans and get the output of possibility of COVID infection.

# Dataset
The dataset for the project was gathered from two sources:
1. Chest X-ray images (1000 images) were obtained from: https://github.com/ieee8023/covid-chestxray-dataset
2. CT Scan images (750 images) were obtained from: https://github.com/UCSD-AI4H/COVID-CT/tree/master/Data-split
80% of the images were used for training the models and the remaining 20% for testing

# Evaluation and Results
<h3>Sample output of test images</h3><br>

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/sample_chest.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/sample_ct.PNG">

<h3>Classification Reports for Chest X-rays:  VGG, InceptionV3, ResNet50, Xception </h3>

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/vgg_chest_report.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/inception_chest_report.PNG">

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/resnet_chest_report.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/xception_chest_report.PNG">

<h3>Confusion Matrix for Chest X-rays:  VGG, InceptionV3, ResNet50, Xception </h3>

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/vgg_chest_cm.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/inception_chest_cm.PNG">

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/resnet_chest_cm.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/xception_chest_cm.PNG">

<h3>Classification Reports for CT Scans:  VGG, InceptionV3, ResNet50, Xception </h3>

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/vgg_ct_report.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/inception_ct_report.PNG">

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/resnet_ct_report.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/flask%20app/assets/images/xception_ct_report.PNG">

<h3>Confusion Matrix for CT Scans:  VGG, InceptionV3, ResNet50, Xception </h3>

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/vgg_ct_cm.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/inception_ct_cm.PNG">

<img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/resnet_ct_cm.PNG"> <img src="https://github.com/kaushikjadhav01/COVID-19-Detection-Flask-App-based-on-Chest-X-rays-and-CT-Scans/blob/master/screenshots/xception_ct_cm.PNG">

