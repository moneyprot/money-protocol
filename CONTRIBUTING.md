# Contributing to Money Protocol

Thank you for your interest in contributing to Money Protocol. We welcome contributions from developers, researchers, and community members.

---

## Ways to Contribute

### 1. Report Bugs
If you find a bug, please open a GitHub issue with:
- A clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Any relevant logs or screenshots

### 2. Suggest Features
Have an idea? Open a GitHub issue labeled `enhancement` and describe:
- The problem you're solving
- Your proposed solution
- Any alternatives you've considered

### 3. Submit Pull Requests
We welcome PRs for:
- Bug fixes
- Documentation improvements
- Test coverage improvements
- Performance optimizations

### 4. Security Vulnerabilities
**Do NOT open a public issue for security vulnerabilities.**
Please follow our [Security Policy](SECURITY.md) and report privately.

---

## Development Setup

### Prerequisites
- Node.js v18+
- Rust (latest stable)
- Solana CLI v1.18+
- Anchor CLI v0.30+

### Getting Started
```bash
# Clone the repo
git clone https://github.com/moneyprot/money-protocol.git
cd money-protocol

# Install dependencies
npm install

# Build programs
anchor build

# Run tests
anchor test
```

---

## Pull Request Guidelines

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit with clear messages: `git commit -m "feat: add yield optimizer bounds check"`
4. Push to your fork: `git push origin feature/your-feature`
5. Open a Pull Request against `main`

### Commit Message Format
```
type: short description

Types: feat, fix, docs, test, refactor, chore
```

---

## Code of Conduct

- Be respectful and constructive
- No spam, harassment, or off-topic content
- Focus on technical merit

---

## Questions?

Join our community:
- Twitter: [@MoneyProt](https://x.com/MoneyProt)
- Telegram: [t.me/moneyprot](https://t.me/moneyprot)
