# PlantsMultiLayerModel

## Commit 1 (18/10) - 5896cadf6c02cb5496795f9c54243de3f426e33c:
- Validation Loss: 2.3568, Validation Accuracy: 0.5980

## Commit 2 (23/10) - Used 10 classes - 3170f5df54a7a6a90fe8f2288c5ee7fbc1420db6:
- Validation Loss: 1.541, Validation Accuracy: 0.725
- Used 10 classes with the accuracy reaching 72%

## Commit 4 (24/10) - Added Testing - 9e4714c965c64ff64c756af1f2474e41af7bec58:
- Plotting graphs to track accuracy and loss
- Added code to test model with new images

## Commit 6 (25/10) - Increased MaxPooling Value - c13f47f2f993cd35c1f13ec90cbdef40390a072c:
- Increased value of the first MaxPooling layer from (2, 2) to (3, 3)
- Accuracy increased from 52% to 62.75%.

## Commit 8 (25/10) - Increased All MaxPooling Values - 79d785935e099ec05c64a4370132d3b33c2f8e71:
- Increased values of the all MaxPooling layers from (2, 2) to (3, 3)
- Accuracy peaked at 70% but ended at 68% (Apply Regularization?)

## Commit 10 (26/10) - Increased Two MaxPooling Values - a5d835aee4ce92c6889533101bcf4ddc285d191d:
- Changig the value of the 1st and last MaxPooling Layer produced the highest accuracy of 73%
- 2nd MaxPooling layers value changed back to (2, 2)

## Commit 12 (15/11) - Increased All MPs & Adding Recordings - cf3441be6a45e5695eed74605e8b29991333b001:
- Ran the algorithm multiple times for Two MaxPooling pool size increased and smade a spreadsheet
- Ran the algorithm multiple times for all MaxPooling pool size increased and smade a spreadsheet
- Accuracy was higher when all MaxPooling pool size were increased so model changed to that

## Commit 14 (22/11) - Increased All MPs to 4x4 - 4d0c3432f6b0f6dd12ac311c1232caf8576d41f1:
- Accuracy was similar to 3x3 pooling layers but loss was significantly lower
- So kept 4x4 layers as they make better predictions on unseen data

## Commit 16 (18/12) - Added Regularization - 873444f93000d163ba0b317b04549a4216c437e1:
- Added regularization to prevent overfitting
