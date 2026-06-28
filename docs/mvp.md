# MVP v1 — Research Copilot

## Goal

Build a minimal working system that converts academic PDFs into structured research notes using AI.

---

## Scope (Strictly Limited)

MVP v1 ONLY includes:

### 1. PDF Upload
- User uploads academic PDF

### 2. Text Extraction
- Extract raw text from PDF using PyMuPDF

### 3. AI Summarization
- Send extracted text to LLM
- Return structured summary

### 4. Note Generation
- Save structured output as reading note

---

## Output Format

Each paper produces:

- Key Argument
- Key Concepts
- Methodology
- Key Evidence / Quotes
- Reflection Notes

---

## Out of Scope (IMPORTANT)

The following are NOT included in MVP v1:

- Knowledge graph
- Theory comparison matrix
- Concept extraction engine
- Writing assistant
- Research gap detection
- Multi-paper analysis

---

##  System Flow

```text 
PDF Upload
   ↓
Text Extraction
   ↓
LLM Processing
   ↓
Structured Output
   ↓
Save Note
