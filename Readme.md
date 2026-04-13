# ORACLE 
## V0.1
This is an ongoing MoE (Mixture of Experts) project that allows vector based databases for the LLM modules, which are connected with an "Advisor Logic". 
The front-hand LLM model handles the comparably easier tasks, if it faces some diffiulties and its confidence score lowers, it calls for its "advisor" to handle complex tasks.
It has its memory management logic designed for various different setups, if the allocated memory is not enough, it arranges its model structure and automatically selects smaller models.

## Requirements
Python Environment (Anaconda)
Microsoft MarkItDown
Ollama with following models:
-> Qwen3.5:35b-a3b
-> Gemma4:e4b
-> Qwen3.5:9b

## How to use run.bat?
Please change the <USERNAME> part with you current user on the desktop.