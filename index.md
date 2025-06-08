---

layout: col-sidebar
title: OWASP Agent Observability Standard
tags: example-tag
level: 2
type: documentation
pitch: A very brief, one-line description of your project

---

The project is available here: [https://trustworthyagents.github.io/AOS/|https://trustworthyagents.github.io/AOS/]

AI agents make critical decisions autonomously. They collaborate, execute code, and access sensitive data. But they operate as black boxes. Enterprises can't trust what they can't see.

AOS introduces a standard way to introduce middleware into agent systems to steer its behavior. It transforms opaque agents into transparent, controllable systems.

AOS requires agents to be instrumentable, traceable and inspectable.

* Instrumentable: we can hook into agent execution and steer it in the right direction. We can put hard controls around agents and define their scope of action. Apply centralized enterprise logic, be it security, compliance or legal, uniformly across agent platforms. Prevent or modify behavior to comply.
* Traceable: we know what the agent did and why. We can trace back any action taken to the reasoning behind it and the originating task. Even if the thread goes through multiple agents and software systems. In case of compromise, we can identify and remediate the root cause.
* Inspectable: we don’t have to guess what’s inside. Which tools, models and capabilities are being used. What software version is running and who built it. What are the services behind them, and which data they can access. Must dynamically adapt to account for rapid changes in agent components.

AOS works by extending other existing standards. MCP and A2A for instrumentation. OCSF and OpenTelemetry for Tracing. CycloneDX, SWID and SPDX for inspectability.

AOs is already being adopted by major AI agent platform vendors, as they react to enterprise needs.

### Road Map
Private release (Q2 2025, already happened)

* Create a draft protocol specification
* Begin collaborative implementation work with agent platform vendors
* Collect security community input
* Create draft spec for AgBOM
* Onboard founding members

Public release, collaboration with agent platform (Q3 2025)

* Ship a first public draft
* Public call for contribution
* Develop integration modules for popular MCP and A2A implementation
* Partner with more AI agent platform vendors for implementation

Target individual devs (Q4 2025)

* Develop testing framework for AOS-compliant agents
* Detailed implementation guides
* Develop integration modules for popular agent frameworks
