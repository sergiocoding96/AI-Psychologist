# AI-Psychologist
This is an AI counselor project

# AI Therapist Conversation App

This application provides a personalized mental wellness experience using AI from a large language model (LLM). It's designed to offer emotional support and coping strategies through empathetic conversations. You can share your thoughts and feelings confidentially and without worry, anytime you want, and get feedback in a seemingly conscientious and thoughtful manner. It gives you ideas to feel calmer and happier, and it's available 24/7.

## Demo

[https://ai-thera.vercel.app/](https://ai-thera.vercel.app/)

## Overview

- **Framework**: [Next.js](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Database**: [PlanetScale](https://planetscale.com/)
- **Cache**: [Upstash w/ Redis](https://upstash.com/)
- **ORM**: [Prisma](https://www.prisma.io/)
- **Authentication**: [Clerk](https://clerk.com/)
- **Deployment**: [Vercel](https://vercel.com)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/)
- **AI LLM**: [Meta's Llama 2 13b Chat - GPTQ
  ](https://replicate.com/lucataco/llama-2-13b-chat)
- **LLM Orchestration**: [Langchain](https://js.langchain.com/docs/get_started/introduction/)

## Running Locally

Clone GitHub repository, install the dependencies, and run the development server:

```bash
$ git clone https://github.com/neilgebhard/ai-therapist
$ cd ai-therapist
$ npm i
$ npm run dev
```

Create a .env file similar to .env.example with the required environment variables.

The app runs on [http://localhost:3000](http://localhost:3000).
