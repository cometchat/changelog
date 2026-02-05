# AI Agents v0.3.1 | 2026-02-03
## New
- Added support for authentication and custom variables in agents created via Agent Builder, enabling dynamic personalization and user-based access control across instructions and API tools (headers and request bodies). Custom variables can source values from message metadata, user metadata, or constants.
- Added support for Frontend Actions in agents created via Agent Builder, allowing agents to trigger UI interactions like opening forms, navigating screens, or executing client-side workflows.

## Enhancements
- None

## Fixes
- Fixed an issue where the `text_message_start` event was not being emitted for agents created via Agent Builder.

# AI Agents v0.3.0 | 2026-01-07

## New
- Added support for LangGraph Agents.
- Added support for CrewAI Agents.

## Enhancements
- None

## Fixes
- Fixed an issue that resulted in deleted messages being processed.
</br>

# AI Agents v0.2.1 | 2025-12-24

## New
- None

## Enhancements
- None

## Fixes
- Fixed an issue where messages were duplicated in agents created via Agent Builder.
- Fixed an issue where messages were duplicated in BYO agents.
</br>

# AI Agents v0.2.0 | 2025-12-17

## New
- Added support for connecting websites as data sources to the Knowledge Base in Agent Builder.
- Added new OpenAI LLMs to Agent Builder.
  - gpt-5.2-chat-latest
  - gpt-5.2  
  - gpt-5.1-chat-latest
  - gpt-5.1
- Added support for Google LLMs in Agent Builder.
  - gemini-2.5-flash
  - gemini-2.5-flash-lite

## Enhancements
- None

## Fixes
-  None
</br>

# AI Agents v0.1.0 | 2025-12-03

## New
- Added RAG support to the Agent Builder, enabling file uploads and text content to be included as part of an agent’s knowledge base.

## Enhancements
- None

## Fixes
- Added a fix to skip action messages from being processed.

</br>

# AI Agents v0.0.9 | 2025-11-18

## New
- Enabled OpenAI GPT-5–based models in Agent Builder.
- Added Google Tool Suite in Agent Builder (includes tools for creating calendar events, sending emails, and other Google Workspace actions).
- Added support for the latest Mastra agents powered by AI SDK v5.

## Enhancements
-  None

## Fixes
-  None
</br>

# AI Agents v0.0.8 | 2025-11-10

## New
-  None

## Enhancements
-  Introduced the ability to create AI agents directly within CometChat. Users can select models, add tools, and configure agents without relying on external services.

## Fixes
-  Fixed an issue where one-on-one messages not intended for AI agents were being processed.

<br/>

# AI Agents v0.0.7 | 2025-11-05

## New
-  Added support for AG-UI Agents.

## Enhancements
-  None

## Fixes
-  None

<br/>

# AI Agents v0.0.6 | 2025-10-31

## New
-  Added support for Agno Agents.
-  Added support for Rasa Agents.

## Enhancements
-  None

## Fixes
-  None

<br/>

# AI Agents v0.0.5 | 2025-10-14

## New
-  Added support for Vercel v5 Agents.
-  Added support for AG2 Agents.

## Enhancements

-  None

## Fixes

-  Added a fix to skip group messages from being processed.
   
<br/>

# AI Agents v0.0.3 | 2025-09-23

## New
-  Added support for providing authentication and custom context to agents.

## Enhancements

-  None

## Fixes

-  None
   
<br/>

# AI Agents v0.0.2 | 2025-9-16

## New
-  None

## Enhancements

-  None

## Fixes

-  Fixed an issue that caused the server to crash.
   
<br/>

# AI Agents v0.0.1 | 2025-08-14

## New
- Introduced **AI Agents**, a new feature enabling intelligent, automated interactions across supported modules. This marks the initial release of AI Agents, laying the foundation for future capabilities.


## Enhancements

-  None

## Fixes

-  None
   
<br/>