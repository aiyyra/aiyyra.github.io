---
title: "Current personal project"
date: 2025-02-18
permalink: /posts/2025/02/current-personal-project/
tags:
  - progress
  - project
---

# Current Project and Update

Hello this is Afiq, feels nice to make an update in my blog for the first time. I am hoping to post at least 1 post per month.

Current Update for me is im doing a personal project based on Daniel Bourke yt channel which is a local RAG pipeline.

I start this project around 3 days ago and today i just finished my final data preprocessing.

## About the project

Im planning to make a htmx-helper chat.

It will use htmx book data that i crawl

### Steps for this project

1. Crawl data on htmx url. `(I have done this with Golang and colly library)`
2. Process the data into chunks of text that would fit into the token size of our embeddings model
3. embed the chunks of text from the htmx books into vector embeddings and save it for later use
4. Utilise a ranking system to evaluate query and embedded data
5. Run a local LLM and embed useful data/ info from the htmx book into the query
6. Generate response!!!!

RAG = retrievel, augment, generation

- step 1 ~ 3 is to help with our retrieval process
- step 4 ~ 5 is the augment process
- step 6 is where we generate the reponse with our llm and the augmented info from htmx book

### Current situation

I have finish the data preprocessing and I can start to embed our data already.

However, we do run into issues regarding our resource to utilise and run an LLM model.

My Professor said he is likely to help me with the GPU and other resources, so I will update later when it happens.

Thats it for now, hope this blog will continue for a long time, so i can keep track and consistent in my learning journey.

> Goodbye
