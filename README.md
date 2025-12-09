# INCO9X1: Introduction to Coding for Data Science

<div align="center">

**University of Johannesburg**
**Faculty of Economic and Financial Sciences**
**Master of Financial Engineering Programme**

---

</div>

## Course Information

**Course Code:** INCO9X1
**Course Title:** Introduction to Coding for Data Science
**Institution:** University of Johannesburg
**Programme:** Master of Financial Engineering (MFE)
**Schedule:** Saturdays, 13h00 – 21h00 (South African Time)

### Instructor

**Dr. John Weirstrass Muteba Mwamba**
- **Email:** johnmu@uj.ac.za | jwmm@yorku.ca
- **Office Phone:** +27 11 559 4371 (UJ Office)
- **Direct Line/WhatsApp:** +1 289 237 0366
- **Office Hours:** By appointment

---

## Table of Contents

- [Course Description](#course-description)
- [Course Objectives](#course-objectives)
- [Course Structure](#course-structure)
- [Repository Organization](#repository-organization)
- [Installation Guide](#installation-guide)
- [Recommended Readings](#recommended-readings)
- [Research Opportunities](#research-opportunities)
- [Academic Integrity](#academic-integrity)
- [Contact Information](#contact-information)

---

## Course Description

In the dynamic landscape of financial engineering, the surge in demand for programming expertise, particularly in Python, R, and SQL, reflects the industry's adaptation to managing and visualizing vast amounts of big data. This course caters specifically to Master of Financial Engineering students at the University of Johannesburg, equipping them with coding skills essential for modern financial engineering applications.

The curriculum delves into fundamental programming principles tailored to data science applications, encompassing:

- **Data Manipulation**: Working with structured and unstructured data
- **Visualization**: Creating insightful graphical representations
- **Database Management**: SQL and NoSQL technologies
- **Text Analytics**: Natural Language Processing for financial texts
- **Machine Learning**: Predictive modeling and classification
- **Deep Learning**: Neural networks and advanced architectures

Recognizing the transformative role of technology in reshaping financial markets, this course emphasizes that traditional numerical data alone may prove insufficient in capturing the intricate dynamics and sentiments at play. By integrating text data sources such as financial reports and social media discourse, students learn to embrace qualitative insights for more robust financial modeling and risk management strategies.

The incorporation of text data not only enhances model accuracy but also empowers financial professionals to navigate the complexities of today's financial landscape with greater precision and agility. For students in financial engineering, leveraging text data in their research endeavors holds the promise of driving innovative and impactful contributions to the field.

---

## Course Objectives

Upon completing this course, students will proficiently:

1. **Import data** into Python and R environments
2. **Code text data** for natural language processing applications
3. **Demonstrate adept coding skills** in Python and R languages
4. **Transform raw data** into relational databases like SQL
5. **Convert textual data** into non-relational databases (NoSQL, Hadoop, Apache, MongoDB)
6. **Acquire foundational knowledge** in Python programming within the context of data science
7. **Manage and visualize** large datasets effectively
8. **Apply computational thinking** across various financial engineering domains to innovate new financial products
9. **Master cutting-edge tools** such as Large Language Models, Fine-tuning, Unstructured data manipulation
10. **Effectively communicate** data analysis findings to stakeholders and collaborate with peers in the Data Science industry

---

## Course Structure

### Part I: Introduction to Coding with Python

**Main Text:** April Speight (2020) "Bite-size Python: An Introduction to Python Programming"

| Week | Topics | Coverage |
|------|--------|----------|
| **Week 1** | Introduction to Python | Variables, Lists, Tuples, Strings and their methods (Chapters 1-8) |
| **Week 2** | Functions and Loops | Functions, Loops, Iterations, Python Modules (Chapters 9-14) |
| **Week 3** | Data Preprocessing | Python Pipelines, Database Building with MySQL |

### Part II: Python Data Science Applications

**Main Texts:** Patrick Rafail and Isaac Freitas (2020) "Natural Language Processing" + Various Academic Papers

| Week | Topics | Focus Areas |
|------|--------|-------------|
| **Week 4** | Machine Learning | Recap on ML and Unsupervised Learning (Clustering with K-Means) |
| **Week 5** | Natural Language Processing | Text Vectorization, Topic Modelling with LSA and LDA |
| **Week 6** | Word Embeddings | Word2Vec, Feature Extraction, Sentiment Prediction |
| **Week 7** | Deep Learning Foundations | Artificial Neural Network, Multi-layer Perceptron, Sequential Models |
| **Week 8** | Advanced Neural Networks I | Convolutional Neural Network (CNN), Recurrent Neural Network (RNN) |
| **Week 9** | Advanced Neural Networks II | Generative Adversarial Networks (GAN), Transformer Network Models |
| **Week 10** | Generative AI | GPT, Large Language Models, Fine-tuning, RAG, Automated Agents |

For detailed weekly content, see [COURSE_OUTLINE.md](./COURSE_OUTLINE.md)

---

## Repository Organization

This repository contains all course materials organized by week:

```
UJ--Introduction-to-Coding/
│
├── Week 1- Intro to Python List Tuples Ops/
├── Week 2 - Functions Loops Iterations Modules/
├── Week 3 - Data Preprocessing and Database Building/
├── Week 4 - Recap on ML Algos and Unsupervised Learning -Clustering K-Means/
├── Week 5 - Natural Langua Processing -Text Vect & Topic Modelling/
├── Week 6 - Word Embedding/
├── Week 7 - Deep Learning ANN & MLP on Keras and TensorFlow/
├── Week 8 - Advanced Neural Networks  CNN RNN Bayesian-Networks/
├── Week 9 - Advanced Neural Networks - GAN Transformers/
├── Week 10 Generative Pretrained Transformers - LLMs & RAG/
│
├── COURSE_DESCRIPTION.md
├── COURSE_OUTLINE.md
├── INSTALLATION_GUIDE.md
├── PROJECT_TOPICS.md
├── RECOMMENDED_READINGS.md
├── RESEARCH_OPPORTUNITIES.md
├── README.md
└── LICENSE
```

---

## Installation Guide

### Python Installation via Anaconda (Recommended)

Python stands out as a potent, adaptable, and easily grasped programming language, renowned for its applicability across diverse domains such as Econometrics, Mathematics, Statistics, Engineering, Big Data analytics, and Data Science.

**Installation Steps:**

1. Visit [https://www.anaconda.com/](https://www.anaconda.com/)
2. Click on "Free Download"
3. Select the appropriate package for your operating system
4. Python and all required modules will automatically be installed
5. Launch Python through:
   - Anaconda Navigator
   - Anaconda Prompt
   - IDEs: Spyder, PyCharm, Jupyter Notebook

**Note:** Python 2.x is obsolete. This course uses **Python 3.12+**

For detailed installation instructions, see [INSTALLATION_GUIDE.md](./INSTALLATION_GUIDE.md)

---

## Recommended Readings

### Core Textbooks

1. **Speight, A.** (2020). *Bite-size Python: An Introduction to Python Programming*. Wiley. ISBN: 978-1-119-64381-4

2. **McKinney, W.** (2017). *Python for Data Analysis*, 2nd edition. O'Reilly Media.

3. **Nelli, F.** (2015). *Python Data Analytics - Data Analysis and Science Using Pandas, Matplotlib, and the Python Programming Language*. Apress. ISBN: 978-1-4842-0959-2

4. **Rafail, P. & Freitas, I.** (2020). *Natural Language Processing*. Online ISBN: 9781529749120

5. **Sundnes, J.** (2020). *Introduction to Scientific Programming with Python*. Simula Springer Briefs on Computing. ISBN: 978-3-030-50356-7

6. **Ramakrishnan, R. & Gehrke, J.** (2002). *Database Management Systems*, 3rd edition. McGraw Hill.

For complete bibliography, see [RECOMMENDED_READINGS.md](./RECOMMENDED_READINGS.md)

---

## Research Opportunities

### Data Science Projects 2026

Students undertake comprehensive data science projects addressing topical issues in South Africa, including:

- Interest Rates and Stock Market Volatility
- Impact of Inflation on Insurance Premiums
- Public Sentiment on Elections
- Climate Risk Analysis for Insurance
- Bayesian Network Analysis for Stock Market Dependencies
- Derivative Pricing and Hedging
- Insurance Claims Fraud Detection

**Full project descriptions available in:** [PROJECT_TOPICS.md](./PROJECT_TOPICS.md)

### Dissertation Topics

This course provides foundation for various dissertation topics:

- Stock market predictions using advanced neural networks
- Fraud detection in financial statements
- Portfolio optimization with sentiment analysis
- Credit risk assessment with text data
- Event-driven investing strategies
- News sentiment analysis and market impact
- Social media analytics for stock prediction

**Full list available in:** [RESEARCH_OPPORTUNITIES.md](./RESEARCH_OPPORTUNITIES.md)

---

## Academic Integrity

### Use of Generative AI

The use of Generative AI tools (e.g., ChatGPT, Claude, GitHub Copilot) is **permitted** in this course; however:

- **Disclosure is MANDATORY**: You must explicitly acknowledge any use of Generative AI in your work
- **Failure to disclose** will result in disqualification and a grade of **0** for the assignment
- Document how AI was used (ideation, debugging, code generation, etc.)

This policy ensures transparency while embracing modern tools in data science education.

---

## Tools and Technologies

### Programming Languages
- Python 3.12+
- R
- SQL (MySQL)

### Development Environments
- Jupyter Notebook
- Spyder
- PyCharm
- Anaconda Navigator

### Key Libraries
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`, `plotly`
- **Machine Learning:** `scikit-learn`
- **Natural Language Processing:** `nltk`, `spacy`, `gensim`
- **Deep Learning:** `tensorflow`, `keras`, `pytorch`
- **Database:** `sqlalchemy`, `pymongo`

### Database Technologies
- SQL: MySQL
- NoSQL: MongoDB, Hadoop, Apache

---

## Contact Information

### Instructor

**Dr. John Weirstrass Muteba Mwamba**

- **Email:** johnmu@uj.ac.za | jwmm@yorku.ac.za
- **Office:** University of Johannesburg
- **Phone:** +27 11 559 4371 (Office)
- **WhatsApp/Direct:** +1 289 237 0366

### University Information

**University of Johannesburg**
Faculty of Economic and Financial Sciences
Master of Financial Engineering Programme

---

## License

This repository is maintained for academic purposes at the University of Johannesburg. Materials are provided for educational use by enrolled students and researchers.

See [LICENSE](./LICENSE) for more information.

---

<div align="center">

**University of Johannesburg**
*Inspiring Excellence in Financial Engineering Education*

© 2025 University of Johannesburg. All Rights Reserved.

</div>
