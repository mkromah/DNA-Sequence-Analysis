# 🧬 DNA Sequence Analysis – Final Exam Project

> **Course:** [Python for Genomic Data Science](https://www.coursera.org/learn/python-genomics)
> **Institution:** Johns Hopkins University & Coursera

---

## 📖 Project Description

This repository contains a Python-based analytical pipeline developed for the **final exam** of a bioinformatics course focused on genomic data processing using Python. The program parses a multi-FASTA file, performs key biological analyses such as open reading frame (ORF) detection and repeat identification, and provides structured responses to biological questions.

This activity demonstrates a comprehensive understanding of:

* Nucleotide sequence parsing
* ORF logic and biological reading frames
* Motif/repeat detection using sliding windows
* Efficient data structures and control flow in Python

---

## 📊 Project Objectives

The program answers 10 exam-style questions on genomic features derived from real DNA sequences in a multi-FASTA file (`dna2.fasta`). These include:

1. Total number of sequences
2. Longest and shortest sequence lengths
3. ORF detection across all three forward reading frames
4. Repeat analysis for motifs of various lengths
5. Specific query-based searches using identifiers

---

## ✅ Final Exam Answers

| #  | Topic                                                                     | Answer    |    |            |      |           |
| -- | ------------------------------------------------------------------------- | --------- | -- | ---------- | ---- | --------- |
| 1  | Total number of FASTA records                                             | `18`      |    |            |      |           |
| 2  | Longest sequence length                                                   | `4894`    |    |            |      |           |
| 3  | Shortest sequence length                                                  | `115`     |    |            |      |           |
| 4  | Longest ORF in reading frame 2                                            | `1458 bp` |    |            |      |           |
| 5  | Start position of the longest ORF in reading frame 3                      | `636`     |    |            |      |           |
| 6  | Longest ORF across all forward reading frames                             | `2394 bp` |    |            |      |           |
| 7  | Longest ORF in sequence \`gi                                              | 142022655 | gb | EQ086233.1 | 16\` | `1644 bp` |
| 8  | Most frequent repeat (6-mer) count                                        | `194`     |    |            |      |           |
| 9  | Number of distinct 12-mer sequences occurring the maximum number of times | `5`       |    |            |      |           |
| 10 | Most frequent 7-mer among listed options                                  | `GCGCGCA` |    |            |      |           |

---

## 🛠 Technologies & Skills Demonstrated

### 🔬 Bioinformatics Skills

* Parsing and processing **FASTA-formatted** sequence data
* **Open Reading Frame (ORF)** detection using biological reading frames
* **Motif discovery** and repeat quantification
* Biological indexing and start/stop codon handling

### 💻 Programming Skills

* Python scripting from scratch
* Use of `collections`, `pathlib`, and string manipulation
* Sliding window techniques for repeat detection
* 1-based biological indexing vs 0-based Python indexing
* Clean modular code structure with reusable functions

---

## 📁 Project Structure

```
📦 DNA-Sequence-Analysis
├── dna2.fasta            # Input FASTA file (exam dataset)
├── dna_analysis.py       # Main script with all functions and logic
└── README.md             # Project documentation
```

---

## 🚀 How to Run

### Requirements

* Python 3.7 or higher
* No external libraries required

### Usage

```bash
python dna_analysis.py
```

Make sure `dna2.fasta` is located in the same directory as the script.

---

## 🧠 Learning Outcomes

This project represents a capstone for understanding core **Python bioinformatics principles**, including:

* Translating biological requirements into algorithmic logic
* Efficiently traversing DNA sequences for meaningful features
* Handling biological sequence complexity through scripting
* Applying foundational programming tools in genomic contexts

---

## 📜 Course Credit

This project was completed as part of:

### 📘 [Python for Genomic Data Science](https://www.coursera.org/learn/python-genomics)

* 💼 Offered by: Johns Hopkins University
* 🧑‍🏫 Instructor: Dr. Jeff Leek
* 🧠 Skills Gained:

  * Python Programming & Scripting
  * Bioinformatics Workflows
  * Data Structures & File Parsing
  * ORF & Motif Analysis
  * Jupyter Notebooks & Scripting Languages

---

## 📝 License

This project is academic in nature and was developed for educational purposes.
Please use it for reference or learning with proper attribution.

---

## 🙌 Acknowledgments

Special thanks to the instructors of **Johns Hopkins University and the Coursera Team** for creating a structured and highly practical course in Python for Genomic Data Science.

