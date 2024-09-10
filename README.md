# Project Proposal: WebIndex

## Project Title
WebIndex: AI-Powered Site Search

## What and Why?

I propose building an LLM-powered search engine for individual websites. Traditional search functions often return a large number of irrelevant results, requiring users to sift through pages of data. WebIndex will provide fast, summarized results, improving productivity and enhancing the user experience. With LLMs, the search engine can rapidly analyze results and provide a summarized output.

## For Whom

This software targets medium to large businesses that rely on website visitors to find information quickly, such as e-commerce stores, corporate sites, and educational platforms. Our initial focus will be on a few select companies to refine the design.

## How?

The process involves two steps for the end-user:

1. Allow our crawler to index the website. For public websites, users simply authorize access. For internal sites requiring login, users provide a valid cookie.
2. Embed our search plugin into their webpage, enabling visitors to use it directly.

## Scope

The project is well-suited for a group of 4-6 programmers. Here is the breakdown of the project:
- A crawler that handles diverse web pages and converts them to precise text content, with algorithms to iterate through entire sites. (2 developers)
- An AI backend that processes website data, stores it, generates embeddings, builds an index, and interacts with LLM APIs to summarize search results. (1-2 developers with LLM experience)
- A frontend plugin that integrates seamlessly into client websites, enabling users to search effectively. (1 frontend developer)
