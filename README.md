<h1> Web Scraping and DataFrame Construction with BeautifulSoup & Pandas </h1>

<h2>Project Description</h2>
This project focused on scraping structured data from a live Wikipedia page and converting it into a clean, analysis-ready dataset using Python. The workflow began with sending an HTTP request to the target URL and parsing the HTML using BeautifulSoup. After inspecting the page structure, the correct table was selected from multiple HTML tables by filtering its class attributes and indexing the results. The column headers (TH tags) were extracted, cleaned, and used to initialize a Pandas DataFrame. The script then iterated through each table row (TR tags), captured each cell’s value (TD tags), cleaned the text, and appended the data row-by-row into the DataFrame. Once the full dataset was assembled (including company rank, name, industry, revenue, revenue growth, number of employees, and headquarters) the data was exported to a CSV file with the index removed to ensure a tidy output. This project demonstrates skills in HTML inspection, web scraping, iterative parsing, data cleaning, and DataFrame construction using Python, BeautifulSoup, and Pandas.

<h2> Python script </h2>

- <b>[Scraping Data from a Website (+Pandas) Project](https://github.com/Ivan-dlpm/Web-Scraping-and-DataFrame-Construction-with-BeautifulSoup-Pandas/blob/main/Scraping_Data_from_Website_Pandas_Project.ipynb)</b>

<h2> Original Website </h2>

- <b>[List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)</b>

<h2> Demonstration </h2>

<p align="left">
Jupyter  <br/>
<img src="https://imgur.com/8e29jpV.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="left">
Wesite  <br/> 
<img src="https://imgur.com/teKf3J9.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
