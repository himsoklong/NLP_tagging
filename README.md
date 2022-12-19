# NLP_tagging
This project aims to acreate an NLP term tagger using RNN and CRF models.

## How to install
0.  We recomend setting up a virtual environment (e.g. a conda venv [https://anaconda.org/anaconda/conda](https://anaconda.org/anaconda/conda))
1.  Clone the data-science repository:
```sh
git clone https://github.com/himsoklong/NLP_tagging.git
```
2.  Go into the project folder and install the needed packages with:
```sh
pip install -r requirements.txt
```
**Note**: Our experiment was run using jupyter notebook, thus you can run the code in the ipynb files.

3. For the RNN model we used a pre-trained model named FastText which can be found in the Code folder.


## How to use

Please refer to Jupyter notebook CRF_model or RNN_Model file in Code folder.

To use the virtual enviroment from Jupyter notebook run:
```sh
pip install --user ipykernel
python -m ipykernel install --user --name=myenv
```



