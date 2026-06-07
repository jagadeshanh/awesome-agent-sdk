# Awesome Agent SDK

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Agent SDKs and frameworks for building intelligent agents, orchestrations, and agentic workflows.

Agent SDKs empower developers to create autonomous agents, multi-agent systems, and complex orchestrations with minimal boilerplate. This list compiles the most comprehensive and openly available Agent SDKs across different platforms and languages.

## Table of Contents

- [Core Agent SDKs](#core-agent-sdks)
- [Language-Specific SDKs](#language-specific-sdks)
- [Agent Orchestration & Frameworks](#agent-orchestration--frameworks)
- [AI Model Providers](#ai-model-providers)
- [Development Tools](#development-tools)
- [Resources & Documentation](#resources--documentation)
- [Contributing](#contributing)

## Core Agent SDKs

### [Claude Agent SDK (Python)](https://github.com/anthropics/claude-agent-sdk-python)
Official Python SDK from Anthropic for building agents with Claude. Features tool use, multi-turn conversations, and enterprise-grade reliability.
- **Language**: Python
- **Features**: Tool calling, streaming, async support, built-in safety
- **Best for**: Production agents with Claude models

### [GitHub Copilot SDK](https://github.com/github/copilot-sdk)
Build agents and extensions powered by GitHub's Copilot capabilities.
- **Language**: JavaScript/TypeScript
- **Features**: Chat API, code analysis, GitHub integration
- **Best for**: GitHub-integrated AI experiences

### [ADK (Autogen Development Kit)](https://adk.dev/)
Comprehensive framework for building multi-agent systems and orchestrations.
- **Language**: Multiple
- **Features**: Agent coordination, complex workflows, multi-agent patterns
- **Best for**: Complex agent orchestrations and multi-agent systems

## Language-Specific SDKs

- [Python Agent SDKs](#python)
- [JavaScript/TypeScript Agent SDKs](#javascripttypescript)
- [Java Agent SDKs](#java)
- [Go Agent SDKs](#go)

### Python
- **[Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python)** - Official Anthropic SDK
- **[LangChain](https://www.langchain.com/)** - Framework for developing applications powered by language models
- **[LlamaIndex](https://www.llamaindex.ai/)** - Data framework for LLM applications
- **[CrewAI](https://www.crewai.com/)** - Framework for orchestrating autonomous agents
- **[Autogen](https://microsoft.github.io/autogen/)** - Microsoft's framework for multi-agent conversation

### JavaScript/TypeScript
- **[GitHub Copilot SDK](https://github.com/github/copilot-sdk)** - Official GitHub SDK
- **[Vercel AI SDK](https://sdk.vercel.ai/)** - TypeScript library for building AI applications
- **[LangChainJS](https://js.langchain.com/)** - JavaScript version of LangChain
- **[OpenAI Node SDK](https://github.com/openai/node-sdk)** - Official OpenAI SDK with agent capabilities

### Java
- **[LangChain4j](https://github.com/langchain4j/langchain4j)** - Java port of LangChain
- **[Spring AI](https://spring.io/projects/spring-ai)** - Spring integration for AI models

### Go
- **[LangChain Go](https://github.com/tmc/langchain)** - Go implementation of LangChain
- **[GoLLM](https://github.com/hupe1980/go-ollm)** - Simple Go library for LLM agents

## Agent Orchestration & Frameworks

- **[Autogen](https://microsoft.github.io/autogen/)** - Create multi-agent conversations with dynamic agent roles
- **[CrewAI](https://www.crewai.com/)** - Role-based agent orchestration framework
- **[Langflow](https://www.langflow.org/)** - Low-code agent workflow builder
- **[Flowise](https://flowiseai.com/)** - Visual builder for LLM and agent workflows
- **[N8N](https://n8n.io/)** - Workflow automation with agent capabilities

## AI Model Providers

- **[Anthropic Claude](https://www.anthropic.com/)** - Claude model family with agentic capabilities
- **[OpenAI](https://openai.com/)** - GPT models with function calling for agent use
- **[Google Gemini](https://deepmind.google/technologies/gemini/)** - Multi-modal models with agent features
- **[Hugging Face](https://huggingface.co/)** - Open-source models and inference APIs
- **[Cohere](https://cohere.com/)** - Command models optimized for enterprise agents
- **[Replicate](https://replicate.com/)** - Run open-source models as APIs

## Development Tools

### SDKs & Libraries
- **[LangChain](https://www.langchain.com/)** - Comprehensive framework for LLM applications
- **[LlamaIndex](https://www.llamaindex.ai/)** - Data indexing and retrieval for agents
- **[Pydantic AI](https://ai.pydantic.dev/)** - Type-safe agent framework for Python
- **[Swarm](https://github.com/openai/swarm)** - Educational framework for multi-agent coordination

### Hosting & Deployment
- **[Vercel](https://vercel.com/)** - Deploy AI agents and applications
- **[Modal](https://modal.com/)** - Cloud functions for agents
- **[Ray](https://www.ray.io/)** - Distributed computing for multi-agent systems
- **[Hugging Face Spaces](https://huggingface.co/spaces)** - Free hosting for agent demos

### Monitoring & Evaluation
- **[LangSmith](https://smith.langchain.com/)** - Debugging and monitoring for LLM applications
- **[OpenTelemetry](https://opentelemetry.io/)** - Observability for AI systems
- **[Weights & Biases](https://wandb.ai/)** - Experiment tracking for AI agents

## Resources & Documentation

### Official Documentation
- [Anthropic Claude Documentation](https://docs.anthropic.com/)
- [GitHub Copilot SDK Docs](https://github.com/github/copilot-sdk)
- [ADK Documentation](https://adk.dev/docs)
- [LangChain Documentation](https://docs.langchain.com/)

### Learning Resources
- [Agent Design Patterns](https://www.anthropic.com/research/agent-design-patterns)
- [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)
- [Multi-Agent Systems](https://arxiv.org/abs/2402.06391)

### Example Projects
- [Claude Agent Examples](https://github.com/anthropics/agents-examples)
- [LangChain Examples](https://github.com/langchain-ai/langchain/tree/master/examples)
- [AutoGen Notebooks](https://github.com/microsoft/autogen/tree/main/notebook)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. To add new SDKs or resources:

1. Add entries in the appropriate section, maintaining alphabetical order where applicable
2. Include a brief description and relevant tags (Language, Features)
3. Ensure links are verified and up-to-date
4. Follow the format of existing entries

## License

This awesome list is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

---

**Note**: This is a community-curated list. If you know of other great Agent SDKs that should be included, please [open an issue](https://github.com/your-repo/issues) or submit a pull request!

**Last Updated**: June 2026
