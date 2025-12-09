# INCO9X1: Introduction to Coding for Data Science

<div align="center">

****U.J.|M.F.E. Programme**

---

</div>

## Course Information

**Course Code:** INCO9X1
**Course Title:** Introduction to Coding for Data Science

**Institution:** U.J.

**Programme:** MFE

**Schedule:** Saturdays, 13h00 – 21h00 (South African Time)

### Instructor

**Prof. John Weirstrass Muteba Mwamba**
- **Email:** johnmu@uj.ac.za | jwmm@yorku.ca
- **Office Phone:** +27 11 559 4371 (UJ Office)
- **Direct Line/WhatsApp:** +1 289 237 0366
- **Office Hours:** By appointment

#### Academic Profiles
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/YOUR-ORCID-ID)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=HmVumxMAAAAJ&hl=en)

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

### 📚 Course Materials by Week

This repository contains all course materials organized with easy access to slides, code, and datasets for each week:

| Week | Topic | 📊 Slides | 💻 Code/Notebooks | 📁 Data |
|:----:|-------|-----------|-------------------|---------|
| **1** | **Intro to Python: Lists, Tuples, Operators** | [Week1.ppt](./Week%201-%20Intro%20to%20Python%20List%20Tuples%20Ops/Week1.ppt) | - | - |
| **2** | **Functions, Loops, Iterations & Modules** | [Functions Loops and Iterations.pptx](./Week%202%20-%20Functions%20Loops%20Iterations%20Modules/Functions%20Loops%20and%20Iterations.pptx)<br>[Python MODULES for Data Analysis.pptx](./Week%202%20-%20Functions%20Loops%20Iterations%20Modules/Python%20MODULES%20for-Data-Analysis.pptx) | [Intro to Python Weeks 1-3.ipynb](./Week%202%20-%20Functions%20Loops%20Iterations%20Modules/2025_WEEK%201%20to%203%20-%20INTRODUCTION%20TO%20PYTHON%20FOR%20DATA%20SCIENCE.ipynb) | [Salaries.csv](./Week%202%20-%20Functions%20Loops%20Iterations%20Modules/Salaries.csv)<br>[flights.csv](./Week%202%20-%20Functions%20Loops%20Iterations%20Modules/flights.csv) |
| **3** | **Data Preprocessing & Database Building** | [Databases SQL & NoSQL.pptx](./Week%203%20-%20Data%20Preprocessing%20and%20Database%20Building/SESSION%205_DATABASES_SQL_NoSQL.pptx) | [Data Preprocessing & Modelling.ipynb](./Week%203%20-%20Data%20Preprocessing%20and%20Database%20Building/2025__WEEK4SLIDES_DATA_PREPROCESSING_SPLIT_MODELLING_STEPS.ipynb)<br>[MySQL with Python & Pandas.ipynb](./Week%203%20-%20Data%20Preprocessing%20and%20Database%20Building/Week%205-CREATE_MySQL_Table_within_Python_call_it_in_Pandas_DataFrame.ipynb) | - |
| **4** | **ML Algorithms & Unsupervised Learning** | - | [Random Forest Classification.ipynb](./Week%204%20-%20Recap%20on%20ML%20Algos%20and%20Unsupervised%20Learning%20-Clustering%20K-Means/RANDOM-FOREST-CLASSIFICATION.ipynb)<br>[Random Forest Regression.ipynb](./Week%204%20-%20Recap%20on%20ML%20Algos%20and%20Unsupervised%20Learning%20-Clustering%20K-Means/RANDOM-FOREST-REGRESSION.ipynb)<br>[Ridge Regression.ipynb](./Week%204%20-%20Recap%20on%20ML%20Algos%20and%20Unsupervised%20Learning%20-Clustering%20K-Means/RIDE-REGRESSION.ipynb)<br>[Unsupervised Learning in Finance.ipynb](./Week%204%20-%20Recap%20on%20ML%20Algos%20and%20Unsupervised%20Learning%20-Clustering%20K-Means/UNSUPERVISED_LEARNING_ALGOS_and_APPLICATIONSinFINANCE.ipynb) | - |
| **5** | **NLP: Text Vectorization & Topic Modelling** | - | [NLP Text Data Analysis.ipynb](./Week%205%20-%20Natural%20Langua%20Processing%20-Text%20Vect%20%26%20Topic%20Modelling/NLP_TextData_Analysis.ipynb) | - |
| **6** | **Word Embedding** | [Word Embeddings.pptx](./Week%206%20-%20Word%20Embedding/Word-embeddings.pptx) | [Word Embeddings Slides.ipynb](./Week%206%20-%20Word%20Embedding/Slides_WORD_EMBEDDINGS.ipynb) | - |
| **7** | **Deep Learning: ANN & MLP (Keras/TensorFlow)** | [Deep Learning KERAS on TensorFlow.pptx](./Week%207%20-%20Deep%20Learning%20ANN%20%26%20MLP%20on%20Keras%20and%20TensorFlow/DL%20ERAS%20ON%20TENSORFLOW.pptx) | [DL with Google News - Regression & Classification (1).ipynb](./Week%207%20-%20Deep%20Learning%20ANN%20%26%20MLP%20on%20Keras%20and%20TensorFlow/AI__DLwithGoogleNewsData_KERAS_Regression_Classification%20(1).ipynb)<br>[DL with Google News - Regression & Classification (2).ipynb](./Week%207%20-%20Deep%20Learning%20ANN%20%26%20MLP%20on%20Keras%20and%20TensorFlow/AI__DLwithGoogleNewsData_KERAS_Regression_Classification%20(2).ipynb)<br>[Multiclass DL with MNIST.ipynb](./Week%207%20-%20Deep%20Learning%20ANN%20%26%20MLP%20on%20Keras%20and%20TensorFlow/AI__MULTICLASS_Deep_LearningWithMNISTdataKERAS.ipynb)<br>[DL KERAS.ipynb](./Week%207%20-%20Deep%20Learning%20ANN%20%26%20MLP%20on%20Keras%20and%20TensorFlow/DL_KERAS.ipynb) | - |
| **8** | **Advanced Neural Networks: CNN & RNN** | [CNN & RNN Models.pptx](./Week%208%20-%20Advanced%20Neural%20Networks%20%20CNN%20RNN%20Bayesian-Networks/CNN%20%26%20RNN%20Models-.pptx) | [CNN with MNIST.ipynb](./Week%208%20-%20Advanced%20Neural%20Networks%20%20CNN%20RNN%20Bayesian-Networks/AI__CNN_MNISTdata_Keras.ipynb)<br>[LSTM Stock Price Prediction.ipynb](./Week%208%20-%20Advanced%20Neural%20Networks%20%20CNN%20RNN%20Bayesian-Networks/LSTM%20for%20predicting%20stock%20prices.ipynb)<br>[RNN-LSTM Stock Market Prediction.ipynb](./Week%208%20-%20Advanced%20Neural%20Networks%20%20CNN%20RNN%20Bayesian-Networks/RNN-LSTM%20for%20regression%20and%20Classification-%20stock%20market%20prediction.ipynb)<br>[RNN Template.ipynb](./Week%208%20-%20Advanced%20Neural%20Networks%20%20CNN%20RNN%20Bayesian-Networks/RNN_%20just%20add%20data%20link.ipynb) | - |
| **9** | **Advanced Neural Networks: GAN & Transformers** | [GAN Network Model.pptx](./Week%209%20-%20Advanced%20Neural%20Networks%20-%20GAN%20Transformers/GAN%20Network%20Model.pptx)<br>[TRANSFORMERS NETWORK.pptx](./Week%209%20-%20Advanced%20Neural%20Networks%20-%20GAN%20Transformers/TRANSFORMERS%20NETWORK.pptx) | - | - |
| **10** | **Generative AI: LLMs & RAG** | [Large Language Models.pptx](./Week%2010%20Generative%20Pretrained%20Transformers%20-%20LLMs%20%26%20RAG/Large%20Language%20Models.pptx) | - | [Getting Started with Ollama.docx](./Week%2010%20Generative%20Pretrained%20Transformers%20-%20LLMs%20%26%20RAG/Getting%20Started%20with%20Ollama.docx) |

### 📖 Additional Resources

| Resource | Description |
|----------|-------------|
| [**COURSE_DESCRIPTION.md**](./COURSE_DESCRIPTION.md) | Detailed course description and learning outcomes |
| [**COURSE_OUTLINE.md**](./COURSE_OUTLINE.md) | Complete weekly syllabus and schedule |
| [**INSTALLATION_GUIDE.md**](./INSTALLATION_GUIDE.md) | Setup instructions for Python, R, and required tools |
| [**PROJECT_TOPICS.md**](./PROJECT_TOPICS.md) | Data science project topics for 2026 |
| [**RECOMMENDED_READINGS.md**](./RECOMMENDED_READINGS.md) | Textbooks, papers, and supplementary materials |
| [**RESEARCH_OPPORTUNITIES.md**](./RESEARCH_OPPORTUNITIES.md) | Dissertation topics and research directions |

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

**Prof. John Weirstrass Muteba Mwamba**
- **Email:** johnmu@uj.ac.za | jwmm@yorku.ac.za
- **Phone:** +27 11 559 4371 (Office)
- **WhatsApp/Direct:** +1 289 237 0366

#### Academic Profiles
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/YOUR-ORCID-ID)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=HmVumxMAAAAJ&hl=en)

---

## License

This repository is maintained for academic purposes by Dr John Weirstrass Muteba Mwamba. Materials are provided for educational use by students and researchers.

See [LICENSE](./LICENSE) for more information.

---

<div align="center">

**John Weirstrass MUTEBA MWAMBA Ph.D.**

*Inspiring Excellence in Financial Engineering Education*

© 2025 Analytics Research Group. All Rights Reserved.

</div>
