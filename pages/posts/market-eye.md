---
title: Market-Eye API
date: 2023/02/31
description: RESTful API for stock market analysis built with Python
tag: web development
author: You
---

# Market-Eye API

**Timelines**:

Jan 2022 – (ongoing baisis, as requested by client)

**Stack**:

FastAPI, MongoDB, Panadas, Scrapy, CI/CD, Github Actions

**Highlights**:

- Designed data pipelines using GitHub Actions to compute indicators for 10,000+ stocks by the end of every trading day
- Developed scraping bots to count stock ticker mentions across eight news websites each day
Implemented a notification system in case of data pipeline failure

**Description**:

Market-Eye API provides methods for computing technical indicators of individual stocks as well as indicators describing the market as a whole. The API includes methods for sorting the stocks and scraping results (for the given date) based on various implemented criteria.

**Links**:

- Code available on [github](https://github.com/andreyxdd/marketeye-api)
- Documented [endpoints](https://marketeye-api.herokuapp.com/docs)
