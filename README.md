# Eigenfaces: Dogs and Cats

Classification of dog and cat faces using the PCA method described by Sirovich and Kirby in the article "Low-dimensional procedure for the characterization of human faces".

Data source: Animal faces dataset (AFHQv2 512×512). Kaggle. \
https://www.kaggle.com/datasets/dimensi0n/afhq-512?select=cat \
https://www.kaggle.com/datasets/dimensi0n/afhq-512?select=dog

Before running this project, please download cat and dog data from the links above. Then unzip the compressed folders into `cat` and `dog` folders respectively.

## How to run this project

After cloning the repository set up virtual environment and install the necessary requirements:
```
python -m venv venv 
venv\Scripts\activate
pip install -r requirements.txt
```

Then launch Jupyter Notebook by typing:
```
jupyter notebook
```

Now you can run the `project.ipynb` file.