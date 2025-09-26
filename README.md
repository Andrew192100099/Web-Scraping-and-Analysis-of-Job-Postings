# 🀄 Web Scraping and Analysis of Job Postings

From scattered online listings → to clear insights for job seekers & recruiters.
_____________
## ✨ The Story

When I first looked at LinkedIn job postings, one thing became clear:
the data was everywhere — thousands of listings, messy titles, scattered skills, and no simple way to answer real career questions.

**So I set out on a mission:**

**1️⃣ Scrape the data using Selenium —** navigating LinkedIn’s structure to collect job postings at scale.

**2️⃣ Organize the chaos —** turning raw job titles and descriptions into structured datasets.

**3️⃣ Ask business-driven questions —** the kind that job seekers, recruiters, and HR professionals really want answers to.

***And slowly, the patterns began to emerge...***
______

## 💡 The Business Questions We Asked

**❔ Which technical skills are most in demand across industries?**

**❔ Do specific cities favor certain tools or languages?**

**❔ What’s the overlap of tools like Python, SQL, and Power BI in job postings?**

**❔ How do job descriptions differ between roles (Data Analyst, Data Scientist, BI Specialist)?**
________________

## 🔍 How We Answered Them

**✔ Extracted skills from job titles using custom keyword detection (Python, SQL, Excel, Power BI, etc.).**
**✔ Grouped and counted skills city by city to see what employers look for in different markets.**
**✔ Built frequency rankings with Python’s Counter to identify the top 8 skills per city.**
**✔ Exported everything into structured CSV reports — easy to reuse and share.**
**✔ Highlighted insights with visuals & summary tables for decision-making.**
_________________________

## 🎯 Key Insights (Highlights from the Analysis)

**➢ Python & SQL were the clear leaders across most job postings.**

**➢ Power BI and Tableau dominated business-focused roles.**

**➢ Excel remains a foundational tool — often required alongside advanced skills.**

**➢ Skill preferences varied by city — some leaned heavily on BI tools, while others emphasized programming.**

**➢ For cities with fewer postings, Data Analysis served as the default baseline skill.**
_______________________

## 🛠️ Technical Journey

**📍 Web Scraping:** *Selenium for LinkedIn navigation & job extraction.*

**📍 Data Cleaning:** *Pandas to remove duplicates, normalize case, and standardize formats.*

**📍 Skill Extraction:** *Custom keyword dictionaries to capture core tech stacks.*

**📍 Analysis:** *Groupby, Counter, and Pandas operations to surface insights.*

**📍 Visualization:** *Matplotlib & Seaborn to highlight trends.*

**📍 Export:** *Clean CSV reports (linkedin_jobs.csv) for sharing & reuse.*
________________

## 📌 Why This Project Matters

*This project wasn’t just about scraping job ads*
**It was about transforming unstructured data into business intelligence:**

**✔ Helping job seekers know where to focus their upskilling**

**✔ Giving recruiters a sharper view of the talent landscape**

**✔ Equipping businesses with knowledge of in-demand skills across regions**

***In short:*** *from raw data → to career strategy*
