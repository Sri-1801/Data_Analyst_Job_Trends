Job Postings Skill Analysis
📊 Project Overview

This project analyzes Data Analyst & Tech Job Postings from online platforms to identify the most in-demand skills in the current job market.
It uses Python for web scraping, text analysis, and data visualization.

🧩 Key Features

Scrapes real job data (titles, companies, and locations).

Extracts and cleans text from job descriptions.

Identifies top technical skills like Python, SQL, Excel, Power BI, etc.

Exports results into a clean CSV file.

Ready for visualization and further analysis.

⚙️ Tech Stack

Python Libraries: requests, BeautifulSoup, pandas, re

Tools Used: Jupyter Notebook / VS Code

Output File: job_postings.csv

🗂️ Folder Structure
📁 Job_Postings_Skill_Analysis/
│
├── job_postings_scraper.py     # Main Python script
├── job_postings.csv            # Final dataset
└── README.md                   # Project documentation

🚀 How It Works

Fetch job data from target site using requests.

Parse job titles, companies, and locations with BeautifulSoup.

Clean and preprocess job text.

Count most frequent skills and export to CSV.

🧾 Sample Output (CSV Preview)
Job Title	Company	Location
Data Analyst	Jobgether	Worldwide
Backend Engineer	Veda Tech Labs	Remote
Machine Learning Engineer	Incode Technologies	Spain
🧠 Top Skills Found
Rank	Skill	Frequency
1	Python	12
2	SQL	10
3	Excel	8
4	Power BI	6
5	Tableau	5
🏁 Next Steps

Add job description scraping for deeper text analysis.

Create Power BI / Python dashboard for visualization.

Extend to multiple job platforms (LinkedIn, Naukri, etc).

👩‍💻 Author

Dhanujasri Sagadevan
Data Analyst | Python & SQL Enthusiast
📍 Salem, Tamil Nadu
🔗 GitHub