# EchoProof
![EchoProof logo](assets/logo.png)

Crowdsourced, verifiable environmental sensing rewarded on Solana.

## Overview

EchoProof turns everyday smartphones into a DePIN network that captures noise, air quality, or GPS-tagged environmental data, cryptographically proves authenticity, and rewards contributors in SOL/tokens. Data buyers such as cities, researchers, and insurers can query verified datasets on-chain.

## Problem

Environmental and urban data is expensive to collect at scale, and existing datasets are often centralized, stale, or unverifiable. City planners, researchers, and insurers lack access to fresh, trustworthy, granular data.

## Solution

A mobile app lets users passively collect sensor data, signs it with device attestation, and submits proofs to Solana. A token-incentive smart contract rewards honest contribution, while data buyers pay per query to access verified datasets through an on-chain marketplace.

## Features (MVP)

- Mobile app for passive sensor data capture (noise/GPS/light)
- On-chain proof-of-contribution and anti-spoofing checks
- Token reward distribution via Solana smart contract
- Marketplace for querying verified datasets by region/time
- Simple map dashboard visualizing live data coverage

## Tech Stack

- React Native (mobile app)
- Anchor, Rust (Solana smart contracts)
- IPFS/Arweave (data storage)
- Solana Pay (payments)
- PostgreSQL (off-chain indexing)

## How It Works

```
[Smartphone Sensors]
   -> capture noise/air/GPS/light
   -> sign with device attestation
        v
[EchoProof Mobile App]
   -> upload raw data to IPFS/Arweave
   -> submit proof + hash to Solana
        v
[Anchor Program on Solana]
   -> verify proof-of-contribution
   -> run anti-spoofing checks
   -> distribute SOL/token rewards
        v
[PostgreSQL Indexer]
   -> index verified datasets by region/time
        v
[Marketplace + Map Dashboard]
   -> buyers query & pay per query via Solana Pay
   -> live coverage visualized on map
```

## Roadmap

- Partner with a city or university for a pilot data purchase
- Add hardware sensor support (air quality dongles)
- Build reputation-weighted rewards to improve data quality

## Pitch

- Full pitch deck: [docs/pitch.pdf](docs/pitch.pdf)
- Spoken pitch script: [docs/pitch-script.md](docs/pitch-script.md)

## Team

- [Name] - Role (placeholder)
- [Name] - Role (placeholder)
- [Name] - Role (placeholder)

Built for the Colosseum hackathon.

---

🎬 Pitch video: [docs/pitch-video.mp4](docs/pitch-video.mp4)


## Prototype

Live prototype: https://ytakahashi2020.github.io/echoproof-2/

The source is [docs/index.html](docs/index.html) (served with GitHub Pages from the /docs folder). All data is simulated.
