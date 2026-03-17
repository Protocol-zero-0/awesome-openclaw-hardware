# awesome-openclaw-hardware

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of hardware and wearable directions for OpenClaw builders: smart glasses, voice devices, edge boards, robotics-adjacent interfaces, and agent-ready device projects.

This is a community-curated repository. It is not an official OpenClaw repository.

## Why This Repo

OpenClaw becomes much more interesting when it moves beyond a terminal window.

The hardware side of the ecosystem is fragmented across:

- smart glasses
- voice recorders and wearable audio devices
- edge and low-power boards
- desktop companion devices
- community demos and experimental builds

This repo exists to make those hardware directions easier to discover and compare.

## Who This Is For

- wearable and device hackers
- OpenClaw builders exploring physical interfaces
- community members looking for demo-worthy projects
- teams evaluating OpenClaw beyond chat and CLI

## Contents

- [Core OpenClaw References](#core-openclaw-references)
- [Smart Glasses And Wearables](#smart-glasses-and-wearables)
- [Voice And Audio Devices](#voice-and-audio-devices)
- [Edge And Embedded Directions](#edge-and-embedded-directions)
- [Experimental Hardware Projects](#experimental-hardware-projects)
- [Setup And Integration Resources](#setup-and-integration-resources)
- [Contributing](#contributing)

## Core OpenClaw References

| Resource | Type | Notes |
| --- | --- | --- |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | Core project | Main OpenClaw repository. |
| [OpenClaw Showcase](https://docs.openclaw.ai/start/showcase) | Showcase | Good place to watch for demo-friendly builds. |
| [openclaw/clawhub](https://github.com/openclaw/clawhub) | Skills | Helpful when device projects depend on skill layers. |

## Smart Glasses And Wearables

| Resource | Type | Notes |
| --- | --- | --- |
| [Rokid](https://global.rokid.com/) | Smart glasses platform | One of the clearest OpenClaw-adjacent wearable directions. |
| [Intent-Lab/VisionClaw](https://github.com/Intent-Lab/VisionClaw) | Demo project | OpenClaw-style real-time assistant experience for smart glasses. |
| [XREAL](https://www.xreal.com/) | Smart glasses platform | Popular AR glasses platform relevant to agent interfaces. |
| [RayNeo](https://www.rayneo.com/) | Smart glasses platform | TCL-backed wearable line worth tracking for OpenClaw use cases. |
| [Meta Ray-Ban](https://www.ray-ban.com/usa/discover-ray-ban-meta-glasses) | Consumer wearable | A useful benchmark for mainstream AI glasses interaction patterns. |

## Voice And Audio Devices

| Resource | Type | Notes |
| --- | --- | --- |
| [PLAUD](https://www.plaud.ai/) | AI voice device | Voice capture and summarization device relevant to assistant workflows. |
| [Rabbit r1](https://www.rabbit.tech/) | AI device | Useful reference point for agent-first physical device UX. |
| [Humane Ai Pin](https://humane.com/) | AI device | Another useful benchmark for ambient assistant hardware design. |
| [OpenAI Voice Mode](https://openai.com/) | Interaction benchmark | Not hardware itself, but useful for thinking about voice-first OpenClaw experiences. |

## Edge And Embedded Directions

| Resource | Type | Notes |
| --- | --- | --- |
| [memovai/mimiclaw](https://github.com/memovai/mimiclaw) | Embedded project | OpenClaw-inspired hardware agent path on small chips. |
| [RightNow-AI/picolm](https://github.com/RightNow-AI/picolm) | Embedded LLM direction | Useful for thinking about constrained-device inference. |
| [Raspberry Pi](https://www.raspberrypi.com/) | Edge platform | Common base for self-hosted device experiments. |
| [Jetson Orin Nano](https://developer.nvidia.com/embedded/jetson-orin-nano-developer-kit) | Edge AI platform | Useful for heavier local multimodal experiments. |

## Experimental Hardware Projects

| Resource | Type | Notes |
| --- | --- | --- |
| [HKUDS/nanobot](https://github.com/HKUDS/nanobot) | Lightweight agent runtime | Useful for builders looking at lower-overhead hardware deployments. |
| [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) | Lightweight runtime | Deploy-anywhere direction that pairs well with hardware experimentation. |
| [nearai/ironclaw](https://github.com/nearai/ironclaw) | Rust implementation | Privacy and security angle useful for hardware-side deployments. |
| [ValueCell-ai/ClawX](https://github.com/ValueCell-ai/ClawX) | Desktop control UI | Useful when hardware projects still need a visible control layer. |

## Setup And Integration Resources

| Resource | Type | Notes |
| --- | --- | --- |
| [justlovemaki/openclaw-docker-cn-im](https://github.com/justlovemaki/openclaw-docker-cn-im) | Docker bundle | Helpful if wearable projects also need China-side messaging channels. |
| [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) | Deployment platform | Useful for self-hosting supporting services for hardware projects. |
| [xianyu110/awesome-openclaw-tutorial](https://github.com/xianyu110/awesome-openclaw-tutorial) | Tutorials | Helpful onboarding material for new builders. |
| [mengjian-github/openclaw101](https://github.com/mengjian-github/openclaw101) | Learning guide | Beginner-friendly reference material. |

## Contributing

Contributions are welcome.

Please prioritize:

- real hardware projects
- demo-worthy integrations
- practical build guides
- clear device-specific notes

Each entry should include:

- name
- link
- category
- one-line description
- why it matters for OpenClaw builders

## License

[MIT](LICENSE)
