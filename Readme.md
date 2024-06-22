# Sentiment Analysis of IMDB Reviews

*From text to insights

## How to use

``` sh
mkdir ./Sentiment

cd Sentiment

git clone https://github.com/kumargautampushkar/Sentiment-Analysis-of-IMDb-Reviews-From-Text-to-Insights
```

First , you need to configure a python virtual environment inside the cloned folder , the code used here is device agnostic code so it does not matter if the end device has cpu or gpu.

``` sh
python -m venv ./Sentiment
```

Activate the shell script after configuring virtual environment

``` sh
source ./Sentiment/Scripts/activate.sh
```

Install all the necessary packages using pip 

``` sh
python -m pip install torch torchvision torchaudio nltk pandas tqdm WordCloud numpy
```

