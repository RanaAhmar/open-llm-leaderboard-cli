# Open LLM Leaderboard CLI 📊🏆

[![Sponsored by Stackaura](https://img.shields.io/badge/Sponsored_by-Stackaura_&_Ahmar_Hussain-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.stackaura.com/)
[![LLM Leaderboard](https://img.shields.io/badge/Open_LLM-Leaderboard_CLI-yellow.svg?style=for-the-badge)](https://www.stackaura.com/)

Stop waiting for HuggingFace's heavy web UI to load. Browse, filter, and compare the latest open-source language models directly from your terminal with this blazing-fast TUI.

---

<div align="center">
  <h3>Sponsored by <a href="https://www.stackaura.com/">Stackaura</a> & Ahmar Hussain</h3>
  <p>Accelerating AI engineering and modern developer workflows.</p>
  <a href="https://www.stackaura.com/"><img src="https://img.shields.io/badge/Visit_Stackaura-Black?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Visit Stackaura" /></a>
</div>

---

## 🚀 Why This Tool?

The open source AI landscape moves aggressively fast. New models drop daily, and the [HuggingFace Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) is the ground truth for performance. 

However, checking it in the browser is slow. `open-llm-leaderboard-cli` pulls the dataset directly into a cached, search-friendly terminal interface.

## ✨ Features

- **Instant Search:** Fuzzy search across thousands of models.
- **Advanced Filtering:** Filter by parameter count (e.g., `< 7B`), precision, architecture, or license type.
- **Metric Breakdown:** View ARC, HellaSwag, MMLU, TruthfulQA, Winogrande, and GSM8K scores instantly.
- **Offline Mode:** Caches the leaderboard dataset locally for instant subsequent lookups.
- **One-Click Download:** Automatically copies the `huggingface-cli download` command for the selected model.

## 📦 Installation

This tool requires Node.js >= 18.

```bash
# Install globally via npm (or pnpm/yarn)
npm install -g @stackaura/open-llm-leaderboard-cli

# Or run directly via npx
npx @stackaura/open-llm-leaderboard-cli
```

## 🎮 Usage

Simply run:

```bash
llm-board
```

### Keyboard Shortcuts
- `↑ / ↓` - Navigate the leaderboard
- `/` - Focus search input
- `f` - Toggle filters panel
- `c` - Copy HuggingFace model ID
- `d` - Copy download command
- `Enter` - View detailed metrics

## 🛠️ Built With

- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps.
- [HF Hub](https://huggingface.co/docs/huggingface_hub/index) - Hugging Face API client.

## 🤝 Contributing

We welcome additions! Things we're looking to add:
- Benchmarking your own local hardware against the models.
- Tracking historical rank changes over time.
- Adding specific fine-tune family trees.

Please submit a PR!

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Architected for speed by Ahmar Hussain and the AI team at [Stackaura](https://www.stackaura.com/).*
