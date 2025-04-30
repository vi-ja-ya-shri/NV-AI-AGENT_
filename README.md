# 🤖 NV AI Agent – Tool-Augmented AI Built with Next.js 15, LangChain, IBM, Clerk, and Convex

NV AI is a powerful, production-ready AI Agent built using cutting-edge technologies: Next.js 15, React 19, LangChain, LangGraph, IBM WxFlows, Clerk, Convex, and OpenAI.
This agent can intelligently interact with external tools, deliver real-time streaming responses, and operate through a modern, dynamic chat interface — built for real-world AI applications.

# 🚀 Features

-🤖 Advanced AI chat interface powered by OpenAI 

-🎨 Modern, responsive UI with Tailwind CSS

-🔐 Authentication via Clerk with Passkey support

-💾 Real-time database with Convex

-⚡ Built using Next.js 15 + React 19

-🌊 Live token streaming with custom implementation

-📱 Fully mobile-friendly design

-🧠 Prompt caching for optimized token usage

-🔧 Intelligent tool orchestration with LangGraph

-🔄 Real-time updates & tool execution feedback

-📚 Seamless IBM WxFlows integration for data/tool APIs

# 🧱 Tech Stack

| Category         |           Stack / Library                |
|------------------|------------------------------------------|
| Frontend         | Next.js 15.1.3, React 19                 |
| UI               | Tailwind CSS, Shadcn/UI                  |
| AI Integration   | OpenAI, LangChain, LangGraph             |
| Auth             | Clerk                                    |
| Database         | Convex                                   |
| Dev Tools        | TypeScript, Vercel, Lucide/Radix UI Icons|


# 🧠 AI & Prompt Management :-
-Prompt Caching: Optimized token usage with custom caching logic.

-Context Window: Smart 4K token context handling.

-Tool-Augmented Replies: AI responses enhanced with integrated tools.

-Context-Aware Conversations: Dynamically managed context and message history.


# 🧰 Tool Integration via IBM WxFlows :-
-One-click tool creation from APIs

-YouTube transcript integration

-Google Books API support

-Custom data source tooling


# 🕸️ LangChain + LangGraph Features :-
-📊 StateGraph: Smart and modular state management

-🔧 ToolNode: Tool orchestration with contextual awareness

-🧠 MemorySaver: Efficient memory management

-✂️ Message Trimming: Maintains conversation quality


# 🔄 Streaming Implementation :-
-✅ Live token streaming from OpenAI

-🔧 Real-time feedback on tool execution

-⚠️ Built-in error handling for tool failures

-🚧 LangChainAdapter workarounds


# 📡 Real-Time Features
-⚡ Live message delivery and sync

-🔍 Real-time tool interaction visualization

-🕓 Efficient message history management


# 🔐 Authentication & Data Sync
-Clerk for secure login/signup with Passkey support

-Convex for real-time data persistence and sync


# 📦 Prerequisites
-[Node.js](https://nodejs.org/en/download)(Latest LTS),

-[Next.js 15.1.3](https://nextjs.org/docs/app/getting-started/installation),

-[Tailwind CSS](https://v3.tailwindcss.com/docs/installation),

-[Shadcn/UI](https://ui.shadcn.com/docs/installation/next),

-[LangChain](https://python.langchain.com/v0.1/docs/get_started/quickstart/) (Your model should be compatible with this , check its docs to verify and initialize model)

-[Clerk account (auth)](https://clerk.com/)

-[Sign up for Convex account (database)](https://www.convex.dev/signup)

-[IBM WxFlows account (tools)](https://wxflows.ibm.stepzen.com/)

-OpenAI API key (ai model) or any model of your choice , initialize model changes in LangGraph according to your model.

-PNPM (preferred) / NPM / Yarn

# 🛠️ Installation
# Clone the repo
git clone (https://github.com/vi-ja-ya-shri/NV-AI-AGENT_)
cd nv-ai-agent

# Install dependencies
pnpm install

# Start the dev server
pnpm dev

App runs at http://localhost:3000

# ⚙️ Performance Optimizations :- 
-Token-optimized prompt caching

-Context window trimming

-Minimal API calls with memory caching

-Streamlined server-side logic

# 🌟 Acknowledgements
Thanks to PapaReact for the inspiration and guidance!
Powered by LangChain, IBM, Convex, Clerk, and OpenAI


## Learn More
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!
