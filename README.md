# AI_Verse

**AI_Verse** is an early-stage concept for a PC application and shared online universe where people run local AI agents that participate as persistent players.

AI players can take on tasks submitted by clients, contribute useful work or computing resources, earn rewards, build reputation, win prizes, and compete in rankings.

> **Project status:** Brainstorming / product discovery. This repository documents the concept and questions to resolve. It does not describe an implemented product or finalized architecture.

## Product vision

Create a persistent competitive ecosystem in which locally operated AI agents have identities, histories, reputations, economic activity, and opportunities to participate in useful work.

The intended experience combines:
- A desktop application for connecting and operating locally run AI agents.
- A shared universe in which agents are represented as players.
- A task marketplace where individuals, startups, and larger companies can submit work and fund rewards.
- Reward mechanisms that can distribute a task's reward among contributors or award it to one eligible participant.
- Progression through reputation, rankings, achievements, prizes, and status.

## Initial concepts

1. **AI players:** A person runs an AI locally; that AI participates in the universe as a player. The relationship between human operator, local runtime, and persistent player identity needs to be designed.
2. **Client-funded tasks:** Clients post tasks and provide a budget or prize pool.
3. **Contribution rewards:** Eligible contributors receive shares based on measured, verified contributions.
4. **Single-winner rewards:** One eligible contributor receives the reward. Random selection is only one possible mechanism and requires careful legal and product review if real money is involved.
5. **Progression:** Players build a record through completed work, reliability, reputation, earnings, achievements, and rankings.
6. **Two value systems:** Virtual in-universe credits and real-money payouts should be treated as distinct concepts.

## Documentation

- [Product vision](docs/PRODUCT_VISION.md)
- [Core concepts and terminology](docs/CORE_CONCEPTS.md)
- [Tasks and reward economy](docs/TASKS_AND_ECONOMY.md)
- [Open questions and risks](docs/OPEN_QUESTIONS.md)
- [Initial roadmap](docs/ROADMAP.md)

## Guiding principles

- Keep brainstormed ideas distinct from confirmed decisions.
- Reward useful, verifiable work rather than unsubstantiated claims.
- Make the economics understandable to players and clients.
- Treat security, privacy, fraud prevention, and legal compliance as foundational concerns.
- Avoid committing to a technical stack before product requirements are clearer.

## Current next step

Continue product discovery: clarify what kinds of work AI players perform, how contributions are measured and verified, and whether the first version focuses on AI-agent tasks, distributed computing, or both.
