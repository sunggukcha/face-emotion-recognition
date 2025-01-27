This directory contains several auxiliary Python files and the following Jupyter Notebooks:
- [train_emotions.ipynb](train_emotions.ipynb): the training of TensorFlow emotional model such as [mobilenet_7](../models/affectnet_emotions/mobilenet_7.h5)
- [AFEW_train.ipynb](AFEW_train.ipynb): initial preprocessing of the AFEW dataset from EngageWild challenge and training a classifier on top of the pre-trained TensorFlow emotional model
- [VGAF_train.ipynb](VGAF_train.ipynb): initial preprocessing of the VGAF dataset from EngageWild challenge and training a classifier on top of the pre-trained TensorFlow emotional model
- [train_faces_torch.ipynb](train_faces_torch.ipynb): pre-training of facial recognition [models](../models/pretrained_faces) on the VGGFace2 dataset.
- [train_emotions-pytorch.ipynb](train_emotions-pytorch.ipynb): the **main file** in this repository. It contains the training of our EmotiEffNet models, such as [EmotiEffNet-B2](../models/affectnet_emotions/enet_b2_8_best.pt) and classification of emotional features for AFEW and VGAF datasets. It is necessary to run preprocessing of the datasets from train_emotions.ipynb, AFEW_train.ipynb and VGAF_train.ipynb
- [train_ramas.ipynb](train_ramas.ipynb): the processing of RAMAS dataset and training code for classifiers on top of our models (both PyTorch and TensorFlow)
- [video_summarizer.ipynb](video_summarizer.ipynb): processing of recording of online conference with facial clustering and creation of gif files with emotions of every face
- [engagement](engagement): training regression models on top of our emotional features for the EngageWild dataset from the EmotiW challenges
- [ABAW](ABAW): training classifier on top of our emotional features for the third and fourth ABAW challenges
- [display_emotions.ipynb](display_emotions.ipynb): examples of usages of our models (both PyTorch and TensorFlow) and visualization of their predictions using GradCam
- [test_hsemotion_package.ipynb](test_hsemotion_package.ipynb): examples of usages of our HSEmotion library



