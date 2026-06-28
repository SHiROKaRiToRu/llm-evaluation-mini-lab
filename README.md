# LLM Evaluation Mini Lab

A portfolio project that benchmarks and compares multiple Large Language Models (LLMs) using a structured evaluation framework across diverse prompt categories.

This project simulates the workflow of an **AI Evaluation Engineer**, where multiple models are assessed for response quality, consistency, instruction following, and efficiency using a manually curated evaluation dataset.

---

## Project Objective

The objective of this project is to evaluate the performance of several state-of-the-art LLMs on the same set of prompts and analyze their strengths, weaknesses, consistency, and response efficiency.

Instead of relying on benchmark leaderboards, this project performs a manual evaluation using predefined scoring criteria and exploratory data analysis.

---

## Models Evaluated

* GPT-5.5
* Gemini 3.1 Pro
* Z.ai (GLM 4.7)

---

## Prompt Categories

The evaluation covers eleven prompt categories, including:

* Instruction Following
* Reasoning
* Coding
* Data Analysis
* Ambiguity Handling
* and additional real-world prompt types

Each model was evaluated on identical prompts to ensure a fair comparison.

---

## Evaluation Metrics

Each response was manually scored using multiple quality dimensions:

* Overall Score
* Correctness
* Completeness
* Instruction Following
* Format Compliance
* Conciseness
* Confidence
* Response Token Count

---

## Exploratory Data Analysis

The accompanying Jupyter notebook includes:

* Average overall score by model
* Metric-wise performance comparison
* Category-wise performance analysis
* Response length vs overall score correlation
* Correlation coefficient analysis
* Highest and lowest performing responses
* Score distribution using box plots
* Score distribution using histograms
* Consistency analysis using standard deviation
* Final model leaderboard

---

## Repository Structure

```
llm-evaluation-mini-lab/
│
├── data/
│   └── raw_results.csv
│
├── notebooks/
│   └── LLM_Evaluation_Analysis.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Key Findings

* Compared the overall performance of multiple LLMs using a structured evaluation framework.
* Measured consistency using score distributions and standard deviation.
* Analyzed category-specific strengths and weaknesses.
* Investigated the relationship between response length and evaluation quality.
* Produced a ranked leaderboard summarizing model performance across multiple evaluation dimensions.

---

## Skills Demonstrated

This project demonstrates practical skills relevant to AI Evaluation and Quality Assurance roles:

* Manual LLM evaluation
* Prompt benchmarking
* Data analysis with Pandas
* Data visualization using Matplotlib
* Statistical analysis
* Performance reporting
* Experimental documentation

---

## How to Run

Clone the repository:

```bash
git clone <repository-url>
cd llm-evaluation-mini-lab
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
notebooks/LLM_Evaluation_Analysis.ipynb
```

---

## Future Improvements

* Expand the benchmark with additional LLMs.
* Increase the number of prompts per category.
* Introduce multiple human evaluators to reduce scoring bias.
* Automate the evaluation pipeline.
* Add statistical significance testing for model comparisons.

---

## License

This project was created for educational and portfolio purposes.
