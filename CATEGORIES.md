# Agent SDK Categories Guide

## Understanding Agent Types

### Core Agent SDKs
These are official SDKs provided by major AI companies and platforms. They typically include:
- Direct API access to their AI models
- Agent/tool calling capabilities
- Built-in safety and reliability features
- Comprehensive documentation and support

**When to use**: You want official support and deep integration with a specific AI provider.

### Language-Specific SDKs
SDKs optimized for specific programming languages. These might wrap multiple providers or be language-first frameworks.

**When to use**: You have a preferred or required programming language for your project.

### Agent Orchestration & Frameworks
Tools and frameworks designed to coordinate multiple agents or manage complex workflows.

**When to use**: You're building:
- Multi-agent systems where agents collaborate
- Complex workflows with conditional logic
- Systems where agents need to communicate or delegate tasks

### AI Model Providers
Services that provide the underlying AI models. You'll combine these with SDKs to build agents.

**When to use**: Evaluating different AI model options for your agents or comparing model performance.

### Development Tools
Supporting libraries, hosting platforms, and monitoring tools that complement your Agent SDK choice.

**When to use**: You need to host, monitor, or enhance your agent applications.

## Common Use Cases

### Building Your First Agent
**Recommended Stack**:
- SDK: Claude Agent SDK or OpenAI SDK
- Framework: LangChain or Pydantic AI
- Hosting: Vercel or Modal
- Monitoring: LangSmith

### Enterprise Multi-Agent System
**Recommended Stack**:
- Framework: AutoGen or CrewAI
- SDK: Claude Agent SDK or Cohere
- Hosting: Ray or Modal
- Monitoring: LangSmith + OpenTelemetry

### GitHub-Integrated AI
**Recommended Stack**:
- SDK: GitHub Copilot SDK
- Framework: LangChain (JavaScript)
- Hosting: Vercel

### Low-Code Agent Workflows
**Recommended Stack**:
- Framework: Langflow or Flowise
- Models: Any supported provider
- Hosting: Built-in or self-hosted

### Open-Source Only
**Recommended Stack**:
- Framework: AutoGen or LlamaIndex
- Models: Llama2, Mistral, or other open models from HuggingFace
- Hosting: Self-hosted or HuggingFace Spaces

## Decision Matrix

| Need | Best Option |
|------|------------|
| Official support | Claude Agent SDK, OpenAI SDK, GitHub Copilot SDK |
| Multi-agent coordination | AutoGen, CrewAI, ADK |
| Data-aware agents | LlamaIndex |
| Quick prototyping | Langflow, Flowise |
| Production deployment | LangChain + LangSmith |
| Type safety | Pydantic AI |
| JavaScript/TypeScript | Copilot SDK, Vercel AI SDK, LangChainJS |
| Distributed systems | Ray, AutoGen |

## Learning Path

1. **Start Here**: Choose a Core Agent SDK matching your AI provider preference
2. **Build Simple**: Create your first agent using official examples
3. **Add Complexity**: Integrate with a framework (LangChain, Pydantic AI, CrewAI)
4. **Multi-Agent**: Explore orchestration frameworks for complex systems
5. **Production**: Deploy with monitoring and observability (LangSmith, OpenTelemetry)

---

For questions or clarifications, please refer to individual project documentation or open an issue in this repository.
