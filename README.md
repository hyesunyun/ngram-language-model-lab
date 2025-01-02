# ngram-language-model-lab

Lab for CS6983/CS4973 Research in Human-Centered NLP.

You can run these notebooks on [Google Colab](https://colab.research.google.com/github/hyesunyun/ngram-language-model-lab/blob/main/n_gram_word_prediction.ipynb). 
You won't need to create a virtual environment for Google Colab as it comes with all the packages we need installed. However, you will need to manually add the data (`en_US.twitter.txt` from data folder) to the files in Google Colab.

![Screenshot 2025-01-02 at 9 52 05 AM](https://github.com/user-attachments/assets/fe12a3c3-dc88-401b-9e36-05e2f545be61)

You can also run them locally (no GPU is needed):
```bash
# clone the repo
git clone https://github.com/hyesunyun/ngram-language-model-lab.git
cd ngram-language-model-lab

# create a virtual environment (conda)
conda create -n ngram python=3.10
conda activate ngram

# install dependencies
pip install -r requirements.txt

# run the server
jupyter notebook
```
