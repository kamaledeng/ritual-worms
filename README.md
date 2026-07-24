# RITUAL Worms — Bomb 'Em All! 💣

A Worms-style artillery game built for **Ritual** — 2 teams (3 worms each), 4 weapons, destructible terrain, Vs CPU or 2-player hotseat, MetaMask wallet connection to the **Ritual Chain testnet**, and on-chain win recording.

## Play
Open `index.html` via a web server (wallet features need http/https, not file://).

## Deploy to Vercel via GitHub
1. Create a new GitHub repository (e.g. `ritual-worms`).
2. Upload `index.html` and `README.md` to the repository.
3. Go to vercel.com → **Add New → Project** → **Import** the repository.
4. Framework Preset: **Other**. No build command / output directory needed (static site).
5. Click **Deploy** — the game goes live at `https://your-project.vercel.app`.

Every push to GitHub triggers an automatic redeploy on Vercel.

## On-chain features (Ritual Chain testnet)
- Chain ID: 1979 (0x7bb) · RPC: rpc.ritualfoundation.org · Symbol: RITUAL
- Claim free gas at faucet.ritualfoundation.org
- The “Record Win On-chain” button appears on the victory screen when a wallet is connected.

## Controls
←/→ move · ↑/↓ aim · hold SPACE then release to fire · Q / 1–4 switch weapon

## About Ritual
Website: ritual.net · Docs: docs.ritualfoundation.org · X: @ritualnet · Discord & GitHub: ritual-net
