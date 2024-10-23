# Request Finance Agent

<img src="https://github.com/user-attachments/assets/aa54bac4-30ef-49bb-bac7-732ff561bd95" alt="cover_image" width="0"/>

Request Finance Agent is a template for creating a Bitte.ai Plugin for facilitating invoicing using Request Finance. Built using Next.js 14 + Elysia.

[![Demo](https://img.shields.io/badge/Demo-Visit%20Demo-brightgreen)](https://ref-finance-agent-next.vercel.app/)
[![Deploy](https://img.shields.io/badge/Deploy-on%20Vercel-blue)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FMintbase%2Fref-finance-agent-next)

**Tooling:**

[![Use Case](https://img.shields.io/badge/Use%20Case-AI-blue)](#)
[![Framework](https://img.shields.io/badge/Framework-Next.js%2014-blue)](#)

## Project Walkthrough

Request Finance Agent facilitates the development of AI-powered. [Build your own agent](https://docs.mintbase.xyz/ai/assistant-plugins)

#### API Base URL

https://request-finance-agent-next.vercel.app

#### Endpoints

- Send Invoice `POST` `/api/invoice/`

- Token Metadata `GET` `/api/token/{token}`

- Swap Transactions `GET` `/api/swap/{tokenIn}/{tokenOut}/{quantity}`

#### Usage
Make LLM requests to the endpoints above. Refer to the full API documentation for detailed parameter and response information.


## Getting Started
[Docs to integrate](https://docs.bitte.ai/agents/quick-start)  

### Installation

Set `NEAR_ENV="mainnet"` in your `.env.local` file.

```bash
# install dependencies
pnpm i

# start the development server
pnpm dev
```


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

<img src="https://i.imgur.com/fgFX6BS.png" alt="detail_image" width="0"/>


