# Olympic Metal Analysis

Freestyle skiing olympic medal analytics and data visualization.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Analysis Details](#analysis-details)
- [License](#license)
- [Author](#author)

## Project Overview

This project provides an in-depth analysis of Olympic freestyle skiing medals, focusing on the aerials event from 1994 to 2018. The analysis includes data visualization to compare metal counts across countries and genders.

## Technologies

- R
- tidyverse
- ggplot2
- lubridate
- rvest
- knitr

## Setup

To run this analysis, ensure you have the following R packages installed:

```r
install.packages(c(
  "tidyverse",
  "lubridate",
  "rvest",
  "knitr"
))
```

## Usage

1. Clone or download the repository.
2. Open `Olympic_Metal_Analysis.Rmd` in RStudio.
3. Run the RMarkdown file to generate the HTML output.

## Analysis Details

The analysis addresses the following questions:

- How do metal counts for each country compare across gold, silver, and bronze from 1994-2018?
- Which country has the highest number of metals for each type?

The data is sourced from Wikipedia's list of Olympic medalists in freestyle skiing. The RMarkdown file includes:

- Data scraping from Wikipedia tables
- Data cleaning and transformation
- Visualization using ggplot2
- Detailed insights and conclusions

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

**Bjorn Melin**

- GitHub: [@BjornMelin](https://github.com/BjornMelin)
- LinkedIn: [Bjorn Melin](https://linkedin.com/in/bjorn-melin)

---

Made with 📊 and ❤️ by Bjorn Melin
