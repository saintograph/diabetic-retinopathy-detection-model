## Diabetic Retinopathy Detection with Convolutional Neural Networks

The data for this project can be found here: https://www.kaggle.com/c/diabetic-retinopathy-detection/data

The following journal paper is this project's main reference: https://jamanetwork.com/journals/jama/fullarticle/2588763

Reports are provided in `.html` format for convenience :

* benchmark model - benchmark_model.html
* final model - final_model.html

The dataset for this project has not been cleaned and the size of training and testing images are:

* training: 39GB (35,126 images)
* testing: 53.9GB (53,576 images)

Images are noisy and come in multiple sizes and resolution.

## Preprocessing

The scripts are modified files from [Tensorflow Slim's Research Model](https://github.com/tensorflow/models/tree/master/research/slim/datasets) and can be found in the `preprocessing-scripts` directory.

The scripts are open sourced: http://www.apache.org/licenses/LICENSE-2.0

The `data_utils.py` pre-processing script was adapted from the script provided by authors of **Machine Learning with Tensorflow 1.x** by Packtpub - Quan Hua, Shams Ul Azeem and Saif Ahmed.

Run `python download_and_convert_data.py --dataset_name diabetic --dataset_dir \diabetic\` , assuming the images were downloaded to the diabetic folder.

## Neural Network

The package requirements are listed in the file `requirements.txt` and can be installed with `pip install -r requirements.txt` in the project's root directory.

**The use of `virtualenv` is recommended.**



