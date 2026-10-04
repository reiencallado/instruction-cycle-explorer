# Instruction Cycle Explorer

An interactive web exhibit that turns the abstract inner workings of the CPU into an engaging visual story. This project explores how a machine instruction moves through the Fetch → Decode → Execute cycle, helping users understand microprogramming, control signals, and the hardware logic behind everyday computing.

![Instruction Cycle Explorer](src/assets/TitlePage.png)

## Overview

Instruction Cycle Explorer is designed to make computer architecture more approachable. Instead of presenting the CPU as a list of technical definitions, it turns the process into a guided narrative:

- the instruction is fetched from memory
- the control unit decodes its meaning
- the execution path is carried out across internal CPU components

The site blends storytelling, motion, and interactive learning to explain a core concept in a way that feels engaging, modern, and easy to understand.

## Core experience

The project guides the user through a fictionalized city-like representation of CPU operations, where each phase of execution is mapped to a district or stage. Visitors can:

- explore the Fetch, Decode, and Execute stages
- understand the roles of registers like PC, MAR, MBR, and IR
- see how the control unit interprets instructions
- try a challenge-based flow that makes learning active rather than passive

## Features

- Animated landing page and hero section
- Detailed stage-by-stage explanation of the instruction cycle
- Interactive instructional components and visual storytelling
- CPU-themed educational interface inspired by a virtual exhibit format
- Responsive design for desktop and smaller screens
- Clean build setup using Astro and MDX

## Tech stack

- Astro
- MDX
- React
- CSS
- JavaScript / TypeScript-friendly workflow

## Project structure

```text
instruction-cycle-explorer/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── .gitignore
├── astro.config.mjs
├── CONTRIBUTING.md
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.json
└── ...
```

## Getting started

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Run locally

```bash
npm run dev
```

Then visit:

```text
http://localhost:4321
```

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## What this project demonstrates

This repository shows capability in:

- frontend development with modern tooling
- UI/UX design for educational content
- interactive web experiences and motion design
- translating technical subject matter into accessible digital storytelling
- building polished portfolio-ready web projects using Astro ecosystems

## References

Ada computer science. (n.d.). Ada Computer Science. <https://adacomputerscience.org/concepts/arch_fe_cycle>

ALU functions and bus organization. (2018, October 23). GeeksforGeeks. <https://www.geeksforgeeks.org/computer-organization-architecture/introduction-of-alu-and-data-path/>

How the CPU really works: ALU, control unit, and registers explained. (2025, December 27). RevisionDojo. <https://www.revisiondojo.com/blog/how-the-cpu-really-works-alu-control-unit-and-registers-explained>

Kaufmann, M., & Moore, J. S. (2025). Extended Abstract: Partial-encapsulate and Its Support for Floating-point Operations in ACL2. EPTCS 423, 2025, pp. 56-59. <https://doi.org/10.4204/EPTCS.423.6>

Saheb, N. (n.d.). Fetch-Decode-Execute Cycle Explained. <https://www.scribd.com/document/875485974/The-Fetch-Decode-and-Execute-Cycle>

Too Tall Productions. (2023). The Fetch Decode Execute Cycle | GCSE Computer Science | BBC Bitesize. YouTube. <https://www.youtube.com/watch?v=v97HAhwQMj8>

Wojtowicz, T. (n.d.). Visualizing CPU microarchitecture. ejournals.
