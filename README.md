<h1>Jupyter notebook</h1>

This repo contains two notebooks for the moment.<br><br>

<h2>Tiger notebook</h2>
This notebook is an analysis of Tiger database. This analysis' goal is to find out if processing titles would give us good results or if we need to process whole documents. If processing whole documents, we would need much more powerfull devices - because of the really high number of features contained in a single document. <br>Each word should be considered as a vector, in order to make the classification computable by neural nets. Processing only titles would allow us to have less powerfull server and this also would be a time save.<br><br>
However, in order to use neural nets, we would need to run classic machine learning algorithms on our collection : if we want to train neural nets, we need a starting point, with at least a part of our database classified.<br>
<br>
Before starting to classify our database, we should check if training a neural net on text would give good results.<br>

<h2>News aggregator</h2>
This second notebook is an analysis of <a href="https://archive.ics.uci.edu/ml/datasets/News+Aggregator">this dataset</a>. We chose to make an analysis of this dataset for several reasons.<br> First of all, it's open source, then we could easily find it on the internet. Second, this dataset contains 4 categories, which a good point to start practicing neural nets. If we got more categories, then the classification would be less efficient, and the results spread over the categories. The categories are also quite different from each other, which should ease the problem.<br><br>
This dataset is also extremely complete and accurate : there are over 400 000 articles' titles, 80 000 different words and the articles are dealing with a very large number of themes/brands/problems. Finally, the dataset perfectly matches our search criteria : we needed a dataset on which we would make our first steps and train our first convnet(s) for NLP. Plus, it is made of titles, which is exactly the thing we were looking for.<br><br>
Actually, the analysis would show encouraging results, as you can see on the notebook. We analyzed many parameters. First, we needed to check if the word representation is the same as in the Tiger database. After that, we had to analyze if certain words were standing for a particular category, i.e. if there is a correlation between words on a title and the category the article belongs to, or if the words used are too "widespread" to make a solid basis for classification.<br><br>
Finally, looking through this dataset also gived us the opportunity to test some python tools for data analysis : graph plotting, wordclouds, mongodb indexing on text are really powerfull tools to use for data science.<br><br>
This also made me learn some kind of "logic" for Data Analysis<br><br><br>


<div style="text-align:center">
<img src="http://graphics.desivalley.com/wp-content/uploads/2011/09/Angry-tiger-1024x640.jpg" width=50% height=50%/>
</div>
