# Llama-3.2-3B-on-colab
Running Llama 3.2 3B 4-bit quantized model (2.04 GB) on Google Colab T4 GPU (free)

- **Purpose**: Lightweight (2.24 GB) model, designed for Google Colab (or) local resource constraint environments.  

The 3B model performs better than current SOTA models (Gemma 2 2B, Phi 3.5 Mini, Qwen 2.5 1B & 3B Models, tested with huggingface serverless inference)

- **Automatic Setup**: Detects the environment, downloads the model from Hugging Face if needed, and saves it locally or in Google Drive.
  
- **Interactive Prompting**: Allows streamable responses, thus outputs are generated as word-to-word as it gets processed.

- **Model Management**: Automatically saves the tokenizer and model for future reuse to avoid redundant downloads.

- **Usage**: Run all cells, input a query when prompted, and view the response directly in the console.  
