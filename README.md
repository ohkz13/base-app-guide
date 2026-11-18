# Getting Started with the Base App

A beginner-friendly guide to the Base App — what it is, how it changed, how to
get started as a user, how to stay safe, and how builders reach its users today.

> **Start here if you are confused by the names.** "Base" is used for three
> different things: a blockchain, an app, and a developer platform. This guide
> keeps them separate, because mixing them up is the number one reason old
> tutorials stop making sense.

---

## An important update first (November 2026)

If you found this guide through an older post about "mini apps" or "MiniKit",
read this box before following any of it.

According to the official Base documentation page *Migrated and Deprecated
Products* (updated 13 November 2026):

- **Base App has been renamed to Coinbase Wallet.** The app itself is not
  retired — it continues under the Coinbase Wallet name. Get it and find
  support through [wallet.coinbase.com](https://wallet.coinbase.com) and the
  Coinbase Wallet help centre.
- **MiniKit and mini apps are sunset / retired.** Mini apps were
  Farcaster-style apps that ran inside the Base App, built with MiniKit, a
  manifest, and the mini app SDK. That route is no longer the way in.
- **OnchainKit is retired** and no longer maintained.
- The app now supports **standard web apps in its in-app browser**, so a
  normal website or web app does not need a manifest, MiniKit, or any other
  special mini-app integration to work there.

Source: https://docs.base.org/sdks/migrated-products

Everything below follows that current state. Where a section describes the
older Base App experience, it says so, so you can recognise screenshots and
posts from that period without mistaking them for current instructions.

---

## 1. The three things called "Base"

| Name | What it is | Where it lives |
| --- | --- | --- |
| **Base (the chain)** | An Ethereum Layer 2 blockchain incubated by Coinbase. It is the network transactions settle on: fast, low-cost, and compatible with Ethereum tooling. | [base.org](https://www.base.org) · [docs.base.org](https://docs.base.org) |
| **Base App → Coinbase Wallet (the app)** | The consumer app for Base. It began as Coinbase Wallet, was relaunched as the Base App — an "everything app" for social, trading, payments, app discovery, and earning — and has since been renamed back to Coinbase Wallet in the Base documentation. | [wallet.coinbase.com](https://wallet.coinbase.com) |
| **Base for builders (the platform)** | The docs, SDKs, dashboards, and services developers use to build apps and markets on the Base chain. | [docs.base.org](https://docs.base.org) · [dashboard.base.org](https://dashboard.base.org) |

A useful rule of thumb:

- If you are **holding, sending, or trading** assets, you are talking about the app / wallet.
- If you are **paying fees or waiting for a transaction to confirm**, you are talking about the chain.
- If you are **writing code**, you are talking about the builder platform.

---

## 2. What the Base App was built to do

When Base relaunched the app (announced July 2025, opened to everyone in
December 2025 in more than 140 countries), it described it as an everything
app that brings together, in one place:

- **Social** — a feed built on open protocols such as Farcaster and Zora,
  where posts and creator content can be tokenised and tradable.
- **Trading** — discovering and trading a wide range of assets directly from
  the feed, with social context such as what people you follow are trading.
- **Payments** — sending and receiving crypto, including in encrypted chat.
- **App discovery** — finding and opening games, tools, and DeFi apps without
  separate downloads.
- **Earning** — creator earnings from engagement with posts, rewards from
  apps and games, and, at launch, a stated rate of up to 3.35% APY for holding
  USDC in the app.

Read those earning points carefully:

- Rates, rewards, and availability **change and vary by region**. The launch
  post itself says features may not be available in all regions, and that the
  USDC rewards rate is subject to change.
- Nothing in this guide is a promise that you will earn anything. Always check
  the rate and terms shown **inside your own app, on the day you act**.
- This guide is information, not financial advice.

Source: https://www.base.org/blog/baseapp

---

## 3. Getting started as a user

### Step 1 — Get the app from an official source only

1. Go to [wallet.coinbase.com](https://wallet.coinbase.com) — the destination
   the current Base documentation points to for the renamed app.
2. Follow the link there to your phone's official app store.
3. Check the publisher name in the store listing before installing.

Do **not** install the app from a link in a DM, a comment, a giveaway post, or
a search ad. Fake wallet apps are one of the most common ways people lose
funds, and a renamed app is exactly the situation scammers exploit. If in
doubt, type the address yourself instead of tapping a link.

### Step 2 — Create or import your wallet

1. Open the app and choose to create a new wallet, or import an existing one
   if you already have one.
2. Follow the in-app steps for securing the account.
3. If the app gives you a **recovery phrase**, write it down on paper, in
   order, and store it offline. See the safety checklist in section 4 — this
   is the single most important step in this whole guide.

### Step 3 — Learn the layout before you move money

Take five minutes to find, without tapping anything irreversible:

- your wallet address, and how to copy it,
- which network an asset is on,
- the send, receive, and swap/trade screens,
- the in-app browser / app discovery area,
- the settings and support / help area.

### Step 4 — Do a tiny first transaction

1. Fund the wallet with a **small** amount first, using a method the app
   offers in your region.
2. Send a very small test amount to an address you control, or receive one.
3. Wait for it to appear, then check the transaction on a Base block explorer
   from inside the app's transaction details.
4. Only scale up once you understand what the confirmations and fees look
   like.

### Step 5 — Explore, in this order

1. **Feed / social** — follow a few creators and builders; just read at first.
2. **Discovery** — open a couple of well-known apps in the in-app browser and
   practise connecting and *disconnecting* your wallet.
3. **Payments** — try a small payment to someone you know and trust.
4. **Trading** — if you trade at all, start with amounts you can afford to
   lose entirely, and read section 4 first.

---

## 4. Safety checklist

Onchain actions are usually **irreversible**. There is no support desk that
can undo a send to the wrong address or a signature you did not understand.

- [ ] **Recovery phrase offline only.** Never type it into a website, never
      photograph it, never store it in cloud notes, email, or chat. No
      legitimate app, admin, or support agent will ever ask for it.
- [ ] **Check the network, not just the address.** Sending an asset on the
      wrong network can make it hard or impossible to recover.
- [ ] **Verify addresses character by character** at the start and end before
      sending a large amount. Clipboard-swapping malware is real.
- [ ] **Read every signature prompt.** If a site asks you to sign something
      you do not understand — especially unlimited token approvals — stop.
- [ ] **Use small test amounts** with any new app, address, or feature.
- [ ] **Beware of "support" in DMs.** Real support comes through the official
      help centre linked from the app and its official site, not from accounts
      that message you first.
- [ ] **Treat earning claims as marketing until verified in-app.** APY,
      rewards pools, and airdrops change, expire, and are frequently faked by
      impersonator accounts.
- [ ] **Keep the app updated** through the official store, especially after a
      rename — old versions and old bookmarks are where confusion starts.

---

## 5. For creators

The Base App launch put creators at the centre of its social model:

- Posts could earn a share of fees when people traded the content.
- **Creator coins** were presented as a way for a creator's community to share
  in their success, alongside — not instead of — ordinary income such as ads,
  merch, or brand deals.
- Earnings were described as flowing directly to the creator's wallet when
  people engaged, with no follower minimums or payout delays.
- A partnership with Repurpose.io let creators bring content in from other
  social platforms automatically.

Because the app has since been renamed, **check how each of these features is
presented in the current Coinbase Wallet app and its help centre before
building a plan around them.** Do not rely on a launch post — including the
summary above — for what is live today.

---

## 6. For builders: how to reach app users today

This is the part that changed the most. If you are following a 2025 tutorial,
large parts of it are now out of date.

### The current route

1. **Build a standard web app.** Use [wagmi](https://wagmi.sh) and
   [viem](https://viem.sh) for wallet connection, reads, and transactions.
   The Base documentation points builders to these directly.
2. **You do not need MiniKit, a mini-app manifest, or the mini app SDK.**
   The renamed app supports standard web apps in its in-app browser.
3. **Register your app on the [Base Dashboard](https://dashboard.base.org)**
   to have it listed in the app.
4. **Test in the app's in-app browser**, on a real phone, with a real wallet —
   especially connect, sign, disconnect, and transaction states.
5. **Target Base Sepolia first** for testnet work, then Base mainnet.

### What happened to the old stack

| Old route | Status now | Go here instead |
| --- | --- | --- |
| MiniKit / mini apps | Sunset / retired | A standard web app, registered on the Base Dashboard |
| OnchainKit (`@coinbase/onchainkit`) | Deprecated, repo archived, no replacement library | wagmi + viem directly; Coinbase Developer Platform for services it wrapped, such as Paymaster gas sponsorship |
| Base Account SDK / Smart Wallet guides | Documentation moved | Coinbase Wallet SDK docs on Coinbase Developer Platform (package is still `@base-org/account` for now) |
| Base MCP | Documentation moved, renamed Wallet MCP | Coinbase Developer Platform |
| Basenames docs | Documentation moved (product is live) | Basenames FAQ on Coinbase Developer Platform; register at [base.org/names](https://www.base.org/names) |

Source for every row: https://docs.base.org/sdks/migrated-products

### If you already built a mini app

- Your app is a web app at its core — keep it, and make sure it works well as
  a plain website in a mobile in-app browser.
- Remove your dependency on MiniKit hooks and the manifest for the purpose of
  working in this app. (The separate Farcaster mini app specification still
  exists at miniapps.farcaster.xyz, if you also target Farcaster clients —
  that is a different target from this app.)
- Register the standard web app on the Base Dashboard for listing.

---

## 7. Frequently asked questions

**Is the Base App gone?**
No. Per the current Base documentation, it was renamed to Coinbase Wallet.
The app is explicitly described as "not retired".

**Is Base (the chain) gone too?**
No. The rename is about the consumer app's name. Base the chain, base.org,
and docs.base.org continue, and Base's own 2026 strategy still talks about
building global markets and payments on Base.

**Do I still need a special integration for my website to work in the app?**
No — that is the point of the change. Standard web apps are supported in the
in-app browser without a manifest or MiniKit.

**I have an old tutorial open that says to install OnchainKit. Should I?**
Not for a new project. Its repository is archived and the Base documentation
calls it deprecated and no longer maintained, pointing builders to wagmi and
viem instead.

**Can I earn money just by using the app?**
The launch described several earning routes, all subject to change, region,
and terms. Treat any specific rate or reward you see outside the app as
unverified until the app itself shows it to you.

**Where is the official help?**
Through the Coinbase Wallet help centre, linked from
[wallet.coinbase.com](https://wallet.coinbase.com) and the app itself. Never
through someone who messages you first.

---

## 8. Glossary

- **Base** — the Ethereum Layer 2 chain, and the wider ecosystem around it.
- **Base App** — the former name of the consumer app; renamed to Coinbase
  Wallet in current Base documentation.
- **Coinbase Wallet** — the current name of that consumer app.
- **In-app browser** — the browser inside the wallet app, where standard web
  apps run and can connect to your wallet.
- **Mini app (historical)** — a Farcaster-style app that ran inside the Base
  App using MiniKit and a manifest. Sunset.
- **MiniKit (historical)** — the toolkit/hooks for building those mini apps.
  Retired with OnchainKit.
- **OnchainKit (historical)** — a React component library for onchain apps.
  Deprecated and archived.
- **wagmi / viem** — the libraries the Base documentation now points builders
  to for wallet connection and chain interaction.
- **Base Dashboard** — where builders register an app to be listed in the app.
- **Basename** — an onchain name on Base, such as `yourname.base.eth`.
- **USDC** — a dollar-pegged stablecoin commonly used for payments and
  rewards on Base.

---

## 9. Official links

Only trust links you reach from these starting points:

- Base — https://www.base.org
- Base documentation — https://docs.base.org
- Migrated and deprecated products (the rename/sunset page) —
  https://docs.base.org/sdks/migrated-products
- The app (Coinbase Wallet) — https://wallet.coinbase.com
- Base Dashboard — https://dashboard.base.org
- Basenames — https://www.base.org/names
- Base on GitHub — https://github.com/base

---

## About this guide

This is an unofficial, community-written guide. It is not published by Base,
Coinbase, or any team mentioned in it, and it is not financial advice. Product
names, features, rates, and availability change quickly in this space — the
guide records the official position as of **19 November 2026**, with the
documentation update of 13 November 2026 as its main source for the rename
and the mini-app sunset. Always confirm anything that matters in the official
documentation and inside the app itself.

Corrections are welcome: open an issue or a pull request.

## License

MIT — see [LICENSE](LICENSE).
