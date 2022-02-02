# Face-Emotion-Detection
## Deployment
Face Emotion Detection using CNN Algorithm
![Alt Text](https://github.com/H8-Assignments-Bay/p2---ftds006---m2-hafidzali04/blob/6f02c9ee9af1760bbd1718490847bbb1ab71ba28/ezgif-7-7d71353450.gif)

* Pada Base model akurasi train yang didapat sebesar 0.81(81%) dan akurasi validation yang didapat sebesar 0.73(73%) dapat disimpulkan model cenderung overfit dan kinerja model masih rendah sehingga model akan di improve
* Pada model improvement ditambahkan beberapa batchnormalization, dropout layer, dan node pada hidden layer serta menambahkan epoch pada training. setelah dilakukan training akurasi model mengalami peningkatan yaitu sebesar 0.87(87%) untuk training, dan 0.80(80%) untuk validation. dapat disimpulkan bahwa improvement yang dilakukan berhasil meningkatkan kinerja model dalam melakukan deteksi emosi pada waja
##Dataset
https://www.kaggle.com/ananthu017/emotion-detection-fer
Data train yang digunakan ada:

7215 happy images
4830 sad images
3171 surprised images
3995 angry images
