# Alzheimer-Classification---Multiclass-Image-Classification-


Alzheimer's disease (AD) is a degenerative, irreversible brain illness that strikes people in their forties. This disease gradually destroys memory and thinking skills, as well as the capacity to carry out even the most basic duties. It's not like other diseases, which can strike at any time. With this  progressive disease, people gradually experience severe memory loss and other cognitive difficulties. 


Classifying several stages of Alzheimer's disease, a transfer learning based pretrained model(Restnet152v2) has been implemented. The dataset has been collected from kaggle that contains 6400 images with 4 classes of Brain images (mild demented, moderate demented, non-demented, very mild demented stages). At the initial stage, the pretrained model was used as the base model and few Conv2D, dropout, pooling and normalization layers were used on it. Moreover, the approach of training with the transfer learning based pretrained model performs better for this multi-class image classification. 
 
Preprocessing & Model Implementation steps : 
Worked on multi class image classification problem 
For better performance data augmentation has been done that creates synthetic data, that means different versions of the same image( it can be zoomed, horizontally flipped etc.)
For transfer learning, used pretrained model(Restnet152v2) along with extra layers of Conv2D
