# casting-product-image-data-for-quality-inspection

# Jafar Abdollahi

<h2> casting product image data for quality inspection </h2>
This project is designed to utilize a ResNet50-based Convolutional Neural Network (CNN) architecture for defect detection in casting products. The pre-trained ResNet50 model, which has been trained on the ImageNet dataset, is repurposed to classify casting images into two categories: "OK" (non-defective) and "Defected".

Workflow:

Loading the Data: Images from two different classes (OK and Defected) are loaded first. The ImageDataGenerator is used to normalize the images and prepare them for the model.

Model Creation: The ResNet50 pre-trained model is used as the base model. Its layers are frozen due to being pre-trained. A GlobalAveragePooling2D layer and a couple of Dense layers are added on top to handle the binary classification of the images.

Model Training: The model is fine-tuned on the training dataset and then evaluated on the test set to assess its performance.

Prediction and Evaluation: After training, new images from the two classes are fed into the model using the predict function. The model outputs its prediction, and the results are displayed alongside the true labels of the images. Key evaluation metrics like Accuracy, Confusion Matrix, and the ROC curve are computed to assess the model's effectiveness.

Key Features:

Utilization of a pre-trained ResNet50 model to reduce the need for large training datasets.
Visualization of prediction results alongside actual labels for each image, enabling better model assessment.
Evaluation of the model using various metrics such as accuracy, precision-recall, and confusion matrix.
This approach demonstrates the power of transfer learning for tasks such as defect detection, where training data might be limited.


<h2> https://www.kaggle.com/datasets/ravirajsinh45/real-life-industrial-dataset-of-casting-product/data </h2>
<img src=" "> 
<img src=" "> 


<h2> Methods </h2>
<img src=" "> 


<h2> GUI </h2>
<img src=" "> 


<h2> Conlusion </h2>
<img src="https://github.com/Jafar-Abdollahi/casting-product-image-data-for-quality-inspection/blob/main/download%20(2).png"> 
<img src="https://github.com/Jafar-Abdollahi/casting-product-image-data-for-quality-inspection/blob/main/download%20(1).png"> 
<img src="https://github.com/Jafar-Abdollahi/casting-product-image-data-for-quality-inspection/blob/main/download.png"> 
<img src=" "> 


<h2> Paper </h2>

<h2> Contact me </h2>
You can reach me at:

Email: ja.abdollahi77@gmail.com
<br>
LinkedIn: https://www.linkedin.com/in/jafar-abdollahi-7647971b3/
<br>
Google Scholar: https://scholar.google.com/citations?user=2dK8kPwAAAAJ&hl=en
<br>
researchgate: https://www.researchgate.net/profile/Jafar-Abdollahi?ev=hdr_xprf&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6ImxvZ2luIiwicGFnZSI6ImhvbWUiLCJwcmV2aW91c1BhZ2UiOiJsb2dpbiIsInBvc2l0aW9uIjoiZ2xvYmFsSGVhZGVyIn19
<br>
youtube: https://www.youtube.com/@jafarabdollahi/featured
<br>
<img src="https://github.com/Jafar-Abdollahi/cuffless-bp-master-in-python-jupyter-/blob/main/2024-07-07_19-45-22.png"> 
