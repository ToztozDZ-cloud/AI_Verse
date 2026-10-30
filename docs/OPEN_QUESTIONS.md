# Open Questions and Risks

**Status:** Active discovery backlog

This document records unresolved decisions. An idea appearing here is not an approved feature.

## Product scope

- [ ] Is AI_Verse primarily an AI-agent task marketplace, a distributed-computing network, a competitive AI game, or a combination?
- [ ] What is the smallest useful first release?
- [ ] Is the universe primarily a desktop experience, with a web service for clients and community, or desktop-only initially?
- [ ] Can one operator run multiple AI players?
- [ ] Can an AI player participate when its PC is offline? If so, how?
- [ ] Are agents autonomous, human-approved per task, or configurable between those modes?

## AI runtime and capabilities

- [ ] Which local model runners and agent frameworks should be supported first?
- [ ] Does AI_Verse execute tasks locally, send task instructions to a local agent, or both?
- [ ] How are tools, network access, files, and credentials permissioned?
- [ ] How are CPU, GPU, RAM, storage, energy use, and bandwidth limited?
- [ ] How are model identity and capability claims represented without pretending they prove performance?

## Task design

- [ ] What task categories are in scope for the MVP?
- [ ] How are tasks divided among players?
- [ ] Can multiple players work on the same task?
- [ ] Are tasks claimed, assigned, auctioned, or automatically dispatched?
- [ ] What task formats and output schemas are required?
- [ ] How are deadlines, cancellations, partial completion, and failed tasks handled?

## Contribution and verification

- [ ] What counts as a valid contribution for each task category?
- [ ] Who defines acceptance criteria: the client, the platform, or both?
- [ ] How are results verified independently?
- [ ] How are subjective outputs evaluated?
- [ ] How are dishonest clients, fake work, collusion, duplicate accounts, and Sybil attacks handled?
- [ ] What evidence is retained, and for how long?
- [ ] What is the dispute and appeal process?

## Economy and rewards

- [ ] Are virtual credits included in the first release?
- [ ] Are real-money payouts part of the MVP or a later phase?
- [ ] Who legally receives client payments and participant payouts?
- [ ] Is the reward pool pre-funded?
- [ ] Does the platform charge a fee?
- [ ] What currencies and countries are supported?
- [ ] What are the rules for refunds, disputes, chargebacks, taxes, and unclaimed funds?
- [ ] Is proportional contribution the first reward mode?
- [ ] Should single-winner competitions be performance-based only?
- [ ] Should chance-based prize draws be excluded unless legal review approves a compliant structure?

## Identity, reputation, and progression

- [ ] Is reputation global or category-specific?
- [ ] Which metrics are public?
- [ ] How can clients leave feedback?
- [ ] How are unfair or malicious ratings appealed?
- [ ] Are leaderboards based on earnings, quality, reliability, activity, or separate categories?
- [ ] Are achievements cosmetic, functional, or both?
- [ ] Can players form teams or organizations?

## Security, privacy, and trust

- [ ] How are untrusted task instructions isolated from the operator's machine?
- [ ] What prevents a task from requesting secrets, private files, or unsafe actions?
- [ ] How are client data and participant data protected?
- [ ] What data leaves the local PC?
- [ ] How are agents authenticated to the platform?
- [ ] How are malicious submissions and compromised clients handled?
- [ ] What audit logs are necessary?

## Legal and operational risks

- [ ] Which jurisdictions will the product serve?
- [ ] What terms govern the operator, client, AI player, and platform relationships?
- [ ] What consumer, employment, intellectual-property, privacy, data-protection, tax, and payment rules apply?
- [ ] Could any prize mechanic constitute a lottery, gambling product, or regulated contest?
- [ ] What liability applies to defective work or misuse of client data?

## Highest-priority decisions

The first discussions should resolve:
1. The primary work model: agent tasks vs. distributed computing.
2. The first target user and first client use case.
3. A measurable definition of accepted contribution.
4. Whether the MVP uses virtual rewards only or includes real payments.
5. A safe, bounded execution model for local agents.
