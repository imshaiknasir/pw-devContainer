# Playwright Test Environment

This repository provides a GitHub Codespaces environment with:
- **Node.js LTS** (latest long-term support version)
- **@playwright/test** with browser dependencies
- **Ubuntu-based container** (Debian Bookworm)
- **VS Code extensions**: Playwright Test, GitHub Copilot, ESLint

## 🚀 Quick Start

**[Launch Codespace](https://codespaces.new/imshaiknasir/pw-devContainer?quickstart=1)**

## What's Included

- Playwright Test framework pre-installed
- Chromium browser with system dependencies
- Pre-configured VS Code settings and extensions
- Common development ports forwarded (3000, 5173, 8080)

## Getting Started

Once your Codespace launches, you can start writing tests:

```bash
# Create a basic test
npx playwright test --help

# Run tests
npx playwright test

# Open test results
npx playwright show-report
```
