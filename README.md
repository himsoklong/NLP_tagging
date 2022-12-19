# NLP_tagging
This project is about making NLP term tagging using RNN and CRF model.

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
**Note**: Our experiment run by using jupyter notebook. so our code is written in ipynb file.

3. This project in RNN model, we use pre-trained model FastText. you can see in code folder. and some external models that need to be downloaded to fully utilise it like KeyBERT and Transfomer.


## How to use

Please refer to Jupyter notebook [**example_function**](example_function.ipynb) on how to use this package.

To use the virtual enviroment from Jupyter notebook run:
```sh
pip install --user ipykernel
python -m ipykernel install --user --name=myenv
```


