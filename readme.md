# ICO Drops Data Scraper
Scraping [ico drops upcoming icos](https://icodrops.com/category/upcoming-ico/)

Currently, it can scrape ico name, description, category, icodrops rating,
hardcap, ico date, telegram link, telegram followers, twitter link, twitter followers, and medium link

## Setup
Install the required packages through
`pip install -r requirements.txt`

If you're not using Windows, You'll also have to [download chromedriver](https://chromedriver.storage.googleapis.com/index.html?path=2.38/) and modify the executable_path in this line to your respective install
`driver = webdriver.Chrome(executable_path='chromedriver.exe', chrome_options=chrome_options)`
