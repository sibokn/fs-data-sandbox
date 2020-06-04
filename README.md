# fs-data-sandbox

## Table of Content:
* 1 Description
  * 1 Background
  * 2 Repo Structure
    * 1 Explore - "How do I access the data?"
    * 2 Expand - "How can I help?"
* 2 A Brief Introduction To...
  * 1 Git
  * 2 Jupyter Notebooks

## 1. Description
The motivation behind this repo is to build a community within financial services - and beyond - where both novice and professionals can collaborate, learn, and do research together on data sets related to the FS sector. The main idea behind a data sandbox is to create an environment where we can play around with data, ideas, code and algorithms. With this in the back of our mind, we taught that the combination of Jupyter notebooks on Git might define a perfect environment for such a project. You can read more about Jupyter notebooks and Git in section 2.

### 1.1. Background
Because off the intrinsically private nature of FS data, it can be challenging to access these resources, and research in this domain often starts off by hours wasted on gathering data. To ease the frustration, we started out by collecting all the publicly available data sets that we could find online. We hope that, in the future, we can expand this portfolio with data sets that we gather “on the way”, either via anonymization, synthetization, or some other method that comply with privacy laws.

### 1.2. Repo Structure
There are two ways that we can use this repo – **Explore & Expand**.

#### 1.2.1. **Explore** - "How do I access the data?"
If you just want to explore and play around with different data sets within the FS domain, go ahead, be our guest!

- Accessing data sets:
    - Data sets can be accessed via the data.md file.
    - The data.md file contains links to an online source where you should be able to locate the corresponding data sets and other resources related to the data.


- Accessing notebooks:
    - Data sets that we're working on, can be located in the Notebooks folder inside this repo.
    - Notebooks should have the same title as the data sets they cover.

#### 1.2.2. **Expand** - "How can I help?"
##### Corrections
If you discover some typos, computational errors, or other things that doesn’t make sense to you, please feel free to either:
- Ask for help:
    - Open an issue in our repo with your problem, discovery, or concern.
    - Hopefully, some of our colleagues will help you out and solve your problem.


- Fix it yourself:
    - Branch the notebook that you’re working on.
    - Edit and commit your changes.
    - Make a pull request.


##### Expansions
- Add data:
    - To bypass possible copy rights restrictions, new data sets should be added via the data.md file, which links to the corresponding resources online.
    - It is our responsibility to check that potential data sets obey privacy policies, before we add them to our repository.


- Add text, code, and insights to notebooks:
    - If you discover some better way of phrasing a sentence, visualizing data, an algorithm that outperforms the standard, or maybe you have some other idea that you think would enrich the notebook you’re working on, please feel free to:
        - Branch the notebook that you’re working on.
        - Edit and commit your changes.
        - Make a pull request.


##### Notes and remarks
- Notebooks should have the following layout:
    - **Information about this notebook**
        - **Source**
            - *Reference the source that you gather the data sets from.*
        - **Data**
            - *List the files that this notebook depends on.*
        - **References**
            - *By intellectual property rights, if you’re copying work done by others, list the references or links that directs to these resources in this paragraph.*
        - **Status:**
            - *Write a short description on the status quo of this notebook.*
            - *This paragraph should be updated on commits that contains major changes in the content of the notebook.*
    - **Introduction**
        - *Write a short introduction that describes the data set and problems related to the data.*
    - INSERT TEXT AND CODE BELOW THIS POINT...


- Stay consistent with notation:
    - If you’re adding code and insights to a notebook that is in production, please stay consistent with notation within that notebook.
    - Note that, if you start a new notebook you get to choose the initial notation.


- Working on a notebook:
    - A notebook usually depend on data sets. If you choose to work on a notebook inside the Notebooks folder of this repo, please remove any data sets from this folder before you perform a commit.
      - Remember: We do not want to add data sets directly to our repository.
    - A good idea might be to create a local working environment outside of the repo, and then replace the notebook inside the repo when you're ready to make a commit.


## 2. A Brief Introduction To...


### 2.1. Jupyter Notebook
#### 2.1.1. "Why Jupyter?"
Jupyter notebook is an open source software project that lets you combine richly formatted text, data, and code all in one place. Jupyter originated from research groups and its name reference to the three core programming languages it supports: Julia, Python, and R.

TODO: Continue short guide + link to potential tutorials...

### 2.2. Git
#### 2.2.1. "Why Git?"
TODO: Write a short guide + link to potential tutorials...
