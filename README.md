# Lab: Similarity Retrieval with Metadata Filtering

This repository contains a specialized data engineering and vector search laboratory project focused on refining similarity matching routines by applying hard constraints via structural metadata filters.

## 🎯 Project Objective

The goal of this lab is to practice advanced information retrieval tactics within vector database ecosystems. The project demonstrates how to combine semantic similarity searches (using vector distance parameters) with structural metadata attributes (such as dates, tags, or categories) to restrict query search paths and yield highly accurate, context-filtered results.

## 📁 Repository Structure

* **`M2L2_Lab.ipynb`**: The primary interactive Jupyter Notebook orchestrating the database collection logic, metadata payload assignment, embedding population, and execution of filtered similarity query pipelines.

## 🛠 Technologies Used

* **Language Core:** Python 3.x
* **Core Environment:** Jupyter Notebooks
* **Vector Store & Pipelines:** Vector Database Engines (e.g., Chroma DB, FAISS, or LangChain vector components)
* **Mathematical Operations:** NumPy, Scikit-learn (or platform-specific similarity algorithms)

## 🚀 Installation and Execution

### Local Environment Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Lab-Similarity-Retrieval-with-Metadata-Filtering
   ```

2. **Install required machine learning packages:**
   Ensure your local execution workspace contains the vector index and data manipulation libraries:
   ```bash
   pip install notebook transformers torch numpy chromadb
   ```

3. **Launch the development environment:**
   ```bash
   jupyter notebook
   ```

4. **Run the data pipeline:**
   Open `M2L2_Lab.ipynb` inside your notebook dashboard workspace and run the execution blocks sequentially.

## 📈 Demonstrated Skills

* **Hybrid Vector Querying:** Engineering advanced retrieval operations that integrate similarity calculations with scalar parameter filters to refine large-scale dataset extraction.
* **Metadata Schema Structural Design:** Structuring rich metadata payloads alongside text embeddings to enable deep, flexible search capabilities within unstructured datasets.
* **Vector Database Resource Optimization:** Implementing efficient filtering patterns to decrease computation latencies during deep query scans.
