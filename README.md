# StockRabbit
Analyze past company events to understand the future

<p align="center">
	<img src="https://media.giphy.com/media/26gR0Tr3sGn8COFMI/giphy.gif">
</p>

## Current Progress
- [x] Splash Page layout
- [ ] Splash Page Typeahead functionality
- [x] Choose stock data API/source
- [ ] Choose news data API/source
- [x] Choose backend platform (Google Cloud)
- [ ] Create daily scheduled API calls/data parsing/updating (cron)
- [x] Front-end layout/functionality (javascript, html, css)
- [ ] Create logic/functions for the app frontend

## Inspiration
Whenever attempting to analyze and gain insights from major news events that affect stock performance, it can be difficult to understand what effect that event had on a certain company. Often, websites such as Google Finance will simply provide a list of news articles for the user to filter through, but no mechanism for comprehending the effects of these events.

## What it does
StockRabbit allows a user to search for a company, and view relevant news articles pertaining to the performance of the company. Clicking on a news article will zoom into the respective location on the stock chart, as well as provide stock price change data during the run-up and response to the event. Based on the change in price, StockRabbit will assign an impact rating to the event, allowing users to easily gain insights about the extent to which the company event/report made an impact. 

## How I am building it
### Tools: 
Flask 0.12.2

Google Cloud Platform (App Engine, Cloud SQL/Spanner OR BigQuery, Logging, Monitoring)

JS: Amcharts, Tether, Handlebars, Chart.js, Fuse.js OR Twitter Typeahead

CSS: Materialize, Bootstrap, Font Awesome

API: Barchart, Intrinio, Quandl

The web framework used for StockRabbit is Flask, along with Google App Engine to handle data storage, querying and static file serving, as well as various javascript libraries (listed above), HTML, and CSS for the frontend. 
