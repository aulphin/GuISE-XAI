# GuISE-XAI
A Guided Input Sampling-based Perturbative Approach for Explainable AI in Image-based Application

Brain Tumor MRI Dataset , which is utilized is available in kaggle https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

evening_medi_rise.ipynb : Finetuned is performed in Resnet-50 model utilizing MRI dataset and saved the model.

After that Finetuned model is used for RISE and GuISE method experimentation for medical image dataset of MRI with the demo pynb file 

evening_medi_rise.ipynb / morning_medi.ipynb : RISE XAI method

Evening_medi_guise.ipynb: GuISE XAI method

The existing method, we utilized is 
RISE XAI method official implementation code - https://github.com/eclique/RISE
GRAD-CAM++, Score-CAM, Faster Score-CAM official implementation code - https://github.com/tabayashi0117/Score-CAM/blob/master/Score-CAM.ipynb

For General image explanation, we utilized publicly available ImageNet and PASCAL-VOC images while experimenting.

GT_metric_GuISE.ipynb: In this Ground truth metric computation is implemented in GuISE method utilizing publicly available MSRA-B dataset
