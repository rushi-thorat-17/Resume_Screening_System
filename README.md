# 🤖 AI Resume Screening System

An intelligent system that evaluates resumes against job descriptions using **LLMs + structured pipelines**.

---

## 🚀 Overview

This project automates candidate screening by extracting, matching, scoring, and explaining resume suitability.

Built with a **modular 4-step AI pipeline**, ensuring accuracy, transparency, and scalability.

---

## ⚙️ Tech Stack

- 🧠 LangChain (LCEL Pipelines)  
- 🤗 HuggingFace Models  
- 🔍 LangSmith (Tracing & Debugging)  
- 🐍 Python  

---

## 🔄 Pipeline Flow

```mermaid
graph TD
    JD[Job Description + Resume] --> E
    E[Extraction] --> M[Matching]
    M --> S[Scoring]
    S --> X[Explanation]
    X --> F[Final JSON Output]

