# SignWordRecognition_DeepLearning
# Rotation, Translation and Scale Invariant Sign Word Recognition Using Deep Learning
Communication between people with disabilities and people who do not understand sign language is a growing social need and can be a tedious task. One of the main functions of sign language is to communicate with each other through hand gestures. Recognition of hand gestures has become an important challenge for the recognition of sign language. There are many existing models that can produce a good accuracy, but if the model test with rotated or translated images, they may face some difficulties to make good performance accuracy. To resolve these challenges of hand gesture recognition, we proposed a Rotation, Translation and Scale-invariant sign word recognition system using a convolu-tional neural network (CNN). We have followed three steps in our work: rotated, translated and scaled (RTS) version dataset generation, gesture segmentation, and sign word classification. Firstly, we have enlarged a benchmark dataset of 20 sign words by making different amounts of Rotation, Translation and Scale of the original images to create the RTS version dataset. Then we have applied the gesture segmentation technique. The segmentation consists of three levels, i) Otsu Thresholding with YCbCr, ii) Morphological analysis: dilation through opening morphology and iii) Watershed algorithm. Finally, our designed CNN model has been trained to classify the hand gesture as well as the sign word. Our model has been evaluated using the twenty sign word dataset, five sign word dataset and the RTS version of these datasets. We achieved 99.30% accuracy from the twenty sign word dataset evaluation, 99.10% accuracy from the RTS version of the twenty sign word evolution, 100% accuracy from the five sign word dataset evaluation , and 98.00% accuracy from the RTS version five sign word dataset evolution. Furthermore, the influence of our model exists in competitive results with state-of-the-art methods in sign word recognition.

## Dataset
20 Word ASL
5 Word ASL 
We uploaded here the Pickle file of the three dataset which contained the landmark information and label for each trial.

# Please Cite the following paper if this information is useful:

Journal
```
@article{miah2023dynamic,
  title={Dynamic Hand Gesture Recognition using Multi-Branch Attention Based Graph and General Deep Learning Model},
  author={Miah, Abu Saleh Musa and Hasan, Md Al Mehedi and Shin, Jungpil},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE}

}
@article{shin2023korean,
  title={Korean Sign Language Recognition Using Transformer-Based Deep Neural Network},
  author={Shin, Jungpil and Musa Miah, Abu Saleh and Hasan, Md Al Mehedi and Hirooka, Koki and Suzuki, Kota and Lee, Hyoun-Sup and Jang, Si-Woong},
  journal={Applied Sciences},
  volume={13},
  number={5},
  pages={3029},
  year={2023},
  publisher={MDPI}
}

@article{miah2023multistage,
  title={Multistage Spatial Attention-Based Neural Network for Hand Gesture Recognition},
  author={Miah, Abu Saleh Musa and Hasan, Md Al Mehedi and Shin, Jungpil and Okuyama, Yuichi and Tomioka, Yoichi},
  journal={Computers},
  volume={12},
  number={1},
  pages={13},
  year={2023},
  publisher={MDPI}
}
@article{miah2022bensignnet,
  title={BenSignNet: Bengali Sign Language Alphabet Recognition Using Concatenated Segmentation and Convolutional Neural Network},
  author={Miah, Abu Saleh Musa and Shin, Jungpil and Hasan, Md Al Mehedi and Rahim, Md Abdur},
  journal={Applied Sciences},
  volume={12},
  number={8},
  pages={3933},
  year={2022},
  publisher={MDPI}
}

@article{miahrotation,
  title={Rotation, Translation and Scale Invariant Sign Word Recognition Using Deep Learning},
  author={Miah, Abu Saleh Musa and Shin, Jungpil and Hasan, Md Al Mehedi and Rahim, Md Abdur and Okuyama, Yuichi},
journal={ Computer Systems Science and Engineering },
  volume={44},
  number={3},
  pages={2521–2536},
  year={2023},
  publisher={TechSchince}

}
```
