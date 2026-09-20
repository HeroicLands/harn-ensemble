---
"harn-ensemble": patch
---

**Foundry package browser listing** now reads from `packageBuild.manifest.descriptionHtml` in the configuration, so the module's Foundry listing is written for Foundry users. **Site meta description** now reads from `site.description` in the configuration, so the page preview that appears in search results and social media is written for web readers. `package.json`'s `description` is no longer read by the toolchain and has been removed.
