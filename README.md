# Benchmark-Harness

## Goal
Create a general infrastructure for running new LMs/inference servers against a set of general benchmarks

### Question Types
- Instruction Following with Ground Truth
- Instruction Following no Ground Truth
- Math (with ground truth)
- Code (ground truth final result)
- Chat / Multiturn

### Answer Extraction
- Keyword Search
- LLM Extraction

### Single Question Evaluation Types
- LLM as a Judge/Battles: choosing the best out of multiple responses
- LLM Ranking: Rank the responses from a list of responses
- Math Verification: keyword search for truth then llm verification if not found
- Code: Environment for executing the code --> verifying outputs against ground truth
- BART Scores compared with ground truth
- BERT Scores compared with ground truth

### Model Ranking / Overall Scoring
Accuracy:
- % correct
- Summed rankings (lower score is better)
- number of battles won


## Project Plan
### 4/9
Goal:
- Instruction Following with Ground Truth
- Instruciton Following with no Ground Truth
- Math with Ground Truth

