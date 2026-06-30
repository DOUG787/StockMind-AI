<div align="center">

# 🧠 StockMind AI

### AI-powered Inventory Intelligence Assistant

Compare inventory spreadsheets, detect business insights and interact with your data using natural language.

<img src="screenshots/home.png" width="900">

</div>

---

## Overview

StockMind AI is an intelligent inventory analysis platform capable of comparing different spreadsheet versions and answering business questions through a conversational interface.

Instead of manually filtering thousands of rows in Excel, users can simply upload two spreadsheets and ask questions such as:

- Which products increased or decreased in stock?
- What are the best sales opportunities?
- Which products are at risk of stock shortage?
- Compare inventory between two periods.
- Show inventory insights.

The project demonstrates how Artificial Intelligence can simplify business decision making using Natural Language Processing and a lightweight neural network implemented from scratch.

---

# Features

### Spreadsheet Comparison

- Upload two Excel files
- Detect changes automatically
- Inventory difference analysis

### AI Assistant

- Natural language chat
- Intent classification
- Business-oriented answers

### Business Intelligence

- Sales opportunities
- Inventory risk detection
- Product ranking
- Inventory insights

### Machine Learning

- Incremental training
- Intent learning
- Feature Hashing
- Multi-Layer Perceptron

---

# Technologies

| Backend | AI | Data |
|----------|----|------|
| Node.js | Neural Network | Excel |
| Express | NLP | XLSX |
| JavaScript | Feature Hashing | JSON |
| REST API | ReLU | Inventory Analysis |

---

# AI Architecture

```
User Question
        │
        ▼
 Tokenization
        │
        ▼
 Feature Hashing
        │
        ▼
 Neural Network (MLP)
        │
        ▼
 Intent Classification
        │
        ▼
 Business Logic
        │
        ▼
 Natural Language Response
```

---

# Neural Network

The intent classifier was implemented from scratch without TensorFlow or other heavy Machine Learning frameworks.

Architecture:

```
Input Layer
      │
      ▼
24 Hidden Neurons (ReLU)
      │
      ▼
Softmax Output
```

Training uses:

- Backpropagation
- Gradient Descent
- Feature Hashing
- Incremental Learning

---

# Example Questions

```
What products decreased in stock?

Show sales opportunities.

Which products require attention?

Compare the last two inventories.

Show inventory risks.
```

---

# Project Structure

```
StockMind-AI/

server.js

intentModel.js

package.json

README.md

screenshots/
```

---

# Installation

```bash
npm install

npm start
```

---

# Future Improvements

- Dashboard
- Charts
- RAG
- LLM Integration
- Docker
- Authentication
- PostgreSQL
- Cloud Deployment

---

# Screenshots

| Home |
|------|
| ![](screenshots/home.png) |

---

# Disclaimer

This repository contains an independent demonstration version created for portfolio purposes.

All datasets, screenshots and examples are fictional and do not contain confidential or proprietary business information.

---

# Author

Douglas Henrique

Backend Developer • AI • Automation • Machine Learning

GitHub:

https://github.com/DOUG787
