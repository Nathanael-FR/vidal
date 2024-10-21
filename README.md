# vidal

## Benchmarks 

* General Benchmarks: Benchmarks such as GLUE (General Language Understanding Evaluation), MMLU (Massive Multi-task Language Understanding), and HellaSwag are widely used to assess the general language understanding, comprehension, and common-sense reasoning skills of an LLM. These benchmarks are essential for any LLM implementation, regardless of its specific use, because the ability to understand requests is fundamental for producing accurate outputs.
  
* Clinical QA Benchmarks: These benchmarks test the fundamental medical knowledge of the LLMs. They rely on LLMs' capacity to answer clinical questions usually found in medical entrance and licensing exams. MedQA (based on US Medical License Exam) and MedMCQA (based on questions from Indians medical exams like AIIMS and NEET PG) are the gold standard here.
  
* Challenge Datasets: Clinical task challenges are datasets that help to evaluate the LLMs performance in different use-cases in healthcare like clinical note taking, summarization, diagnosis, symptom collection etc.  For example - ClinicalSTS (Clinical Semantic Textual Similarity) is a good tool for use-cases like CDSS, or clinical summarization task as it measures the similarity in different sentences having the same meaning.
