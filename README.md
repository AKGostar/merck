# merck
Merck Molecular Activity Challenge code

re-implementation of the paper: 

`Ma, J., Sheridan, R.P., Liaw, A., Dahl, G.E. and Svetnik, V., 2015. Deep neural nets as a method for quantitative structure–activity relationships. Journal of chemical information and modeling, 55(2), pp.263-274.`

## Installation
The code was tested in keras with Tensorflow backend. 
The packages needed are listed in the `requirements.txt`

## Running the Code
* Download the training and test dataset from: [Paper supplementary materials](http://pubs.acs.org/doi/suppl/10.1021/ci500747n/suppl_file/ci500747n_si_002.zip)
* Set `data_root` and `save_root` varibles in `data_preprocessing.py` and run it (This will remove the features that are not common to both training and test sets and, rescale features and activations).
* point the `data_root` to where the pre-processed training and test files are located.
* `python main.py`






