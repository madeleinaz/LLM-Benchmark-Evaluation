# LLM Benchmark Evaluation

Evaluation of four open-source large language models for developer tooling use 
on an Azure-hosted infrastructure.

## Models Evaluated
- Mistral 7B
- DeepSeek
- Qwen
- Code Llama

## Evaluation Criteria
Models were tested across 5 prompts covering algorithmic coding, conceptual 
explanation, mathematical reasoning, real-world software engineering, and 
conversational ability. Each model was run 3 times per prompt on an Azure VM.

## Key Finding
Mistral 7B was selected for deployment due to its balance of coding performance, 
reasoning quality, response speed, and consistent conversational ability.

## Full Report
The complete benchmark report with all model responses, per-prompt analysis, 
and final scoring is available in `LLM_Benchmark_Report.docx`.

## Stack
Python · Azure VM · Ollama · REST API · Linux · SSH
