# Shad Ali Shah | Economics and Data Science Portfolio

[![Website](https://img.shields.io/badge/Portfolio-Visit%20Website-176BBD?style=for-the-badge)](https://shadalishah.com)
[![GitHub](https://img.shields.io/badge/GitHub-shadalishah-181717?style=for-the-badge&logo=github)](https://github.com/shadalishah)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shad%20Ali%20Shah-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shadalishah/)

A professional academic and analytics portfolio built with **RStudio and Quarto**. The website presents work across **Applied Economics, Econometrics, Economic Research, Data Analytics, Data Science, Machine Learning, Business Intelligence, forecasting, NLP, and Retrieval-Augmented Generation**.

> **Live website:** [https://shadalishah.com](https://shadalishah.com)

## Portfolio Overview

The website includes:

- Professional profile and career focus
- Education and academic research
- Research Assistant and internship experience
- Independent Economics and Data Science experience
- Economic analysis and econometric methods
- Data Science and Machine Learning projects
- Skills, certifications, and technical tools
- Publications and documented research outputs
- Downloadable Universal Master CV
- GitHub, LinkedIn, and contact information

## Professional Highlights

- MPhil Economics coursework and thesis completed at Quaid-i-Azam University, Islamabad
- BS Economics with Distinction
- Research Assistant experience
- Three Data Science and AI/ML internships
- Best Intern Award
- 29 documented independent and academic/research project repositories
- Practical work with large economic, customer, transaction, employment, and text datasets

## Core Areas

### Economics and Econometrics

- Applied Economics and Economic Research
- Macroeconomics and Financial Economics
- Policy Analysis and Quantitative Research
- VAR, SVAR, VECM, and ARIMA
- Stationarity, Cointegration, Granger Causality, IRFs, and FEVD
- Time-Series Analysis and Forecasting

### Data Analytics and Business Intelligence

- SQL and Google BigQuery
- Microsoft Excel
- Power BI and Tableau
- Data Cleaning, Validation, and Transformation
- KPI Reporting and Dashboard Development
- Customer, Employment, Transaction, and Business Analytics

### Data Science and Machine Learning

- Python, Pandas, NumPy, and Scikit-learn
- Regression, Classification, and Clustering
- Random Forest and K-Means
- Feature Engineering and Model Evaluation
- Natural Language Processing and BERT Feasibility Analysis
- Retrieval-Augmented Generation Applications

## Selected Projects

### Pakistan Macroeconomic Dynamics

Applied VAR, SVAR, VECM, ARIMA, stationarity testing, cointegration, causality analysis, IRFs, and FEVD to more than 44 quarters of Pakistan macroeconomic data.

[View repository](https://github.com/shadalishah/Macroeconomic-Time-Series-Analysis-VAR-SVAR-VECM)

### Pakistan E-Commerce Analytics

Cleaned more than one million raw records into 584,524 validated transactions covering 115,326 customers and performed segmentation, forecasting, and analytical reporting.

[View repository](https://github.com/shadalishah/Pakistan-E-Commerce-Data-Analysis-2016-2018-)

### Advanced SQL Analytics with Google BigQuery

Used SQL, CTEs, and window functions to analyse and segment 50,000 customer records and prepare KPI-focused outputs.

[View repository](https://github.com/shadalishah/Basic-to-Advanced-SQL-Analytics-with-Google-BigQuery)

### Pakistan and Global Employment Analytics

Analysed more than 57,500 employment observations across 183 countries and developed policy-oriented forecasts and Tableau visualizations.

[View repository](https://github.com/shadalishah/Pakistan-Global-Employment-Analytics-Tableau)

### NewsSense-BERT

Conducted NLP and transformer-feasibility analysis on 120,000 news articles, including text profiling, n-gram analysis, Named Entity Recognition, and BERT architecture planning.

[View repository](https://github.com/shadalishah/NewsSense-BERT)

### BankWise AI RAG Assistant

Developed a Retrieval-Augmented Generation-focused application for banking-related information and documented the analytical workflow.

[View repository](https://github.com/shadalishah/BankWise-AI-RAG-Assistant)

## Publications and Research Outputs

The portfolio documents **29 GitHub project repositories** across Economics, Econometrics, Data Analytics, Data Science, Machine Learning, Business Intelligence, forecasting, NLP, and RAG.

Academic papers currently in development are identified as **works in progress** and will be added only after reaching an appropriate publication or preprint stage. GitHub project publication is presented separately from formal academic publication.

## Website Structure

```text
shadali-portfolio-complete/
├── _quarto.yml
├── index.qmd
├── about.qmd
├── experience.qmd
├── projects.qmd
├── economic-analysis.qmd
├── data-science.qmd
├── publications.qmd
├── skills.qmd
├── education.qmd
├── cv.qmd
├── contact.qmd
├── 404.qmd
├── assets/
│   └── css/
│       └── styles.css
├── files/
│   └── Shad_Ali_Shah_CV.pdf
├── CNAME
├── .nojekyll
└── README.md
```

## Run Locally

### Requirements

Install:

- [R](https://cran.r-project.org/)
- [RStudio](https://posit.co/download/rstudio-desktop/)
- [Quarto](https://quarto.org/docs/get-started/)

### Preview the website

Open the `.Rproj` file in RStudio. Then use the **Terminal**, not the R Console:

```bash
quarto preview
```

Quarto will open a local preview address such as:

```text
http://localhost:XXXX
```

### Build the production website

```bash
quarto render
```

The rendered site will be written to the output folder configured in `_quarto.yml`.

## Add or Replace the CV

Place the final PDF inside the `files` folder using this exact filename:

```text
files/Shad_Ali_Shah_CV.pdf
```

The CV view and download links in `cv.qmd` must point to the same path.

Example:

```html
<a href="files/Shad_Ali_Shah_CV.pdf" class="btn btn-primary" download>
  Download My CV
</a>
```

## Deployment

### GitHub Pages

1. Push the complete Quarto project to this repository.
2. Render the website with `quarto render`.
3. Configure GitHub Pages using the rendered output method used by the project.
4. Add the custom domain in **Repository Settings → Pages**.
5. Configure the domain DNS records through the domain registrar.
6. Enable **Enforce HTTPS** after DNS verification succeeds.

### Custom Domain

The intended custom domain is:

```text
shadalishah.com
```

The repository includes a `CNAME` file for the custom-domain configuration. The domain must be owned and its DNS records must be connected to GitHub Pages before the URL becomes active.

## Updating the Website

After changing any `.qmd`, CSS, or website configuration file, run:

```bash
quarto render
git add .
git commit -m "Update portfolio website"
git push
```

## Important Notes

- Do not run `quarto preview` multiple times simultaneously.
- Stop an existing preview with `Ctrl + C` before starting another one.
- Use the RStudio **Terminal** for Quarto commands, not the R Console.
- Keep internal filenames and letter capitalization consistent because GitHub Pages is case-sensitive.
- Do not present GitHub repositories as peer-reviewed academic publications.
- Do not publish CNIC numbers, degree serial numbers, private references, or other sensitive documents.

## Contact

**Shad Ali Shah**  
Islamabad, Pakistan  
Email: [shadalishah45@gmail.com](mailto:shadalishah45@gmail.com)  
LinkedIn: [linkedin.com/in/shadalishah](https://www.linkedin.com/in/shadalishah/)  
GitHub: [github.com/shadalishah](https://github.com/shadalishah)

## License

This repository is available under the license included in the project. Portfolio content, personal information, reports, and project materials remain attributable to their respective author and sources.
