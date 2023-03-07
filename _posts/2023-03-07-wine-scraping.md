---
layout: post
title: Wine Data: From Mining to Visualization
subtitle: Selenium scraper and streamlit data visualization app
gh-repo: velajua/wine_scraping
gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/wine_france.jpg
cover-img: /assets/img/python-banner_.jpg
tags: [concurrency, python, selenium, streamlit, visualization, functions, PIL, scraping]
comments: true
---

This project aims to scrape wine data from the [Decanter website](https://www.decanter.com/wine-reviews/search/france/page/1/3)
('France' per default) and visualize it using Streamlit. The scraping is done using Selenium, and the data is stored in a CSV file,
which can then be used for data analysis and visualization (using streamlit in this case). 

This [`repository`](https://github.com/velajua/wine_scraping) contains the necessary files to daploy a containerized app using Docker which is able to create
a Streamlit server, usign the data scraped.


