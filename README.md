# Dream Journal

An easy way to record and keep track of your dreams

# Features
-Write and save dreams by the date
-Search for certain dreams with keywords
-Record yourself describing your dreams and have the transcribed text (and possibly AI summaries) saved to that dream's record
-(Coming later) multi-user login?

## Tech Stack

- **Frontend:** Next.js 14, React, TypeScript
- **Styling:** Tailwind CSS
- **Transcription:** OpenAI Whisper (via API route)
- **Storage:** Local JSON / PostgreSQL (via Supabase or Prisma, planned)





## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
