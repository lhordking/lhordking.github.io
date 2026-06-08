# LoRA Forge

LoRA Forge is a powerful, client-side, browser-based tool designed for generating, managing, and exporting high-quality training datasets for Large Language Models (LLMs). Whether you are fine-tuning LoRAs for coding assistance, game development logic, or specialized domain reasoning, LoRA Forge streamlines the process from prompt generation to final dataset export.

## Features

* **Multi-Provider Agent Mode**: Connect to various LLM providers to generate training examples:
    * ☁️ **Cloud**: Claude, Groq, Gemini, OpenRouter, Mistral.
    * 🖥 **Local**: Ollama (for offline, privacy-focused generation).
* **Diverse Domain Specializations**: Supports 25+ LoRA specializations including:
    * Programming (Python, JavaScript, TypeScript, Go, C++, Rust, etc.)
    * Game Development (Unity C#, Shader programming, MMORPG systems)
    * Reasoning & Logic (AI Agents, Compiler Design, Smart Contracts)
    * Finance & Trading (Forex, Crypto)
* **Structured Dataset Management**:
    * Auto-detects and structures dataset records from chat exchanges.
    * Supports multiple export formats: **JSONL**, **Alpaca**, and **ShareGPT**.
    * Includes a built-in Dataset Drawer to manage, edit, and export your collections.
* **Privacy-First Design**: 
    * **All operations are performed client-side**. 
    * Your API keys are stored only in your browser's local storage and are **never** transmitted to any third-party server by this tool.
    * Data generation sessions are persisted locally using IndexedDB.

## How to Use

1.  **Configure**: Open the Cloud Agent config (or scan your local Ollama instance) and add your API key if using cloud providers.
2.  **Rules**: Fine-tune your generation output in the **Fine-Tune Rules** panel (choose persona, format, and quality filters).
3.  **Topics**: Use the **Topic Library** to select specific coding domains, difficult scenarios, or question types (e.g., *Refactor*, *Debug*, *Implement*).
4.  **Generate**: Hit the "Generate" button. The tool will stream outputs and populate your dataset.
5.  **Export**: Once satisfied, use the **Dataset Drawer** on the right to download your data in your preferred format.

## Privacy & Security

This tool runs entirely in your browser. 
* **No backend storage**: We do not store your data, datasets, or API keys on our servers.
* **Local Storage**: Your API keys and generated training records are kept locally in your browser's `localStorage` and `IndexedDB`. You are in full control of your data.

## Deployment

To host this tool, you can deploy it as a static site via **GitHub Pages**, **Vercel**, or **Netlify**. Simply upload the `index.html` file to your hosting environment.

---
*Built for developers by developers.*
