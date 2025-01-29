# Chat Summarizer with LLMs

## Overview
This project is a **chat summarization system** leveraging **Large Language Models (LLMs)** to generate concise and accurate summaries from chat transcripts. The system is designed to be computationally efficient, scalable, and optimized for large-scale chat data processing.

## Features
- **Summarization using LLMs:** Utilizes **Gemma-2B-IT** to generate high-quality summaries.
- **Efficient memory usage:** Implements **quantized Low-Rank Adaptation (qLoRA)** to reduce model size and computational cost by converting vectors to 4-bit precision.
- **Local Deployment:** Runs entirely on local machines, ensuring **data privacy** and eliminating dependency on cloud services.
- **Contextual Understanding:** Uses **semantic search** to retrieve relevant chat sections before summarization, improving accuracy.
- **Scalable Design:** Handles large chat logs with minimal resource consumption.

## Technologies Used
- **Python** (Primary programming language)
- **Gemma-2B-IT** (LLM for text summarization)
- **qLoRA** (Model optimization)
- **FAISS** (Efficient similarity search for semantic retrieval)
- **PyTorch** (Model fine-tuning and inference)
- **Hugging Face Transformers** (LLM integration)
- **PDF Processing:** PyMuPDF for extracting text from PDFs

## Installation
```bash
# Clone the repository
git clone https://github.com/Vraj103/chat-summarizer.git
cd chat-summarizer

# Install dependencies
pip install -r requirements.txt
```

## Usage
```bash
python summarizer.py --input chat_transcript.pdf --output summary.txt
```

## Future Enhancements
- Implement **GUI support** for user-friendly interaction.
- Add **multi-document summarization** capability.
- Improve summarization quality using **Reinforcement Learning from Human Feedback (RLHF)**.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.

