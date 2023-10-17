# Tutorial: Intro to Data Science
Instructor: [Grishma Jena](https://gjena.github.io)

Want to perform Data Science but don’t know how to go about it? Have a dataset that you really want to analyze but not sure where to start? This hands-on session teaches how to explore datasets, use Machine Learning algorithms and derive insights from predictive models using popular tools in Python.

We will be using Jupyter to execute Python code for the purpose of this Data Science tutorial. A [virtual environment](https://docs.python.org/3/tutorial/venv.html) can be used to manage and isolate the packages for our project. Please follow these instructions to have all the dependencies ready before the tutorial as that will enable us to hit the ground running.

__Pre-requisites__

*Option A : Using Jupyter on your local machine*

Requires installation of packages but you will be able to use Jupyter and run code offline.
1. Ensure that pip is installed and upgrade it. Pip should already be available if you are using Python 3 >= 3.4 downloaded from python.org. For further installation instructions check [this](https://pip.pypa.io/en/stable/installing/).

2. Optional: If you plan on using a virtual environment, ensure venv (Python 3) is installed. Create a virtual environment and activate it. Detailed instructions [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/).

3. Install the required packages using pip in the terminal:

```
python3 -m pip install jupyter numpy pandas nltk lxml requests matplotlib sklearn graphviz
wikipedia gensim wordcloud --user
```

If you face problems installing NLTK, take a look at [this](https://www.nltk.org/install.html).

4. Open a Jupyter notebook with jupyter notebook in your terminal. This opens in your browser at default port 8888.

5. Download the sample notebook ‘Introduction to Data Science test’ and open it in Jupyter. Execute the code by clicking on Cell -> Run Cells. Check out [this video](https://www.youtube.com/watch?v=jZ952vChhuI) for a quick introduction to Jupyter.

*Option B: Using Google colaboratory on the cloud*

Bypasses installation of packages but needs internet to run code on the cloud. 

1. Access [Google colab](https://colab.research.google.com/notebooks/welcome.ipynb) and familiarize yourself with running code in the browser.

2. Read the 'Getting started' guide and take a look at the introductory video.

3. Download the sample notebook ‘Introduction to Data Science test’, upload it in Colab and open it. Execute the 
code by clicking on Runtime -> Run all.

Feel free to contact me in case of any queries.

