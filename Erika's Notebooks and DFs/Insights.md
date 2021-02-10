## First Logistic Regression Baseline Model with Atlanta Weather
GridSearch with few params revealed:
#### Best max_iter: 100
#### Best penalty: l2
#### Best l1_ratio: 0.01
- With weather feature: 0.7076390669059216
- Without weather feature: 0.707254550115355

- With weather only slight improvement

## First Random Forest Baseline Model with Atlanta Weather
- With weather feature = Accuracy: 0.7326326582927455
- Without weather feature = Accuracy : 0.7332735196103564

- Weather made it slightly worse

## Logistic Regression Model with Chicago Weather, penalty = l2, max_iter = 1000
- With weather Accuracy: 0.6212341807593236
