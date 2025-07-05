# 🚀 Apache Spark - Complete Presentation

## 💡 What is Apache Spark?

Apache Spark is an open-source distributed data processing engine designed for big data workloads.  
It enables fast computation through **in-memory execution** and supports a variety of workloads, including:

- Batch processing
- Streaming
- Machine learning
- Graph processing

---

## 🧱 Architecture

Spark consists of several key components:

- **Driver**: orchestrates execution, transforms code into tasks
- **Executors**: run the tasks on cluster nodes
- **Cluster Manager**: manages resources (YARN, Kubernetes, or Standalone)
- **DAG Scheduler**: builds an optimized Directed Acyclic Graph of stages and tasks

---

## 🔗 Integration with Hadoop

Spark does **not require Hadoop**, but can integrate with it:

- **HDFS**: Spark can read/write data stored in Hadoop Distributed File System
- **YARN**: Spark can run on Hadoop YARN to manage cluster resources
- Spark often **replaces Hadoop MapReduce** as a faster, in-memory processing alternative

---

## 🧠 Core Components

- **Spark Core**: the base execution engine
- **Spark SQL**: for querying structured data using SQL or DataFrame API
- **Spark Streaming**: for real-time processing
- **MLlib**: for distributed machine learning
- **GraphX**: for graph processing and graph algorithms

---

## 🔄 Available APIs

### RDD (Resilient Distributed Dataset)

- Low-level abstraction
- Immutable collections of distributed objects
- Functional-style operations like `map`, `filter`, `reduce`

### DataFrame

- Higher-level API with schema
- Optimized via Catalyst optimizer
- Supports SQL queries

### Dataset

- Strongly-typed version of DataFrame (Scala/Java only)
- Combines benefits of RDD (type-safety) and DataFrame (performance)

---

## ⚡ Advantages of Spark

- **In-memory computation** leads to high speed
- Unified ecosystem: batch, streaming, SQL, ML, graph
- Scalable across clusters with thousands of nodes
- Integrates with many data sources: HDFS, S3, Hive, Cassandra, JDBC, etc.

---

## ❓ Typical Interview Questions

- What is the difference between RDD and DataFrame?
- What does the Spark Driver do?
- What is a DAG in Spark?
- Can Spark run without Hadoop?
- What’s the difference between Spark SQL and Spark Streaming?
