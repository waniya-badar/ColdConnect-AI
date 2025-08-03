# ColdConnect-AI
ColdConnect AI - A powerful tool that automates the process of extracting job postings from company career pages, matching those jobs with your portfolio case studies and generating personalized cold emails using Groq's LLaMA 4 model. Built using LangChain, Groq, Streamlit, and ChromaDB, it enables business development professionals to create high-impact outreach in seconds.

### Use Case:
Business teams often struggle to keep up with job listings and craft emails manually. ColdConnect AI solves this by:
- Scraping job descriptions from company URLs
- Parsing relevant info (role, experience, skills, description)
- Finding matching portfolio links based on skillsets
- Writing cold emails from the perspective of your company’s representative

### Features:
- Extracts job info from any career/job listing page
- Uses LLM to understand and generate personalized emails
- Connects job skillsets to your own portfolio links
- Fully customizable for different company profiles

### Tech Stack:
| Tool             | Purpose                                  |
| ---------------- | ---------------------------------------- |
| `LangChain`      | Prompting & LLM chaining                 |
| `Groq + LLaMA 4` | LLM inference                            |
| `Streamlit`      | Web UI for easy interaction              |
| `ChromaDB`       | Vector-based portfolio similarity search |
| `Pandas`         | Portfolio CSV parsing                    |
| `Regex`          | HTML & text cleaning                     |

### How To Run:
streamlit run app/main.py

### Usage Instructions:
- Paste a job URL from a career page.
- Click "Submit".
- The app will:
1. Scrape and clean the page
2. Extract job descriptions
3. Match relevant portfolio projects
4. Generate a complete cold email
- Copy & send the email directly from your email client.
