# Job Advertisement Skill & Sentiment Analyzer

An NLP analysis of working student job advertisements in Germany,
extracting the most in-demand skills, tools, and language patterns
from real job descriptions.

> Built out of a personal need: I wanted to understand exactly what
> skills companies are looking for in NLP and data-related roles —
> so I analyzed the job ads themselves.

## What I found

**Most demanded technical skills:**
Python, SQL, Power BI, Tableau, Excel, AI, automation, process mining

**Most common themes:**
data, business processes, project work, customer orientation,
communication, analytical thinking

**Sentiment:** All 6 job ads were positive or neutral in tone —
consistent with the persuasive nature of job postings.

## Methods

**Preprocessing:**
- Lowercasing, punctuation removal
- Tokenization, stop word removal, lemmatization

**Analysis:**
- Word frequency analysis
- Skill & tool frequency extraction
- Sentiment analysis (VADER / TextBlob)

## Dataset

Manually collected from real German job portals.
6 working student job ads across IT, data, automation,
and business roles.

| File | Description |
| `job-ads.xlsx` | Raw collected job advertisements |
| `processed_job_ads.xlsx` | Cleaned and processed data |
| `analysis.ipynb` | Full analysis notebook |

## Tech stack

- Python
- pandas
- NLTK / spaCy
- VADER or TextBlob (sentiment)
- Matplotlib / seaborn (visualization)

## Run locally

git clone https://github.com/tamarataha/job-ad-skill-analyzer
cd job-ad-skill-analyzer
pip install -r requirements.txt
jupyter notebook analysis.ipynb

## Why this project

I built this while actively applying for working student roles in
Germany. Instead of guessing what skills to highlight, I used NLP
to extract patterns from actual job postings — turning the job
search itself into an NLP problem.
