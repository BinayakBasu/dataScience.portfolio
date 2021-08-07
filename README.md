# dataScience.portfolio
<h1>Basics of Web Scraping</h1>
    <h2> What is Web Scraping?</h2>
    <hr size="3" noshade>
    <p><strong>Web Scraping:</strong>It means Automated Web Data Extraction. There are 
    two parts: <strong>A. Crawling:</strong>A web crawler or spider searches for content
    by following links and exploring & <strong>B. Scrapers:</strong> A Scrape 
    program does data extraction from web pages. </p>
    <p> However while Web Scraping the Ethics of Scraping must be maintained.</p>
    <h2>What is an API?</h2>
    <hr size="3" noshade>
    <p><strong>API stands for Application Programming Interface. </strong></p>
    <li> It is a software intermediary that allows two applications to talk to each 
        other. Each time you use an app like Facebook, send an instant message, 
        or check the weather on your phone, you're using an API.</li>
    <li>APIs are thus required to incorporate a third party functionality.</li>
    <li>API can be free or paid.</li>
    <li>Every API must have some form of documentation.</li>
    <li>API can be considered as a form of contract between the client and the server.
        Thus if a client makes an request in a specific format the server will 
        initiate a defined action. The common step is to make a http request to the 
        server. 
    </li>
    <h2> What are http requests?</h2>
    <hr size="3" noshade>
    <p><strong>http stands for hypertext transfer protocol</strong></p>
    <li>It specifies how requests and responses are to be formmatted ans transmitted.</li>
    <li>
        Websites contain a collection of files : the html code for web pages along 
        with other supplementary resources like images, videos , styles. These 
        files are stored in remote computers somewhere called Server. While surfing
        all we do is download these files on our computer and use our browser to 
        display the results properly. This is carried out by making a http request.
    </li>
    <li>
        The requests can be classified into 2 categories: <strong>A. GET & 
        B. POST</strong>
    </li>
    <h2>Working with certain APIs</h2>
    <hr size="3" noshade>
    <h3>GET Requests : </h3>
    <ul>
        <li>
            <strong>Exchange Rate API (a Public API): </strong><a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/Exchange%20Rate%20API.ipynb" target="_blank">Pulling data from Exchange Rate API</a>
        </li>
        <li>
            <strong>iTunes API(Public API) : </strong><a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/iTunes%20Api.ipynb" target="_blank">Pulling data from iTunes API</a>
        </li>
    </ul>
    <h3>POST Requests</h3>
    <ul>
        <li>
            <strong>Edamam API : </strong><a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/POST%20request.ipynb" target="_blank">Pulling data from Edamam API</a>
        </li>
    </ul>
    <h2> Scraping Rotten Tomatoes</h2>
    <hr size="3" noshade>
    <p>I have scraped the Rotten Tomatoes website using Beautiful Soup in Python. I have scraped
        to find out the top 100 action and adventure movies and then used multiple pages Scraping
        to obtain more information about each movie. The link to the code is given below:
    </p>
    <a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/Scraping%20rotten%20tomatoes.ipynb" target="_blank">Click here</a>
    
<h1>Exploratory Data Analysis</h1>
    <div>
        <b>Definition :</b><a href="https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15">
        Exploratory Data Analysis(EDA)</a> refers to the critical process of 
        performing initial investigations on data so as to discover patterns,to spot anomalies,
        to test hypothesis and to check assumptions with the help of summary statistics and 
        graphical representations.
    </div>
    <hr size="4" noshade>
    <div>
        <strong>Project 1 :</strong>I have taken the data of world happiness report from kaggle and 
        used it to draw conclusions and insights about the index.<br>
        <a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/world%20happiness%20report%20EDA.ipynb">Click here</a>
        <br><br>
        <strong>Project 2 : </strong>Using the Emergency Calls data from kaggle I have tried to 
        find out the factors mostly causing an emergency.<br>
        <a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/Emergency-911%20calls.ipynb">Click here</a><br><br>
        <strong>Project 3 :</strong> Using the Titanic set I did an EDA and made it fit for prediction
        throught Machine Learning models.<br>
        <a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/Titanic_EDA.ipynb">Click here</a>
    </div>


 <h1>Interactive Visualization : Plotly and Cufflinks</h1>
    <hr size="4" noshade>
    <h2>What is Interactive Visualization?</h2>
    <div>
        <b>Interactive visualization</b> technology enables the exploration of data via the 
        manipulation of chart images. Thus one can interact with the chart and manipulate it 
        according to one's own needs. Thus it is more favourable to analyze a data from various
        fronts.
        <br>
        I have used <b>Plotly and Cufflinks</b> to show some Interactive visualizations in 
        the datset.
    </div>
    <h2>Data</h2>
    <div>
        <a href="https://www.kaggle.com/shekpaul/global-superstore" target="_blank">Click here</a>to download 
        the dataset
    </div>
    <h2>Interactive Visualization</h2>
    <div>
        <h3>Installing libraries</h3>
        <li>
            <b>pip install chart_studio</b>
        </li>
        <li>
            <b>pip install cufflinks</b>
        </li>
        <br>
        <b>
            <a href="https://nbviewer.jupyter.org/github/BinayakBasu/dataScience.portfolio/blob/da0489b500bc816be6e37cec300534d11919436b/Interactive_%20Visualization.ipynb" target="_blank">
                Click here</a> to download and view the interactive data visualization.
        </b>
    </div>
    <hr size="10" noshade>
    
    
<h1>Data Analytics with Python</h1>
    <hr color="#fe8e28" size="4" noshade>
    <h2>Measures of Central Tendency and Dispersion</h2>
    <hr color="#fe8e28" size="2" noshade>
    <div>
        <h3>Measures of Central Tendency</h3>
        <p>A measure of central tendency describes a set of data by identifying the central 
            position in the data set as a single value.</p>
        <li>
            <b>Mean</b> :The arithmetic mean of a given data is the sum of all observations divided 
            by the number of observations.
        </li>
        <li>
            <b>Median</b> : The value of the middlemost observation, obtained after arranging the data 
            in ascending order, is called the median of the data.
        </li>
        <li>
            <b>Mode</b> : The value which appears most often in the given data i.e. the observation 
            with the highest frequency is called a mode of data.
        </li>
        <li>
            <b>Percentile : </b>This forms the basis for Box plot. If say, 25th percentile 
            is given as 50 , then it means that 25% of the data have values less than or 
            equal to 50. When percentile is 50 , it is referred to as the Median. 25 percentile 
            and 75 percentile are referred to as 1st Quartile and 3rd Quartile respectively.
        </li>
        <li>
            <b>Relation Between Mean, Median and Mode </b>: The three measures of central values 
            i.e. mean, median, and mode are closely connected by the following relations 
            (called an empirical relationship). 
            <br>
            <b>2Mean + Mode =3Median</b>
        </li>
        <h3>Measures of Dispersion</h3>
        <li>
            <b>Range :</b>It is the differenec between the maximum and the minimum value of the 
            variable 
        </li>
        <li>
            <b>Inter-Quartile Range (Q<sub>3</sub>-Q<sub>1</sub>):</b>It is the difference 
            between the 3rd Quartile and the 1st Quartile. <b> Note: </b>Any value of a 
            variable lying above 1.5*Q<sub>3</sub> or below 1.5*Q<sub>1</sub> are considered 
            to be outliers. It is one of the ways to get rid of the outliers in the dataset.
        </li>
        <li>
            <b>Variance : </b>Average of squared deviations from the Arithmetic Mean.
        </li>
        <li>
            <b>Standard Deviation :</b>Square root of the variance.
        </li>
        <h3>Working with Data</h3>
        <a href="https://github.com/BinayakBasu/dataScience.portfolio/blob/main/analysis%20of%20central%20tendency%20and%20dispersion.ipynb" target="_blank">Analysis of Central Tendency and Variance</a>
    </div>
