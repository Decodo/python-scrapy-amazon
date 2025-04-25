<p align="center">
<a href="https://dashboard.decodo.com/?page=residential-proxies&utm_source=socialorganic&utm_medium=social&utm_campaign=resi_trial_GITHUB"><img src="https://github.com/user-attachments/assets/60bb48bd-8dcc-48b2-82c9-a218e1e4449c"></a>
</p>


[![](https://dcbadge.vercel.app/api/server/Ja8dqKgvbZ)](https://discord.gg/Ja8dqKgvbZ)


# Python Scrapy Amazon Scraper
Scrape Amazon product listings utilising Scrapy &amp; residential proxies

# Prerequisites
To get started with Scrapy, you will first need to install it using the methods provided in its documentation. [Check here for more information](https://docs.scrapy.org/en/latest/intro/install.html)

# Authentication & Proxy setup

Once you have an active subscription, you can find your credentials & proxy addresses in **Dashboard > Residential > Proxy Setup**

Navigate to settings.py in `/amazon/amazon/` folder and modify the following lines to authenticate.

```
DECODO_USER = 'username' ## Decodo Username (Sub-user)
DECODO_PASSWORD = 'password' ## Password for your user
DECODO_ENDPOINT = 'gate.decodo.com' ## Endpoint you'd like to use
DECODO_PORT = '7000' ## Port of the endpoint you are using.
```

# Running the scraper

Navigate to the project folder and run the following command:

```
scrapy crawl amazon_search
```

# Results

Amazon search results will be saved in `/amazon/data` folder in a .csv format
