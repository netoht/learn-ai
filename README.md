# AI

> A curated list of resources, techniques, tools, and settings for building AI applications, with a focus on LLMs (Large Language Models) and AI code assistants.

## Blogs

- [The Pragmatic Engineer - Real-world engineering challenges: building Cursor](https://newsletter.pragmaticengineer.com/p/cursor)
- [Engineering at Anthropic - Building effective agents](https://www.anthropic.com/engineering/building-effective-agents)

## Techniques / Prompts

- [Prompt Engineering Guide - Prompting Techniques](https://www.promptingguide.ai/techniques)
- [Anthropic - Prompt engineering overview](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [llms-txt - A proposal to standardise on using an /llms.tx](https://llmstxt.org/)
- [Prompt Dev](https://gist.github.com/wesleywillians/5fcd35fd34efa265c56345e055b4270d)
- [Continue.dev - Custom AI code assistants](https://hub.continue.dev/explore/assistants)
- [Context7 - documentation for LLMs and AI code editors](https://context7.com/)

## Courses

- [Asimov - Chatbot de IA do zero](https://github.com/rtadewald/Agents-Prompts)
- [Web Security - Web LLM attacks](https://portswigger.net/web-security/llm-attacks)
- [Vector Databases com Qdrant](https://www.youtube.com/watch?v=KRiFMFVPL1Q)
- [DeepLearning.AI - All Courses](https://www.deeplearning.ai/courses/)
- [DeepLearning.AI - MCP: Build Rich-Context AI Apps with Anthropic](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)
- [Anthropic - Academy](https://www.anthropic.com/learn)
- [Anthropic - courses](https://github.com/anthropics/courses)
- [Anthropic - AI Fluency](https://www.anthropic.com/ai-fluency)
- [OpenAI - Academy](https://academy.openai.com/)
- [OpenAI - A practical guide to building agents](https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf)
- [Microsoft - Develop Generative AI solutions with Azure OpenAI in Foundry Models](https://learn.microsoft.com/en-us/training/paths/develop-ai-solutions-azure-openai/)
- [FC - MBA Engenharia de Software com IA](https://ia.fullcycle.com.br/mba-ia/)

## Tools

- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- [LM Studio - Your local AI toolkit](https://lmstudio.ai/)
- [Abacus.AI - ChatLLM Teams](https://chatllm.abacus.ai/)
- [Roo Code - Your AI-Powered Dev Team, Right in Your Editor](https://roocode.com/)
- [Pinecone - The vector database for scale in production](https://www.pinecone.io/)
- [LlamaIndex - Build AI Knowledge Assistants over your enterprise data](https://www.llamaindex.ai/)
- [SearXNG - free internet metasearch engine which aggregates results from various search services and databases](https://github.com/searxng/searxng)
- [TaskMaster - An AI-powered task-management system you can drop into Cursor, Lovable, Windsurf, Roo, and others.](https://github.com/eyaltoledano/claude-task-master)
- [Google Cloud - Model Armor overview (Security)](https://cloud.google.com/security-command-center/docs/model-armor-overview)
- [docling - Get your documents ready for gen AI](https://github.com/docling-project/docling)
- [OpenRouter - The Unified Interface For LLMs](https://openrouter.ai/)

#### MCP

- [Model Context Protocol (MCP) - Introduction](https://modelcontextprotocol.io/introduction)
- [Model Context Protocol - servers](https://github.com/modelcontextprotocol/servers)
- [Awesome MCP Servers](https://mcpservers.org/)
- [GitHub's official MCP Server](https://github.com/github/github-mcp-server)
- [Glama - Open-Source MCP servers](https://github.com/punkpeye/awesome-mcp-servers)
- [DockerHub - MCP Servers](https://hub.docker.com/catalogs/mcp)
- [MCP Server Prompt Generator For Devs Guide](https://github.com/wesleywillians/mcp-prompts-for-devs)
- [dbhub - Universal database MCP server connecting to MySQL, PostgreSQL, Oracle, SQL Server, MariaDB, SQLite.](https://github.com/bytebase/dbhub/)

#### Agents - Frameworks / Libraries

- [Google Agent Development Kit (ADK)](https://google.github.io/adk-docs/)
- [ADK - Common Multi-Agent Patterns](https://google.github.io/adk-docs/agents/multi-agents/#2-common-multi-agent-patterns-using-adk-primitives)
- [Microsoft - Multi-agent design patterns](https://github.com/microsoft/ai-agents-for-beginners/tree/main/08-multi-agent)
- [LangChain](https://www.langchain.com/)
- [LangGraph](https://www.langchain.com/langgraph)
- [CrewAI - The Leading Multi-Agent Platform](https://www.crewai.com/)
- [Microsoft AutoGen](https://microsoft.github.io/autogen/)
- [LiteLLM - LLM Gateway to provide model access](https://docs.litellm.ai/docs/)
- [ADK - Sistema de Criação de Posts com Múltiplos Agentes de IA](https://github.com/elvisassis/multiple_agents_to_post_instragram)

## IDEs / Settings

- [Cursor - Context Rules](https://docs.cursor.com/context/rules#rule-structure)
- [VSCode - GitHub Copilot](https://code.visualstudio.com/docs/copilot/overview)
- [VSCode - GitHub Copilot Customization](https://code.visualstudio.com/docs/copilot/copilot-customization)

#### VSCode

`settings.json`

```json
{
  "github.copilot.chat.codeGeneration.instructions": [
    { "file": ".vscode/rules/javascript/coding-guidelines.md" },
    { "file": ".vscode/rules/javascript/coding-style.md" }
  ],
  "github.copilot.chat.reviewSelection.enabled": true,
  "chat.promptFiles": true,
  "chat.promptFilesLocations": {
    ".github/prompts": true,
    ".vscode/prompts": true
  }
}
```
