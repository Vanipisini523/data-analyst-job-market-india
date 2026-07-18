# Data Analyst Job Market Analysis — India

**Status:** Completed

## What this is
A self-collected dataset of live Data Analyst job postings from across India, built to answer a simple question: what do Indian companies actually want from an entry-level Data Analyst right now?

Instead of using a pre-made Kaggle dataset, I sourced real, current postings myself — so the analysis reflects the job market as it exists today, not a static historical snapshot.

## How the data was collected
- **Sources:** Naukri, Indeed, Glassdoor
- **Scope:** 149+ postings across 17 Indian cities (Visakhapatnam, Hyderabad, Bengaluru, Noida, Gurgaon, Mumbai, Chennai, Kochi, Kolkata, Lucknow, Jammu, Ahmedabad, Chandigarh, Pune, Jaipur, Coimbatore, and more)
- **Fields captured per posting:** Job Title, Company, Location, Experience Required, Salary, Salary_Type, Skills Mentioned, Job Type, Source, Date Collected
- **Skill tagging:** each posting is tagged Yes/No for SQL, Python, Excel, Power BI, Tableau, R, and SAS based on the listed requirements

## Salary data note
Only ~7% of postings disclosed an actual salary figure. Where a posting didn't disclose salary, I filled in an approximate market-rate estimate (marked in the Salary_Type column as "Estimated"). Postings that did list a real figure are marked "Disclosed".

## Tools used / pipeline
1. **Excel** — data collection, cleaning, and skill-tagging
2. **MySQL** — querying for skill frequency, city-wise demand, experience-level breakdowns, and salary disclosure trends
3. **Power BI** — interactive dashboard visualizing skill demand, salary transparency, and postings by city, filterable by experience level and location

## Key findings
- SQL and Excel are the two most in-demand skills, followed by Power BI, Tableau, and Python
- Only 7.38% of postings disclose an actual salary figure
- Hyderabad, Bengaluru, Lucknow, and Noida lead in posting volume

## Files in this repo
- `data_analyst_job_tracker.xlsx` — the full dataset
- Dashboard screenshot — the finished Power BI dashboard

## Why I built this
I'm a fresher applying for Data Analyst roles myself, so this project doubles as market research for my own job search — and a way to show, not just tell, that I can take messy real-world data from collection through to a finished analytical product.

## Author
Vani Pisini
[LinkedIn](https://linkedin.com/in/vani-pisini)
