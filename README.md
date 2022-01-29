# Get Pythonissed

### **Jupyter Notebooks**

Jupyter notebook is a web based notebook environment which is widely used for interactive programming, that is, code execution combined with rich markdown text and much more. The Jupyter notebook runs a local Ipython kernel on your machine and launches in your web browser. These notebooks are also called as Ipython notebooks, and have a '.ipynb' extension instead of traditional '.py' extension for Python files. 

Visit this link for installing and setting up a basic notebook - [Setting up Jupyter Notebook](https://realpython.com/jupyter-notebook-introduction/). The link also teaches you to write and execute a basic Python code in a Notebook cell.

### **Google Colab**
Google Colab is a platform provided by Google, which runs a Jupyter notebook in the cloud. While it is a convenient way to get set up, there are some caveats you would like to know before it.
The setup is platform agnostic i.e. all you need is a browser. The recommended way to get started is first logging in to Google. Sign in > Head to the home page for Google Colab [here](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) > click on New Notebook.
From this point, everything is basically the same as a Jupyter notebook.

#### Momentum-Effect in Stock Trading

* There's something which goes by the name of Momentum Anamoly in Trading, which says that what was strongly going up in the near past will probably continue to go up shortly. Stocks which outperform peers on 3-12 month period tend to perform well also in the future.
* You may read more about Momentum from [here](https://quantpedia.com/strategies/momentum-factor-effect-in-stocks/).

You can make use of instructions which we've provided for you in this [easier version](https://github.com/Karrthik-Arya/Get_Pythonissed/blob/main/Momentum.ipynb) of the assignment or implement everything from scratch in this [notebook](https://github.com/Karrthik-Arya/Get_Pythonissed/blob/main/MomentumH.ipynb) containing only the bare minimum instructions required to implement a strategy which exploits the Momentum Effect in Stock Trading.

#### Paired Switching

* You should get familiar with [Correlation](https://www.investopedia.com/ask/answers/032515/what-does-it-mean-if-correlation-coefficient-positive-negative-or-zero.asp) and its significance in Trading.
* Next, Read up about [Paired Switching](https://quantpedia.com/strategies/paired-switching/).
* The basic idea behind Paired Switching is to select two stocks which are negatively co-related, so that if one falls then the other should be rising shortly afterwards and vice versa.

You can start implementing this strategy by taking help of instructions given in [this](https://github.com/Karrthik-Arya/Get_Pythonissed/blob/main/Pairs.ipynb) of the assignment, or implement everything from Scratch in this [notebook](https://github.com/Karrthik-Arya/Get_Pythonissed/blob/main/PairsH.ipynb) containing only the bare minimum instructions required to implement the strategy.

### Moving Ahead

#### Predicitng Outlooks using a Naive Bayes' Model

* Get to know about the Naive Bayes' Model from this [article](https://towardsdatascience.com/all-about-naive-bayes-8e13cef044cf) on Naive Bayes' Models and the part on Bernoulli's Naive Bayes' Classifier from this Wikipedia [article](https://en.wikipedia.org/wiki/Naive_Bayes_classifier).
* Get to know about various indicators used to judge where the market/prices are going. [RSI](https://blog.quantinsti.com/rsi-indicator/) (Relative Strength Index) and [Stoch](https://blog.quantinsti.com/stochastic-oscillator/) (Stochastic Oscillator) are great indicators, you may or may not stop just at them.
* Next you can use RSI, Stoch (and other Indicators of your choice) and implement a Bernoulli Naive Bayes' Classifier to predict next day's returns and then use that to trade.

You should also use Matplotlib/Seaborn to plot these results.

Pre-defined functions from the sklearn library may help you with this task!
