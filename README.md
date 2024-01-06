# IMDB-LLM: Movie Query Made Simple

![IMDB-LLM Demo](./image/llm-imdb.gif)

Welcome to IMDB-LLM, a proof of concept app that demonstrates the power of [LangChain](https://github.com/hwchase17/langchain) and LLMs in extracting information from graphs! 

## Overview

IMDB-LLM's Graph Explorer is built using [LangChain](https://github.com/hwchase17/langchain) and LLMs, state-of-the-art technologies in natural language processing and machine learning. The application employs a graph representation of the IMDB dataset, encompassing data on movies, actors, directors, and more. Users can input queries in natural language, such as "Give me some drama movie options with Leonardo DiCaprio" or "Show me movies directed by Christopher Nolan", and the LLM will retrieve the pertinent information from the graph.

Should the LLM be unable to provide an answer, it will utilize the Google Search API to find supplementary information, which it will then use to refine the search.

## Features

- Search for movie titles within the graph
- Discover similar movies using natural language queries
- Automatic Google search for missing information
