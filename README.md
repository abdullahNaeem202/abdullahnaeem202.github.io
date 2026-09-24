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

## Where the Built Site Lands
Once rendered, all the relevant site files are written into the `docs/` folder. To view the site locally from the terminal, run either of the following commands from the top level: 
```bash
uv run quarto preview
```

```bash
quarto preview
```

This will start a local server and open the site in your browser automatically. 

## Data Source

Both the R and Python posts use data from the [COVID-19 Data 
Repository by the Center for Systems Science and Engineering (CSSE) at 
Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19), 
licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

**note that no data file is committed to this repository.** Instead, both posts read the 
releavnt data directly from its GitHub URL at render time. 

- **An internet connection is required to build this site.** If the linked repository 
  is ever moved, renamed, or taken offline, rebuilding 
  will fail even though all code and environments are correctly set up.
