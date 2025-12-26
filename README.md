# Regressioanalyysi keskituntipalkasta

Regression analysis of hourly wages using data from 1976.

This repository contains a Quarto document that analyzes the relationship between education, work experience, and hourly wages.

**View the analysis:** https://isosaari.github.io/palkka-analyysi/

## Local Development

To render the document locally:

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Install R and required packages:
   ```r
   install.packages(c("wooldridge", "car"))
   ```
3. Render and push:
   ```bash
   quarto render
   git add docs
   git commit -m "Update site"
   git push
   ```
