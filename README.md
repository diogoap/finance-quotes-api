# Finance-Quotes-Api

This is a simple scraper tool which provides a wrapper api to read stock quotes from investing.com.

It can returns data both in JSON and CSV formats.

Docker file is available for quick deployments.

To run it locally just type node `server.js`

Request example:

```
curl --location --request GET 'https://my-own-deploymenyt-server/api/stock/quotes/indices_us-spx-500;indices_eu-stoxx50;etfs_vanguard-s-p-500-uk!cid=962112'
```
