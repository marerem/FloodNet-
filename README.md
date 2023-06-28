

# FloodNet: Segmentation of images during a flooding event
# Group : Chang Chun, Maria Eremina, Tian Tian



## Evaluation Repository
"https://colab.research.google.com/drive/1qOz66oToUl7gVtwbrzcIWrGL7kAxhuD6?usp=sharing"
This is a shared code for evaluation part "evaluation.ipynb". Run it and download the checkpoint file in the proper data path. If want to visualize image samples (the last part of the code), download the "test" data folder first. If run this code in Colab, please save the data in Google Drive first, then right click the file and "Add a shortcut to Drive".

"https://colab.research.google.com/drive/1f0h6ZGIgItqxLrVqn61HGLps1oW-az6K?usp=sharing"
This is the full code of this project "FloodNet_Group3.ipynb", it best run in google colab because the data is stored in Google Drive and all the file paths have been set based on that. Please ensure that the back-end GPU is available when running. You don't need to run this code for checking the results.



## Setup

please tell us how to install dependencies in a new python environment for this code:
```
# create a local virtual environment in the venv folder
python -m venv venv
# activate this environment
source venv/bin/activate
# install requirements
pip install -r requirements.txt
```

we will start jupyter notebook in this environment and then run your evaluation.ipynb
```
jupyter notebook
```

## Repostory Size and Runtime Considerations

* we will not train a model for you. Provide a checkpoint and some (few) test data to reproduce your results.
* please do not commit massively large files (>500MB) in a repository. Maybe add one final model checkpoint that you do not update anymore (any update of large files in this repository will increase its size massively).
* if you have larger datasets, make sure that you make it available online (e.g. via GoogleDrive and EnacShare) and tell us how to download it if necessary.
