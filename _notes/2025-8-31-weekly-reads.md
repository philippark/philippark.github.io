---
layout: post
---

Interesting articles I read this week:

[martinfowler.com: AI Thoughts](https://martinfowler.com/articles/202508-ai-thoughts.html)  
- very interesting idea is that other engineering fields deal with indeterminism, and software was unique for being 
deterministic. but now with ai, we are finally joining the other engineering fields lol. 

[simonwillison.net: The Lethal Trifecta](https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/)  
- When an llm has access to private data, untrusted content, and communication to the external world, that is 
called the "lethal trifecta", and is always a security risk due to threats like prompt injections.
- prompt injection meaning a lethal instruction disguised in a text that makes the model act in a harmful way to its user/owner.
- That implies the MCP is also a security risk.

[simonwillison.net: Agentic Browser Security](https://simonwillison.net/2025/Aug/25/agentic-browser-security/)  
- Cool approach from Google Deepmind on dealing with prompt injections. 
- Essentially, uses the concept of a privilege and quarantine LLM, but adds additional security to the quarantine LLM by converting
the prompt into Python code and using a custom Python interpreter to make sure certain precautionary rules are applied.

[seangoedecke.com: The Simplest Thing That Could Possibly Work](https://www.seangoedecke.com/the-simplest-thing-that-could-possibly-work/)