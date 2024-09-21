# DefiDash

<center>
<img src="https://github.com/DefiDash/.github/blob/main/defidash.png?raw=true"/ width=200>
</center>

> A Generative UI DeFi Blockchain Data Analytics Platform PoC built on <a href="https://phala.network">Phala Network</a> (Decentralized AI) and <a href="https://thegraph.com">The Graph</a> blockchain data querying service for <a href="https://ethglobal.com/events/singapore2024">ETHGlobal Singapore Hackathon</a>

## Team Members
- <a href="https://github.com/DreamerChaserHAH">DreamerChaserHAH - Victor Mak</a><br>
- <a href="https://github.com/marcofernandioo">marcofernandioo - Marco Fernandio</a>
- <a href="https://github.com/ryuux05">ryuux05 - Bryan Hirawan</a>

## Problem Statement

Existing Web3 analytics tools lack the flexibility to cater and diverse user needs, offering limited visualization options and rigid reporting structures.

## Solution

An AI-powered Web3 analytics tool that dynamically generates custom graphs and visualizations based on user-specific requests, providing flexible and adaptive data exploration.

## General Flow

1. User visits our Dapp Data Visualization Website
2. User enters the prompt telling us the data they are interested in.
3. Phala Network AI Agent Contract receives the prompt and decides which API to call to get the necessary data
4. The external APIs are provided by the Graph to effectively query the data provided by other existing Dapps
5. Using the data received from the Graph, the ai agent later decides what kind of data visualization is the most suitable for the project.
6. Data Visualization is done on the frontend

## Repositories

- <a href="AI Agent Smart Contract">https://github.com/DefiDash/ai-agent-contract</a>
- <a href="DeFiDash Frontend">https://github.com/DefiDash/defidash</a>
