# HCL-Software: Enhancing Software Security with LLMs

## 🚀 Executive Summary
This was my capstone project with HCL Software. Our project focuses on using **Large Language Models (LLMs)** to provide recommendations (code lines or contextual information) for vulnerabilities, enhancing software security and efficiency.

Traditional manual patching is time-consuming and error-prone. We introduce an accelerated approach using LLMs to provide accurate, context-specific recommendations, speeding up remediation while ensuring transparency through cited sources.

## 🔑 Key Outcomes
- Successfully built prototype models (QA, GPT-2, and ChatOpenAI).
- Models provide remediation advice and recommendations for code fixes.
- Our solution has commercial potential, reducing operational risks, enhancing security, and promoting safer digital environments.

## 🛠 Methods and Tools

### Datasets Used:
- **OWASP Cheat Sheets** (integrated from the OWASP GitHub repository).

### Analytical Models:
1. **QA Model** (Haystack, InMemoryDocumentStore, BM25 algorithm).
2. **GPT-2 Model** (Fine-tuned GPT-2, Hugging Face Transformers).
3. **ChatOpenAI Model** (Langchain, RAG, OpenAI API).

### Tools and Platforms:
- **Python**, **Google Colab**, **Hugging Face**, **Haystack**, **OpenAI API**, **GitHub**, **Google Drive**, **Visual Studio Code**.

## ⚙️ Results and Conclusions
Our models successfully identified software vulnerabilities and provided actionable advice:
- **QA Model**: Found vulnerability causes and offered patch suggestions.
- **GPT-2 Model**: Improved extended responses using fine-tuned datasets.
- **ChatOpenAI Model**: Delivered the most comprehensive and contextually relevant recommendations.

## 🌍 Business & Social Impact
- **Business**: Reduces the time and cost of securing software, increasing trust and reliability.
- **Social**: Contributes to a safer digital environment, protecting users from sophisticated cyber threats.

## 📄 Screenshots of Results

### QA Model Output:
![QA Output](assets/qa-output.png)

### GPT-2 Model Output:
![GPT-2 Output](assets/gpt2-output.png)

### ChatOpenAI Model Output:
![ChatOpenAI Output](assets/chatopenai-output.png)

## 📋 How to Reproduce Results

### 1. QA Model
- **Step 1**: Install Haystack, create a DocumentStore, Retriever, and Reader.
- **Step 2**: Feed datasets ('causes', 'risks', and 'recommendations') into the model.
- **Step 3**: Query the system using prompts like "What is Cross-Site Scripting?"

### 2. GPT-2 Model
- **Step 1**: Fine-tune GPT-2 with the combined dataset (HCL + OWASP).
- **Step 2**: Set up a text generation pipeline using Hugging Face.

### 3. ChatOpenAI Model
- **Step 1**: Create a database using Chroma and Langchain's RAG.
- **Step 2**: Query the model with prompts like "What is SQL injection?"

## 🛠 Tools to Run the Project
- Python, Hugging Face, Haystack, OpenAI API
- Google Colab for processing

## 🏗 Future Work
- Integrate the model into a chat-bot within coding environments to offer instant remediation advice to developers.
- Continuously train the model on new vulnerabilities.

## ✨ License
This project is licensed under the MIT License.
