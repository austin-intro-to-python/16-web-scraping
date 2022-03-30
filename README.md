# 16 Web Scraping

* Often times data is not available in the neat & tidy formats we are used from databases and APIs. We need to out into the world and capture the data.

* Enter web scraping which is the process of crawling a website(s) and extracting structured information from the pages of the site(s).

### User Agents
if you try to scrape a website too many times, the web server thinks that your IP address is a bot and it will ban you. The workaround to this problem is to install a user-agent to your code. This is a little bit advanced, but I wanted to put it out there in case others run into a similar problem. Here's some code you can imitate: https://github.com/allenchua1/reddit_scraper/blob/7fc38a0fecb6a15b14f2080cb62ef60ba875e425/helpers.py#L8

here are some additional articles to read about the problem/solution:
* https://hhsm95.dev/blog/the-importance-of-using-user-agent-to-scraping-data/
* https://infatica.io/blog/user-agents-in-web-scraping-what-are-they-and-how-to-use-them/
* https://brightdata.com/blog/how-tos/user-agents-for-web-scraping-101

### Notes

* There are a whole host of ethical concerns with web scraping. Make sure to read a site's robots.txt before initating a web scraping project.

* View this repo deployed as a static webpage: https://pages.git.generalassemb.ly/python-programming-11-08-2021/16-web-scraping/
