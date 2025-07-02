---
layout: default
title: Blog
---

# 📝 Blog

Welcome to my blog! I write about:

- RAG and Retrieval-Augmented Generation techniques
- LangChain, Gemini, and Vector DBs
- Kubernetes deployments for ML
- Building enterprise-grade Conversational AI
- MLOps pipelines and LLM applications

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}
