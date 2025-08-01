# DEVELOP A STOCK TICKER

## DESCRIPTION

The goal of this challenge is to develop a stock ticker. You will be provided with `simulated_sp500_intraday.csv`, a file containing sample S&P500 data for a single day.  The challenge has basic requirements and stretch goals.

## INSTRUCTIONS

1. Choose front-end and back-end programming language(s) and framework(s) of your choice.
2. Develop the stock ticket. You can use the following steps as a guide:
    - Create a back-end REST API  which serves each line of the `.csv` file, sequentially, to the front-end.
    - Create a basic front-end which, for each minute, retrieves and displays ticker date for that tick.

## Basic Requirements

- The stock ticker should have the following required features:
    - A front-end and back-end
    - A front-end that retrieves per-minute data from the back-end
    - A front-end that displays the following per-minute data for each symbol:
      - Stock symbol
      - Current price
- You must use Copilot to speed up your development

## Stretch Goals

- Customize front end to mimic a real-life stock ticker
  - Make a stock ticker scrolls horizontally or has a grid interface (see below for examples)
  - Include delta
  - Include delta %
  - Include up/down arrow
  - Include Sparkline graph
  - Include intra-day high/low
- Add unit/integration tests
- Add documentation
- Have your codebase confirm to the following coding standard

## Example Ticker Formats

### Horizontal Scroll w/Sparklines

![horizontal-scroll](https://github.com/user-attachments/assets/cf29f994-2826-418c-bd24-cbbd177b43f1)

### Grid
![grid](https://github.com/user-attachments/assets/d01b173d-ee92-44e9-9ee1-57a2c528cd20)
