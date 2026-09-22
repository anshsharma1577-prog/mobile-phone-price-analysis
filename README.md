# Mobile Phone Price Analysis Using R

Academic R Markdown Tiny Project by **Ansh Sharma**, BCA (Hons), Division G.

## What this project demonstrates
- CSV data importing
- Data inspection and preprocessing
- Missing-value and duplicate checks
- Descriptive statistics
- Brand-wise price analysis
- Data visualization using `ggplot2`
- Correlation analysis
- Interpretation, findings and conclusion
- Reproducible R Markdown workflow

## Dataset
`data/mobile_phone_data.csv` contains 44 curated sample phone records. The values are intended for academic demonstration and should not be interpreted as a live market-price database.

## Files
```text
mobile-phone-price-analysis/
├── README.md
├── requirements.txt
├── .gitignore
├── mobile_phone_price_analysis.Rmd
├── mobile_phone_price_analysis.html
├── data/
│   └── mobile_phone_data.csv
├── plots/
│   ├── price_distribution.png
│   ├── price_by_brand.png
│   ├── ram_distribution.png
│   ├── storage_distribution.png
│   ├── ram_vs_price.png
│   ├── storage_vs_price.png
│   ├── battery_vs_price.png
│   └── price_vs_rating.png
└── screenshots/
    └── report_preview.png
```

## R packages
```r
install.packages(c("rmarkdown", "knitr", "ggplot2"))
```

## How to reproduce the report
1. Open `mobile_phone_price_analysis.Rmd` in RStudio.
2. Keep the `data` folder beside the R Markdown file.
3. Install the required packages.
4. Click **Knit → Knit to HTML**.
5. RStudio will generate the final HTML report.

## Important
The supplied HTML is a polished preview generated from the same dataset and analysis. For faculty submission, the authoritative reproducible source is the `.Rmd` file; knitting it in RStudio produces the native R Markdown HTML output.
