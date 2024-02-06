# Brain-Tumor-Classification-using-CNN

How to load the datset : 

-> Go to kaggle.com and open an account 
-> Go to setting and Create a new Token
-> A kaggle.json file will be downloaded into your designated folder. 
-> Upload the .json file into google colab. And run 
  !cp kaggle.json ~/.kaggle/
-> Then go to the dataset on kaggle , Link : https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri
-> Copy API command from clicking on the three dots on the right of the screen. 
-> Paste the api commad on tou Google Colab Cell. 
  !kaggle datasets download -d sartajbhuvaji/brain-tumor-classification-mri
-> After that follow the given code to run a CNN on classifying brain tumor. 


I used a basic cnn architecture to classify betwwn Glioma, Meningioma, NoTumor and Pituitary. You can tweak as much as you can with the code and dataset given. Maybe even have better result. 
