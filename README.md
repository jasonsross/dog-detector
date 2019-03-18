# Dog Breed Classifer
by: Jason S. Ross

### Goal

This is an extension of the work done by Jeremy Jordan [here](https://github.com/jeremyjordan/dog-breed-classifier). My goal was to push the accuracy on this unique and small dataset by using more advanced techniques not seen in Jeremy's work. In this notebook you will learn about the following (italic items are new material compared to Jeremy's work).

- **Multiclass image classification** - image data organization, loading, preprocessing, and general pipelines
- **Imagenet models** - see how to use pre-trained models (from keras)
- **Transfer learning** - utilizing pre-trained models for accurate modeling of small datasets
- ***Image data generators*** - load, preprocess, categorize, and batch train your image data with little memory usage
- ***Automatic Image augmentation*** - increasing effective dataset size and model accuracy using image generator augmentation
- ***Fine-tuning*** - pushing transfer learning accuracy to it's limit

### Python Environment
Please make sure your environment has the following and any dependencies. I recommend starting with Anaconda:
- jupyter notebook
- numpy
- pandas
- scikit-learn
- keras/tensorflow

### Data

The data for the project is available [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip it to the dogImages folder in the project directory.

Pre-trained weights for the various models in this notebook are available [on my google drive here.](https://drive.google.com/file/d/1rglj434BMzlZP7Rih9b344BIefFGeZ1O/view?usp=sharing) This allows you to skip deep CNN training in this notebook which can be unreasonably long without a powerful GPU. Look for the cells that run `top_model.load_weights()`

## To Begin: Open the dog_detector.ipnyb in jupyter notebook
