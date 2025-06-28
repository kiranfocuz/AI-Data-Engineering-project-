# 🧠 Product Sentiment Pipeline – ETL + Analytics + ML Search

## 🎯 Objective
Build a complete pipeline that ingests product reviews, transforms them using Talend, loads to multiple databases, performs ML sentiment classification, and enables semantic search with pgvector & Go REST API.

## 🛠️ Stack
- Talend Cloud
- Python (scikit-learn, pandas)
- PostgreSQL 17 + pgvector
- MSSQL, Oracle (via Talend)
- Go (REST API)

## 📁 Structure
- `data/`: CSV input
- `ml/`: ML pipeline
- `api/`: REST API in Go
- `sql/`: DB setup
- `etl/`: Talend job (upload your export)

## 🚀 How to Use

### Python
```bash
cd ml
pip install pandas scikit-learn pgvector psycopg2
python sentiment_pipeline.py
```

### PostgreSQL
```sql
CREATE EXTENSION IF NOT EXISTS vector;
-- Run schema_postgres.sql
```

### Go API
```bash
cd api
go run main.go
```

## 👤 Author
Kiran  
🔗 [GitHub](https://github.com/kiranfocuz)
