# NLP4Geo

Material for the NLP tutorial at the [Geo text mining workshop](https://ersa.org/events/geo-text-workshop/) organised by the University of Groningen


## Tutorial Outline 

1. NLP
    1. working with Spacy to analyze the linguistic structure of a text
2. Named Entity Classification
3. Named Entitiy Linking and Geocoding
4. Information Extraction using linguistic patterns
5. Using a pretrained language model (ChatGPT)

## Prerequisites

In this tutorial we will be using Python as programming language, and Jupyter notebooks for the exercises and experiments. There are two ways you can work with Jupyter notebooks: either by ensuring that the software is installed on your laptop or by using Google 

### Installation of Python and Jupyter

Installation instructions

* Python ([download](https://www.python.org/downloads/), [installation](https://www.python.org/about/gettingstarted/))
* [Jupyter](https://jupyter.org/install)


### Using Google colaboratory

If you do not have access to a computer where you can install Python/Jupyter, you can also use [Google colaboratory](https://colab.research.google.com/notebooks/intro.ipynb), a cloud platform that supports working with Jupyter notebooks. The libraries mentioned below are available in colaboratory as well. 

(Uploading documents, linking with google drive)

### Python Libraries

For NLP we will be using [Spacy](https://spacy.io/), an industry-strength general-purpose open-source framework for NLP. You will need to install the spacy (python) library, as well as at least one language model. 

1. [Spacy Installation](https://spacy.io/usage) 
2. **Spacy models**: By default, Spacy installation only installs the small (-sm) models for a language you selected (ie. en_core_web_sm). You can also install larger (and more accurate models) by follwing the instructions [here](https://spacy.io/usage/models).  The -trf (transformer) model for English is the most accurate for that language, but installation can be tricky (esp. if you have other versions of the python transformer libraries installed). Alternatively, you can also try the large English model. For other languages, transformer-based models are not always available (e.g. Dutch), for those languages the large models are also the most accurate.
3. For access to [geonames](https://www.geonames.org/), we will use the [geocoder](https://geocoder.readthedocs.io/) Python library

