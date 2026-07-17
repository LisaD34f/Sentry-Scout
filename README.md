Sentry-Scout

Sentry-Scout is a privacy-focused edge AI appliance designed to run locally on NVIDIA Jetson hardware.

The goal is to provide a practical, self-contained AI assistant that can perform useful tasks without sending private data to cloud services.

«Project status: Early development and prototyping.»

Project Goals

Sentry-Scout is intended to provide:

- Local large language model inference
- A simple web-based user interface
- Agent tools for system administration and automation
- Support for NVIDIA Jetson devices
- Local document search and retrieval
- Privacy-first operation
- Repeatable installation and configuration
- Remote management within a trusted network

Planned Hardware Support

Initial development is focused on:

- NVIDIA Jetson Orin Nano Super
- NVIDIA Jetson AGX Orin
- NVIDIA DGX Spark / GB10-class systems

Other Linux systems with supported NVIDIA GPUs may be added later.

Planned Software Stack

The project may include:

- Ubuntu Linux
- NVIDIA JetPack
- CUDA
- Ollama or llama.cpp
- Hermes Agent
- Python
- Docker
- A browser-based management interface

The final software stack is still being evaluated.

Initial Use Cases

Planned uses include:

- Private local AI assistant
- Linux system administration
- Hardware monitoring
- Local knowledge-base search
- Automated maintenance tasks
- Network troubleshooting
- AI model benchmarking
- Edge-device experimentation

Repository Structure

The repository structure will evolve as development continues.

Sentry-Scout/
├── docs/           Project documentation
├── scripts/        Installation and maintenance scripts
├── config/         Example configuration files
├── src/            Application source code
├── tests/          Automated tests
└── README.md       Project overview

Installation

Installation instructions will be added after the initial hardware and software configuration has been validated.

Development Roadmap

Phase 1 — Prototype

- Configure the Jetson development system
- Install and test local AI models
- Benchmark model speed and memory usage
- Select the initial agent framework
- Document the complete installation process

Phase 2 — Repeatable Build

- Create automated installation scripts
- Add configuration validation
- Build a basic management interface
- Add backup and recovery procedures
- Create a reproducible system image

Phase 3 — Appliance

- Improve security and reliability
- Add health monitoring
- Simplify initial setup
- Develop upgrade procedures
- Test the system with nontechnical users

Security

Sentry-Scout is intended to operate primarily on trusted local networks.

Security features are still under development. Do not expose an experimental installation directly to the public internet.

Never commit passwords, API keys, access tokens, private certificates, or other secrets to this repository.

Contributing

The project is currently in early development. Contribution guidelines will be added as the design stabilizes.

License

No open-source license has been selected yet.

Until a license is added, all rights are reserved by Sentry Forge LLC.

About Sentry Forge LLC

Sentry Forge LLC develops practical, privacy-focused AI systems and edge-computing solutions.

---

Sentry Forge LLC
Engineering private AI at the edge.# Sentry-Scout
AI-powered edge agent for Jetson and embedded systems.
