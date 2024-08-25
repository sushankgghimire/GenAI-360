# Language Translation, Question Answering, and AI Interaction with Mistral Instruct 7B

This repository contains a Jupyter notebook that demonstrates the usage of the `mistral-7b-instruct` model, quantized to 4-bit integer precision, for tasks such as language translation, question answering, and AI interaction. The notebook showcases how this model can be effectively used for these tasks.

## Overview

### Models Used:
- **Mistral Instruct 7B (4-bit Quantized):**
  - This model was the primary focus of the notebook. Quantized to 4-bit integer precision, it provides a good balance between performance and efficiency, making it suitable for a wide range of tasks.
  - **Performance:** The model performed well across different tasks, including generating accurate translations, answering questions effectively, and maintaining coherent conversations.

- **Mistral 7B Orca (4-bit Quantized):**
  - Although not included in the notebook, a variant of the Mistral 7B model trained on the Orca dataset was tested separately. It did not perform as well as the `mistral-7b-instruct` model, particularly in handling nuanced translations and generating high-quality responses.

### Issues with HuggingFace Integration:
- **HuggingFaceEndpoint:**
  - The `HuggingFaceEndpoint` was initially considered for deploying the model. However, due to an HTTP error caused by unsupported model arguments, it was not suitable for some of the code in the notebook.
  
- **HuggingFaceHub:**
  - As a workaround, the notebook utilizes `HuggingFaceHub`, which, while effective, is scheduled for deprecation soon. Future updates may require transitioning to a more sustainable solution.

## Notebook Content

The notebook includes:
1. **Language Translation:** 
   - A prompt structure that allows users to input text in one language and receive a translation in another language using the `mistral-7b-instruct` model.
  
2. **Question Answering:**
   - Demonstrations of the model's ability to answer questions accurately and provide relevant, informative responses.

3. **AI Interaction:**
   - Examples of the model's ability to handle conversational prompts, offering witty and contextually appropriate responses.

## Future Work

As `HuggingFaceHub` is set to be deprecated, future iterations of this project will need to explore alternative deployment options. Additionally, further experimentation with other quantized models may help optimize performance for specific tasks.

