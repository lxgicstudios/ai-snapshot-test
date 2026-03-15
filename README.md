# ai-snapshot-test

[![npm version](https://img.shields.io/npm/v/ai-snapshot-test.svg)](https://www.npmjs.com/package/ai-snapshot-test)
[![npm downloads](https://img.shields.io/npm/dm/ai-snapshot-test.svg)](https://www.npmjs.com/package/ai-snapshot-test)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-snapshot-test)](https://github.com/lxgic-studios/ai-snapshot-test/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Auto-generate Jest snapshot tests for your React components. Covers all prop variations and edge cases.

## Install

```bash
npm install -g ai-snapshot-test
```

## Usage

```bash
npx ai-snapshot-test ./src/components/Button.tsx
# → Generated ./src/components/Button.snap.test.tsx

npx ai-snapshot-test "./src/components/*.tsx"
# → Generates tests for all components
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT


---

Built by [LXGIC Studios](https://github.com/LXGIC-Studios)

🔗 [GitHub](https://github.com/LXGIC-Studios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
