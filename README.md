# Fast SCNN on CITY SCAPES DATASET

This repo is the directory structure of "cityscapes" folder.

This project is carried out on google colaboratory.

This project includes:
1. Downloading cityscapes dataset to google drive using colab.
2. Building Cityscapes dataset (GTFINE and GTTRAINVALTEST) into TensorFlow sharded data TFRECORD.
3. Building and running FASTSCNN model on the dataset.

please refer to the build_cityscapes.ipynb python notebook to know how to build cityscapes dataset into sharded TFrecord successfully.

please refer to FastSCNN.ipynb python notebook for the FASTSCNN model.

please maintain the same diretory struture as given or change the directory parameters as required.
Because of the large size of the data, it has not been committed to the repo but the directory structure remains the same.
