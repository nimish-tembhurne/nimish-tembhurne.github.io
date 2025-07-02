---
layout: default
title: Blog
---

# 📝 Blog

Welcome to my blog! Here, I share:

- **Technical Insights:** Deep dives into AI, ML, LLMs, and MLOps, covering topics like RAG, LangChain, Gemini, Vector DBs, Kubernetes deployments, and building conversational AI.
- **Learnings from Studies:** Key takeaways from courses, research papers, books, and documentation.
- **Project Notes:** Experiences and lessons from side projects, coding hacks, and debugging challenges.
- **Reflections:** Thoughts on productivity, continuous learning, and life in the world of technology.

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}