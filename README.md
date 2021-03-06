# Web Scraper - Amazon product price monitoring


## Description

This program uses Python's Beautiful Soup library to pull data out of any website, according to the targeted HTML component.
Based on a product item from the Amazon website, the price is pulled and periodically compared to a desired price.
When the item cost is in the desired range, an email is automatically send to  the user.
To be more efficient, this code can be hosted in the cloud with platforms like pythonanywhere and it can be scheduled as a task to automatically run daily.


## Getting Started

1. Clone the repository by entering the following command in your IDE terminal:
	git clone https://github.com/andreibarstan/WebScraper_AmazonProductPriceAlert.git

2. Install required libraries:
	pip3 install requests bs4 lxml --user 

3. Open main.py file and populate "my_email" and "password" variables. 

3. Run the program:
	python main.py


## Acknowledgments

* Udemy - Python bootcamp
* requests / beautiful soup library documentation
* smtplib library documentation
