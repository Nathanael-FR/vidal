# Introduction

We have chosen to develop a **Medical Information Assistant based on the Vidal** to address the growing need for reliable and up-to-date medical information. As a key reference in the healthcare field in France, the Vidal provides a rich and precise source of data on medications, their uses, potential side effects, as well as possible interactions between different treatments.

The goal of this assistant is to support healthcare professionals and patients by providing reliable medical information, ensuring the safe and informed use of medications. Drawing on the wealth of data from Vidal, this assistant aims to become a trusted resource for anyone seeking guidance on medications.


# Evaluation Methodology

To assess the performance of our Vidal-based Medical Information Assistant, we have developed an evaluation method centered around a structured set of specific question-answer pairs. The goal is to test the ability of our AI to provide accurate and reliable medical information based on Vidal’s reference data.

We have created a [JSON file](https://github.com/nlahary/vidal/blob/main/QA_evaluation.json) containing question-answer pairs that cover a wide range of categories for different medications.

Once our AI is fully operational, we will submit these questions to it and compare its answers to those in our reference JSON file. We will analyze the results using criteria such as accuracy, precision, relevance, and consistency of the information provided. This method will allow us to identify the strengths of our assistant, as well as areas that require adjustments to enhance the quality of its responses.




# vidal

## Benchmarks 

* General Benchmarks: Benchmarks such as GLUE (General Language Understanding Evaluation), MMLU (Massive Multi-task Language Understanding), and HellaSwag are widely used to assess the general language understanding, comprehension, and common-sense reasoning skills of an LLM. These benchmarks are essential for any LLM implementation, regardless of its specific use, because the ability to understand requests is fundamental for producing accurate outputs.
  
* Clinical QA Benchmarks: These benchmarks test the fundamental medical knowledge of the LLMs. They rely on LLMs' capacity to answer clinical questions usually found in medical entrance and licensing exams. MedQA (based on US Medical License Exam) and MedMCQA (based on questions from Indians medical exams like AIIMS and NEET PG) are the gold standard here.
  
* Challenge Datasets: Clinical task challenges are datasets that help to evaluate the LLMs performance in different use-cases in healthcare like clinical note taking, summarization, diagnosis, symptom collection etc.  For example - ClinicalSTS (Clinical Semantic Textual Similarity) is a good tool for use-cases like CDSS, or clinical summarization task as it measures the similarity in different sentences having the same meaning.
