# Vito Santanelli

Software engineer working across backend, full-stack development, and local AI systems.

I build with Rust, Python, .NET/C#, TypeScript, and Angular. My current research focuses on the software around local language models: tools, context, permissions, verification, and the evidence needed to tell whether an agent actually completed a task.

## Current focus

- [**poorAI**](https://github.com/VitoSanta/PoorAI) — an experimental local agent harness, with software engineering as its first proving ground. It gives locally served models a conversation loop, typed tools for working in repositories, explicit permissions, and task verification. The public alpha includes its own MLX inference engine and a Tauri + Angular desktop app. A llama.cpp / GGUF path exists with substantial performance limitations; Windows support and reliable gains for smaller models remain research goals. The project measures how changes to the harness affect results and resource cost. See the [current status and evidence](https://github.com/VitoSanta/PoorAI#current-maturity).

## Selected work

- [**Aegis**](https://github.com/VitoSanta/aegis) — an AI support system with RAG, durable human-in-the-loop workflows, multi-tenant authorization, MCP tools, and reproducible evaluation.
- [**pdf-translator**](https://github.com/VitoSanta/pdf-translator) — a local Ollama document translator designed to preserve PDF layout and keep documents on-device.
- [**national-identifiers**](https://github.com/VitoSanta/national-identifiers) — a cross-runtime TypeScript and .NET validation library for national tax IDs, VAT numbers, and company identifiers.
- [**FleetOps**](https://github.com/VitoSanta/FleetOps) — a cloud-native fleet-management reference architecture using .NET, Angular, Docker, Kubernetes, and event-driven microservices.

## How I work

- Test model and system behavior on real tasks instead of assuming capability from a model name.
- Compare changes against reproducible baselines and record failed experiments as well as successes.
- Keep authorization, workspace boundaries, and verification outside model control.
- Make limitations visible in documentation and in the product.

## Technologies

Rust · Python · .NET / C# · TypeScript · Angular · PostgreSQL · Docker · GitHub Actions · MLX · llama.cpp · Ollama · RAG · MCP

Based in Bari, Italy. Interested in software engineering roles that connect reliable backend systems with practical AI applications.
