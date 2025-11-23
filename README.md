
# Interactive Food Search & RAG Chatbot System

### **Advanced Vector Search • ChromaDB • RAG • CLI Interface • LLM-Powered Food Recommendations**

This project demonstrates how to build a complete **AI-powered food recommendation system** using vector databases, similarity search, and a Retrieval-Augmented Generation (RAG) chatbot.

You will implement **three major components**:

1. **Interactive CLI Food Search Interface**
2. **Advanced Metadata Filtering System**
3. **RAG Chatbot using ChromaDB + LLM**

The system uses a rich food dataset containing **nutritional values, ingredients, cooking methods, and taste profiles** to perform intelligent real-time recommendations.

---

## Features

### **1. Interactive CLI Search**

* Real-time text-based food search
* Displays top similar food items
* Allows step-by-step selection and navigation
* No web framework required – works directly in the terminal

### **2. Advanced Metadata Filtering**

* Filter foods by:

  * Cuisine type
  * Calorie limits
  * Ingredient match (include/exclude)
* Dynamic result filtering with vector similarity
* CRUD operations (Create, Read, Update, Delete) on ChromaDB

### **3. RAG (Retrieval-Augmented Generation) Chatbot**

* Uses vector embeddings + LLM to recommend dishes
* Understands natural-language questions such as:

  > “Recommend a high-protein breakfast under 300 calories.”
* Retrieves relevant foods from database
* Generates conversational responses

---

## **Technologies Used**

| Component       | Technology                                 |
| --------------- | ------------------------------------------ |
| Vector Database | **ChromaDB**                               |
| Embeddings      | **Sentence Transformers / LLM Embeddings** |
| Chatbot         | **RAG (LLM + Vector Search)**              |
| Interface       | **Python CLI**                             |
| Data Processing | **Pandas, JSON, Metadata Filters**         |

---

## Example Queries

### **CLI Search**

```
Enter food name: pasta
Top 5 similar foods:
1. Spaghetti
2. Fettuccine Alfredo
3. Macaroni
...
```

### **RAG Chatbot**

User:

> “Suggest something sweet and low calorie.”

Chatbot:

> “You can try **Greek yogurt with honey**. It has a sweet flavor profile, low calories, and high protein…”

---

## Key Concepts Demonstrated

### **Similarity Search Techniques**

* Vector embeddings
* Cosine similarity
* Metadata-based filtering

### **RAG Concepts**

* Retriever + Generator
* Improved LLM responses using context
* Answering food-related natural language queries

### **Database Operations**

* Add new food items
* Update nutritional metadata
* Delete or modify records
* Re-run similarity search instantly

---

## Final-Outcome

A **complete, production-style AI system** that integrates:

* Search engine
* Recommendation engine
* Conversational RAG chatbot
* Vector database indexing
* Advanced filtering logic
