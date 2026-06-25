## Netflix Data Analytics & Content Recommendation System
#### A comprehensive end-to-end data pipeline, analytics suite, and Retrieval-Augmented Generation (RAG) recommendation engine engineered to transform raw streaming dataset insights into interactive intelligence. This production-style system features automated Python ETL workflows, an optimized cloud-hosted relational data warehouse, advanced SQL diagnostic querying, and an embedded AI semantic search architecture.

## ✨ Features
#### 💬 Interactive AI Recommendation Interface
Smooth, conversational semantic search experience driven by context-rich RAG data lookups.

#### 📜 Advanced Content Analytics
Deep platform insights powered by recursive window groupings, CTEs, and cumulative distribution calculations.

#### 📊 Business Performance KPI Simulation
Tracks production statistics, average movie durations, historical top genres, and dynamic catalog growth trends.

#### 🤖 Hybrid Semantic Engine
Leverages persistent vector embeddings to deliver deep metadata matches based on description, title, genre, and cast alignment.

#### 🧠 Context-Aware Inference
Interfaces with generative Large Language Models to structure narrative, personalized explanations behind recommended titles.

## 🛠️ Project Architecture
Ingestion & Data Cleansing
Pulls unstructured metadata via Kagglehub, structures parsing anomalies, drops duplicated contexts, and optimizes text datatypes.

#### Feature Engineering
Extracts temporal structures (years, months, names) and serial duration elements via precise RegEx engines.

#### Relational Storage
Establishes connection pools to an online, serverless Neon PostgreSQL cluster for analytical data partitioning.

#### Statistical Modeling
Executes recursive Common Table Expressions (CTEs), window groupings, aggregations, and cumulative time-lag distributions.

#### AI Hybrid Retrieval (RAG System)
Pools features into a custom semantic metadata context block, embeds titles with HuggingFace Sentence Transformers, registers them into an operational vector space using ChromaDB for persistence, and interfaces with a Generative Large Language Model for smart content generation.

## 📦 Tech Stack
#### Frontend & Dashboards
Power BI Desktop / Data Visualization layers

#### Backend Pipeline
Python 3 (Pandas, NumPy, SQLAlchemy)

#### Relational Database
Neon PostgreSQL (Cloud-native relational warehouse)

#### Vector Store & AI Embedding
ChromaDB / FAISS & HuggingFace sentence-transformers

## ⚙️ Project Setup
#### Prerequisites
Python 3.8 or higher \
Neon PostgreSQL account and access credentials

## Local Environment Setup
Clone the repository to your local system and navigate to the project directory. \
Install the necessary system packages including database connectors (psycopg2-binary, sqlalchemy) and AI dependencies (sentence-transformers, chromadb). \
Set your target database connection credentials securely in your environment parameters. \
Execute the pipeline initialization to load the data warehouse and construct your vector search space.
