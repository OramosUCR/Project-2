# Project 2: Computational Review of ranger

This repository contains a computational review of the paper:

**Wright, M. N., & Ziegler, A. (2017). ranger: A Fast Implementation of Random Forests for High Dimensional Data in C++ and R. *Journal of Statistical Software*, 77(1), 1-17.**

## Contents

- `report.qmd`: Main Quarto report containing the computational review
- `wright2017ranger.pdf`: The original paper being reviewed

## Building the Report

To render the Quarto report:

```bash
quarto render report.qmd
```

This will generate `report.html` with all code chunks executed.

## Requirements

The report requires the following R packages:
- `ranger`: Fast random forest implementation
- `ggplot2`: For visualizations
- `dplyr`: For data manipulation
- `microbenchmark`: For performance comparisons

Install with:
```r
install.packages(c("ranger", "ggplot2", "dplyr", "microbenchmark"))
```

## Report Structure

The report follows the grading rubric requirements:

1. **Background/Summary**: Overview of the problem, main contributions, and computational aspects
2. **Review of Methods**: Detailed description of computational methods, bottlenecks, and gaps
3. **Technical Demonstration**: Working, reproducible examples using ranger
4. **Discussion**: Critical analysis of achievements and limitations

