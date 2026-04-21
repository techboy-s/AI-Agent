# AI-Agent

Day 2: OpenAI / Anthropic API

Call your first LLM and understand how it works

Learn
Total: 5–6 hrs
2h learn + 3h build
What to study & do
Understand how LLMs work: tokens, context window, temperature, system prompts
Get your API key from Anthropic or OpenAI
Make your first API call using the Python SDK
Learn about roles: system, user, and assistant messages
Experiment with temperature, max_tokens, and structured JSON output
Resources
Anthropic docs
OpenAI Cookbook (GitHub)
Prompt Engineering Guide
Project of the day
Build this
## AI Q&A chatbot (CLI)
## Build a terminal chatbot that keeps conversation history, has a custom system prompt (e.g. 'You are a helpful sales assistant'), and can hold a multi-turn conversation.


Day 3: Prompt Engineering

Master the craft of getting reliable LLM outputs

Learn
Total: 4–5 hrs
2h learn + 2h experiment
What to study & do
Learn chain-of-thought prompting (ask the model to reason step by step)
Practice few-shot prompting (give examples inside the prompt)
Master structured JSON output prompting — this is critical for agents
Learn how to write system prompts that control persona, tone, and format
Understand hallucination — when it happens and how to reduce it
Resources
LearnPrompting.org
Anthropic prompt library
Claude Cookbook
Project of the day
Build this
## Invoice data extractor
## Given a raw invoice text, prompt an LLM to extract vendor name, amount, date, and line items as clean JSON. Test with 5 different invoice formats and fix prompts until it's reliable.

Day 4: Tool Calling + Function Use

Give your AI the ability to take real actions

Build
Total: 6 hrs
2h learn + 4h build
What to study & do
Understand what tool/function calling is — AI deciding when to use a tool
Define custom tools (Python functions) and pass them to the LLM
Build a tool that searches the web (use DuckDuckGo or Serper API)
Build a tool that reads a local file or Google Sheet
Handle tool call responses and feed results back into the conversation
Resources
OpenAI function calling docs
Anthropic tool use docs
LangChain tools guide
Project of the day
Build this
## Research assistant agent
## An agent that takes a question, decides whether to search the web, reads the result, and answers with citations. It should be able to run 2–3 tool calls in sequence.


Day 5: LangChain Fundamentals

Learn the most popular AI agent framework

Build
Total: 6–7 hrs
2h learn + 4h build
What to study & do
Install LangChain and understand its core concepts: chains, agents, memory
Build a simple chain: prompt → LLM → output parser
Understand LCEL (LangChain Expression Language) syntax
Build a ReAct agent with multiple tools
Add conversation memory so the agent remembers past turns
Resources
LangChain Python docs
LangChain YouTube channel
LangSmith for debugging
Project of the day
Build this
## FAQ chatbot with memory
## A LangChain agent that reads a company FAQ document, answers user questions from it, remembers the conversation, and falls back to a default message if unsure.


Day 6: RAG — Retrieval Augmented Generation

Make AI answer from your own data

Build
Total: 6–7 hrs
2h learn + 4h build
What to study & do
Understand embeddings — how text is turned into vectors for search
Set up ChromaDB (free, local) as a vector database
Chunk, embed, and store a PDF document into the vector DB
Build a retriever that finds the most relevant chunks for a question
Combine retriever + LLM into a full RAG pipeline
Resources
LangChain RAG guide
ChromaDB docs
Chunking strategies blog (Pinecone)
Project of the day
Build this
## Document Q&A bot
## Drop in any PDF (legal doc, policy manual, product catalog) and ask questions. The bot answers ONLY from that document, cites the source page, and says 'I don't know' if the answer isn't there.


Day 7: Integrations — Email, Sheets, Slack

Connect your agents to real business tools

Build
Total: 6 hrs
1h learn + 5h build
What to study & do
Connect to Gmail API — read, send, and label emails with Python
Connect to Google Sheets API — read/write rows using `gspread`
Send messages to Slack using the Slack Webhook API
Chain these as LangChain tools your agent can call
Learn about OAuth 2.0 basics for securing integrations
Resources
Google API Python quickstart
gspread docs
Slack Webhooks guide
Project of the day
Build this
## Email triage agent
## An agent that reads your last 10 emails, classifies each one (urgent / FYI / spam), logs the summary to a Google Sheet, and sends a Slack message with a daily digest.

Day 8: n8n Workflow Automation

No-code glue to sell faster and serve more clients

Build
Total: 5 hrs
1h learn + 4h build
What to study & do
Install n8n locally (Docker) or use n8n cloud free tier
Build a basic workflow: trigger → HTTP node → LLM node → output
Connect n8n to your Python agent via a webhook
Build a workflow that triggers on a new form submission
Understand when to use n8n vs pure Python
Resources
n8n.io docs
n8n YouTube channel
Make.com as alternative
Project of the day
Build this
## Lead qualification workflow
## When a new contact fills out a Typeform/Tally form, n8n triggers an AI agent that scores the lead, writes a summary, adds to Google Sheets, and sends an intro email automatically.

Day 9: Deploy Your Agent

Put your project live so clients can see it

Deploy
Total: 5–6 hrs
1h learn + 4h build
What to study & do
Wrap your Day 6 or Day 7 project in a FastAPI backend
Build a simple chat UI with Streamlit or Gradio (no frontend skills needed)
Deploy to Railway or Render for free in under 30 minutes
Set environment variables securely — never commit API keys to GitHub
Test your live URL, share it, add it to your portfolio
Resources
FastAPI docs
Streamlit docs
Railway.app quickstart
Project of the day
Build this
## Live portfolio project
## Take your best project (e.g. Document Q&A bot or Email triage agent), wrap it in Streamlit, deploy to Railway, and document it with a before/after business impact statement.

Day 10: Build Your Freelance Presence

Position, pitch, and land your first client

Pitch
Total: 5–6 hrs
All business
What to study & do
Write your LinkedIn headline: 'AI Automation Freelancer — I build agents that save businesses 10+ hrs/week'
Post your 3 portfolio projects with a short before/after story for each
Write a cold outreach message targeting ops managers or founders of 10–50 person companies
Identify 10 local Delhi businesses that have repetitive manual workflows
Offer a free 30-min 'AI Audit' — find 3 automatable tasks, propose 1 pilot project
Resources
Toptal / Contra / Upwork profile
LinkedIn creator mode
Hunter.io for emails
Project of the day
Build this
## First outreach batch
## Send 10 personalized cold DMs or emails today using your audit offer. Track responses in a simple Google Sheet. Your goal: 1 discovery call booked within 7 days.

