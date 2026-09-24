# abdullahnaeem202.github.io
## About this Repository 
This repository is a portfolio of my background, who I am, and why I chose to pursue the Masters of Data Science at UBC. Navigate through the different links on my website to learn more about me and look through some data anlaysis I did in R and Python. 
## What to Install
- [Quarto](https://quarto.org/docs/get-started/) version 1.10.18 or later
- [uv](https://docs.astral.sh/uv/getting-started/installation/) version 0.12.6 or later
- [R](https://cran.r-project.org/) version 4.6.1 or later
## Commands
Run the following commands in order, **from the top level of the repository thats cloned**,

**1. Clone the Repository (shell)**
```bash
git clone git@github.com:abdullahNaeem202/abdullahnaeem202.github.io.git
cd abdullahnaeem202.github.io
```

**2. Set up the Python environment (shell - from top level of repo)**
```bash
uv sync
```

**3. Set up the R environment (R console - started from top level of repo)**
```r
renv::restore()
```

**4. Render the site (shell - from top level of the repo)**
```bash
uv run quarto render
```