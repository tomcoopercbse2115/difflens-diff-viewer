# DiffLens - Text and JSON Diff Tool 2026

> **DiffLens is a self-contained browser application for comparing text and JSON on your own device. It uses LCS-based matching, multiple result layouts, normalization controls, and offline-friendly local execution without dependencies.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tomcoopercbse2115/difflens-diff-viewer?style=flat-square)](https://github.com/tomcoopercbse2115/difflens-diff-viewer)

---

<p align="center">
  <a href="https://tomcoopercbse2115.github.io/difflens-diff-viewer/">
    <img src="https://img.shields.io/badge/Download-DiffLens%20Latest-brightgreen?style=for-the-badge" alt="Download DiffLens">
  </a>
</p>

> **[Download DiffLens](https://tomcoopercbse2115.github.io/difflens-diff-viewer/)**

---

[Download Latest Build](https://tomcoopercbse2115.github.io/difflens-diff-viewer/)

---

## Overview

DiffLens provides a straightforward way to inspect differences between two text values or JSON documents. Its line-oriented longest common subsequence (LCS) algorithm identifies changes, while side-by-side and inline modes provide different ways to review the result. It can be used for source-code review, document comparison, and structured-data checks.

Everything runs in the browser from one HTML file. No external libraries are needed. For more control over the comparison, DiffLens includes JSON normalization, optional recursive ordering of keys, case and whitespace settings, input swapping, change statistics, and light or dark themes.

---

## Highlights

- Compare text and JSON with line-based LCS matching
- Choose between inline output and a two-column side-by-side view
- Normalize JSON and optionally sort keys recursively
- Treat letter case and whitespace as significant or ignore them
- Reverse the A/B direction with the swap action
- See summary statistics for the detected changes
- Use either a light or dark interface
- Run locally from a single HTML file with zero dependencies

---

## Getting Started

### Download and run

1. Visit the [latest DiffLens build](https://tomcoopercbse2115.github.io/difflens-diff-viewer/).
2. Save the page to your computer for local, standalone use.
3. Open the saved HTML file in a modern web browser.

### Use the repository copy

```bash
git clone https://github.com/tomcoopercbse2115/difflens-diff-viewer.git
cd REPO
```

After cloning, open the primary HTML file in a browser. Local operation needs neither a package manager nor a build process or web server.

---

## Comparing Content

1. Open DiffLens in a web browser.
2. Put the earlier or original content into the A panel.
3. Enter the updated content in the B panel.
4. Pick either the side-by-side or inline result layout.
5. When working with JSON, turn on normalization to minimize formatting-related differences.
6. Enable recursive key sorting if object property order should be disregarded.
7. Select the appropriate case and whitespace behavior.
8. Use the swap control whenever you need to reverse the comparison.
9. Inspect the highlighted edits and the accompanying statistics.

---

## Available Settings

DiffLens has no separate configuration file. All comparison choices are made through the controls in the application.

The interface provides settings for:

- JSON normalization
- Recursive sorting of JSON object keys
- Case-sensitive or case-insensitive matching
- Whitespace-sensitive or whitespace-insensitive matching
- Inline or side-by-side diff output
- Light or dark themes

---

## Requirements

- A modern web browser
- No installed runtime or package manager
- No network access for local execution
- A local copy of the single-file HTML application
- Enough browser memory for the documents being compared

---

## Frequently Asked Questions

### Is an internet connection needed?

No. DiffLens is intended for offline-first use. After the HTML file has been obtained, you can open it locally without a network connection.

### Does it support JSON comparisons?

Yes. JSON input can be compared with normalization enabled, and object keys can optionally be sorted recursively.

### What output formats can I use?

DiffLens offers both side-by-side and inline presentations of the comparison.

### Can formatting changes be excluded?

Yes. You can ignore differences in letter case or whitespace through the comparison controls. JSON normalization can further reduce differences caused only by how structured data is represented.

### How can I get a newer version?

Open the [latest build link](https://tomcoopercbse2115.github.io/difflens-diff-viewer/), download the currently published version, and replace your existing local file when necessary.

### How can I make a busy comparison easier to understand?

Switch between the inline and side-by-side layouts and adjust the case or whitespace options. For structured documents, try JSON normalization. Reversing the inputs with the swap control may also make the change direction clearer.

### Where are the settings saved?

No configuration file is required. DiffLens settings are chosen directly in the browser interface.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
