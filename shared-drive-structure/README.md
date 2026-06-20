# Shared Drive structure (reference)

This folder holds a **machine-readable snapshot** of the InnerSource Commons **Google Shared Drive** root layout: [`root-structure.jsonc`](root-structure.jsonc).

The `.jsonc` file is ordinary JSON plus `//` comments. Those comments carry the human-readable intent from the governance write-up (folders, files, workflow, and access notes). Pipelines that need strict JSON can strip comments or generate JSON from this file.

**Automation:** The [InnerSourceCommons/n8n](https://github.com/InnerSourceCommons/n8n) repo consumes this structure so workflows can **create or check Drive layout** against the agreed tree. If you change folder names or nesting here, update n8n (or any other consumer) so it stays aligned with Drive.
