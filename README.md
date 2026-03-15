## 🔍 Data Retrieval
A Python and Jupyter Notebook project that implements a full data retrieval pipeline, from web scraping raw wikipedia articles to building and evaluating multiple search engine models.

## 📋 Requirements
Install the required packages before running:
```bash
pip install nltk scikit-learn rank-bm25 import-ipynb
```
> ⚠️ **First time only** — before running `Part2.ipynb`, uncomment the following line in the notebook, run it once, then comment it out again:
> ```python
> nltk.download('stopwords')
> ```

## 🚀 How to Run
1. Clone the repository 
   ```bash
    git clone https://github.com/PetrosIbrah/Data-Retrieval.git
   ```
2. Open the notebooks in order and **run all cells sequentially**, each part depends on the output of the previous one. <pre>
Part1 → Part2 → Part3 → Part4a / Part4b → Part5
</pre>

## 🗂️ Project structure
 
The project is structured as a sequential pipeline across 5 parts:
 
| Part | Notebook | Description |
|-|-|-|
| 1 | `Part1.ipynb` | Web scraping. Ccollect articles from the web. |
| 2 | `Part2.ipynb` | Text preprocessing. Remove punctuation and stopwords. |
| 3 | `Part3.ipynb` | Build an inverted index for all remaining words |
| 4a | `Part4a.ipynb` | Boolean Retrieval search |
| 4b | `Part4b.ipynb` | Vector Space Model & Probabilistic search |
| 5 | `Part5.ipynb` | Evaluation. Precision, Recall, F1, MAP |
