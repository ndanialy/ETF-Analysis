# ETF-Analysis

An application that pulls and analyzes etf data from a database.

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [hvplot](https://hvplot.holoviz.org/) for more interactive data visualization.

* [sqlalchemy](https://docs.sqlalchemy.org/en/14/) for integrating sql with python.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install hvplot

pip install SQLAlchemy

pip install voila

```
---

## Usage

The App pulls data from the database and visualizes the daily returns:

![DailyReturns](https://user-images.githubusercontent.com/96391748/153796408-0ec3a62b-b70e-4fd9-a0fa-9756945748be.PNG)

The cumulative return is calculated and also graphed:

![CumulativeReturn](https://user-images.githubusercontent.com/96391748/153796491-ac4921e5-fc39-47e5-a935-1231eb2b3b1c.PNG)

The data is limited to positive cumulative return above a set threshhold, and the top 10 results are displayed:

![TopDays](https://user-images.githubusercontent.com/96391748/153796673-242fb38f-797f-4b36-8a5b-54747bb4cae4.PNG)

Finally, the cumulative portfolio return is calculated and visualized:

![PortfolioReturn](https://user-images.githubusercontent.com/96391748/153796736-e5d458b7-844b-47df-9604-96c2d640ee14.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
