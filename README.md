# Simple-Chatbot-using-LangGraph-GenAI-Project
This Repository contains my working files of "Simple Chatbot using LangGraph Project", an GenAI Project

(i) Configured secret API keys for Groq and LangSmith to enable LLM interaction and state tracking within the chatbot.

(ii) Defined a State class to manage and persist messages, ensuring all user and assistant interactions were tracked throughout the session.

(iii) Built a graph-based workflow using StateGraph, creating a ChatBot node that invoked the Groq LLM and connected it to start and end nodes for sequential execution.

(iv) Compiled the graph and implemented a real-time interactive loop, allowing the user to converse with the chatbot while maintaining state and displaying assistant responses dynamically.
