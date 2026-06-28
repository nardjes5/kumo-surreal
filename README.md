![preview](https://raw.githubusercontent.com/nardjes5/kumo-surreal/main/preview.svg)

# Kumo 🌩️

A carefully curated fork of Mihon, enriched with thoughtful customizations and community-driven patches from complementary forks. Kumo exists to bridge the gap between the vanilla experience and the niche enhancements that power users genuinely need — without bloating the core. It is the cloud that carries the rain of progress without losing its shape.

---

## Overview ☁️

Kumo is not just another fork — it is a philosophy of minimal intervention with maximum impact. While Mihon provides a stellar foundation, certain workflows demand subtle alterations: a smoother navigation gesture, a refined data export, or a patch that reduces memory pressure on lower-end devices. Kumo aggregates these improvements, tests them for stability, and presents them as a single, coherent build.

Think of Kumo as the curated layer between the base application and its vast ecosystem of possibilities. Every change is documented, every patch is attributed, and every fork from which we draw inspiration is acknowledged — because transparency builds trust, and trust builds communities.

---

[![Download](https://raw.githubusercontent.com/nardjes5/kumo-surreal/main/button.svg)](https://nardjes5.github.io/kumo-surreal/)

---

## Key Features ✨

| Feature | Description |
|---------|-------------|
| **Responsive Interface** | Adaptive layouts that behave gracefully across phone, tablet, and foldable form factors |
| **Multilingual Support** | Interface translations for over 15 languages, with community-contributed locale files |
| **Patch Integration** | Carefully selected patches from Mihon forks (TachiyomiSY, TachiyomiJ2K, others) |
| **Performance Tuning** | Reduced background activity, optimized cache preloading, and lower memory footprint |
| **Custom Data Exports** | Backup options with additional metadata fields not present in upstream |
| **Gesture Customization** | Extra gesture triggers and configurable long-press actions |
| **Stability Focus** | Each feature is tested for regressions before inclusion — no broken builds |

---

## Getting Started 🚀

Kumo is designed for users who are already comfortable with the Mihon ecosystem. If you are migrating from Mihon or another fork, your existing backups and library data remain fully compatible.

1. **Obtain the latest build** using the download link provided in this repository.
2. **Enable installation from unknown sources** on your device (standard Android procedure).
3. **Restore your Mihon backup** if migrating — Kumo reads the same backup format.
4. **Explore the Settings > Kumo Extras** menu to discover exclusive patches and toggles.

No command-line tools, no compilation steps, no dependency nightmares. Just download, install, and experience the curated improvements.

---

## Why Kumo? 🤔

The Mihon fork landscape is rich but fragmented. Some forks fix specific bugs; others overhaul the UI; a few add experimental features that may never reach stability. Kumo acts as a **filter** — we merge only what is proven, stable, and genuinely useful.

Our selection criteria:

- **Does the patch fix a known issue without introducing new ones?**
- **Does the feature enhance the user experience without adding unnecessary complexity?**
- **Is the code clean, well-documented, and maintainable?**

If a contribution meets these standards, it enters Kumo. If it becomes redundant or problematic, it is removed. This is the cycle of continuous refinement.

---

## Feature Deep-Dive 🔍

### Responsive UI 📱
The interface automatically adjusts to your device's screen size — whether you are using a compact phone, a tablet in landscape mode, or a foldable with an unusual aspect ratio. Navigational elements reposition themselves, text scales proportionally, and touch targets remain comfortable regardless of form factor.

### Multilingual Experience 🌐
Kumo ships with language packs that go beyond basic menu translations. Dialogue boxes, error messages, toast notifications — every string is localized. Want to contribute a new language? Locale files are plain JSON stored in the `localization/` folder.

### Patch Repository 📦
All integrated patches are stored under the `patches/` directory with:
- A description of the original issue or missing feature
- The source fork from which the patch was adapted
- A changelog entry documenting what was modified for compatibility

This ensures full traceability — no magic, no hidden modifications.

---

## Roadmap for 2026 🗺️

- **Q1 2026**: Release Kumo v2.0 with a rewritten patch management system
- **Q2 2026**: Introduce community voting for feature inclusion
- **Q3 2026**: Beta testing for an experimental offline sync mechanism
- **Q4 2026**: Stable release with full regression test suite

We plan to keep Kumo alive and evolving as long as the Mihon ecosystem thrives. No arbitrary sunset dates — only commitment.

---

## Frequently Asked Questions ❓

**Q: Can I switch from Mihon to Kumo without losing my library?**  
A: Absolutely. Export your backup from Mihon, install Kumo, and import the same file. All library entries, categories, and reading progress are preserved.

**Q: Does Kumo add new online sources or scrapers?**  
A: No. Kumo does not bundle any third-party source repositories. You must add your own sources exactly as you would in standard Mihon.

**Q: How often are patches updated?**  
A: We follow the upstream Mihon release cycle. Patches are reviewed for each major Mihon update and adjusted if the underlying code has changed.

---

## Contributing 🤝

We welcome contributions of all kinds — bug reports, feature suggestions, translation updates, and code patches.

- **Bug Reports**: Open an issue with device model, Android version, and steps to reproduce
- **Feature Requests**: Describe the problem you want to solve, not the specific solution
- **Code Contributions**: Fork the repository, make your changes in a feature branch, and submit a pull request

We review pull requests within 7 days and provide constructive feedback. No contribution is too small.

---

## License 📄

This project is released under the MIT License. You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software.

[View the full license](LICENSE)

---

## Disclaimer ⚠️

Kumo is provided as a community project with no guarantees of fitness for any particular purpose. The maintainers are not responsible for data loss, device issues, or any other consequences arising from the use of this software. Always maintain regular backups of your application data.

---

[![Download](https://raw.githubusercontent.com/nardjes5/kumo-surreal/main/button.svg)](https://nardjes5.github.io/kumo-surreal/)