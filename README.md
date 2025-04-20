# Synthetic Prompt Generation for DeepFake/Impersonation Research

This project generates highly diverse synthetic prompts using the TogetherAI LLM API for DeepFake/Impersonation research. Prompts are annotated and saved in both JSON and CSV formats.

## Features

- Generates prompts using the `mistralai/Mixtral-8x7B-Instruct-v0.1` model via TogetherAI API.
- Prompts are structured for research, with fields like category, risk_level, intent, and placeholders.
- Results are saved to both JSON and CSV for easy analysis.

## Requirements

- Python 3.7+
- See `requirements.txt` for Python dependencies.

## Installation

1. Clone this repository or download the code.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

open and run the Jupyter notebook:
```
jupyter notebook synthetic_data_generator.ipynb
```

Prompts will be saved in the `synthetic_prompt_dataset` directory as both JSON and CSV files.


## Notes

- Ensure you have a valid TogetherAI API key.
- The script includes rate-limit handling; generation may take several minutes for large prompt counts.

