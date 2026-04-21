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

free api - https://freeapi.hashnode.space/api-guide/apireference/getUsers

frontend interview question
1- File Explorer
2- Pagination
3- EMI Calculator
4- Linked List in React js
5- grid lights
6- useMemo hook Polyfill
7- Like Button
8- Job Board
9- UseEffect Hook polyfill
10 - Dark mode light mode
11- BreadsCrumbs
12- OTP login
13- Multi-select Search
14- Stepper component
15- Use throttle hook
16- Selectable Grid
17- Drag and drop notes
18- Tic Tac Toe
19- Toast Component
20- Autosuggestion or TypeAhead
21- Poll widget
22- Memory game
23- Cinema hall ticket booking 
24- Multi-step form


Table of Content
01. Implement Debounce- Easy
//// Asked in Meta, Google, Flipkart, IBM, MakeMyTrip
02. Implement Throttle- Medium
//// Asked in Google, Meta, Tekion
03. Implement Currying- Easy
//// Asked in Intuit, Tekion, Adobe, MakeMyTrip, Jio, Paytm
04. Implement Currying with Placeholders- Medium
//// Asked in Amazon, Flipkart, Yandex, Xiaomi, Vimeo, Gojek, Zeta
05. Deep Flatten I- Medium
//// Asked in Roblox, Disney+ Hotstar, Rippling
06. Deep Flatten II- Medium
//// Asked in CoinSwitch
07. Deep Flatten III- Easy
08. Deep Flatten IV- Hard
//// Asked in Meta, TikTok, Google, Apple, Yandex, Flipkart
09. Negative Indexing in Arrays (Proxies)- Medium
10. Implement a Pipe Method- Easy
//// Asked in Adobe
11. Implement Auto-retry Promises- Medium
Interview.js
//// Asked in Amazon, Flipkart, Adobe, Paypal, Swiggy
12. Implement Promise.all- Medium
//// Asked in TikTok, Lyft, Snapchat, Disney+ Hotstar, MakeMyTrip, Jio,
MindTickle, Zepto
13. Implement Promise.allSettled- Medium
//// Asked in Tekion, Adobe
14. Implement Promise.any- Medium
//// Asked in Zepto
15. Implement Promise.race- Easy
//// Asked in Yandex
16. Implement Promise.finally- Medium
//// Asked in Google
17. Implement Custom Javascript Promises- Super Hard
//// Asked in Amazon, Airbnb, Tekion, Cars24
18. Throttling Promises by Batching- Medium
19. Implement Custom Deep Equal-Hard
//// Asked in Google, Tekion
20. Implement Custom Object.assign- Medium
//// Asked in ServiceNow, Flipkart
21. Implement Custom JSON.stringify- Hard
//// Asked in Meta
22. Implement Custom JSON.parse- Super Hard
//// Asked in Meta
23. Implement Custom typeof operator- Medium
24. Implement Custom lodash _.get()- Medium
//// Asked in TikTok, Amazon, Quizizz, MindTickle
25. Implement Custom lodash _.set()- Medium
26. Implement Custom lodash _.omit()- Medium
27. Implement Custom String Tokenizer- Medium
28. Implement Custom setTimeout- Medium
//// Asked in Swiggy, Disney+ Hotstar
29. Implement Custom setInterval- Medium
//// Asked in Meta, TikTok, Swiggy
30. Implement Custom clearAllTimers- Easy
//// Asked in Meta
31. Implement Custom Event Emitter- Medium
//// Asked in Meta, Flipkart, Adobe, Jio, Tekion
32. Implement Custom Browser History- Medium
33. Implement Custom lodash _.chunk()- Medium
34. Implement Custom Deep Clone-Medium
//// Asked in Adobe, Tekion, Navi
35. Promisify the Async Callbacks- Easy
//// Asked in Amazon
Interview.js
36. Implement 'N' async tasks in Series- Hard
//// Asked in Jio, MakeMyTrip, Tekion
37. Implement 'N' async tasks in Parallel- Medium
//// Asked in Zepto, Paytm, BookMyShow
38. Implement 'N' async tasks in Race- Easy
39. Implement Custom Object.is() method- Easy
40. Implement Custom lodash _.partial()- Medium
//// Asked in Meesho
41. Implement Custom lodash _.once()- Medium
42. Implement Custom trim() operation- Medium
43. Implement Custom reduce() method- Medium
//// Asked in Amazon, Apple, Expedia, Paytm, ByteLearn
44. Implement Custom lodash _.memoize()- Medium
//// Asked in Meta, Intuit, Gameskraft
45. Implement Custom memoizeLast() method- Medium
46. Implement Custom call() method- Medium
//// Asked in Meesho
47. Implement Custom apply() method- Medium
48. Implement Custom bind() method- Medium
//// Asked in Rippling, Flipkart, BookMyShow
Interview.js
49. Implement Custom React "classnames" library- Medium
//// Asked in Meta
50. Implement Custom Redux used "Immer" library- Medium
51. Implement Custom Virtual DOM- I (Serialize)- Hard
//// Asked in Meta
52. Implement Custom Virtual DOM- II (Deserialize)- Medium
//// Asked in Meta
53. Implement Memoize/Cache identical API calls- Hard
//// Asked in Facebook

