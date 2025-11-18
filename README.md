# Uptitude
# CUAD Contract Analysis Pipeline (Local LLM + Ollama)

This project implements a complete document processing pipeline for the CUAD dataset using a **local LLM** (Ollama + Qwen2.5). It extracts key legal clauses and generates detailed contract summaries with no API cost and no rate limits.

---

## 🚀 Objective

Build a fully reproducible pipeline that:
1. Loads CUAD contracts (50 PDFs)
2. Extracts text using PyMuPDF
3. Cleans + chunks text
4. Performs **LLM-powered clause extraction**:
   - Termination conditions  
   - Confidentiality clauses  
   - Liability clauses  
5. Generates **120–150 word contract summaries**:
   - Purpose of the agreement  
   - Key obligations of each party  
   - Risks, penalties, termination/breach information  
6. Saves results into a CSV file.

All LLM inference is done **locally** using Ollama.

---

## 📁 Repository Contents

