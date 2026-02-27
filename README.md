# StarkSeal Dapp

StarkSeal is a secure, private commit-reveal auction protocol built on Starknet. This Dapp allows users to participate in auctions using a three-phase process: Commit, Reveal, and Finalize. Built with JavaScript, Vite, TypeScript, Tailwind CSS, and Starknet.js.

## Features

- Commit-reveal auction flow (commit, reveal, finalize)
- Starknet wallet integration (Braavos, ArgentX)
- Pedersen hash for bid privacy
- Slashing for non-reveal
- Dashboard for managing bids
- Modern, responsive UI

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Run the development server:
   ```bash
   npm run dev
   ```
3. Open [http://localhost:7153](http://localhost:7153) in your browser.

## Starknet Contract

- Address: `0x03e915de50fe62d90305e41fa31d7eff8c005244311c1253dae9d74af88df1e1`
- RPC: `https://starknet-sepolia.public.blastapi.io/rpc/v0_8`
- ABI: See `src/assets/ABI.ts`

## Project Structure

- `/src/pages` - App Router pages (commit, reveal, dashboard)
- `/src/components/layout` - Reusable UI components
- `/public/images` - Dapp logo
