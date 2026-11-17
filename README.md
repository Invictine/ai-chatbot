# AI Chatbot

Understanding end-to-end generative AI application flow is best learned through clean separation of concerns. This full-stack starter pairs a responsive React frontend with an Express API gateway and OpenAI model completions, persisting session histories in MongoDB. Includes streaming token responses, syntax-highlighted code blocks, and configurable system instructions. Fork the repository as a clean launchpad for domain-specific conversational assistants.

[![AI Chatbot](media/overview.png)](media/walkthrough.mp4)
*Click preview above to watch illustrated architecture overview.*


## Explore the project

- [Frontend](AI%20chatbot/frontend) contains the Vite app and sign-in and chat views. From that folder, run `npm install` and `npm run dev`.
- [Backend](AI%20chatbot/backend) contains the TypeScript API. From that folder, run `npm install` then `npm run dev` for the compiler and development server.

A working chat requires a separately configured MongoDB instance and OpenAI API access. This is an archived development snapshot using an older provider SDK. Review the backend configuration locally before connecting either service.
