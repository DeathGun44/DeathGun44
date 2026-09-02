<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:A972F5,100:44475A&height=150&section=header&text=Krishna%20Mewara&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=learn!%20apply!%20repeat!&descAlignY=60&descSize=18&descColor=ffffff&animation=fadeIn" alt="Krishna Mewara" />
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/krishna-mewara-127699280/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:krishnamewara418@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.naukri.com/code360/profile/3b05669a-3097-4581-a02f-fc26f7354a6e">
    <img src="https://img.shields.io/badge/Code360-FFA500?style=for-the-badge&logo=codingninjas&logoColor=white" alt="Code360" />
  </a>
</div>

<br />

Final-year ECE student at NIT Silchar, and a [**Google Summer of Code 2026**](https://summerofcode.withgoogle.com/programs/2026/projects/yRedsyg7) contributor with the Apache Software Foundation. I like building things, and I like them not falling over.

Most of what I shipped this year went into other people's production codebases. What I keep gravitating towards there is the unglamorous half - the test suite nobody wants to migrate, the CI job that takes seven minutes too long, the thread pool that quietly exhausts itself under load. That's the work that decides whether software still behaves once a lot of people depend on it, and it turns out I enjoy it.

The GSoC project was a large one - 350 hours, rebuilding Fineract's integration test suite - and I was [Mifos Star Contributor for May 2026](https://mifos.org/blog/star-contributor-krishna-mewara-2/). The rest of the time I follow whatever I'm curious about - RL environments, Go services, whichever agent stack I haven't taken apart yet.

<br />

## Open source

| Project | What I did | |
| :--- | :--- | :--- |
| **Apache Fineract** | Rebuilt the integration test suite on a type-safe Feign client for GSoC '26, plus security, concurrency and CI work outside it - 28 PRs, 115 commits, 19th of 317 all-time contributors | [#6158](https://github.com/apache/fineract/pull/6158) |
| **Mifos Self-Service Plugin** | Primary developer - 2FA token flows, atomic self-enrollment, async notifications, E2E suite | [33 PRs](https://github.com/openMF/selfservice-plugin/pulls?q=is%3Apr+author%3ADeathGun44+is%3Amerged) |
| **Hyperledger Besu** | Moved multi-arch Docker publishing off Gradle into a reusable GitHub Actions workflow | [#10366](https://github.com/besu-eth/besu/pull/10366) |
| **Hiero** · LF Decentralized Trust | Reorganised the Python SDK docs and rebuilt the contributor label taxonomy | [#2106](https://github.com/hiero-ledger/hiero-sdk-python/pull/2106) |

<!-- OSS:START -->
**95** pull requests merged into repos I don't own · **15** of other people's PRs reviewed ·
[full list](https://github.com/search?q=is%3Apr+author%3ADeathGun44+is%3Amerged+-user%3ADeathGun44&type=pullrequests&s=created&o=desc)

Latest: [apache/fineract#6324](https://github.com/apache/fineract/pull/6324) · [apache/fineract#6321](https://github.com/apache/fineract/pull/6321) · [apache/fineract#6241](https://github.com/apache/fineract/pull/6241)
<!-- OSS:END -->

<br />

## Things I've built

**[CodePair](https://github.com/DeathGun44/codepair)** - real-time collaborative interview practice. Go + Fiber backend, WebSocket sync over Redis pub/sub, Postgres-backed matchmaking worker, Monaco editor, ECS Fargate via Terraform.
`Go` `React` `TypeScript` `PostgreSQL` `Redis` `AWS` `Terraform`

**[AgentGuard](https://huggingface.co/spaces/DeathGun44/agent-guard)** - an RL environment where the agent plays security reviewer, deciding whether to approve permission requests from other agents that may be honest, deceptive, or compromised. Four-dimension reward that scores *how* it investigated, not just what it decided. Built for the Meta × PyTorch OpenEnv Hackathon, alongside [theWorld](https://huggingface.co/spaces/DeathGun44/theWorld).
`Python` `FastAPI` `OpenEnv` `Docker`

**Also** - [AuditAI](https://github.com/DeathGun44/cloud-run-AuditAi) (five-agent expense audit on Cloud Run, Google ADK), [cf_ai_task_manager](https://github.com/DeathGun44/cf_ai_task_manager) (Cloudflare Workers AI + Durable Objects, live), [DevOps Intelligence Agent](https://github.com/DeathGun44/devops-intelligence-agent) (AWS Bedrock). Three different agent stacks in six months, mostly because I wanted to know how each one felt to build on.

<br />

## Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,go,python,ts,cpp&theme=dark" alt="Languages" /><br />
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,aws,gcp,githubactions,linux&theme=dark" alt="Infrastructure" /><br />
  <img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,angular,react,nodejs&theme=dark" alt="Data and frontend" />
</div>

<br />

## Elsewhere

- Global rank **947** at [Meta Hacker Cup 2025](https://www.facebook.com/codingcompetitions/hacker-cup/2025/certificate/1471432427467454) - top 1%
- Top 1,500 nationally in Google The Big Code 2026

<details>
<summary><b>The numbers, if you want them</b></summary>
<br />
<div align="center">
  <img src="./github-metrics.svg" alt="GitHub metrics" width="100%">
</div>
</details>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DeathGun44/DeathGun44/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DeathGun44/DeathGun44/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/DeathGun44/DeathGun44/output/github-snake.svg" />
  </picture>
</div>
