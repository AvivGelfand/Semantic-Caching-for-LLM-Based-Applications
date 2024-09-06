# Semantic Caching for LLM-Based Applications

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Data](#data)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Technologies Used](#technologies-used)
8. [Future Work](#future-work)
9. [Acknowledgments](#acknowledgments)

## Project Overview
This project is a tiny step towards investigating the effectiveness of semantic caching in improving the performance and cost-efficiency of Large Language Model (LLM) based applications. By implementing and analyzing a semantic caching system, I aim to reduce response times and API call costs while maintaining high-quality outputs.

## Data
We used the Quora Question Pairs Dataset, a benchmark for natural language understanding tasks containing over 400,000 question pairs. This dataset provides a rich source of varied and semantically diverse queries for my experiments.

## Methodology
Our experiment compares the performance of an LLM-based system with and without semantic caching. Key components of our methodology include:

1. Data Collection: Diverse set of queries simulating real-world usage
2. Experimental Setup: Control group (no cache) vs. Experimental group (with cache)
3. Variables: 
   - Independent: Use of semantic caching
   - Dependent: Response time, API call cost, cache maintenance cost, cache hit rate
4. Analysis: Performance analysis, statistical tests, and cost-benefit analysis

## Results
Our experiments revealed significant improvements in both performance and cost-efficiency:

1. Response Time: Semantic caching reduced average response times (p-value < 0.05)
2. Cost Efficiency: Implemented caching resulted in a 49% cost reduction
3. Cache Hit Rate: Achieved a 20.12% cache hit rate, indicating effective caching strategy

Detailed statistical analyses, including Kolmogorov-Smirnov and T-tests, confirmed the significance of our findings.

## Technologies Used

### Programming Languages and Core Libraries
- Python 3.11
- NumPy: For numerical computing and array operations
- Pandas: For data manipulation and analysis

### Machine Learning and NLP
- Transformers (Hugging Face): For state-of-the-art NLP models and tokenization
- SciKit-Learn: For additional machine learning utilities and metrics
- NLTK: For natural language processing tasks

### Similarity Search and Caching
- FAISS (Facebook AI Similarity Search): For efficient similarity search and clustering of dense vectors

### API Integration
- Groq API: For accessing large language models
- Requests: For making HTTP requests to APIs

### Data Structures and Algorithms
- OrderedDict: For implementing ordered cache with efficient item eviction

### Data Visualization and Analysis
- Matplotlib: For creating static, animated, and interactive visualizations
- Seaborn: For statistical data visualization
- Plotly: For interactive, publication-quality graphs

### Development Tools
- Jupyter Notebooks: For interactive development and data exploration
- Git: For version control

### Statistical Analysis
- SciPy: For scientific computing and statistical tests
- Statsmodels: For statistical modeling and econometrics

### Performance Optimization
- Cython: For optimizing performance-critical parts of the code
- Joblib: For lightweight pipelining in Python

## Future Work
1. Optimize caching algorithms for improved hit rates
2. Implement dynamic cache size adjustment
3. Explore advanced embedding techniques for better semantic matching
4. Conduct large-scale, real-world deployment tests

## Acknowledgments
- [Yahlli Levy](https://www.linkedin.com/in/yahllilevy/) for providing the internship opportunity and resources
