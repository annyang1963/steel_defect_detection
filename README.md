# steel_defect_detection
### data
Images are named with a unique ImageId.

Each image may have no defects, a defect of a single class, or defects of multiple classes. For each image you must segment defects of each class (ClassId = [1, 2, 3, 4]).

### severstal-predict-missing-masks.ipynb
Create a CNN to predict if a certain image has no defect (i.e., it has 4 missing masks).

### severstal-simple-2-step-pipeline.ipynb
Train the model on the training data that have defects. Then, perform inference only on test images that have defects.
