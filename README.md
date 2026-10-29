# Etalon course notebooks

The free notebooks for Etalon's beginner course on trading bots: the data, the idea, testing it, the risk, and running it. Each one opens in Google Colab, so all you need is a browser and a free Google account. Nothing to install.

Nothing here connects to a broker or uses real money. Nothing here is a trading signal or financial advice.

## The notebooks

| Module | Notebook | Open |
|---|---|---|
| 2. Just enough Python | Python from zero, then real SPY prices, daily returns and a moving average | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/snapwyrm/etalon-course/blob/main/notebooks/02-just-enough-python.ipynb) |

Modules 0 and 1 are reading only. The rest of the course adds one notebook per module.

## How to use one

1. Click **Open in Colab**.
2. Run the cells in order with **Shift + Enter**.
3. To keep your changes, use **File > Save a copy in Drive**. Colab does not save anything back here.

## Where the prices come from

The notebooks load prices with [yfinance](https://github.com/ranaroussi/yfinance), which reads Yahoo Finance. It is free and unofficial, and Yahoo's data is for personal use. If Yahoo turns Colab away, each notebook has a Plan B: a file you download by hand and upload.

## Something broken?

Open an issue with the notebook's name, the cell that failed, and the error it printed.
