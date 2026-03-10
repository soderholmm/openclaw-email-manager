# 📧 Email Manager Skill for OpenClaw

A complete, non-interactive email management skill for [OpenClaw](https://github.com/openclaw/openclaw) agents, built for Postfix (MTA) and Dovecot (MDA) infrastructure. Zero external dependencies, pure Python standard library.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.6+](https://img.shields.io/badge/python-3.6+-blue.svg)](https://www.python.org/downloads/)

## ✨ Features

- ✅ **Complete email management** - Read, send, drafts, folders, flags, spam
- ✅ **Zero dependencies** - Uses only Python standard library
- ✅ **Non-interactive** - Perfect for AI automation
- ✅ **Human-readable output** - Clean formatting with emojis
- ✅ **JSON output** - Machine-parsable for agents
- ✅ **Postfix/Dovecot ready** - Works with your existing infrastructure

## 📚 Documentation

For complete usage instructions, commands, and examples, see the **[SKILL.md](SKILL.md)** file.

## ⚙️ Quick Start

```bash
# Clone repository
git clone https://github.com/yourusername/openclaw-email-manager.git
cd openclaw-email-manager

# Configure your email settings
cp config.example.json config.json
# Edit config.json with your credentials

# Make scripts executable
chmod +x scripts/*.py

# Test connection
python3 scripts/imap_utils.py list-folders
```

## 📦 Installation for OpenClaw

```bash
# Create skill directory
mkdir -p ~/OpenClaw-Workspace/skills/email-manager

# Copy files
cp -r * ~/OpenClaw-Workspace/skills/email-manager/

# Link skill (if using OpenClaw)
openclaw skills link ~/OpenClaw-Workspace/skills/email-manager
```

## 🤝 Support the Project

If you find this skill useful, consider buying me a coffee! Your support helps maintain and improve the project.

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/yourusername)

**PayPal:**
```
https://paypal.me/yourusername
```

**Bitcoin:** `bc1qxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx`

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

Copyright (c) 2024 Mattias Söderholm

## 🙏 Acknowledgements

- [OpenClaw](https://github.com/openclaw/openclaw) - The AI agent framework
- Postfix and Dovecot - The excellent MTA and MDA

## 📬 Contact

- GitHub Issues: [https://github.com/yourusername/openclaw-email-manager/issues](https://github.com/yourusername/openclaw-email-manager/issues)
- Email: your.email@example.com


## 🖼️ Optional: Add Donation Badges

You can also add these badges at the top for visibility:

[!["Buy Me A Coffee"](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-FF813F?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://www.buymeacoffee.com/yourusername)
[![PayPal](https://img.shields.io/badge/PayPal-donate-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/yourusername)
```

Just replace `yourusername` with your actual:
- Buy Me A Coffee username
- PayPal.me username
- Bitcoin address (if including)