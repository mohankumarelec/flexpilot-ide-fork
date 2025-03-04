# Flexpilot IDE - Open-Source AI Native IDE






```
export CC_aarch64_unknown_linux_musl=aarch64-linux-musl-gcc
export CXX_aarch64_unknown_linux_musl=aarch64-linux-musl-g++
export AR_aarch64_unknown_linux_musl=aarch64-linux-musl-ar
export CARGO_TARGET_AARCH64_UNKNOWN_LINUX_MUSL_LINKER=aarch64-linux-musl-gcc
```

```
rustup target add aarch64-unknown-linux-musl
cargo build --release --target aarch64-unknown-linux-musl

cargo build --target aarch64-unknown-linux-musl

export VSCODE_QUALITY=stable
export BUILD_SOURCEVERSION=cd4ee3b1c348a13bafd8f9ad8060705f6d4b9cba
npm run gulp vscode-reh-linux-arm64

./kill-code-server.sh
mkdir -p ~/.vscode-server-oss/cli/servers/Stable-cd4ee3b1c348a13bafd8f9ad8060705f6d4b9cba/server
cp -r ~/vscode-reh-linux-arm64/* ~/.vscode-server-oss/cli/servers/Stable-cd4ee3b1c348a13bafd8f9ad8060705f6d4b9cba/server/
```












> _"An open-source, free, AI-native, privacy-first IDE, forked from VS Code, offering the flexibility to bring your own keys for the LLMs of your choice."_

![Build](https://github.com/flexpilot-ai/flexpilot-ide/actions/workflows/build.yml/badge.svg)
![Release](https://github.com/flexpilot-ai/flexpilot-ide/actions/workflows/release.yml/badge.svg)
[![License](https://img.shields.io/badge/license-GNU%20GPLv3-blue.svg)](extensions/flexpilot/LICENSE)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.txt)
[![Star on GitHub](https://img.shields.io/github/stars/flexpilot-ai/flexpilot-ide?style=social)](https://github.com/flexpilot-ai/flexpilot-ide)

Flexpilot IDE is an open-source, AI-native, privacy-first IDE that offers the flexibility to bring your own keys for the LLMs of your choice. Forked from VS Code, Flexpilot IDE is designed to provide a seamless, AI-powered coding experience that is fully customizable, community-driven, and transparent.

## 🚀 Try Instantly Online

Experience the power of Flexpilot IDE without any installation! Click the button below to launch Flexpilot IDE in your browser and start browsing with AI-powered chat, and more.

[![Open in Flexpilot AI Web IDE](https://badges.flexpilot.ai/open-in-web-ide.svg)](https://flexpilot.ai/web-ide-redirect?provider=github&owner=flexpilot-ai&repo=flexpilot-ide&branch=main)

## 📦 Installation

1. Install Flexpilot IDE from the [GitHub Releases](https://github.com/flexpilot-ai/flexpilot-ide/releases/latest) page.
2. Configure your preferred Language model providers as explained [here](https://flexpilot.ai/configuration/chat.html) in the official documentation.
3. Start coding with AI-powered completions, chat, and more!

## ✨ Why Flexpilot?

- 🎯 **100% Native VS Code Experience** - No clunky webviews, just pure coding bliss
- 🔑 **Your Keys, Your Control** - Use your own API keys with top AI providers
- 🎨 **Ultimate Flexibility** - Mix and match AI models for different tasks
- 🌟 **Open Source Freedom** - Fully transparent, customizable, and community-driven
- 🚀 **Privacy-First Design** - No data collection, no tracking, no ads
- 💎 **GitHub Copilot Compatible** - Leverage your existing GitHub Copilot Extensions

## 🎯 Supported AI Providers

- Anthropic
- OpenAI
- Azure OpenAI
- Groq
- Google Gemini
- Mistral AI
- _Any many more!_

## 🤝 Contributing

We love contributions! Whether it's:

- 🐛 Bug Reports
- ✨ Feature Requests
- 📝 Documentation
- 💻 Code Contributions

## 📜 License

- The original code from [Code-OSS](https://github.com/microsoft/vscode) is licensed under the MIT license. See `LICENSE.txt` for details.
- Modifications made to the `extensions/flexpilot` folder are licensed under the GNU General Public License v3.0 (GPLv3). See `extensions/flexpilot/LICENSE` for details.

When using this repository, ensure compliance with both licenses as applicable.

## 🌟 Star Us on GitHub!

If you love Flexpilot, show your support [here](https://github.com/flexpilot-ai/flexpilot-ide) by starring us on GitHub! Every star motivates us to make Flexpilot even better.

<p align="center">
Made with ❤️ by developers, for developers
<br>
© 2024 Flexpilot AI Inc.
</p>
