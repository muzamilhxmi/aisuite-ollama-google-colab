# AI Model Comparison with Ollama, AIsuite & Gradio

<a href="https://www.youtube.com/watch?v=1QnYeaSg_VA" target="_blank" rel="noopener noreferrer">
  <img src="https://img.youtube.com/vi/1QnYeaSg_VA/0.jpg" alt="Watch the video" style="width: 100%; max-width: 560px; border: 1px solid #ddd;"/>
</a>
<p align="center">
  <a href="https://www.youtube.com/watch?v=1QnYeaSg_VA" target="_blank" rel="noopener noreferrer" style="text-decoration: none;">
    <span style="font-size: 20px; font-weight: bold; color: #FF0000;">YouTube</span>
  </a>
</p>



Welcome to the **AI Model Comparison Notebook** repository! This project features a comprehensive Jupyter Notebook that demonstrates how to compare various AI models using Ollama, integrated with AIsuite and Gradio. Run the notebook on Google Colab with free GPU support for an interactive and efficient experience.

## Overview

In this notebook, you'll:
- **Compare Multiple AI Models:** Evaluate outputs from models such as `llama3.2:1b`, `smollm2:135m`, `phi3`, `tinyllama:latest`, and `gemma2:2b`.
- **Experience an Elegant UI:** Use a sleek Gradio interface that organizes each model's output into separate, easily navigable tabs.
- **Leverage Google Colab:** Utilize free GPU support to accelerate model testing and demonstration.
- **Integrate AIsuite Tools:** Enhance your workflow with additional functionalities provided by AIsuite.

Whether you're new to AI or an experienced practitioner, this notebook offers a user-friendly approach to exploring state-of-the-art AI models.

## What's Included

- **ollama_aisuite_gradio.ipynb:** The main Jupyter Notebook containing all the code and interactive demos.

## How to Run

### Using Google Colab
1. Open the notebook directly on [Google Colab](https://colab.research.google.com/).
2. Ensure GPU is enabled by navigating to *Runtime > Change runtime type > Hardware accelerator > GPU*.
3. Run the cells sequentially to interact with the models via the Gradio interface.

## How to Customize models?

Feel free to play with this cell under section 2.
To get more about model Ollama offers, visit this link:

https://ollama.com/search

```python
!ollama pull llama3.2:1b
!ollama pull phi3
!ollama pull smollm2:135m
!ollama pull tinyllama:latest
!ollama pull gemma2:2b

models = [
  'llama3.2:1b',
  'smollm2:135m',
  'phi3',
  'tinyllama:latest',
  'gemma2:2b'
]
```
## SEO Keywords

Ollama, AIsuite, Gradio, Google Colab, Free GPU, AI Models, Machine Learning, Jupyter Notebook, Interactive AI Demo, AI Model Comparison, ChatGPT, GitHub Repository

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributors

- [JalalHxmi](https://github.com/jalalhxmi)

