# session6
session6 repository

## Changes to achieve 99.40 validation accuracy
In this assignment I have used the following changes in model 
* Batch Normalization
* Dropout
* Global Average Pooling
* Maxpooling
* 3x3 Convolution

## Results
Total Number of parameters: 11,354
Best Validation Accuracy: 99.40 (After 15th Epoch)

## Logs



Epoch:  1

  0%|          | 0/469 [00:00<?, ?it/s]<ipython-input-2-16a0b1419c2e>:38: UserWarning: Implicit dimension choice for log_softmax has been deprecated. Change the call to include dim=X as an argument.
  return F.log_softmax(x)
loss=0.12514454126358032 batch_id=468: 100%|██████████| 469/469 [00:24<00:00, 18.95it/s]


Test set: Average loss: 0.0587, Accuracy: 9818/10000 (98.18%)

Epoch:  2

loss=0.038616325706243515 batch_id=468: 100%|██████████| 469/469 [00:21<00:00, 22.00it/s]


Test set: Average loss: 0.0394, Accuracy: 9869/10000 (98.69%)

Epoch:  3

loss=0.06341923028230667 batch_id=468: 100%|██████████| 469/469 [00:22<00:00, 21.14it/s]


Test set: Average loss: 0.0336, Accuracy: 9894/10000 (98.94%)

Epoch:  4

loss=0.04360603168606758 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 22.58it/s]


Test set: Average loss: 0.0299, Accuracy: 9908/10000 (99.08%)

Epoch:  5

loss=0.03194396570324898 batch_id=468: 100%|██████████| 469/469 [00:19<00:00, 23.60it/s]


Test set: Average loss: 0.0303, Accuracy: 9901/10000 (99.01%)

Epoch:  6

loss=0.028794623911380768 batch_id=468: 100%|██████████| 469/469 [00:19<00:00, 23.68it/s]


Test set: Average loss: 0.0257, Accuracy: 9915/10000 (99.15%)

Epoch:  7

loss=0.03611478582024574 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 23.10it/s]


Test set: Average loss: 0.0219, Accuracy: 9934/10000 (99.34%)

Epoch:  8

loss=0.015238378196954727 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 23.17it/s]


Test set: Average loss: 0.0236, Accuracy: 9922/10000 (99.22%)

Epoch:  9

loss=0.03035607375204563 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 22.45it/s]


Test set: Average loss: 0.0225, Accuracy: 9932/10000 (99.32%)

Epoch:  10

loss=0.06629817932844162 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 22.44it/s]


Test set: Average loss: 0.0200, Accuracy: 9938/10000 (99.38%)

Epoch:  11

loss=0.03406406566500664 batch_id=468: 100%|██████████| 469/469 [00:21<00:00, 22.25it/s]


Test set: Average loss: 0.0206, Accuracy: 9935/10000 (99.35%)

Epoch:  12

loss=0.007630960550159216 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 23.21it/s]


Test set: Average loss: 0.0220, Accuracy: 9931/10000 (99.31%)

Epoch:  13

loss=0.0061639477498829365 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 23.03it/s]


Test set: Average loss: 0.0217, Accuracy: 9933/10000 (99.33%)

Epoch:  14

loss=0.007158093154430389 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 22.45it/s]


Test set: Average loss: 0.0212, Accuracy: 9930/10000 (99.30%)

Epoch:  15

loss=0.01895444095134735 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 22.49it/s]


Test set: Average loss: 0.0200, Accuracy: 9940/10000 (99.40%)

Epoch:  16

loss=0.03947668895125389 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 22.64it/s]


Test set: Average loss: 0.0233, Accuracy: 9930/10000 (99.30%)

Epoch:  17

loss=0.0073380316607654095 batch_id=468: 100%|██████████| 469/469 [00:21<00:00, 22.07it/s]


Test set: Average loss: 0.0227, Accuracy: 9930/10000 (99.30%)

Epoch:  18

loss=0.05423063412308693 batch_id=468: 100%|██████████| 469/469 [00:20<00:00, 22.96it/s]


Test set: Average loss: 0.0200, Accuracy: 9939/10000 (99.39%)





