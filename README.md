# Capstone Project Data Analytics: R Analysis of the 2022 Fortune 1000 for Market Cap Prediction
---
---

## Data Dictionary

**Table of Data Dictionary**

| Field           | Description |
|-----------------|-------------|
| company         | Name of the company |
| rank            | The 2021 rank established by Fortune (1-1000) |
| rank_change     | The change in the rank from 2020 to 2021. There is only a rank change listed if the company is currently in the top 500 and was previously in the top 500. |
| revenue         | Revenue of each company in millions. This is the criteria used to rank each company. |
| profit          | Profit of each company in millions. |
| num_of_employees| The number of employees each company employs. |
| sector          | The sector of the market the company operates in. |
| city            | The city where the company's headquarters is located. |
| state           | The state where the company's headquarters is located |
| newcomer        | Indicates whether or not the company is new to the top Fortune 500 ("yes" or "no"). No value will be listed for companies outside of the top 500. |
| ceo_founder     | Indicates whether the CEO of the company is also the founder ("yes" or "no"). |
| ceo_woman       | Indicates whether the CEO of the company is a woman ("yes" or "no"). |
| profitable      | Indicates whether the company is profitable or not ("yes" or "no"). |
| prev_rank       | The 2020 rank of the company, as established by Fortune. There will only be previous rank data for the top 500 companies. |
| ceo             | The name of the CEO of the company |
| website         | The url of the company website |
| ticker          | The stock ticker symbol of public companies. Some rows will have empty values because the company is a private corporation. |
| market_cap      | The market cap (or value) of the company in millions. Some rows will have empty values because the company is private. Market valuations were determined on January 20, 2021. |