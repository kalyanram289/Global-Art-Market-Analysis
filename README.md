# Global Art Market Analytics

A data analytics case study exploring artwork pricing patterns across countries, genres, artist tiers, and time.

## Project Overview

This project analyzes 34,200 artwork records to understand the factors associated with artwork valuations and how pricing patterns vary across different market segments.

The analysis was performed using Python, and the results were presented through an interactive Power BI dashboard.

## Key Questions

- How do artwork prices vary across countries?
- Which art genres have higher typical prices?
- How does artist tier relate to artwork valuation?
- How do artwork prices change over time?
- How often do recorded prices fall above or below their estimates?
- Is artwork size associated with price?

## Key Findings

- Artist tier shows a strong relationship with typical artwork prices.
- Photography has a higher median price than the other major genres in the dataset.
- Artwork prices are highly skewed, with a small number of very high-value works.
- Artwork size has a moderate positive relationship with price.
- Recorded prices vary considerably relative to their estimated ranges.
- Artwork prices fluctuate over time rather than increasing steadily.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Power BI
- Statistical Analysis

## Dataset

The dataset contains artwork-level information including:

- Artwork price
- Year
- Country
- Genre
- Artist tier
- Artwork dimensions
- Price estimates
- Event date

**Dataset source:** Lee et al. (2024), *Social signals predict contemporary art prices better than visual features, particularly in emerging markets*, Scientific Reports.

## Project Structure

```text
Global-Art-Market-Analytics/
│
├── data/
│   └── art_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── powerbi/
│   └── dashboard.pdf
│
├── presentation/
│   └── case_study.pptx
│
└── README.md
