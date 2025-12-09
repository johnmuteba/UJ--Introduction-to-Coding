# Installation Guide

## Python Setup for INCO9X1: Introduction to Coding for Data Science

### University of Johannesburg | Master of Financial Engineering Programme

---

## Table of Contents

1. [About Python](#about-python)
2. [Python Versions](#python-versions)
3. [Installation Methods](#installation-methods)
4. [Recommended: Anaconda Installation](#recommended-anaconda-installation)
5. [Alternative: Direct Python Installation](#alternative-direct-python-installation)
6. [Integrated Development Environments (IDEs)](#integrated-development-environments-ides)
7. [Essential Libraries](#essential-libraries)
8. [Verification](#verification)
9. [Troubleshooting](#troubleshooting)

---

## About Python

Python stands out as a potent, adaptable, and easily grasped programming language, renowned for its applicability across diverse domains such as:

- **Econometrics**: Time series analysis, econometric modeling
- **Mathematics**: Numerical computing, symbolic mathematics
- **Statistics**: Statistical analysis, hypothesis testing
- **Engineering**: Scientific computing, simulation
- **Big Data Analytics**: Processing large-scale datasets
- **Data Science**: Machine learning, predictive modeling

According to Dasgupta (2013), Python (alongside R) ranks among the foremost open-source programming languages favored in the realm of Data Science. **Proficiency in these languages has evolved into a standard expectation within the labor market for both Data Scientists and Financial Engineers.**

---

## Python Versions

### Important Version Information

Python encompasses two main version families:

- **Python 2.x** (OBSOLETE)
  - Python 2.7 was the final major release
  - No longer maintained or supported
  - **DO NOT USE for this course**

- **Python 3.x** (CURRENT)
  - Python 3.12+ is the recommended version
  - Actively maintained and updated
  - **REQUIRED for this course**

### Why Python 3.x?

Python 3.x offers:
- Improved syntax and features
- Better Unicode support
- Enhanced performance
- Active community support
- Compatibility with modern libraries

---

## Installation Methods

### Method 1: Anaconda Distribution (RECOMMENDED)

**Advantages:**
- ✅ Automatic installation of Python and 1500+ data science packages
- ✅ No manual library installation needed
- ✅ Includes Jupyter Notebook, Spyder, and other IDEs
- ✅ Cross-platform package management
- ✅ Environment management capabilities
- ✅ Beginner-friendly

**Best for:** Students, researchers, data scientists, and anyone new to Python

### Method 2: Direct Python Installation

**Advantages:**
- ✅ Lightweight installation
- ✅ Full control over package installation
- ✅ Minimal disk space usage

**Disadvantages:**
- ❌ Manual library installation required
- ❌ Potential dependency conflicts
- ❌ More complex for beginners
- ❌ Time-consuming setup

**Best for:** Experienced developers with specific requirements

---

## Recommended: Anaconda Installation

### Step 1: Download Anaconda

1. Visit the official Anaconda website:
   ```
   https://www.anaconda.com/
   ```

2. Click on **"Free Download"** or **"Download"**

3. Select the appropriate installer for your operating system:
   - **Windows**: Windows Installer (64-Bit)
   - **macOS**: macOS Installer (Intel or M1/M2)
   - **Linux**: Linux Installer (64-Bit)

### Step 2: Install Anaconda

#### Windows Installation

1. Run the downloaded `.exe` installer
2. Follow the installation wizard:
   - Click "Next"
   - Accept the License Agreement
   - Choose "Install for: Just Me" (recommended)
   - Select installation location (default is fine)
   - **Important**: Check "Add Anaconda to my PATH environment variable" (optional but helpful)
   - Complete the installation

#### macOS Installation

1. Open the downloaded `.pkg` installer
2. Follow the installation prompts:
   - Click "Continue"
   - Accept the License Agreement
   - Select installation location
   - Complete the installation

3. Open Terminal and verify installation:
   ```bash
   conda --version
   ```

#### Linux Installation

1. Open terminal in the directory containing the downloaded `.sh` file

2. Make the installer executable:
   ```bash
   chmod +x Anaconda3-2024.XX-Linux-x86_64.sh
   ```

3. Run the installer:
   ```bash
   bash Anaconda3-2024.XX-Linux-x86_64.sh
   ```

4. Follow the prompts:
   - Press Enter to review the license
   - Type "yes" to accept
   - Press Enter to confirm installation location
   - Type "yes" to initialize Anaconda

5. Restart your terminal or run:
   ```bash
   source ~/.bashrc
   ```

### Step 3: Verify Installation

Open Anaconda Navigator:

- **Windows**: Start Menu → Anaconda3 → Anaconda Navigator
- **macOS**: Applications → Anaconda Navigator
- **Linux**: Type `anaconda-navigator` in terminal

You should see the Anaconda Navigator interface with icons for various applications.

### Step 4: Launch Python Environments

Anaconda provides multiple ways to work with Python:

#### Option 1: Anaconda Navigator (GUI)
- Launch from Start Menu/Applications
- Click on application icons to launch

#### Option 2: Anaconda Prompt (Command Line)
- **Windows**: Start Menu → Anaconda3 → Anaconda Prompt
- **macOS/Linux**: Use standard terminal

#### Option 3: Launch Specific IDEs
Choose from:
- **Jupyter Notebook**: Interactive notebooks for data science
- **JupyterLab**: Advanced notebook interface
- **Spyder**: IDE similar to MATLAB/RStudio
- **VS Code**: Versatile code editor

---

## Alternative: Direct Python Installation

### Step 1: Download Python

1. Visit the official Python website:
   ```
   https://www.python.org
   ```

2. Navigate to Downloads

3. Select Python 3.12+ installer for your operating system

### Step 2: Install Python

#### Windows
1. Run the installer
2. **IMPORTANT**: Check "Add Python to PATH"
3. Click "Install Now"

#### macOS
1. Open the downloaded `.pkg` file
2. Follow installation prompts

#### Linux
```bash
sudo apt-get update
sudo apt-get install python3.12
sudo apt-get install python3-pip
```

### Step 3: Install Essential Libraries

After Python installation, install required libraries using pip:

```bash
# Data manipulation
pip install pandas numpy

# Visualization
pip install matplotlib seaborn plotly

# Machine Learning
pip install scikit-learn

# Natural Language Processing
pip install nltk spacy gensim

# Deep Learning
pip install tensorflow keras torch

# Database connectivity
pip install sqlalchemy pymongo

# Jupyter
pip install jupyter jupyterlab

# Additional utilities
pip install requests beautifulsoup4 openpyxl
```

**Note:** This method is cumbersome and not recommended for students new to Python programming.

---

## Integrated Development Environments (IDEs)

### Jupyter Notebook (Recommended for Course)

**Features:**
- Interactive coding environment
- Mix code, text, and visualizations
- Excellent for data exploration
- Industry standard for data science

**Launch:**
```bash
jupyter notebook
```

### JupyterLab

**Features:**
- Advanced version of Jupyter Notebook
- Multiple notebooks in tabs
- Integrated file browser
- Terminal access

**Launch:**
```bash
jupyter lab
```

### Spyder

**Features:**
- IDE designed for scientific Python
- Variable explorer
- Integrated debugging
- MATLAB-like interface

**Launch:**
- Through Anaconda Navigator, or
- Command line: `spyder`

### PyCharm

**Features:**
- Professional Python IDE
- Advanced debugging
- Version control integration
- Code analysis

**Download:** https://www.jetbrains.com/pycharm/

**Versions:**
- Community Edition (Free)
- Professional Edition (Paid, free for students)

### Visual Studio Code

**Features:**
- Lightweight code editor
- Extensive extensions
- Multi-language support
- Integrated terminal

**Download:** https://code.visualstudio.com/

---

## Essential Libraries

### Data Manipulation
```python
import pandas as pd          # DataFrames and data manipulation
import numpy as np           # Numerical computing
```

### Visualization
```python
import matplotlib.pyplot as plt   # Basic plotting
import seaborn as sns             # Statistical visualization
import plotly.express as px       # Interactive plots
```

### Machine Learning
```python
from sklearn import *             # Scikit-learn for ML algorithms
```

### Natural Language Processing
```python
import nltk                       # Natural Language Toolkit
import spacy                      # Industrial-strength NLP
from gensim import models         # Topic modeling
```

### Deep Learning
```python
import tensorflow as tf           # TensorFlow
from tensorflow import keras      # Keras API
import torch                      # PyTorch
```

### Database
```python
from sqlalchemy import *          # SQL database toolkit
import pymongo                    # MongoDB driver
```

---

## Verification

### Check Python Installation

Open terminal/command prompt and run:

```bash
python --version
```

Expected output: `Python 3.12.X` or higher

### Check pip Installation

```bash
pip --version
```

### Check Anaconda Installation

```bash
conda --version
```

### Test Python in Interactive Mode

```bash
python
```

Then try:
```python
>>> print("Hello, UJ!")
>>> import pandas
>>> import numpy
>>> quit()
```

### Create and Run Test Script

Create `test.py`:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Test data manipulation
data = {'Name': ['Alice', 'Bob', 'Charlie'],
        'Score': [85, 92, 78]}
df = pd.DataFrame(data)
print(df)

# Test visualization
plt.plot([1, 2, 3], [1, 4, 9])
plt.title('Test Plot')
plt.savefig('test_plot.png')
print("Test successful!")
```

Run:
```bash
python test.py
```

---

## Troubleshooting

### Issue: "Python not found" or "command not found"

**Solution:**
- Ensure Python is added to PATH
- Restart terminal/command prompt
- Reinstall with PATH option checked

### Issue: "pip not found"

**Solution:**
- Anaconda: Use `conda` instead of `pip`
- Direct installation: Reinstall Python ensuring pip is included

### Issue: Library import errors

**Solution:**
```bash
# For Anaconda
conda install package_name

# For pip
pip install package_name
```

### Issue: Jupyter Notebook won't start

**Solution:**
```bash
# Reinstall Jupyter
pip install --upgrade jupyter
# or
conda install jupyter
```

### Issue: Permission denied (Linux/macOS)

**Solution:**
```bash
sudo pip install package_name
# or use --user flag
pip install --user package_name
```

### Issue: Multiple Python versions

**Solution:**
- Use virtual environments
- Specify Python version explicitly: `python3` or `python3.12`

---

## Getting Help

### Course Resources
- **Instructor:** Dr. John Weirstrass Muteba Mwamba
- **Email:** johnmu@uj.ac.za
- **Office Hours:** By appointment

### Online Resources
- **Python Documentation:** https://docs.python.org/3/
- **Anaconda Documentation:** https://docs.anaconda.com/
- **Stack Overflow:** https://stackoverflow.com/questions/tagged/python

### Community Support
- Python Discord servers
- Reddit: r/learnpython
- UJ student forums

---

## Next Steps

After successful installation:

1. ✅ Complete the verification tests
2. ✅ Launch Jupyter Notebook
3. ✅ Review Week 1 materials
4. ✅ Practice basic Python syntax
5. ✅ Join course communication channels

---

**University of Johannesburg**
Faculty of Economic and Financial Sciences
Master of Financial Engineering Programme

© 2025 University of Johannesburg
