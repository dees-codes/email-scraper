# email-scraper

Scrapes emails from a given website including those from links within the website.

It asks for a url, extracts email from the html page in the url and also extracts the emails from the child urls in the page. This process is done until 100 url's are accessed. Regex is used to find emails in the html code of the page. At the end, all the emails found are printed.
