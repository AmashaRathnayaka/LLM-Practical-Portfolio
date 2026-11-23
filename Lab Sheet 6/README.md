# Lab Sheet 6 – Building a Tool-Using AI Agent

**Module:** PUSL 3205 – Large Language Models and Generative AI

**Project:** Building a Tool-Using AI Agent

**Development Environment:** Google Colab

## 1. Project Overview

This project demonstrates the development of a tool-using AI agent capable of performing mathematical calculations, storing and retrieving conversation history, retrieving information from PDF documents, and interacting with Google Calendar.

The project was implemented in Google Colab using Python, LangChain, a Hugging Face language model, SQLite, ChromaDB, and the Google Calendar API.

The implementation covers Parts A, B, C, and D of Lab Sheet 6.

## 2. Project Implementation

### Part A – Building a Calculator Agent

A basic AI agent was developed to perform mathematical calculations using a calculator tool.

Additional tools were implemented to demonstrate different capabilities, including date and time retrieval and word counting.

**Testing results:**
- Calculator: 25 × 4 = 100
- Date and Time: Successfully retrieved the current date and time
- Word Counter: Successfully counted the words in a sentence

### Part B – Adding Conversation Memory

SQLite was integrated to store user questions and agent responses.

The agent can save conversations and retrieve previously stored information.

**Testing results:**
- Successfully calculated 15 × 3 = 45
- Stored the conversation in SQLite
- Retrieved the saved information that the user's favourite subject is Data Science

### Part C – Integrating RAG and Tools

Retrieval-Augmented Generation (RAG) was implemented to allow the AI agent to retrieve information from an uploaded university lab sheet.

The system uses PDF loading, text chunking, embeddings, and ChromaDB for document retrieval.

Three tools were integrated:

1. Calculator Tool – Performs mathematical calculations.
2. Memory Search Tool – Retrieves information from stored conversations.
3. RAG Search Tool – Retrieves information from the uploaded PDF knowledge base.

**Testing results:**
- Calculator returned 100 for 25 × 4
- Memory Search retrieved the user's favourite subject
- RAG Search successfully retrieved the three required tools from Lab Sheet 6

### Part D – Google Calendar Integration

Google Calendar API was integrated to allow the agent to interact with calendar events.

OAuth 2.0 authentication was used to authorize access to the Google Calendar account.

**Implemented features:**
- Retrieve upcoming calendar events
- Check today's schedule
- Create a calendar event after user confirmation
- Integrate calendar functionality with the existing AI agent

**Testing results:**
- Successfully connected to Google Calendar
- Retrieved upcoming events
- Retrieved today's schedule
- Successfully created a test event
- Verified Calculator, Memory Search, and RAG Search functionality alongside Google Calendar

## 3. Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Qwen2.5-0.5B-Instruct
- LangChain
- SQLite
- ChromaDB
- Hugging Face Sentence Transformers
- Google Calendar API
- Google OAuth 2.0

## 4. Project Files

```text
LabSheet6_Submission/
├── LabSheet6_Tool_Using_AI_Agent.ipynb
├── README.md
└── LabSheet6_Screenshots/
    ├── Part_A_Calculator.png
    ├── Part_B_Memory.png
    ├── Part_C_RAG.png
    ├── Part_D_Upcoming_Events.png
    └── Part_D_Final_Testing.png
```

## 5. How to Run the Project

1. Open `LabSheet6_Tool_Using_AI_Agent.ipynb` in Google Colab.
2. Select a suitable runtime, such as T4 GPU.
3. Install the required Python libraries using the installation cells.
4. Execute the notebook cells in order.
5. Upload the required PDF document when prompted.
6. Run the calculator, memory, and RAG testing cells.
7. For Part D, configure Google Calendar API credentials and complete OAuth authentication.
8. Execute the calendar integration and testing cells.

**Note:** Google Calendar authentication requires personal OAuth credentials. These credentials are not included in the submission for security reasons. SQLite memory and uploaded files may need to be initialized again when a new Colab runtime starts.

## 6. Conclusion

This project successfully demonstrates the development of a tool-using AI agent with calculator functionality, conversation memory, document-based retrieval, and Google Calendar integration.

All four implemented parts were tested successfully in Google Colab.