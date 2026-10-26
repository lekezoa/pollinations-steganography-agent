# 🌸 Pollinations Secret Steganography Studio

> Built for **[POLLEN-QUEST #18367](https://github.com/pollinations/pollinations/issues/18367)**: An app, game or tool about messages hidden in images.

[![Pollinations](https://img.shields.io/badge/Pollinations.ai-BYOP%20Ready-yellow?logo=star)](https://enter.pollinations.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## 🎯 Overview
Inspired by research on LLM steganography (where models hide secrets within generated SVG code or visual pixel matrices without altering image appearance), this tool lets users:
1. **Synthesize AI Visual Vector Art:** Generate responsive, dynamic vector artwork via Pollinations.ai API models (`openai`, `claude`).
2. **Hide Secret Messages Invisibly:** Embed encrypted tokens, passwords, or secret instructions directly into the vector layer or metadata.
3. **AI Cryptanalysis & Extraction:** Extract, verify, and decipher hidden payloads with zero visual distortion.
4. **Bring Your Own Pollen (BYOP):** Integrated with the native `<pollinations-connect>` web component, allowing users to connect their Pollen wallets directly.

## 🚀 Live Demo & Usage
Open `index.html` in any web browser or host on GitHub Pages:
- **Encode:** Enter a scene description and your secret message. Click **Generate & Hide Secret**.
- **Download:** Download the generated `.svg` file containing the invisible steganogram.
- **Decode:** Upload any generated stego file to instantly extract the hidden message.

## 📦 Tech Stack
- **AI Models:** Pollinations.ai Text & Multimodal APIs
- **Wallet Auth:** Pollinations Bring Your Own Pollen (`connect.js`)
- **Format:** Scalable Vector Graphics (SVG) + Steganographic payload layer
- **Architecture:** Zero-dependency, 100% client-side + edge API execution.

---
**Author:** [@lekezoa](https://github.com/lekezoa)  
**Submission for Issue:** https://github.com/pollinations/pollinations/issues/18367
