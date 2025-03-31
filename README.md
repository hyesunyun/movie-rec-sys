# movie-rec-sys

Extra Lecture for CS6983/CS4973 Research in Human-Centered NLP (Northeastern University).

You can run these notebooks on [Google Colab](https://colab.research.google.com/github/hyesunyun/). 
You won't need to create a virtual environment for Google Colab as it comes with all the packages we need installed.

In order to run the Colab with GPU, change the runtime type to one of the GPU options for Hardware accelerator.

You can also run them locally (although you will need a GPU to run distilBERT code):
```bash
# clone the repo
git clone https://github.com/hyesunyun/movie-rec-sys.git
cd movie-rec-sys

# create a virtual environment (conda)
conda create -n movie-rec-sys python=3.12
conda activate movie-rec-sys

# install dependencies
pip install -r requirements.txt

# run the server
jupyter notebook
```
