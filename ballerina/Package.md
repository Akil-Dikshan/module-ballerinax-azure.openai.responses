## Overview

[Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/) provides access to OpenAI's powerful language models including GPT-4o, GPT-4, and o-series models through Microsoft Azure's enterprise-grade infrastructure. The `ballerinax/azure.openai.responses` package offers functionality to connect and interact with the [Responses API](https://learn.microsoft.com/en-us/rest/api/aifoundry/) of the Azure AI Foundry Models Service, a stateful API supporting multi-turn conversations, built-in tools (web search, file search, code interpreter), and background processing. This connector exposes the create model response operation (`POST /responses`).

## Key Features

- Stateful, multi-turn conversational model responses
- Built-in tools: web search, file search, and code interpreter
- Background processing for long-running requests
- Authentication via Azure API key (`api-key` header)
