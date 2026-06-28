# Research-copilot for Social Sciences

An AI-powered Research Workspace for Social Science & Humanities Students

# Motivation

Students in humanities and social sciences engage with complex theoretical texts across multiple disciplines such as sociology, political theory, anthropology, cultural studies, and media studies.

However, these readings are often fragmented across notes, summaries, and essays, making it difficult to build cumulative and comparative understanding of theory.

This project explores a central question:

How can students transform interdisciplinary academic reading into a structured system of concept extraction, comparison, and synthesis?

Rather than treating reading as passive consumption, this system reframes it as an analytical workflow grounded in theory-building and structured thinking.

# Goal

This system is designed to support students and researchers working with theoretical and interpretive academic texts by transforming reading into a structured research process:

📖 Reading → 🧠 Concept Extraction → 🔗 Theory Mapping → ✍️ Academic Writing

The goal is not to replace reading, but to make theoretical reasoning more explicit, comparable, and cumulative.

# Core Design Philosophy

## 1. Theory-first, not tool-first

The system is designed around academic thinking processes rather than productivity optimization.

## 2. Comparative reasoning over summarization

Instead of generating summaries, the system emphasizes:

- cross-text concept comparison
- theoretical mapping
- structural interpretation

## 3. Research workflow integration

Reading is treated as part of a continuous academic pipeline:

    literature → interpretation → synthesis → writing

# Intended Users

This system is designed for students and researchers in:

- Sociology
- Political Science
- Anthropology
- Communication & Media Studies
- Cultural Studies
- Gender Studies
- Humanities & interdisciplinary social sciences
- .....

who engage with:

  theoretical, interpretive, and concept-driven academic texts

# System Architecture

## 1. Text Ingestion Layer

- PDF upload and parsing
- Chapter and paragraph segmentation
- Highlighting and annotation support

## 2. Concept Extraction Engine

Transforms raw text into structured theoretical components:

- Key concepts (e.g., “stigma”, “habitus”, “symbolic power”)
- Theorist attribution (Durkheim, Goffman, Bourdieu, Mills, Giddens, etc.)
- Structural themes (identity, power, inequality, resistance)

## 3. Annotation System for Theoretical Reading

A structured tagging system for academic interpretation:

- Identity
- Power
- Structure
- Inequality
- Resistance
- Representation

This allows users to move from notes → analytical categories → theoretical insight.

## 4. Literature Comparison Matrix

A cross-text analytical framework for theory synthesis:

| Concept   | Goffman | Bourdieu | Scott | Mills |
| --------- | ------- | -------- | ----- | ----- |
| Power     | ✔       | ✔        | ✔     | ✔     |
| Identity  | ✔       | ✔        | ✖     | ✔     |
| Structure | ✔       | ✔        | ✔     | ✔     |

This enables:

- cross-theory comparison
- conceptual convergence mapping
- structured academic reasoning

## 5. Academic Writing Support Layer

A structured framework for argument construction:

- claim formulation
- theory integration
- evidence linking
- paragraph scaffolding for essays

## 6. Research Journal System

A structured reflection space for each reading session:

Each entry includes:

- key concepts
- analytical interpretation
- theoretical connections
- research questions
- potential essay applications

# Example Workflow

   ## Text: Goffman — Stigma
   
   ### 1. Upload PDF → system segments structure
   
   ### 2. Extract key concepts:
      - stigma
      - identity management
      - social labeling

   ### 3. Annotate theoretical dimensions:
      - identity ✔
      - structure ✔
      - power ✔

   ### 4. Compare with Bourdieu:
      - symbolic power connection

   ### 5. Output:
      - structured research note
      - writing-ready analytical paragraph

# Tech Stack

## Frontend:
- React
- Next.js

## Backend:
- Python
- FastAPI

## Data Layer:
- PostgreSQL
- Vector database (semantic retrieval)

## AI Layer:
- LLM API integration
- embedding-based concept extraction

# Roadmap

## Phase 1 — Core Reading System
- PDF ingestion and segmentation
- annotation system
- concept extraction engine

## Phase 2 — Comparative Theory Layer
- literature comparison matrix
- cross-text concept linking
- structured theory mapping

## Phase 3 — Writing Integration
- argument scaffolding system
- academic paragraph generation support
- theory-to-writing pipeline

## Phase 4 — Knowledge Graph (Advanced)
- concept network visualization
- theorist relationship mapping
- cross-disciplinary theory graph

# Academic Context

This project is informed by foundational and contemporary social theory, including:

- Erving Goffman — Stigma, The Presentation of Self in Everyday Life
- Pierre Bourdieu — Language and Symbolic Power
- James C. Scott — Domination and the Arts of Resistance
- C. Wright Mills — The Sociological Imagination
- Virginia Woolf — A Room of One’s Own

This list represents the texts used as example inputs during development, selected based on my current reading focus.

# Intended Impact

This system is designed as a cognitive scaffold for interdisciplinary theoretical thinking, helping users:

-move beyond summarization into conceptual analysis
-develop comparative theoretical reasoning
-connect micro-level interaction with macro-level structures
-build cumulative academic understanding across texts

# Status

Early-stage research prototype (in development)
