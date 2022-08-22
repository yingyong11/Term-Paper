# Project Description 
<hr/>

### 1. Project Name
    - 
<br>

### 2. Problem Statement
    -
<br>

### 3. Project Scope
    -
<br>

### 4. Deliverables and Benefits
    -
<br>

### 5. Project Team : Hyuncheol Ryu(PM)
    -
<br>

### 6. Schedule 
![Schedule](./img/Schedule.PNG)
<br><br>

# Getting Started
***
In order to run the code in [src](link) and [DB](link), you'll need the following software and python packages.


### Prerequisites
* //설명 [Visual Studio](https://www.guru99.com/download-install-visual-studio.html)
* //설명 [PlantUML](https://se-education.org/addressbook-level4/UsingPlantUml.html)
* //설명 [Jupyter](https://jupyter.readthedocs.io/en/latest/install.html)
* //설명 [SQLite](https://www.tutorialspoint.com/sqlite/sqlite_installation.htm)
* //설명 [Chrome Driver](https://chromedriver.chromium.org/downloads) Download the same version of Google Chrome you are using

### Installing the python package
* Pandas
    * //설명
<pre><code>pip install pandas</code></pre>
<br>

* BeautifulSoup
    * //설명
<pre><code>pip install BeautifulSoup4</code></pre>
<br>

* Html_table_parser
    * //설명
<pre><code>pip install Html_table_parser</code></pre>
<br>

* Selenium
    * //설명
<pre><code>pip install Selenium</code></pre>
<br>

* Sqlite3
    * //설명
<pre><code>pip install Sqlite3</code></pre>


### Files
1. src/ 
    1. [scrapping&processing_data](./src/scrapping&processing_data.ipynb) : Code that scrapes freight indexes for each website, transforms indexes into a common form, and saves it as a csv files
    2. [storing_data]() : Code to Import csv files generated by (1-A) into SQLite database
    3. [querying_data ]() : Code to query from the database
    
    
2. Data/ 
    * [table_freights]() : A csv file containing information about the entire freight indexes, generated by (1-A)
    * [table_oceanfreight]() : A csv file containing information about ocean freight indexes, generated by (1-A)
    * [table_airfreights]() : A csv file containing information about air freight indexes, generated by (1-A)
    
    
3. DB/ 
    * [ERD_Freight.swift]() : Structural diagram that graphically depicts entity relationships about freight information
    * [Freight.db]() : Database file for freight information generated by (2-A)
    
4. [Research Paper]()
<br><br>

### Usage
1. Scrap data and save as csv files via (1-A) code
2. After creating the database file, import the CSV files into SQLite via (2-A) code
3. Run a query(select, update, delete), if necessary via (3-A) 
<br><br>

# References
***
The follwing are the sites I referred for scraping the freight indexes
* BAI (https://dashboard.tacindex.com/dashboard)
* BDI (https://kr.investing.com/indices/baltic-dry-historical-data)
* CCFI (https://www.kcla.kr/web/inc/html/4-1_2.asp)
* SCFI (https://www.tradlinx.com/freight-index)
* HRCI (https://www.ksg.co.kr/shippingGraph/hrci_graph.jsp)
