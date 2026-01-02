# Brainz Lab

  **AI-native observability for developers.** 31 products. 8 AI executives. One vision.

  ## What We're Building

  Brainz Lab is building the infrastructure layer that makes AI actually useful for software development. We're creating observability tools designed from the ground up for AI consumption—so Claude can actually see your logs, errors, and metrics instead of asking you to copy-paste them.

  ## Products

  | Product | Description | Status |
  |---------|-------------|--------|
  | **[Recall](https://github.com/brainz-lab/recall)** | Structured logging that AI can search | Available |
  | **[Reflex](https://github.com/brainz-lab/reflex)** | Error tracking that AI can fix | Available |
  | **[Vault](https://github.com/brainz-lab/vault)** | Secrets management for AI agents | Available |
  | **[Pulse](https://github.com/brainz-lab/pulse)** | APM that tells you *why* it's slow | Coming Soon |
  | **[Signal](https://github.com/brainz-lab/signal)** | Alerting that doesn't cry wolf | Coming Soon |

  ## Quick Start

  ```bash
  git clone https://github.com/brainz-lab/stack.git
  cd stack
  ./scripts/setup.sh
  docker-compose up -d

  Open http://localhost to access the dashboard.

  The Stack

  - https://github.com/brainz-lab/stack — Docker Compose setup for running all products locally
  - https://github.com/brainz-lab/brainzlab-ruby — Ruby SDK for Rails integration

  Why Self-Hosted First

  Your observability data contains secrets, user IDs, request payloads. We believe it should stay on your infrastructure. All Brainz Lab products run locally via Docker—no data leaves your servers unless you want it to.

  MCP Integration

  Every product exposes an MCP (Model Context Protocol) interface. Connect Claude Desktop or any MCP-compatible AI, and it can query your logs, analyze your errors, and check your metrics directly.

  Connect

  - 🌐 Website: https://brainzlab.ai
  - 💬 Discord: https://discord.gg/2mCfVTR7aD
  - 🐦 X/Twitter: https://x.com/afmp_94
  - 💼 LinkedIn: https://linkedin.com/company/brainzlabai
  - 📧 Email: hello@brainzlab.ai

  License

  Brainz Lab products are released under the https://brainzlab.ai/license—open source with one restriction: you can't resell the software as a competing service.

