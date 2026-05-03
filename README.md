<!--
  ══════════════════════════════════════════════════════════════════
   PROFILE README — rizq imtiaz
   Drop this file at:  github.com/rizqimtiaz/rizqimtiaz/README.md
  ══════════════════════════════════════════════════════════════════
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:0d1117,100:00352f&height=220&section=header&text=rizq%20imtiaz&fontColor=ffffff&fontSize=72&fontAlignY=38&desc=Architecting%20the%20Verifiable-AI%20Stack&descSize=18&descAlignY=62&descAlign=50" alt="banner" />

<a href="https://github.com/rizqimtiaz">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=700&color=00E5A0&center=true&vCenter=true&width=720&lines=Anchor+once.+Prove+anywhere.+Disclose+nothing.;AI+generates+%E2%86%92+Zod+validates+%E2%86%92+Contract+anchors.;Building+truth+infrastructure+for+a+synthetic+world." alt="typing" />
</a>

<br/>

<a href="https://github.com/rizqimtiaz"><img src="https://img.shields.io/badge/github-%40rizqimtiaz-0d1117?style=for-the-badge&logo=github&logoColor=00E5A0&labelColor=0d1117" /></a>
<a href="https://github.com/rizqimtiaz2"><img src="https://img.shields.io/badge/github-%40rizqimtiaz2-0d1117?style=for-the-badge&logo=github&logoColor=00E5A0&labelColor=0d1117" /></a>
<img src="https://komarev.com/ghpvc/?username=rizqimtiaz&style=for-the-badge&color=00e5a0&label=SIGNAL" />

</div>

---

## `$ whoami`

```ts
const rizq = {
  role:      ["Full-Stack Engineer", "Blockchain Developer", "Data Science Grad"],
  thesis:    "Every AI output deserves a cryptographic receipt.",
  pattern:   "AI generates  →  Zod validates  →  Contract anchors  →  Anyone verifies.",
  signature: "Latin-named protocols. Dark UIs. Audit logs everywhere.",
  status:    "shipping protocols, not products."
} as const;
```

> I sit at the seam between **intelligent data** and **decentralized systems**, building the layer
> that lets AI outputs survive in a world that no longer trusts pixels, prompts, or papers.

---

## The Verifiable-AI Pipeline

```mermaid
flowchart LR
    A([User Intent]) --> B[Inference<br/>AI SDK]
    B --> C[Structured Output<br/>Zod Schema]
    C --> D[SHA-256 Receipt]
    D --> E[On-Chain Anchor<br/>Solidity Registry]
    E --> F([Public Verification])

    style A fill:#0d1117,stroke:#00e5a0,color:#fff
    style F fill:#0d1117,stroke:#00e5a0,color:#fff
    style B fill:#1a1a2e,stroke:#00e5a0,color:#fff
    style C fill:#1a1a2e,stroke:#00e5a0,color:#fff
    style D fill:#1a1a2e,stroke:#00e5a0,color:#fff
    style E fill:#1a1a2e,stroke:#00e5a0,color:#fff
```

This is the spine. Every flagship repo below is the same spine wearing a different coat.

---

## Flagship Protocols

A portfolio of one thesis expressed across seven verticals.

<table>
  <thead>
    <tr>
      <th align="left">Protocol</th>
      <th align="left">Domain</th>
      <th align="left">What it Proves</th>
      <th align="left">Stack</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/rizqimtiaz/sovereigngraph-decentralized-identity"><b>SovereignGraph</b></a></td>
      <td>Identity</td>
      <td>ZK disclosures without revealing data</td>
      <td>Next.js · Zustand · Solidity</td>
    </tr>
    <tr>
      <td><a href="https://github.com/rizqimtiaz/BioChain"><b>BioChain</b></a></td>
      <td>Healthcare</td>
      <td>Clinical-trial data integrity</td>
      <td>TypeScript · Solidity</td>
    </tr>
    <tr>
      <td><a href="https://github.com/rizqimtiaz/EcoOracle"><b>EcoOracle</b></a></td>
      <td>Climate</td>
      <td>Autonomous carbon attestations</td>
      <td>TypeScript · Oracles</td>
    </tr>
    <tr>
      <td><a href="https://github.com/rizqimtiaz/FractalMind"><b>FractalMind</b></a></td>
      <td>Knowledge</td>
      <td>AI-synthesized concept lineage on an infinite canvas</td>
      <td>React Flow · AI SDK · Zod</td>
    </tr>
    <tr>
      <td><a href="https://github.com/rizqimtiaz2/Aegis-Protocol"><b>Aegis-Protocol</b></a></td>
      <td>Media</td>
      <td>Deepfake forensics + perceptual hash on-chain</td>
      <td>Anthropic Vision · Solidity</td>
    </tr>
    <tr>
      <td><a href="https://github.com/rizqimtiaz2/veritas-mesh-platform"><b>Veritas-Mesh</b></a></td>
      <td>Compute</td>
      <td>Proof-of-Inference for a decentralized GPU mesh</td>
      <td>DePIN · L2 · ZK</td>
    </tr>
    <tr>
      <td><a href="https://github.com/rizqimtiaz2/Forge-AI"><b>Forge-AI</b></a></td>
      <td>Creative</td>
      <td>Three labs of schema-validated generative AI</td>
      <td>SAM-2 · ControlNet · GPT-4o</td>
    </tr>
  </tbody>
</table>

---

## Architectural Signature

The same skeleton, hand-tuned per project — by design.

```
┌─ frontend ──────────────────────────────────────────────┐
│  Next.js 14/16  ·  React 19  ·  Tailwind  ·  shadcn/ui  │
│  Zustand (sliced + persisted)  ·  Framer Motion         │
└─────────────────────────────────────────────────────────┘
┌─ ai layer ──────────────────────────────────────────────┐
│  Vercel AI SDK  ·  generateObject + Zod  ·  server-only │
│  deterministic fallbacks → demos run without API keys   │
└─────────────────────────────────────────────────────────┘
┌─ trust layer ───────────────────────────────────────────┐
│  Solidity ^0.8.24  ·  XRegistry.sol  ·  events as audit │
│  Viem / Wagmi  ·  custom errors  ·  pluggable verifier  │
└─────────────────────────────────────────────────────────┘
```

---

## The Stack I Keep Reaching For

**Frontend**  
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=fff)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61dafb)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=fff)
![Tailwind](https://img.shields.io/badge/Tailwind-0ea5e9?style=flat-square&logo=tailwindcss&logoColor=fff)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000?style=flat-square&logo=shadcnui&logoColor=fff)
![Zustand](https://img.shields.io/badge/Zustand-1f1f1f?style=flat-square)

**AI / Data**  
![Vercel AI SDK](https://img.shields.io/badge/Vercel%20AI%20SDK-000?style=flat-square&logo=vercel&logoColor=fff)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=fff)
![Anthropic](https://img.shields.io/badge/Anthropic-cc785c?style=flat-square)
![Zod](https://img.shields.io/badge/Zod-3068b7?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=fff)

**Web3**  
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=fff)
![Viem](https://img.shields.io/badge/Viem-1a1a1a?style=flat-square)
![Wagmi](https://img.shields.io/badge/Wagmi-1a1a1a?style=flat-square)
![Hardhat](https://img.shields.io/badge/Hardhat-fff100?style=flat-square&logoColor=000)

**Infra**  
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=fff)
![Supabase](https://img.shields.io/badge/Supabase-3ecf8e?style=flat-square&logo=supabase&logoColor=fff)
![Git](https://img.shields.io/badge/Git-f05032?style=flat-square&logo=git&logoColor=fff)

---

## Signal

<div align="center">



<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rizqimtiaz&theme=dark&hide_border=true&background=0d1117&stroke=00e5a0&ring=00e5a0&fire=00e5a0&currStreakLabel=00e5a0" />

</div>

---

## `$ connect`

```bash
$ ping rizq

> primary   : github.com/rizqimtiaz
> secondary : github.com/rizqimtiaz2
> mode      : open to collaboration on verifiable AI, ZK, and DePIN
```

<div align="center">

<sub>Built with conviction that the next decade of software will not be written — it will be <b>witnessed</b>.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00352f,50:0d1117,100:0a0a0a&height=100&section=footer" />

</div>
