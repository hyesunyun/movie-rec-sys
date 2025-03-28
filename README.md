# movie-rec-sys

Extra Lecture for CS6983/CS4973 Research in Human-Centered NLP (Northeastern University).

You can run these notebooks on [Google Colab](https://colab.research.google.com/github/hyesunyun/). 
You won't need to create a virtual environment for Google Colab as it comes with all the packages we need installed. However, you will need to manually add the data (`Top_10000_Movies.csv` from data folder) to the files in Google Colab.

![Screenshot 2025-01-02 at 9 52 05 AM](https://github.com/user-attachments/assets/fe12a3c3-dc88-401b-9e36-05e2f545be61)

You can also run them locally:
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
