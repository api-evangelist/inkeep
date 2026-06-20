# Inkeep (inkeep)

Inkeep is an AI support and agent platform for documentation and products. Its developer platform exposes an OpenAI-compatible RAG / chat completions API over your own content, an Analytics API for logging conversations, feedback, and events, and an Agents / management surface for building and operating AI agents and copilot experiences.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/inkeep/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/inkeep/refs/heads/main/apis.yml)

## Tags

- AI
- Support
- RAG
- Agents
- Documentation

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Inkeep Chat Completions (RAG) API

OpenAI-compatible chat completions endpoint that runs retrieval-augmented generation over your own content. Modes (inkeep-qa, inkeep-context, inkeep-rag, inkeep-base) are selected through the OpenAI `model` field, with streaming via Server-Sent Events and citations returned alongside answers.

- **Human URL:** [https://docs.inkeep.com/cloud/ai-api/chat-completions-api](https://docs.inkeep.com/cloud/ai-api/chat-completions-api)
- **Base URL:** `https://api.inkeep.com/v1`

#### Tags

- Chat
- Completions
- RAG
- LLM

#### Properties

- [Documentation](https://docs.inkeep.com/cloud/ai-api/chat-completions-api)
- [API Reference](https://docs.inkeep.com/cloud/ai-api/rag-mode)
- [OpenAPI](openapi/inkeep-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/inkeep-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/inkeep.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/inkeep.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Inkeep Analytics API

Logs and retrieves OpenAI-compatible conversations, captures end-user feedback, and records custom interaction events (answer_copied, chat_shared) so usage and quality are viewable and reportable in the Inkeep Portal.

- **Human URL:** [https://docs.inkeep.com/cloud/overview/developer-platform](https://docs.inkeep.com/cloud/overview/developer-platform)
- **Base URL:** `https://api.inkeep.com/v1`

#### Tags

- Analytics
- Conversations
- Feedback
- Events

#### Properties

- [Documentation](https://docs.inkeep.com/cloud/overview/developer-platform)
- [OpenAPI](openapi/inkeep-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/inkeep.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/inkeep.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Inkeep Agents / Management API

REST management surface for the Inkeep Agents framework - create and operate agents, sub-agents, projects, tools, MCP servers, conversations, and feedback for building no-code or TypeScript-SDK AI agent workflows.

- **Human URL:** [https://docs.inkeep.com/api-reference](https://docs.inkeep.com/api-reference)
- **Base URL:** `https://api.inkeep.com`

#### Tags

- Agents
- Management
- Projects
- Conversations

#### Properties

- [Documentation](https://docs.inkeep.com/api-reference)
- [API Reference](https://docs.inkeep.com/api-reference)

## Common Properties

- [GitHub Organization](https://github.com/inkeep)
- [LinkedIn](https://www.linkedin.com/company/inkeep)
- [Website](https://inkeep.com)
- [Documentation](https://docs.inkeep.com)
- [Plans](plans/inkeep-plans-pricing.yml)
- [Rate Limits](rate-limits/inkeep-rate-limits.yml)
- [Fin Ops](finops/inkeep-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
