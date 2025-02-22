# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

**Name**: Yiling Cao

---

## Overview

Build a **content-based recommendation system** that, given a **short text description** of a user’s preferences, suggests **similar book items** from the books dataset. 

## Dataset
The dataset is a collection of the 100 most popular books downloaded from the [Gutenburg Project](https://www.gutenberg.org/browse/scores/top). These 100 books form the corpus that I consider for this challenge. Each file contains the text of a book. I will read in all 100 books.


## Requirements

- Python version 3.11.10 or above.
- Numpy 1.26.4
- Dependencies are installed via pip (see **Setup** section for details).

## Setup
- Unzip the books.zip in the same directory

### Python Installation

Ensure Python 3.11.10 or higher is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Virtual Environment

It is recommended to create a virtual environment for this project to manage dependencies efficiently. Execute the following commands in your terminal:

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
.\venv\Scripts\activate
# On Unix or MacOS
source venv/bin/activate
```

### Install dependencies
```bash
pip install -r requirements.txt
```

## Running The System
- Launch the Jupyter Notebook
- Navigate to the notebook file and open it.
- Run the cells sequentially to interact with the system.

## Result
### Example Query
```bash
#Input:

I like European History

#Output:

Recommended books based on what you input:

Beyond Good and Evil by Friedrich Wilhelm Nietzsche: 0.03
Democracy in America — Volume 1 by Alexis de Tocqueville: 0.02
On Liberty by John Stuart Mill: 0.01
```


