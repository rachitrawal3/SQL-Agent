🧠 SQL-Agent

Turn natural language into SQL, visualizations, and insights with ease.
Built with Agentic AI + LLMs, this project automates end-to-end data analysis across any SQL database.

🌟 Overview

SQL-Agent is a multi-agent system that bridges LLMs and SQL databases. It allows users to ask questions in plain English and get back SQL queries, data visualizations, structured tables, and LLM-driven insights—all in a single pipeline.

The system is database-agnostic, lightweight, and modular, making it easy to integrate into analytics platforms, dashboards, and decision-support systems.

🔑 Key Functionalities
1️⃣ SQL Generator

Converts natural language queries into optimized SQL.

Supports any SQL database (PostgreSQL, MySQL, SQLite, MS SQL, etc.).

Dynamically fetches both structured and unstructured data.

2️⃣ Chart Generator

Automatically generates charts and graphs (bar, line, pie, scatter, etc.) from SQL results.

Ensures contextually relevant visualization selection.

3️⃣ Insight Generator

Uses LLMs to summarize and explain query results.

Provides trends, comparisons, and predictive insights.

4️⃣ Output Formatter

Formats query results into clean, structured tables.

Standardizes outputs for easy interpretation or export.

5️⃣ Session Memory (RAM-based)

Custom lightweight memory module stores the last n interactions.

Enables context-aware, multi-turn queries in a single session.

6️⃣ FastAPI Backend

Orchestrates the multi-agent pipeline.

Exposes REST APIs for external integrations.

7️⃣ Streamlit Dashboard

User-friendly interactive interface.

Displays charts, tables, and insights dynamically.

8️⃣ CSV Logging & Monitoring

Logs queries, metadata, insights, and token usage.

Useful for optimization, debugging, and cost tracking.

🛠️ Tech Stack

Languages/Frameworks: Python, FastAPI, Streamlit

Agentic AI: Microsoft AutoGen, LangChain

Data & Visualization: Pandas, Plotly

Memory: Custom RAM-based session memory

Databases: Works with any SQL database
