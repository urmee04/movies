# Recommendation Systems for Movies

Recommendation Systems are a type of information filtering systems as they improve the quality of search results and provides items that are more relevant to the search item or are realted to the search history of the user.

There are basically three types of recommender systems:-
- **Demographic Filtering:** They offer generalized recommendations to every user, based on movie popularity and/or genre. The System recommends the same movies to users with similar demographic features. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience. 

- **Content Based Filtering:** They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

- **Collaborative Filtering:** This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.

While demographic filtering is very elemantary and cannot be used practically, **Hybrid Systems** can take advantage of content-based and collaborative filtering as the two approaches are proved to be almost complimentary.

## Project Setup and Installation
## streamlit
**Streamlit** is a free, open-source, all-python framework that enables Machine Learning and Data scientists to quickly build interactive data apps.

## Install streamlit

### Prerequisites
- Favourite IDE or Text Editor
- Python 3.7 - Python 3.10
- PIP

### Setup Virtual Environment

It is recommended to use virtual environment to ensure that the dependencies pulled in for Streamlit don't impact any other Python projects you're working on. 

Below mentioned tools can be used for environment management:
- pipenv
- poetry
- venv
- virtualenv
- conda

### Install Streamlit on Windows
1. In the terminal, type:

   pip install streamlit

2. Test that the installation worked:

   streamlit hello

## Surprise 

**Surprise** is a Python scikit for building and analyzing recommender systems that deal with explicit rating data

## Install Surprise
**With pip (you'll need numpy, and a C compiler. Windows users might prefer using conda):**

- pip install numpy
- pip install scikit-surprise

**With conda:**

conda install -c conda-forge scikit-surprise

**For the latest version, you can also clone the repo and build the source (you'll first need Cython and numpy):**

- pip install numpy cython
- git clone https://github.com/NicolasHug/surprise.git
- cd surprise
- python setup.py install

## Demo
To launch the UI, run the application using **streamlit run app.py**







