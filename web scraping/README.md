
# Scraping Flipkart website 

Please click [here](https://github.com/rakesh-upx/web_scraping/tree/master/web%20scraping/Notebook) to view the notebooks containing Web Scraping method & scraped data

## Objective 
The analysis aims at how to scrape data from Flipkart's website & using the scraped data for Cluster Analysis to find how samples can be assigned to various groups & obtain meaningful insights.




<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/iphone-8-flipkart-offer-1.png",alt="neofetch" align="middle" height="300px">
  </p>




## Data Description

* The website contains data on various models of iphone & Samsung mobiles.
* Model of phone,Rating & Price were scraped from each page

## Tools used
The entire experiment was conducted in Python.`BeautifulSoup,urllib` libraries were used to scrape each page of the website.The scraped data was tabulated using `csv & Pandas` libraries.


## Code Snippets

### Import required libraries






<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/libs_import.PNG",alt="neofetch" align="middle" height="80px">
  </p>


### Open the url of the website


<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/urllib.PNG",alt="neofetch" align="middle" height="80px">
  </p>


### Prepare the soup 
The soup was prepared using BeautifulSoup & passing html parser



<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/soup.PNG",alt="neofetch" align="middle" height="80px">
  </p>




### Have look at a html markup

The html contains tag,class body & `find_all` function returns all other html markup 

<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/html_tag.PNG",alt="neofetch" align="middle" height="80px">
  </p>



### Prettify 

It helps to find all the html markup in a sequential way so that it get easy for us to find the markup.



<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/prettify.PNG",alt="neofetch" align="middle" height="200px">
  </p>



### Lets scrape 

The below `for loop` helps us to scrape all the data from the pages


<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/scrape_now.PNG",alt="neofetch" align="middle" height="200px">
  </p>





### Result

#### iphone

<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/apple_1st.PNG",alt="neofetch" align="middle" height="200px">
  </p>





#### Samsung

<p align="center">
  <img src="https://github.com/rakesh-upx/web_scraping/blob/master/web%20scraping/Images/samsung.PNG",alt="neofetch" align="middle" height="200px">
  </p>










