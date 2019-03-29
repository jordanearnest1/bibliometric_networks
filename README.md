# Bibliographic Networks: A Python Tutorial
**By Hannah VanWingen and Jordan Earnest**

Networks can provide significant measures to identify data driven patterns and dependencies. Though, given a data file it can be difficult to discern how one may approach creating such a network. In this tutorial, we will use a bibliographic data file downloaded from a query search in [Scopus](https://https://www.scopus.com/search/form.uri) to walk through the process of cleaning the data file, writing a python script to parse the data into nodes and edges, computing graphical measures using [NetworkX](https://https://networkx.github.io/documentation/stable/index.html), and creating an interactive network display using [HoloViews](https://http://holoviews.org). 

We tried out multiple Python libraries for ease of use and efficiency before landing on this combination. Building a network was more intuitive in NetworkX than [iGraph](https://igraph.org/redirect.html). However, it took several minutes to render our large graph and a interaction was sticky. [Pyvis](https://pyvis.readthedocs.io/en/latest/#) was easy to build a network with and can be expanded to incorporate more advanced NetworkX functionality with only a couply lines of code. However it still took a long time to render, with slow manipulation. Holoviews, which runs on top of the native Python visualization library Bokeh, enables NetworkX to render quickly, with versitile manipulation. The graphs are produced in HTML and JavaScript for easy integration into webpages.

### About Colaboratory
While we originally developed this script in a local notebook, we found that running it through Google's cloud-based Jupyter notebook environment [Colaboratory](https://colab.research.google.com) is a smooth option, particularly for nacent coders. We encountered version conflicts between the dependencies when setting up a local notebook environment that were bipassed in Colab. Colaboratory allows you to use and share Jupyter notebooks from your browser, without having to download, install, or run anything on your own computer. Notebooks can be saved to Google Drive, Github or downloaded locally. A single line of code adapts the script render in Colab. 

Click on the icon ___ to open our notebook directly in Colaboratory. 

Cloning a Github Repo to Colab


You can run this notebook in Colaboratory by clicking this icon at the top of the notebook, downlading the notebook and importing it to Colaboratory manually, or downloading the notebook to run locally

- how do you make a copy of the notebook in colab into your own repo
- link to put things on a webpage. 
- how to download your graph
- and you have to tell it not to "reset run times" after each time. 
