# AI SQL Assistant Agent

## Project Overview

AI SQL Assistant Agent is a Generative AI-powered assistant that helps users generate, understand, optimize, debug, and learn SQL queries using natural language.

The project is designed for Data Analysts, Business Analysts, Data Engineers, Data Science students, and SQL learners who want to improve their SQL skills and productivity.

---

## Features Completed

### Day 1 - SQL Query Generation

- Database Schema Input
- Natural Language Query Input
- AI SQL Query Generation
- SQL Query Export

### Day 2 - SQL Analysis & Optimization

- SQL Query Explanation
- SQL Optimization Suggestions
- SQL Performance Analysis
- SQL Code Quality Review
- SQL Best Practices Recommendations

### Day 3 - SQL Learning & Debugging

- SQL Error Detection
- SQL Query Correction
- SQL Practice Question Generation
- SQL Interview Preparation Assistant
- SQL Learning Support

---

## Target Users

- Data Analysts
- Business Analysts
- Data Engineers
- Data Science Students
- SQL Learners
- Database Developers

---

## Technologies Used

- Python
- Google Colab
- Google Gemini API
- Generative AI
- Prompt Engineering

---

## Project Workflow

Database Schema

↓

Natural Language Question

↓

AI SQL Query Generation

↓

SQL Explanation

↓

Performance Analysis

↓

Optimization Suggestions

↓

Error Detection

↓

Query Correction

↓

Interview Preparation

---

## Sample Use Cases

### SQL Generation

Input:

"Show top 5 customers by total spending."

Output:

```sql
SELECT c.customer_name,
       SUM(o.amount) AS total_spending
FROM Customers c
JOIN Orders o
ON c.customer_id = o.customer_id
GROUP BY c.customer_name
ORDER BY total_spending DESC
LIMIT 5;
