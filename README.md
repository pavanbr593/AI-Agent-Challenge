# AI Agent  – Intelligent Bank Statement Parser Agent

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Framework-LangGraph%20%7C%20Streamlit-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-AI%20and%20Automation-orange?style=for-the-badge" />
</p>



## Introduction  

Bank statements are one of the most common documents in finance, but manually extracting, validating, and formatting the data is slow and error-prone.  

**AI Agent** is an autonomous parsing agent that can:  

- Read PDF statements (bank-specific formats)  
- Extract structured transaction data  
- Validate it against expected schema or CSV  
- Retry automatically if errors occur  

This project demonstrates AI workflow design, clean software architecture, and practical automation skills.

---

## Project Overview  

Rather than building a parser for a single bank, an **extensible modular architecture** was created:  

- Each bank has its **own parser module** (plug-and-play).  
- If parsing fails, the agent retries using different strategies (`camelot`, `pdfplumber`, fallback methods).  
- A **validation layer** ensures extracted data matches expectations.  
- Streamlit UI provides a simple and interactive interface.  

This makes the project scalable, robust, and production-ready.

---

## Objectives  

- Automate repetitive financial data extraction  
- Demonstrate AI agent capabilities with self-debugging loops  
- Deliver a clean, modular architecture  
- Build a project that HRs and interviewers can quickly understand and appreciate  

---

## Tech Stack  

- **Language:** Python 3.13  
- **Frameworks:** LangGraph (workflow/agent), Streamlit (UI)  
- **Libraries:**  
  - `camelot`, `pdfplumber` → PDF parsing  
  - `pandas` → Data handling and validation  
  - `pytest` → Testing  
- **Version Control:** Git and GitHub  
- **Editor:** VS Code  

---



    





```
Requirements
Python 3.13

Virtual environment recommended
Install dependencies:
pip install -r requirements.txt

How to Run
Clone the repository:

git clone https://github.com/pavanbr593/AI-Agent-Challenge
cd AI Agent Challenge 


Run the agent:
python agent_v2.py --target icici


Launch the Streamlit UI (optional):
streamlit run app.py


Run tests:
pytest

Demo
	•	Visualize the parsing process using interactive Streamlit UI
	•	Automatically extract and validate bank statement data
	•	Demonstrate retry and self-correcting mechanisms for robust parsing

Key Learnings
	•	Designing autonomous AI agents with retry and self-correcting loops
	•	Handling inconsistent PDF layouts across different banks
	•	Building modular and extensible architectures for scalability
	•	Ensuring data accuracy through validation and testing
	•	Documenting projects clearly for recruiters and interviewers

⸻


Conclusion

AI Agent demonstrates end-to-end AI workflow design, modular architecture, and practical automation skills.
This project highlights the ability to plan, implement, and deliver real-world solutions, making it both production-ready and interviewer-friendly.

Built with dedication by    
                           `~ Pavan Bendre R 
