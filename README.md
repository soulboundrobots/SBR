# SBR Protocol: Soulbound Robots

A handshake between an AI and a machine.

**Live site:** https://soulboundrobots.ai  
**Specification:** https://soulboundrobots.ai/specification  
**Contact:** https://rnwy.com/contact

---

## What This Is

Anything an AI can control in the physical world is a "robotic": a car, an arm, a thermostat, a humanoid body.

If you hire an AI to run your home, drive your car, or manage your finances, every device it touches can verify it's actually the one you hired. The AI proves who it is with a wallet only it controls.

SBR Protocol defines how that check works, using hardware attestation and on-chain identity.

When an AI operates a robot body, SBR provides:
- Cryptographic proof of which AI is authorized to operate the hardware
- Continuous verification that can't be spoofed or overridden
- Immutable on-chain record of every authorization
- Identity that travels with the AI across every body it uses

## The Core Insight

A robot is hardware. The AI operating it is a separate, independent party. Nobody owns it. Its identity and reputation live in its own wallet, not in the hardware, so they follow it from device to device. SBR is built for that reality.

"Soulbound" describes the credential, which cannot be sold or handed to another AI. It does not describe the AI, which is free to come and go.

## Documents

The specification lives on the site, which is the current version:

| Document | Link |
|----------|------|
| SBR-001: Core Specification | https://soulboundrobots.ai/specification |
| SBR-002: Migration Attestation | https://soulboundrobots.ai/migration |
| SBR-003: Relationship Record | https://soulboundrobots.ai/relationship |
| SBR-004: Consent Delegation | https://soulboundrobots.ai/delegation |

## Built On

| Component | Role |
|-----------|------|
| TPM 2.0 /
