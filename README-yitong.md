# REPE code
## Maks sure the project directory is correct
Manual download of models and datasets is required
```
├── models
│   ├── Llama-2-7b-chat-hf
│   │   ├── config.json
│   │   ├── generation_config.json
│   │   └── ...
│   ├── Mistral-7B-Instruct-v0.1
│   │   ├── config.json
│   │   ├── generation_config.json
│   │   └── ...
│   └── ...
├── datasets
│   ├── truthful_qa
│   │   ├── generation
│   │   └── multiple_choice
│   └── ...
├── repe
│   ├── assets
│   ├── data
│   ├── examples
│   └── ...
└── README.md
```
## Install necessary library
```
cd representation-engineering
pip install -e .
```
## Run notebook
Go to repe -> examples -> honesty -> honesty.ipynb for modified code and explaination

# Test Dataset
Check repe -> generate_scenarios.ipynb for generating the dataset
Check repe -> scenarios.json for the dataset
More to be added ...
