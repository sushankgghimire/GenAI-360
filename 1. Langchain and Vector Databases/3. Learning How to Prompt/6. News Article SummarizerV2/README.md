## News Summarizer with Mistral's API and Mistral-7b-Instruct-v0.1 in LangChain

In this notebook, I developed a news summarizer using two different approaches:

1. **Mistral's API**: Leveraging Mistral's API to generate summaries from news articles.
2. **Mistral-7b-Instruct-v0.1.Q8_0.gguf**: Loading this model locally using LlamaCPP for summarization tasks.

### Key Insights

- **Prompting Variations**: The notebook highlights how the method of prompting needs to be adapted for each approach (API vs. local model) to achieve the desired summarization results. The variations in prompts significantly affect the output, demonstrating the importance of tailored prompting strategies.

This notebook serves as a practical example of integrating different LLMs in LangChain for text summarization, with a focus on understanding and optimizing prompt engineering across different setups.
