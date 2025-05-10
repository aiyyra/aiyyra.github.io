---
title: "Second project in 2025"
date: 2025-05-10
permalink: /posts/2025/05/second-project-2025/
tags:
  - project
  - progress
---

# Second Project

Do you remember the project I last mentions - Link summariser. I planned a lot for that but it is a relatively easy project. I finished it within 5 days of starting the development. I thought on making it more complex but I will just stuck with the original plan and make my next project a lot complex.

# Link Summariser

So let me give an overview about the project. The initial plan was to create an agentic system that will take my link and summarize it for me. It is too simple and does not really need an agentic system. Therefore, I do make a small changes into the system.

1. This project could take any query, text or links.
2. Based on the input, it will either research, summarizer and search the web for the results.
3. The agent that are used in this project is from llama scout hosted on groq api. It is used as a tool calling agent that will responds according to my query.

For this project, I create 3 tools:

1. searching tool with tavily api
2. crawling tool using beautifolSoup
3. Summarizing tool which calls another groq model to summarize given knowledge.

### Limitation/ Improvement on future projects

1. This project is run only on terminal. I personally thing this will forever be on the improvements list as I am less passionate on building UI
2. This project does not have any memory. One small reasons is to make the token usage controlled, but it does make the system capabilities limited to one query per session.
3. This system always summarizes whatever knowledge it retrieves from the web. This is due to the token limitation that we have.
4. The search quality when using search tool is quite bad given the high standard that I have. Maybe future prompt-tuning could solve this issues.
5. One obvious improvement I would love to add is creating a RAG enabled system.
6. I would also love to make it multi-agent environment. I already look into it and the popular options is either crew ai or langgraph.

# Next

I would spend most of my times in my university course as this upcoming months is critical for my programme. But worry not, I will find more times to make personal project as I think that the course in my university would not be enough.

I am looking foward to make a project to learn more on multi-agent system, I already learn RAG implementation from previous projects (htmx-summarizer), so I would try to hold back from including it on the next project. I would also love to use Langgraph for the orchestration of my agents.

> Note: Btw, as of how things stand, my FYP looks like it will need multi-agent with langgraph(for parallel agent call), RAG(for accurate Information Retrieval), a good enough UI, an integrated memory system and (maybe) chat interactions. Overall pray for my wallet and hope it will goes smoothly.
