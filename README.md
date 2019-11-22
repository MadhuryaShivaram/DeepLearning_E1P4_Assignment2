# DeepLearning_E1P4_Assignment2

20 EPOCHS:

Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 8s 135us/step - loss: 0.5314 - acc: 0.8508 - val_loss: 0.1123 - val_acc: 0.9773
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 6s 100us/step - loss: 0.2582 - acc: 0.9237 - val_loss: 0.0538 - val_acc: 0.9880
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1977 - acc: 0.9413 - val_loss: 0.0541 - val_acc: 0.9856
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 6s 101us/step - loss: 0.1697 - acc: 0.9470 - val_loss: 0.0392 - val_acc: 0.9903
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1522 - acc: 0.9504 - val_loss: 0.0299 - val_acc: 0.9915
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 6s 102us/step - loss: 0.1405 - acc: 0.9512 - val_loss: 0.0265 - val_acc: 0.9934
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1294 - acc: 0.9527 - val_loss: 0.0272 - val_acc: 0.9930
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1243 - acc: 0.9528 - val_loss: 0.0238 - val_acc: 0.9928
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1196 - acc: 0.9540 - val_loss: 0.0212 - val_acc: 0.9937
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1130 - acc: 0.9555 - val_loss: 0.0242 - val_acc: 0.9928
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 6s 98us/step - loss: 0.1097 - acc: 0.9550 - val_loss: 0.0224 - val_acc: 0.9941
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1061 - acc: 0.9564 - val_loss: 0.0209 - val_acc: 0.9937
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1013 - acc: 0.9575 - val_loss: 0.0198 - val_acc: 0.9943
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1048 - acc: 0.9553 - val_loss: 0.0184 - val_acc: 0.9944
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1007 - acc: 0.9567 - val_loss: 0.0201 - val_acc: 0.9947
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 6s 98us/step - loss: 0.0984 - acc: 0.9567 - val_loss: 0.0184 - val_acc: 0.9951
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 6s 98us/step - loss: 0.0953 - acc: 0.9579 - val_loss: 0.0186 - val_acc: 0.9946
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 6s 98us/step - loss: 0.0960 - acc: 0.9583 - val_loss: 0.0181 - val_acc: 0.9953
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 6s 99us/step - loss: 0.0938 - acc: 0.9583 - val_loss: 0.0183 - val_acc: 0.9953
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 6s 99us/step - loss: 0.0915 - acc: 0.9579 - val_loss: 0.0179 - val_acc: 0.9946
<keras.callbacks.History at 0x7f8a30f54208>


2. mode.evaluate() on Test Data :
   Output : [0.01962876503764419, 0.9942]

3. Strategy taken to achieve this.
   Reduced the number of filters used in the 2nd layer (from 32 to 16) as it would reduce the no. of parameters but maintain the accuracy around 99.4 
