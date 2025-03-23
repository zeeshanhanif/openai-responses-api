# OpenAI Responses API & Chat API Comparison Repository

This repository explores the differences between OpenAI's new **Responses API** and the existing **Chat API**, providing practical, side-by-side examples in each Jupyter notebook.  
It aims to help developers understand the enhanced functionality, flexibility, and multi-turn interaction capabilities of the Responses API while comparing it with the familiar Chat API.

## Overview

OpenAI's Responses API simplifies the development of agentic applications by supporting:
- **Multi-turn conversations**  
- **Multiple tool integrations** like Web Search, File Search, and Computer Use  
- **Structured and streaming outputs**  

This API reduces the complexity of manually integrating tools and conversational logic, making it easier to build advanced AI-driven applications.

Each Jupyter notebook in this repository includes:
1. **Chat API Example**  
   Traditional usage of OpenAI's Chat API for comparison.
2. **Responses API Example**  
   Demonstrates how the same task can be accomplished using the new Responses API, highlighting the key differences and improvements.

---

## Getting Started

### Clone the Repository  
```bash
git clone https://github.com/zeeshanhanif/openai-responses-api.git
cd openai-responses-api
```

### Install Dependencies  
```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook  
```bash
jupyter notebook
```

### Open and Explore  
Run the desired notebook to compare Chat API and Responses API examples side by side.

---

## Prerequisites

- **Python 3.7 or higher**  
- **Jupyter Notebook** – Install it if needed:  
  ```bash
  pip install jupyter
  ```
- **OpenAI API Key** – Get your key from OpenAI and set it as an environment variable:  
  ```bash
  export OPENAI_API_KEY='your-api-key'
  ```

---

## Why Compare Chat API vs. Responses API?

This repository helps you understand key differences and new functionalities:
- **Multi-turn interactions**: The Responses API handles ongoing conversation state more efficiently.  
- **Tool integrations**: Explore tool-calling features built into the Responses API, compared to manual logic in the Chat API.  
- **Structured outputs**: The Responses API's structured responses allow more control over output formats.  

---

## Additional Resources

- **OpenAI Responses API Documentation**:  
  [https://platform.openai.com/docs/quickstart?api-mode=responses](https://platform.openai.com/docs/quickstart?api-mode=responses)  
- **OpenAI Responses API Launch Announcement**:  
  [Product Hunt](https://www.producthunt.com/posts/openai-responses-api-and-agents-sdk)
- **OpenAI Chat API Documentation**:  
  [https://platform.openai.com/docs/quickstart?api-mode=chat](https://platform.openai.com/docs/quickstart?api-mode=chat)



