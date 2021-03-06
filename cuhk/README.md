# Data projects

This notebook is used for introducing some of my representative works(non-confidential) related to data scraping, data analyzing, data visualization.

## 1. Web Scraping

There are basically 3 kinds of web-scraping methods for extracting data from websites. The following will give you basic information about each method and how to apply those methods to different cases.

* Static web scraping
* Browser emulation
* Social media scraping

### 1.1. Static web scraping

Most traditional websites can be scraped by this method. They don't use technology like dynamic loading, and the limitation about scraping this kind of website is usually small.

Example: jobsdb, [initium mews](https://github.com/hupili/python-for-data-and-media-communication-gitbook/blob/master/notes-week-07.md#bonus-scrape-all-articles-features-of-all-pages), [carpark hk](https://github.com/XIAO-Chao/hkbu-big-data-media/tree/master/homework2)

How to scrape: Requests, Beautifulsoup/Regular expression

### 1.2. Browser emulation

Websites with dynamic loading can be scraped by this method. They usually have speed limitation and Anti craping barriers, which need some human actions to activate certain content loading.

Example: [Openrice](https://mp.weixin.qq.com/s/aFfa7WlyT0vwXBlDYvacCg), [CNN](https://github.com/hupili/python-for-data-and-media-communication-gitbook/blob/master/notes-week-08.md#advanced-version-all-pages), [JD](https://nbviewer.jupyter.org/github/iiiJenny/python-data-assignments/blob/master/assignment1/JD_scraper_final.ipynb),HK GOLDEN

How to scrape: Selenium browser emulation, User agent, Handling Anti-scraping

### 1.3. Social media scraping

Social media website usually can be scraped by the method 1 and 2, but need some further steps like Website login model to support. The limitation about scraping social media is higher than above two.

Example: [Weibo keywords searching - "核电站"](https://github.com/ChicoXYC/exercise/blob/master/weibo_scraper/%E6%A0%B8%E7%94%B5%E7%AB%990311-0312.csv), [Twitter keywords searching - "山竹台风"](https://nbviewer.jupyter.org/github/ChicoXYC/exercise/blob/master/twitter-selenium/twitter-try2.ipynb)

There are also other methods like *Network Traces*, if needed.

## 2. Data analysis and visualization

The following are analysis reports or notebooks about how to perform analysis related to different kind of data. You can click to view the full stories.

1. Text data: [A text analysis for comments of video channels - TF-IDF,Topic modeling,NLP](https://nbviewer.jupyter.org/github/ChicoXYC/exercise/blob/master/text-mining-test/text-mining-final.ipynb)
2. Geographical data: [Flying in the sky, a report of air crash worldwide](https://dnnsociety.org/2018/04/30/flying-in-the-sky-a-report-of-air-crash-worldwide/)
3. Network data: [Les Misérables class demo](https://github.com/hupili/python-for-data-and-media-communication-gitbook/blob/master/notes-week-14.md#common-network-analysis-routine-via-les-mis%C3%A9rables-dataset)
4. Numerical data: [Correlations between absent rate with grade performance](https://github.com/hupili/python-for-data-and-media-communication-gitbook/blob/master/notes-week-10.md#correlation)
5. Data-driven story: [Elder Suicide in HK, honorable mention in data journalism competition, HKBU](https://chicoxyc.github.io/Elder-Suicide-in-Hong-Kong/)
