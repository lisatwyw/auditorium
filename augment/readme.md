
# 4-class problem

- Last trained on helios on July 1, 2022
- Number of filter banks changed to 75





## Sample results 


```

2022-07-01 01:21:39.804627: I tensorflow/stream_executor/platform/default/dso_loader.cc:44] Successfully opened dynamic library libcudnn.so.7
2022-07-01 01:27:23.509341: W tensorflow/stream_executor/cuda/redzone_allocator.cc:312] Not found: ./bin/ptxas not found
Relying on driver to perform ptx compilation. This message will be only logged once.
2022-07-01 01:27:23.818920: I tensorflow/stream_executor/platform/default/dso_loader.cc:44] Successfully opened dynamic library libcublas.so.10.0


Epoch 1/100
1509/1510 [============================>.] - ETA: 0s - loss: 1.2397 - acc: 0.4273
WARNING: Logging before flag parsing goesto stderr.
W0701 01:31:34.621206 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 595s 394ms/step - loss: 1.2394 - acc: 0.4275 - val_loss: 1.1772 - val_acc: 0.4964
Epoch 2/100
1509/1510 [============================>.] - ETA: 0s - loss: 1.0129 - acc: 0.5690W0701 01:34:25.315012 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 171s 113ms/step - loss: 1.0128 - acc: 0.5691 - val_loss: 1.0140 - val_acc: 0.5682
Epoch 3/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.8377 - acc: 0.6489W0701 01:37:16.430156 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 171s 113ms/step - loss: 0.8376 - acc: 0.6490 - val_loss: 0.9615 - val_acc: 0.6030
Epoch 4/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.6856 - acc: 0.7212W0701 01:40:07.721470 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 171s 113ms/step - loss: 0.6855 - acc: 0.7212 - val_loss: 0.9313 - val_acc: 0.6229
Epoch 5/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.5803 - acc: 0.7669W0701 01:42:58.814606 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 171s 113ms/step - loss: 0.5802 - acc: 0.7670 - val_loss: 0.9315 - val_acc: 0.6662
Epoch 6/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.4868 - acc: 0.8088W0701 01:45:46.888887 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 168s 111ms/step - loss: 0.4866 - acc: 0.8088 - val_loss: 1.0259 - val_acc: 0.6577
Epoch 7/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.4201 - acc: 0.8342W0701 01:48:33.065274 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 166s 110ms/step - loss: 0.4202 - acc: 0.8341 - val_loss: 0.9145 - val_acc: 0.6953
Epoch 8/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.3555 - acc: 0.8618W0701 01:51:19.549323 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 166s 110ms/step - loss: 0.3554 - acc: 0.8618 - val_loss: 0.9039 - val_acc: 0.7067
Epoch 9/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.3072 - acc: 0.8818W0701 01:54:07.361194 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 168s 111ms/step - loss: 0.3071 - acc: 0.8817 - val_loss: 1.1046 - val_acc: 0.6861
Epoch 10/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.2659 - acc: 0.8989W0701 01:56:54.201306 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 167s 110ms/step - loss: 0.2658 - acc: 0.8990 - val_loss: 1.0677 - val_acc: 0.7131
Epoch 11/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.2334 - acc: 0.9125W0701 01:59:39.917165 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 166s 110ms/step - loss: 0.2334 - acc: 0.9125 - val_loss: 1.1566 - val_acc: 0.7124
Epoch 12/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.2098 - acc: 0.9209W0701 02:02:26.951761 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 167s 111ms/step - loss: 0.2097 - acc: 0.9209 - val_loss: 1.2511 - val_acc: 0.7173
Epoch 13/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.1866 - acc: 0.9295W0701 02:05:18.283322 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 171s 113ms/step - loss: 0.1865 - acc: 0.9296 - val_loss: 1.1699 - val_acc: 0.7173
Epoch 14/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.1683 - acc: 0.9378W0701 02:08:09.817447 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 172s 114ms/step - loss: 0.1684 - acc: 0.9377 - val_loss: 1.3959 - val_acc: 0.7017
Epoch 15/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.1484 - acc: 0.9450W0701 02:11:02.971046 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 173s 115ms/step - loss: 0.1484 - acc: 0.9450 - val_loss: 1.5540 - val_acc: 0.7124
Epoch 16/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.1501 - acc: 0.9451W0701 02:13:54.932244 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 172s 114ms/step - loss: 0.1500 - acc: 0.9451 - val_loss: 1.1960 - val_acc: 0.7251
Epoch 17/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.1367 - acc: 0.9508W0701 02:16:46.788187 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 172s 114ms/step - loss: 0.1366 - acc: 0.9508 - val_loss: 1.4198 - val_acc: 0.7450
Epoch 18/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.1256 - acc: 0.9556W0701 02:19:39.245077 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 172s 114ms/step - loss: 0.1256 - acc: 0.9557 - val_loss: 1.4768 - val_acc: 0.7138
Epoch 19/100
1509/1510 [============================>.] - ETA: 0s - loss: 0.1147 - acc: 0.9580W0701 02:22:32.147260 47560028488704 callbacks.py:990] Can save best model only with val_accuracy available, skipping.
1510/1510 [==============================] - 173s 115ms/step - loss: 0.1147 - acc: 0.9580 - val_loss: 1.3170 - val_acc: 0.7074




## run two: with early stopping... 0 patience so stopped too early

batchsize = 64

Epoch 1/20
377/377 [==============================] - 96s 255ms/step - loss: 1.3099 - acc: 0.3690 - val_loss: 1.2616 - val_acc: 0.3878
Epoch 2/20
377/377 [==============================] - 94s 248ms/step - loss: 1.1390 - acc: 0.5017 - val_loss: 1.0967 - val_acc: 0.5050
Epoch 3/20
377/377 [==============================] - 93s 248ms/step - loss: 0.9868 - acc: 0.5773 - val_loss: 1.0501 - val_acc: 0.5575
Epoch 4/20
377/377 [==============================] - 92s 244ms/step - loss: 0.8684 - acc: 0.6305 - val_loss: 1.1081 - val_acc: 0.5497


              precision    recall  f1-score   support

        none       0.74      0.63      0.68       755
    crackles       0.49      0.45      0.47       378
     wheezes       0.42      0.43      0.43       181
        both       0.26      0.57      0.35       107

    accuracy                           0.55      1421
   macro avg       0.47      0.52      0.48      1421
weighted avg       0.59      0.55      0.57      1421

[[476 141  69  69]
 [108 171  22  77]
 [ 55  17  78  31]
 [  6  23  17  61]]



## run two - part 2: 0 -> 5 patience 

batchsize = 128, resumed from epoch 4


uld be performance gains if more memory were available.
188/188 [==============================] - 82s 434ms/step - loss: 0.7375 - acc: 0.6907 - val_loss: 0.9601 - val_acc: 0.5945
Epoch 6/20
188/188 [==============================] - 79s 418ms/step - loss: 0.6815 - acc: 0.7184 - val_loss: 0.9276 - val_acc: 0.6286
Epoch 7/20
188/188 [==============================] - 77s 412ms/step - loss: 0.6196 - acc: 0.7483 - val_loss: 0.9835 - val_acc: 0.6193
Epoch 8/20
188/188 [==============================] - 79s 419ms/step - loss: 0.5495 - acc: 0.7771 - val_loss: 0.8940 - val_acc: 0.6662
Epoch 9/20
188/188 [==============================] - 77s 412ms/step - loss: 0.4922 - acc: 0.8036 - val_loss: 0.8989 - val_acc: 0.6662
Epoch 10/20
188/188 [==============================] - 82s 436ms/step - loss: 0.4450 - acc: 0.8223 - val_loss: 0.9060 - val_acc: 0.6967
Epoch 11/20
188/188 [==============================] - 78s 413ms/step - loss: 0.3953 - acc: 0.8442 - val_loss: 0.9710 - val_acc: 0.6619
Epoch 12/20
188/188 [==============================] - 78s 414ms/step - loss: 0.3631 - acc: 0.8578 - val_loss: 0.9839 - val_acc: 0.6697
Epoch 13/20
188/188 [==============================] - 78s 413ms/step - loss: 0.3307 - acc: 0.8692 - val_loss: 0.9718 - val_acc: 0.6932
              precision    recall  f1-score   support

        none       0.84      0.70      0.77       755
    crackles       0.62      0.67      0.64       378
     wheezes       0.53      0.69      0.60       181
        both       0.46      0.62      0.53       107

    accuracy                           0.69      1421
   macro avg       0.61      0.67      0.64      1421
weighted avg       0.71      0.69      0.70      1421

[[532 130  79  14]
 [ 65 255  14  44]
 [ 29   9 125  18]
 [  6  19  16  66]]
 
 


None
writing to NB75_MID3_DO0.30_BS64_hen
Epoch 1/30
378/378 [==============================] - 160s 423ms/step - loss: 1.4442 - acc: 0.4611 - val_loss: 2.6680 - val_acc: 0.1705
Epoch 2/30
378/378 [==============================] - 157s 416ms/step - loss: 0.9978 - acc: 0.5897 - val_loss: 2.3626 - val_acc: 0.2642
Epoch 3/30
378/378 [==============================] - 157s 416ms/step - loss: 0.8759 - acc: 0.6451 - val_loss: 1.6475 - val_acc: 0.4311
Epoch 4/30
378/378 [==============================] - 155s 410ms/step - loss: 0.7807 - acc: 0.6854 - val_loss: 2.2784 - val_acc: 0.3963
Epoch 5/30
378/378 [==============================] - 157s 415ms/step - loss: 0.6856 - acc: 0.7255 - val_loss: 1.1087 - val_acc: 0.6016
Epoch 6/30
378/378 [==============================] - 157s 415ms/step - loss: 0.5966 - acc: 0.7606 - val_loss: 1.0754 - val_acc: 0.6200
Epoch 7/30
378/378 [==============================] - 155s 411ms/step - loss: 0.5568 - acc: 0.7815 - val_loss: 1.1667 - val_acc: 0.5959
Epoch 8/30
378/378 [==============================] - 158s 418ms/step - loss: 0.4930 - acc: 0.8064 - val_loss: 1.4367 - val_acc: 0.6129
Epoch 9/30
378/378 [==============================] - 194s 513ms/step - loss: 0.4281 - acc: 0.8322 - val_loss: 1.1811 - val_acc: 0.6676
Epoch 10/30
378/378 [==============================] - 191s 504ms/step - loss: 0.3764 - acc: 0.8560 - val_loss: 1.2679 - val_acc: 0.6577
Epoch 11/30
378/378 [==============================] - 195s 516ms/step - loss: 0.3440 - acc: 0.8660 - val_loss: 1.1000 - val_acc: 0.6747
              precision    recall  f1-score   support

        none       0.67      0.82      0.74       760
    crackles       0.68      0.40      0.50       375
     wheezes       0.52      0.36      0.42       185
        both       0.40      0.58      0.47       111

    accuracy                           0.63      1431
   macro avg       0.57      0.54      0.53      1431
weighted avg       0.63      0.63      0.61      1431

[[622  54  50  34]
 [194 149   4  28]
 [ 83   3  66  33]
 [ 26  13   8  64]]
 
 
 
 
 
 '''    
Epoch 1/30
755/755 [==============================] - 162s 215ms/step - loss: 1.5323 - acc: 0.4433 - val_loss: 1.4336 - val_acc: 0.5426
Epoch 2/30
755/755 [==============================] - 163s 216ms/step - loss: 1.1082 - acc: 0.5669 - val_loss: 1.1537 - val_acc: 0.5433
Epoch 3/30
755/755 [==============================] - 163s 215ms/step - loss: 0.9245 - acc: 0.6391 - val_loss: 1.2524 - val_acc: 0.5774
Epoch 4/30
755/755 [==============================] - 162s 215ms/step - loss: 0.7898 - acc: 0.6914 - val_loss: 1.0782 - val_acc: 0.5795
Epoch 5/30
755/755 [==============================] - 161s 213ms/step - loss: 0.6533 - acc: 0.7440 - val_loss: 1.0547 - val_acc: 0.6300
Epoch 6/30
755/755 [==============================] - 158s 210ms/step - loss: 0.5725 - acc: 0.7770 - val_loss: 1.3998 - val_acc: 0.5291
Epoch 7/30
755/755 [==============================] - 160s 212ms/step - loss: 0.5097 - acc: 0.7993 - val_loss: 1.2421 - val_acc: 0.6634
Epoch 8/30
755/755 [==============================] - 163s 216ms/step - loss: 0.4319 - acc: 0.8315 - val_loss: 1.0946 - val_acc: 0.6477
Epoch 9/30
755/755 [==============================] - 165s 218ms/step - loss: 0.3854 - acc: 0.8529 - val_loss: 0.9407 - val_acc: 0.7088
Epoch 10/30
755/755 [==============================] - 163s 216ms/step - loss: 0.3345 - acc: 0.8708 - val_loss: 1.1463 - val_acc: 0.6790
Epoch 11/30
755/755 [==============================] - 163s 216ms/step - loss: 0.2878 - acc: 0.8892 - val_loss: 1.4695 - val_acc: 0.6371
Epoch 12/30
755/755 [==============================] - 163s 216ms/step - loss: 0.2531 - acc: 0.9028 - val_loss: 1.2604 - val_acc: 0.6733
Epoch 13/30
755/755 [==============================] - 163s 216ms/step - loss: 0.2266 - acc: 0.9125 - val_loss: 1.0813 - val_acc: 0.6768
Epoch 14/30
755/755 [==============================] - 163s 216ms/step - loss: 0.2006 - acc: 0.9261 - val_loss: 1.2451 - val_acc: 0.6875
              
              
              precision    recall  f1-score   support    - Ref f1-scoe 

        none       0.81      0.74      0.77       755    -   0.81
    crackles       0.65      0.66      0.66       378    -   0.70
     wheezes       0.49      0.67      0.56       181    -   0.62
        both       0.56      0.53      0.55       107    -   0.57

    accuracy                           0.69      1421
   macro avg       0.63      0.65      0.63      1421
weighted avg       0.71      0.69      0.70      1421












188/188 [==============================] - 84s 446ms/step - loss: 1.2910 - acc: 0.4014 - val_loss: 1.1512 - val_acc: 0.4915
Epoch 2/30
188/188 [==============================] - 80s 425ms/step - loss: 1.0925 - acc: 0.5277 - val_loss: 1.1389 - val_acc: 0.4979
Epoch 3/30
188/188 [==============================] - 80s 424ms/step - loss: 0.9870 - acc: 0.5832 - val_loss: 1.0916 - val_acc: 0.5163
Epoch 4/30
188/188 [==============================] - 80s 424ms/step - loss: 0.8941 - acc: 0.6252 - val_loss: 0.9689 - val_acc: 0.6072
Epoch 5/30
188/188 [==============================] - 78s 416ms/step - loss: 0.7996 - acc: 0.6695 - val_loss: 0.9326 - val_acc: 0.6009
Epoch 6/30
188/188 [==============================] - 80s 424ms/step - loss: 0.7172 - acc: 0.7035 - val_loss: 0.9123 - val_acc: 0.6364
Epoch 7/30
188/188 [==============================] - 78s 415ms/step - loss: 0.6325 - acc: 0.7402 - val_loss: 0.9938 - val_acc: 0.5902
Epoch 8/30
188/188 [==============================] - 78s 416ms/step - loss: 0.5762 - acc: 0.7665 - val_loss: 0.9673 - val_acc: 0.6136
Epoch 9/30
188/188 [==============================] - 80s 424ms/step - loss: 0.5005 - acc: 0.7972 - val_loss: 0.8565 - val_acc: 0.6648
Epoch 10/30
188/188 [==============================] - 79s 423ms/step - loss: 0.4544 - acc: 0.8182 - val_loss: 0.9016 - val_acc: 0.6811
Epoch 11/30
188/188 [==============================] - 80s 425ms/step - loss: 0.4050 - acc: 0.8371 - val_loss: 0.8506 - val_acc: 0.6932
Epoch 12/30
188/188 [==============================] - 78s 415ms/step - loss: 0.3551 - acc: 0.8595 - val_loss: 0.9650 - val_acc: 0.6903
Epoch 13/30
188/188 [==============================] - 80s 424ms/step - loss: 0.3163 - acc: 0.8773 - val_loss: 0.9644 - val_acc: 0.7010
Epoch 14/30
188/188 [==============================] - 80s 424ms/step - loss: 0.2999 - acc: 0.8840 - val_loss: 0.9184 - val_acc: 0.7116
Epoch 15/30
188/188 [==============================] - 78s 415ms/step - loss: 0.2636 - acc: 0.8971 - val_loss: 1.0105 - val_acc: 0.6911
Epoch 16/30
188/188 [==============================] - 80s 425ms/step - loss: 0.2313 - acc: 0.9101 - val_loss: 0.9138 - val_acc: 0.7493
              precision    recall  f1-score   support

        none       0.81      0.73      0.76       755
    crackles       0.60      0.74      0.66       378
     wheezes       0.57      0.52      0.54       183
        both       0.49      0.49      0.49       105

    accuracy                           0.69      1421
   macro avg       0.62      0.62      0.61      1421
weighted avg       0.70      0.69      0.69      1421

[[549 149  39  18]
 [ 71 280  13  14]
 [ 47  20  95  21]
 [ 14  20  20  51]]


'''
    
    




 
## Best model so far ## 
 
Params: 'NB75_MID0_DO0.30_BS64_hen'
 
 
 Test set:
              precision    recall  f1-score   support

        none       0.84      0.87      0.85       764
    crackles       0.80      0.70      0.75       376
     wheezes       0.73      0.80      0.77       182
        both       0.73      0.75      0.74       109

    accuracy                           0.81      1431
   macro avg       0.78      0.78      0.78      1431
weighted avg       0.81      0.81      0.81      1431

[[665  50  41   8]
 [ 98 263   3  12]
 [ 21   4 146  11]
 [  8  10   9  82]]
 
 
 
Training set:
              precision    recall  f1-score   support

        none       0.83      0.84      0.84        64
    crackles       0.80      0.77      0.78        64
     wheezes       0.81      0.81      0.81        64
        both       0.82      0.84      0.83        64

    accuracy                           0.82       256
   macro avg       0.82      0.82      0.82       256
weighted avg       0.82      0.82      0.82       256

[[54  6  4  0]
 [ 8 49  3  4]
 [ 3  1 52  8]
 [ 0  5  5 54]]
 
 ```




## Code snippet

```
    model = tf.keras.Sequential()
    model.add(Conv2D(128, [7,11], strides = [2,2], padding = 'SAME', input_shape = (sample_height, sample_width, 1)))
    model.add(LeakyReLU(alpha = 0.1))
    model.add(MaxPool2D(padding = 'SAME'))

    model.add(Conv2D(256, [5,5], padding = 'SAME'))
    model.add(LeakyReLU(alpha = 0.1))
    model.add(MaxPool2D(padding = 'SAME'))

    model.add(Conv2D(256, [1,1], padding = 'SAME'))
    model.add(Conv2D(256, [3,3], padding = 'SAME'))
    model.add(LeakyReLU(alpha = 0.1))
    model.add(MaxPool2D(padding = 'SAME'))

    model.add(Conv2D(512, [1,1], padding = 'SAME'))
    model.add(Conv2D(512, [3,3], padding = 'SAME',activation = 'relu'))
    model.add(Conv2D(512, [1,1], padding = 'SAME'))
    model.add(Conv2D(512, [3,3], padding = 'SAME', activation = 'relu'))
    model.add(MaxPool2D(padding = 'SAME'))
    model.add(Flatten())

    model.add(Dense(4096, activation = 'relu'))
    model.add(Dropout(0.5))

    model.add(Dense(512, activation = 'relu'))
    model.add(Dense(4, activation = 'softmax'))
```

## Model
```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_16 (Conv2D)           (None, 38, 123, 128)      9984      
_________________________________________________________________
leaky_re_lu_6 (LeakyReLU)    (None, 38, 123, 128)      0         
_________________________________________________________________
max_pooling2d_8 (MaxPooling2 (None, 19, 62, 128)       0         
_________________________________________________________________
conv2d_17 (Conv2D)           (None, 19, 62, 256)       819456    
_________________________________________________________________
leaky_re_lu_7 (LeakyReLU)    (None, 19, 62, 256)       0         
_________________________________________________________________
max_pooling2d_9 (MaxPooling2 (None, 10, 31, 256)       0         
_________________________________________________________________
conv2d_18 (Conv2D)           (None, 10, 31, 256)       65792     
_________________________________________________________________
conv2d_19 (Conv2D)           (None, 10, 31, 256)       590080    
_________________________________________________________________
leaky_re_lu_8 (LeakyReLU)    (None, 10, 31, 256)       0         
_________________________________________________________________
max_pooling2d_10 (MaxPooling (None, 5, 16, 256)        0         
_________________________________________________________________
conv2d_20 (Conv2D)           (None, 5, 16, 512)        131584    
_________________________________________________________________
conv2d_21 (Conv2D)           (None, 5, 16, 512)        2359808   
_________________________________________________________________
conv2d_22 (Conv2D)           (None, 5, 16, 512)        262656    
_________________________________________________________________
conv2d_23 (Conv2D)           (None, 5, 16, 512)        2359808   
_________________________________________________________________
max_pooling2d_11 (MaxPooling (None, 3, 8, 512)         0         
_________________________________________________________________
flatten_2 (Flatten)          (None, 12288)             0         
_________________________________________________________________
dense_6 (Dense)              (None, 4096)              50335744  
_________________________________________________________________
dropout_2 (Dropout)          (None, 4096)              0         
_________________________________________________________________
dense_7 (Dense)              (None, 512)               2097664   
_________________________________________________________________
dense_8 (Dense)              (None, 4)                 2052      
=================================================================
Total params: 59,034,628
Trainable params: 59,034,628
Non-trainable params: 0
_______________________________

```
