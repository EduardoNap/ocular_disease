# ocular_disease
Ocular_disease recognition using a MLP-CNN model with 'VGG16' as base.

# Steps
1. CSV preprocessing: This preprocess makes a diagnosis by eye instead of diagnosis by individual.
2. Image preprocessing: Remove black pixels, resize and equalize the images.
3. Data augmentation: Balance the classes with shifts, rotations, zooms and brightness.
4. Files: add stratification, add the additional tabular data and divide in train and test files.
5. Model and hyperparamters: Build the MLP-CNN model with attention and search for optimal hyeperparameters.
6. Model: Create the final model with the hyperparameters and evaluate the model.
   
