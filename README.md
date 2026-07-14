# AI Chatbot — Frontend

React + Vite client for the AI Chatbot demo. Talks to the [backend repo](../ai-chatbot-backend) over HTTP.

## Setup

```bash
npm install
cp .env.example .env
# edit .env if your backend isn't on localhost:6767
npm run dev
```

## Environment Variables

| Variable | Description | Default |
|---|---|---|
| `VITE_API_BASE_URL` | Base URL of the backend API | `http://localhost:6767/api` |

> `.env` is git-ignored — never commit it.

## Build

```bash
npm run build
```
