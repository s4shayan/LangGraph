# 🚀 LangGraph Mastery: Advanced AI Workflows

Welcome to the **LangGraph Mastery** repository! This project serves as a comprehensive collection of advanced patterns and practical implementations using **LangGraph**, a powerful library for building stateful, multi-agent applications with LLMs.

Whether you're just starting with basic chains or building complex, hierarchical subgraphs, this repository provides hands-on notebook examples for every major pattern.

---

## 🏗️ Project Structure & Modules

The repository is organized into distinct learning modules, each focusing on a specific LangGraph capability:

### 1. Fundamentals
*   **[`simple_LLM_workflow.ipynb`](./simple_LLM_workflow.ipynb)**: The "Hello World" of LangGraph. Learn how to define a single-node state machine.
*   **[`Prompt_Chaining.ipynb`](./Prompt_Chaining.ipynb)**: Move beyond simple chains. Learn how to link multiple LLM calls where the output of one informs the next.
*   **[`bmiWorkflow.ipynb`](./bmiWorkflow.ipynb)**: A practical utility workflow demonstrating data processing and conditional logic.

### 2. Advanced Graph Patterns
*   **[`ParallelLLMWorkflow.ipynb`](./ParallelLLMWorkflow.ipynb)**: Optimize performance by running multiple LLM processes simultaneously and merging results.
*   **[`Subgraphs.ipynb`](./Subgraphs.ipynb)**: Learn modularity by embedding entire graphs as nodes within a parent graph.
*   **[`Subgraph_Shared.ipynb`](./Subgraph_Shared.ipynb)**: Deep dive into state management between parent and child graphs.
*   **[`ConditionalReviewHandling.ipynb`](./ConditionalReviewHandling.ipynb)**: Implement complex routing logic and human-in-the-loop verification patterns.

### 3. Practical Applications
*   **[`Chatbot.ipynb`](./Chatbot.ipynb)**: A complete conversational AI implementation featuring state persistence and history management.
*   **[`X_PostGenerator.ipynb`](./X_PostGenerator.ipynb)**: A specialized workflow tailored for generating viral content for X (formerly Twitter).

---

## 🛠️ Setup & Installation

### Prerequisites
- Python 3.10+
- A Google Cloud Project with Gemini API access (or access to other LLM providers supported by LangChain).

### 1. Clone the repository
```bash
git clone https://github.com/Shayannoore/LangGraph.git
cd LangGraph
```

### 2. Create and Activate Virtual Environment
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# Linux/macOS
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configuration
Create a `.env` file in the root directory and add your API keys:
```env
GOOGLE_API_KEY=your_gemini_api_key_here
LANGSMITH_API_KEY=your_langsmith_api_key_here (optional)
LANGSMITH_TRACING=true (optional)
```

---

## 🧰 Built With

*   **[LangGraph](https://github.com/langchain-ai/langgraph)**: Orchestrating the agentic workflows.
*   **[LangChain](https://github.com/langchain-ai/langchain)**: The backbone framework for LLM interactions.
*   **[Google Gemini](https://deepmind.google/technologies/gemini/)**: Powering the intelligent reasoning.
*   **Jupyter Notebooks**: Providing an interactive and documented coding environment.

---

## 🌟 Why LangGraph?

Traditional DAGs (Directed Acyclic Graphs) limitation... LangGraph allows for **cycles**, **persistence**, and **human-in-the-loop** interactions which are essential for building robust AI agents that can backtrack, correct errors, and maintain complex state over time.


## 🤝 Contributing

Contributions are welcome! If you have a pattern or workflow you'd like to share:
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingPattern`)
3. Commit your Changes (`git commit -m 'Add some AmazingPattern'`)
4. Push to the Branch (`git push origin feature/AmazingPattern`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` (if added) for more information.

---
*Created with ❤️ by [Shayannoore](https://github.com/Shayannoore)*

---

