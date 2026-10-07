# EchoProof

_Crowdsourced, verifiable environmental sensing rewarded on Solana_

## Summary

EchoProof turns everyday smartphones into a DePIN network that captures noise, air quality, or GPS-tagged environmental data, cryptographically proves authenticity, and rewards contributors in SOL/tokens. Data buyers (cities, researchers, insurers) can query verified datasets on-chain.

## Target users

City planners, researchers, insurers, everyday contributors with smartphones

## Problem

Environmental and urban data is expensive to collect at scale and existing datasets are often centralized, stale, or unverifiable.

## Solution

A mobile app lets users passively collect sensor data, signs it with device attestation, and submits proofs to Solana where a token-incentive program rewards honest contribution and data buyers pay per query.

## MVP features

- Mobile app for passive sensor data capture (noise/GPS/light)
- On-chain proof-of-contribution and anti-spoofing checks
- Token reward distribution via Solana smart contract
- Marketplace for querying verified datasets by region/time
- Simple map dashboard visualizing live data coverage

## Chains

Solana

## Tech

React Native, Anchor, Rust, IPFS/Arweave, Solana Pay, PostgreSQL for indexing

## Category

DePIN

## Why now

DePIN is one of Solana's fastest-growing sectors, and cheap smartphone sensors plus low-cost transactions make crowdsourced verified data newly viable.

## Roadmap

- Partner with a city or university for pilot data purchase
- Add hardware sensor support (air quality dongles)
- Build reputation-weighted rewards to improve data quality
