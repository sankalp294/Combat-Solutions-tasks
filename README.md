# MLOps, LangChain, and Docker Assignment

This repository contains my completed assignment on MLOps, LangChain, LangGraph, and Docker fundamentals.

---

## ✅ What I Have Done

### Task 1: MLOps for LLMs
- Added basic monitoring for latency and throughput
- Created Python script to call the LLM endpoint
- Tested with multiple different prompts

### Task 2: LangChain & LangGraph Basics
- Installed langchain, langgraph, and openai packages
- Built a simple LangChain pipeline with PromptTemplate, ChatOpenAI, and ConversationBufferMemory
- Created basic LangGraph flow: Input Node → LLM Node → Output Node

### Task 3: Chatbot with Memory
- Built a chatbot using LangGraph with 4 nodes: User Input, LLM, Memory, and Output
- Tested with 5 messages to confirm memory is working properly
- The bot remembers previous conversation context

### Task 4: Docker Basics
- ⏳ **Not completed yet** (less experienced with Docker)
- Will work on this part

### Task 5: DAG with LangGraph
- Created a simple DAG with conditional routing
- If user asks for calculation → goes to Calculator Node
- Otherwise → goes to LLM Node
- Tested both routes successfully

### Task 6: Prompt Engineering
- Tried 3 different prompt variations
- Documented which one worked best and why
- Compared response quality for each version

---

## 🔧 Setup Instructions

### All work was done in Google Colab

1. **Open the notebook** in Google Colab
2. **Install dependencies** (already in notebook):
   ```python
   !pip install langchain langgraph openai
   ```
3. **Add your API keys** (I replaced mine with "xyz" for security):
   ```python
   openai_api_key = "your-actual-key-here"
   ```
4. **Run all cells** in order

---

## 🔑 Important Note About API Keys

**All API keys in the uploaded files are replaced with "xyz" because they are confidential.**

To run the code, you need to replace "xyz" with your actual API keys:
- OpenAI API Key
- Azure OpenAI credentials (if using Azure)

---

## 📖 How to Run

1. Open the `.ipynb` notebook file in Google Colab
2. Replace all instances of `"xyz"` with your actual API key
3. Run the cells one by one
4. Test the chatbot by typing messages in the input prompts

---

## 💬 Example Usage

**Simple Conversation:**
```
User: Hello!
Bot: Hi! How can I help you today?

User: What did I just say?
Bot: You said "Hello!"
```

**Calculator Example:**
```
User: What is 15 + 25?
Bot: The answer is 40

User: Tell me a joke
Bot: Why did the chicken cross the road? To get to the other side!
```

---

## 📁 Files in Repository

- `assignment_notebook.ipynb` - Main Colab notebook with all tasks
- `README.md` - This file
- Code files for each task (if separated)

---

## 🚧 What's Pending

- Docker containerization (Task 4) - Need to learn more about Docker first

---

## 📝 Notes

- Everything was completed in Google Colab
- API keys are confidential and replaced with "xyz"
- All tasks except Docker are complete and tested
- Memory functionality works across multiple conversation turns
