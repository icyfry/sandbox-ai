# Sandbox AI

Tools Required
* [taskfile](https://taskfile.dev/)
* docker

Setup the repository
```
task docker-build
```

## Tools
* [Cursor code editor](https://cursor.com/home)
* [Gemini CLI](https://github.com/google-gemini/gemini-cli)
* [Ollama](https://ollama.com/)

## Models

### Ollama

Launch ollama docker container with `task ollama-run` and access the container with `task ollama-shell` or with api on port `11434`

* [LLaMA](https://fr.wikipedia.org/wiki/LLaMA)
```
docker exec -it ollama ollama run llama3
```

## MCP

* [modelcontextprotocol.io](https://modelcontextprotocol.io/introduction)
* [docker MCP](https://docs.docker.com/ai/mcp-catalog-and-toolkit/toolkit/)

## SDK and Frameworks

### Python

* [PyTorch](https://pytorch.org/)
* [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)
* [Langraph (AI agents)](https://www.langchain.com/langgraph)

### Typescript

* [AI Toolkit for TypeScript](https://ai-sdk.dev/) by [vercel](https://vercel.com/)