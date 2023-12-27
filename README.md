# OpenAI platform

A proxy/middleware to perfectly emulate the OpenAI APIs platform and implement all endpoints.

## Why not just use open source servers like OobaBooga or FastChat?

Open source servers do implement OpenAI-compatible endpoints however  
They DO NOT implement everysingle endpoint.

If you want to use multiple services such as: LLM and embeddings, you will have to run a server for LLMs and a server for embeddings

This will collect all:
- image generation
- text completion
- text embeddings
- listing models
