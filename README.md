
---

# 🛡️ Warden Mint Story 🎙️✨

**Guard your legacy. Mint your story. Own your on-chain identity.**

[![Tailwind CSS 4](https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?logo=tailwindcss&logoColor=white&style=flat-square)](https://tailwindcss.com/)
[![OnchainKit](https://img.shields.io/badge/Coinbase-OnchainKit-0000FF?logo=coinbase&logoColor=white&style=flat-square)](https://onchainkit.xyz)
[![Coinbase CDP](https://img.shields.io/badge/Coinbase-CDP-000?logo=coinbase&logoColor=white&style=flat-square)](https://docs.cdp.coinbase.com/)
[![Farcaster MiniApp](https://img.shields.io/badge/Farcaster-MiniApp-6f3aff?style=flat-square)](https://www.farcaster.xyz/)
[![Base Network](https://img.shields.io/badge/Base-Mainnet-0052FF?logo=coinbase&logoColor=white&style=flat-square)](https://www.base.org/)

Warden Mint Story transforms your blockchain journey into a living chronicle — narrated by AI, forged on-chain, and immortalized as NFTs.
Every trade, swap, or mint becomes part of your evolving digital legend.

> **"You just safeguarded 1.2 ETH in a brave move to Base — the Warden salutes your strategic foresight."**

## Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#-project-structure)
- [Available Scripts](#-available-scripts)
- [Environment Variables](#-environment-variables)
- [Contributing](#-contributing)
- [Deployment](#-deployment)

## ✨ Features

- **Personalized Story Feed:** Connect your wallet to see a chronological, infinitely-scrolling feed of your on-chain activities, narrated by AI.
- **AI Narration & Voice Synthesis:** Each transaction is analyzed, summarized with personality, and converted to audio using advanced AI models — now with a guardian theme.
- **Customizable Narrators:** Visit the **Narrator Studio** to choose your AI's voice and narrative theme—from a vigilant warden to a mystical guardian.
- **Mint "Moments" as NFTs:** Immortalize your most memorable transactions by minting them as collectible "Story NFTs" with unique, generative artwork.
- **Community Hub:** Compete on leaderboards for "Top Guardian" or "Top Collector," and vote for the community's "Legend of the Week."
- **Responsive & Mobile-First:** A seamless experience whether you're on a desktop or on the go.

## 🛠️ Tech Stack

This project is built with a modern, scalable, and robust technology stack:

- **Framework:** [React](https://reactjs.org/) with [TypeScript](https://www.typescriptlang.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) with a custom design system using CSS variables.
- **Component Library:** [shadcn/ui](https://ui.shadcn.com/) for accessible and composable components.
- **Blockchain Integration:**
  - [Wagmi](https://wagmi.sh/): Powerful React Hooks for Ethereum.
  - [Reown AppKit](https://reown.com/): For a seamless wallet connection experience.
- **Routing:** [React Router DOM](https://reactrouter.com/)
- **Animation:** [Framer Motion](https://www.framer.com/motion/)
- **State Management:** React Hooks & [TanStack Query](https://tanstack.com/query/latest) for async state.

## 🚀 Getting Started

Follow these instructions to set up the project locally for development and testing.

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18.x or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1️⃣ **Clone & Install**
```sh
git clone https://github.com/mumair738/warden-mint-story.git
cd warden-mint-story
npm install
```

2️⃣ **Configure Environment**

Create your `.env` file:
```sh
cp .env.example .env
```

Then set your WalletConnect project ID:
```sh
VITE_REOWN_PROJECT_ID=your-walletconnect-project-id
```

3️⃣ **Run Dev Server**
```sh
npm run dev
```

Now open: 👉 http://localhost:8080

## 📂 Project Structure

```
warden-mint-story/
 ├── src/
 │   ├── pages/
 │   ├── components/
 │   │   ├── layout/
 │   │   ├── story/
 │   │   ├── moments/
 │   │   ├── community/
 │   │   └── ui/
 │   ├── hooks/
 │   ├── lib/
 │   ├── config/
 │   ├── types/
 │   ├── App.tsx
 │   └── main.tsx
 ├── public/
 ├── .env.example
 ├── package.json
 └── vite.config.ts
```

## ▶️ Available Scripts

-   `npm run dev`: Starts the development server with Hot Module Replacement.
-   `npm run build`: Bundles the app for production.
-   `npm run lint`: Lints the code using ESLint.
-   `npm run preview`: Serves the production build locally for previewing.

## 🔑 Environment Variables

To run the application, you need to provide a WalletConnect Project ID. You can obtain one for free from [WalletConnect Cloud](https://cloud.walletconnect.com/).

-   `VITE_REOWN_PROJECT_ID`: Your unique project ID from WalletConnect Cloud.

```
VITE_REOWN_PROJECT_ID=your-project-id-goes-here
```

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features, bug fixes, or improvements, please feel free to:

1.  **Fork the repository.**
2.  **Create a new branch** (`git checkout -b feature/your-amazing-feature`).
3.  **Make your changes** and commit them (`git commit -m 'Add some amazing feature'`).
4.  **Push to the branch** (`git push origin feature/your-amazing-feature`).
5.  **Open a Pull Request.**

## ☁️ Deployment


