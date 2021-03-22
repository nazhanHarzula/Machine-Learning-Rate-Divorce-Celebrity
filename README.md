# Machine-Learning-Process (Analysis and Predictions of Celebrity Divorce)
This project includes scraping and machine learning processes regarding actresses or actors who are getting divorced

<h6>Inside Script "Scraping Data Artist.ipynb"</h6>
<ul>
    <li>First, what we need to prepare includes a package such as pandas, selenium, bs4 as the core of the data scraping process this time. If it doesn't exist, it needs to be installed (pip install "name_package")</li>
    <li>Second, because here I use the chrome web browser, I need to download a chromedriver (http://chromedriver.chromium.org/downloads) according to the version installed on the computer (how to check: open chrome - select menu - help - press about google chrome )</li>
    <li>Third, because we need to find data on actors or actresses, we need to find a list of their names. (https://www.imdb.com/search/name/?gender=male,female&ref_=rlm)</li>
    <li>Fourth, after getting the list of names. We need to find their biographical data, using wikipedia we can search for the appropriate name keywords. (https://en.wikipedia.org/wiki/name)</li>
    <li>Fifth, it needs to be converted into a file with a .csv or .xlsx extension</li>
</ul>

<h6>Inside Script "Process Data Artist.ipynb"</h6>
<ul>
    <li>This section will analyze various patterns in scraped data on IMDb and Wikipedia</li>
    <li>EDA (Exploratory Data Analysis) and data visualization are carried out to find out the inside of the data and to analyze it carefully</li>
    <li>The advanced stage is features engineering, the process of knowing and dealing with blank / NaN data, duplicating data, extracting new (or known) data, data outliers to data labeling for classification models.</li>
    <li>This stage will carry out the process of data balancing (imbalanced data handling), normalization, encoding to predictive modeling of the training data.</li>
    <li>Finally, assess with confusion matrix and ROC visualization to find out how good the model is from the prediction results</li>
</ul>

* Note : Attached is a dataset (`Folder: External Output`) of 831 lines, if you want to immediately do the modeling and prediction process
