# EDA Election Results

In this assignment you will practice a different kind of exploratory data analysis. One where you ask a targeted question and seek an answer. The repo contains data from the 2016,2020, and 2024 presidential elections as well as 2024 senate elections. Those live in the `data` folder.

It also contains the following three notebooks
- `01-cleaning.ipynb` - Reads the raw data and cleans it up. Combines it into one big dataframe. Make sure to read this notebook and understand what it is doing. There are some methodological choices in there that you should be aware of. When you run the notebook, it will output a file called `election_results.csv` which contins the cleaned data from all four elections mentioned above in one big dataframe.
- `02-example.ipynb` - this notebook reads `election_results.csv` and does an EDA for one question about ticket splitting. Ticket splitting is when people vote for one party for president but another party for downballot races like Senate. This notebook asks the question, "In what regions did Trump outperform the Republican Senate candidate in 2024?". There are a few small to-do items at the end of this notebook.
- `03-your-question.ipynb` - This is a blank notebook where you will ask your own question and do your own EDA. You can use the example notebook as a guide.

When you're done, you will write a short memo in a google doc and submit it to the assignment on canvas. Include the chart or map you made and a few lines explaning what you think you've found. You don't have to get to the real answer, just asking the question is enough. Write your initial question, any conclusions you're ready to draw now that you've done the analysis, and any further questions you have.

## Installation

### Python packages

Install required Python packages using pip:

```bash
pip install us
```
### R packages

Install required R packages using the following command:
```r
install.packages(c(
  'tidyverse',  # includes ggplot2, dplyr, tidyr, etc.
  'sf',         # for spatial data handling
  'tigris'      # for county shapefiles
))
```