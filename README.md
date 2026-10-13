<div align="center">

# 📚 Big Data MCQ Practice Set

### 89 Solved Questions for NPTEL / SWAYAM Exam Preparation

Clean, to-the-point MCQs with the correct answer written right below each question. No long explanations, just fast revision.

![Questions](https://img.shields.io/badge/Questions-89-blue?style=for-the-badge)
![Topics](https://img.shields.io/badge/Topics-9-green?style=for-the-badge)
![Format](https://img.shields.io/badge/Format-PDF-red?style=for-the-badge)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge)

[📥 Download PDF](./Big_Data_MCQs.pdf) • [🗂️ Topics](#-topics-covered) • [🚀 How to Use](#-how-to-use) • [🤝 Contribute](#-contributing)

</div>

---

## 📖 About

Preparing for the **NPTEL / SWAYAM Big Data exam**? This repository has a ready-made practice set covering the core topics: Hadoop, Spark, Cassandra, ZooKeeper, machine learning and graph processing.

Every question is in the same simple format:

```
12. Which of the following statements about Oozie is CORRECT?
    A. Oozie is a distributed NoSQL database.
    B. Oozie is a workflow scheduler system for Hadoop jobs.
    C. Oozie is used to store data in HDFS.
    D. Oozie is a machine learning library for Spark.

    Answer: B. Oozie is a workflow scheduler system for Hadoop jobs.
```

Duplicate questions have been removed, so every question you practise is a new one.

---

## 🗂️ Topics Covered

| # | Topic | Questions | Q. No. |
|:-:|-------|:---------:|:------:|
| 1 | HDFS and MapReduce | 10 | 1 – 10 |
| 2 | Hadoop Ecosystem and the Vs of Big Data | 9 | 11 – 19 |
| 3 | Big Data Fundamentals | 10 | 20 – 29 |
| 4 | Cassandra and ZooKeeper | 10 | 30 – 39 |
| 5 | Apache Spark and RDDs | 10 | 40 – 49 |
| 6 | Ensemble Learning (Random Forest and Boosting) | 10 | 50 – 59 |
| 7 | Spark Streaming | 10 | 60 – 69 |
| 8 | Cluster Analysis and K-Means | 10 | 70 – 79 |
| 9 | GraphX | 10 | 80 – 89 |
| | **Total** | **89** | |

---

## 🚀 How to Use

1. **Download** [`Big_Data_MCQs.pdf`](./Big_Data_MCQs.pdf) from this repository.
2. **Attempt first**: cover the green answer line and try each question yourself.
3. **Check** your answer against the one written below the question.
4. **Note** the questions you got wrong and revise those topics again.
5. **Repeat** the full set a day or two before the exam.

> 💡 **Tip:** Practise topic by topic first, then take all 89 questions in one sitting to check your speed and accuracy.

---

## 🧠 Quick Revision Points

A few high-yield facts that come up again and again in these questions:

| Topic | Remember this |
|-------|---------------|
| NameNode | Stores HDFS metadata and monitors replication |
| DataNode | Stores the actual data blocks |
| `dfs.replication` | Default value is **3** |
| HDFS Federation | Improves **namespace scalability** |
| Partitioner | Decides which Reducer gets a key-value pair |
| YARN Application Master | Detects task failures for its job |
| Oozie | Workflow scheduler for Hadoop jobs |
| Flume | Collects and moves log data |
| ZooKeeper | Coordination, synchronization and leader election |
| Hive | Data warehouse on Hadoop, queried with HiveQL |
| Cassandra (CAP) | **AP** system (Availability + Partition Tolerance) |
| Bloom Filter | Can give false positives, **never** false negatives |
| Spark fault tolerance | Achieved through **lineage** |
| Spark Action vs Transformation | `collect()`, `count()` are actions; `map()`, `filter()`, `join()` are transformations |
| DAGScheduler / TaskScheduler | DAGScheduler makes stages; TaskScheduler launches and retries tasks |
| `reduceByKey()` | Better than `groupByKey()` because of map-side combining |
| Spark Streaming | Micro-batch model, abstraction is **DStream** |
| Bagging | Reduces variance |
| Boosting | Combines weak learners into a strong one |
| K-Means | Unsupervised, evaluated using WSS |
| GraphX | Unifies data-parallel and graph-parallel analytics |

---

## 📁 Repository Structure

```
.
├── Big_Data_MCQs.pdf   # Complete question set with answers
└── README.md           # You are here
```

---

## 🤝 Contributing

Found a wrong answer, a typo, or want to add more questions? Contributions are welcome.

1. **Fork** this repository
2. **Create** a branch: `git checkout -b fix/question-number`
3. **Commit** your changes: `git commit -m "Fix answer for Q23"`
4. **Push** the branch: `git push origin fix/question-number`
5. **Open** a Pull Request

You can also open an **Issue** if you think any answer needs to be double-checked.

---

## ⚠️ Disclaimer

This is an **unofficial**, student-made practice resource. It is not affiliated with or endorsed by NPTEL, SWAYAM or any institute. Questions are for practice only and may not match your actual exam. Always cross-check answers with your course lectures and official material.

---

## ⭐ Support

If this helped you, please **star the repository** and share it with your friends preparing for the same exam. It helps others find it too.

<div align="center">

**All the best for your exam! 🎯**

Made with ❤️ for students preparing for NPTEL / SWAYAM

</div>
