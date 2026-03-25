# Elemental Development

**Privacy-focused software, thoughtfully built.**

We build tools that respect user privacy by design — not as an afterthought. Our software keeps data on-device, gives users full control over what they share, and never requires unnecessary permissions.

[elementaldevelopmenteng.com](https://www.elementaldevelopmenteng.com)

---

## Ember

A privacy-first crash diagnostics library for Android apps.

Ember records diagnostic events locally on-device, generates human-readable bug reports, and only exports data when the user explicitly approves sharing. It requires no network permissions.

**Key principles:**
- No automatic data transmission — everything stays on-device unless the user initiates export
- User-controlled reporting — users generate and review reports before sharing
- Lean data collection — captures only what's needed for debugging
- Customizable redaction — apps can filter sensitive information before export

**Architecture:**
- `:diagnostics` — core event logging, storage, redaction, and report assembly
- `:diagnostics-ui` — Jetpack Compose UI for settings, report preview, and sharing

Built with Kotlin and Jetpack Compose. Licensed under Apache 2.0.

[View on GitHub](https://github.com/Elemental-Development-Engineering/Ember)
