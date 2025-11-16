# AI Job Match Analyzer
This project focuses on building a personal AI Resume Match Analyzer, a practical tool that uses Large Language Models (LLMs) to analyze and match a candidate’s profile with job descriptions from the web.

## Project Overview

The goal of this project is to create an AI-powered assistant that can:
- Scrape job description pages from websites.
- Read and analyze a candidate’s resume or portfolio (e.g., GitHub or PDF)
- Compare both and generate a match score (in %).
- Highlight skill gaps and suggest improvements.
- Optionally extract job insights — salary, location, and type (full-time/contract)

## Tools & Technologies

- Python (core language)
- OpenAI GPT models (gpt-4.1-mini, gpt-5-nano)
- Web Scraping: Custom scraper using requests and BeautifulSoup
- Environment Setup: .env for API key management
- IDE: Cursor (for AI-powered coding)
- LLM API Integration: via the OpenAI Python SDK

## How It Works

- The system fetches job description text from a given URL
- It reads the candidate’s resume or GitHub profile
- An LLM compares both datasets
- The model generates:
    - A match percentage
    - Key skill matches and missing skills
    - Job details such as salary range, location, and employment type

## Learning Outcome

This project combines AI fundamentals(prompt engineering, API setup, web summarization) with a real-world business application — turning raw text data into a meaningful AI insight system for career analysis and decision-making.
Key skill matches and missing skills, Job details such as salary range, location, and employment type.
