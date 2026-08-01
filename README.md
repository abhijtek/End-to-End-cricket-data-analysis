# T20 World Cup 2022 - Best Playing XI Analysis

An end-to-end cricket data analytics project that uses the ICC Men's T20 World Cup 2022 to identify a balanced **Best Playing XI**.

The project combines data preparation in Python and Pandas with an interactive Power BI dashboard to assess player performance across specialist roles.

## Project overview

The analysis evaluates players across five roles:

- Openers
- Middle-order / anchor batters
- Finishers
- All-rounders
- Specialist bowlers

Performance measures such as runs, strike rate, batting position, wickets, economy rate, dot balls, boundaries, and bowling extras are used to scope and compare players.

## Data source and scraping note

This repository includes the original web-scraping scripts in [`web_scrapping_codes/`](web_scrapping_codes/), which target ESPN Cricinfo's T20 World Cup statistics pages.

However, the analysis data in this project was **sourced from [Codebasics](https://codebasics.io/), not scraped live from ESPN Cricinfo**. ESPN Cricinfo's table links use a security layer that causes web-scraping requests to time out, so a reliable live scrape was not possible for this project.

## Tools used

- **Python** and **Pandas** for cleaning and transforming data
- **Jupyter Notebook** for the preprocessing workflow
- **Power BI** for data modelling, DAX measures, and dashboarding
- **JavaScript** scraping scripts retained for reference

## Repository structure

```text
|-- Cricket Best 11.pbix                        # Power BI dashboard
|-- DAX Measures and Calculated columns.xlsx    # DAX reference material
|-- Paramaeter Scoping.pdf                       # Player-selection criteria
|-- t20_data_preprocessing.ipynb                # Data cleaning and transformation
|-- t20_csv_files/                              # Cleaned CSV files used by Power BI
|-- t20_json_files/                             # Source JSON data
`-- web_scrapping_codes/                        # ESPN Cricinfo scraper scripts (reference)
```

## Cricket Best 11 dashboard

### Quick view

[View the live Cricket Best 11 dashboard](https://app.powerbi.com/reportEmbed?reportId=238a8d3e-9212-44fc-a3c5-d972c8470ac8&autoAuth=true&ctid=f4669cc9-6065-4d34-9017-684988b21f7a)

### HTML embed

Copy the following code into an HTML page, portfolio, or website to embed the report:

```html
<iframe title="Cricket Best 11" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=238a8d3e-9212-44fc-a3c5-d972c8470ac8&autoAuth=true&ctid=f4669cc9-6065-4d34-9017-684988b21f7a" frameborder="0" allowFullScreen="true"></iframe>
```

> GitHub does not display iframe content inside a README. Use the **Quick view** link above on GitHub; use the iframe code on HTML-enabled pages.

## Dashboard screenshots

The Power BI report contains role-based analysis pages and the final Best Playing XI selection.

![Dashboard overview](Board%20ScreenShots/Screenshot%202026-08-01%20184708.png)

![Dashboard analysis page](Board%20ScreenShots/Screenshot%202026-08-01%20184726.png)

![Dashboard analysis page](Board%20ScreenShots/Screenshot%202026-08-01%20184744.png)

![Dashboard analysis page](Board%20ScreenShots/Screenshot%202026-08-01%20184804.png)

![Dashboard analysis page](Board%20ScreenShots/Screenshot%202026-08-01%20184813.png)

![Dashboard analysis page](Board%20ScreenShots/Screenshot%202026-08-01%20184821.png)

![Dashboard analysis page](Board%20ScreenShots/Screenshot%202026-08-01%20184829.png)

![Final Best Playing XI](Board%20ScreenShots/Screenshot%202026-08-01%20184840.png)

## Getting started

1. Clone or download this repository.
2. Open [`t20_data_preprocessing.ipynb`](t20_data_preprocessing.ipynb) in Jupyter Notebook to review the data-cleaning process.
3. Review the prepared datasets in [`t20_csv_files/`](t20_csv_files/).
4. Open [`Cricket Best 11.pbix`](Cricket%20Best%2011.pbix) with Power BI Desktop.
5. Use the dashboard filters and role-specific pages to explore the selected Best Playing XI.

## Conclusion

This project demonstrates a practical analytics workflow: working with sourced sports data, transforming it with Pandas, defining player-selection parameters, and communicating the results in Power BI. It is a useful portfolio project for demonstrating data cleaning, analysis, DAX, and dashboard design skills.

## Author

**Abhijeet Singh Rajput**

Student, IIT Dhanbad
