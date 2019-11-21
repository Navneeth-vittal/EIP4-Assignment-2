# EIP4-Assignment-2

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 11s 183us/step - loss: 0.2123 - acc: 0.9344 - val_loss: 0.0816 - val_acc: 0.9733
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 6s 94us/step - loss: 0.0689 - acc: 0.9788 - val_loss: 0.0419 - val_acc: 0.9863
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 6s 95us/step - loss: 0.0545 - acc: 0.9827 - val_loss: 0.0336 - val_acc: 0.9893
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 6s 99us/step - loss: 0.0440 - acc: 0.9862 - val_loss: 0.0317 - val_acc: 0.9894
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 6s 101us/step - loss: 0.0395 - acc: 0.9878 - val_loss: 0.0407 - val_acc: 0.9884
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 6s 98us/step - loss: 0.0348 - acc: 0.9892 - val_loss: 0.0219 - val_acc: 0.9940
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 6s 98us/step - loss: 0.0323 - acc: 0.9896 - val_loss: 0.0224 - val_acc: 0.9926
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 6s 97us/step - loss: 0.0295 - acc: 0.9902 - val_loss: 0.0228 - val_acc: 0.9929
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 6s 95us/step - loss: 0.0285 - acc: 0.9913 - val_loss: 0.0221 - val_acc: 0.9934
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 6s 94us/step - loss: 0.0271 - acc: 0.9917 - val_loss: 0.0218 - val_acc: 0.9932
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 6s 95us/step - loss: 0.0258 - acc: 0.9917 - val_loss: 0.0206 - val_acc: 0.9936
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 6s 93us/step - loss: 0.0246 - acc: 0.9923 - val_loss: 0.0190 - val_acc: 0.9942
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 6s 93us/step - loss: 0.0235 - acc: 0.9924 - val_loss: 0.0178 - val_acc: 0.9945
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 6s 92us/step - loss: 0.0210 - acc: 0.9937 - val_loss: 0.0193 - val_acc: 0.9941
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 6s 93us/step - loss: 0.0217 - acc: 0.9929 - val_loss: 0.0201 - val_acc: 0.9936
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 6s 94us/step - loss: 0.0200 - acc: 0.9933 - val_loss: 0.0173 - val_acc: 0.9950
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 6s 94us/step - loss: 0.0192 - acc: 0.9938 - val_loss: 0.0187 - val_acc: 0.9940
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 6s 93us/step - loss: 0.0198 - acc: 0.9937 - val_loss: 0.0200 - val_acc: 0.9944
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 6s 93us/step - loss: 0.0184 - acc: 0.9940 - val_loss: 0.0233 - val_acc: 0.9930
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 6s 93us/step - loss: 0.0179 - acc: 0.9942 - val_loss: 0.0182 - val_acc: 0.9945
<keras.callbacks.History at 0x7fc320107ba8>


score = model.evaluate(X_test, Y_test, verbose=0)
print(score)
[0.018185722491616617, 0.9945]

99.40% accuracy[Epoch 00006]
99.50% max accuracy[Epoch 00016]
12,658 parameters
Batchsize-128
Epochs-20

Use of Batch Normalization that reduces the number of training epochs to train the network and stabilize the learning process.
Dropout of 0.09 provides remarkable effective regularization and reduce overfitting.
Use of scheduler and round.
