# Auk Documentation

Documentation for Auk - Local-first API development tool

## About Auk

Auk is a local-first API development tool based on Auk. It focuses on local storage and Git collaboration, giving you full control over your API data without relying on cloud services.

**Key Features:**
- 🏠 Local-first: All data stored on your device
- 🔄 Git Sync: Team collaboration via Git
- 💼 Multi-Workspace: Organize projects independently
- ⚡ High Performance: Native desktop app
- 🌐 Offline Ready: Work without internet
- 🔒 Data Security: You control your data

## Documentation Structure

```
docs/
├── documentation/          # Main documentation
│   ├── getting-started/   # Installation and setup
│   ├── concepts/          # Core concepts
│   ├── workspace/         # Workspace management
│   ├── git-sync/          # Git synchronization
│   ├── features/          # Feature documentation
│   ├── storage/           # Data storage
│   ├── clients/           # Desktop and CLI
│   └── protocols/         # API protocols
├── guides/                # Guides and tutorials
│   ├── migration/         # Migration guides
│   └── articles/          # Best practices
└── support/               # Support resources
```

## Local Development

### Prerequisites

- Node.js (version 19 or higher)
- npm or pnpm

### Setup

```bash
# Install Mintlify CLI globally
npm i -g mintlify

# Or using pnpm
pnpm add -g mintlify
```

### Run Development Server

```bash
# Start the dev server
mintlify dev

# Open browser to http://localhost:3000
```

### Build for Production

```bash
# Build static site
mintlify build

# Preview production build
mintlify preview
```

## Documentation Guidelines

### Writing Style

- Use clear, concise language
- Write in active voice
- Use present tense
- Be specific and actionable
- Include code examples where helpful

### Structure

Each documentation page should include:

1. **Title and Description** - Clear frontmatter
2. **Introduction** - Brief overview
3. **Main Content** - Organized with headings
4. **Examples** - Code snippets and use cases
5. **Next Steps** - Related documentation links

### Code Examples

Use code blocks with language specification:

````markdown
```bash
# Bash commands
auk --version
```

```javascript
// JavaScript code
pw.env.set("token", "value");
```

```json
{
  "key": "value"
}
```
````

### Components

Available Mintlify components:

- `<Card>` - Feature cards
- `<CardGroup>` - Group of cards
- `<Steps>` - Step-by-step instructions
- `<Tabs>` - Tabbed content
- `<Accordion>` - Collapsible sections
- `<Note>` - Information notes
- `<Warning>` - Warning messages
- `<Tip>` - Helpful tips

## Project Information

- **Website:** [auk.mamahuhu.io](https://auk.mamahuhu.io)
- **Documentation:** [auk.mamahuhu.dev](https://auk.mamahuhu.dev)
- **GitHub:** [github.com/mamahuhu-io/auk](https://github.com/mamahuhu-io/auk)
- **Based on:** [Hoppscotch](https://github.com/hoppscotch/hoppscotch)

## Contributing

We welcome contributions to improve the documentation!

### How to Contribute

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `mintlify dev`
5. Submit a pull request

### What to Contribute

- Fix typos and grammar
- Improve clarity and examples
- Add missing documentation
- Update outdated information
- Translate to other languages

## Documentation Status

### Completed ✅

- [x] Home page and introduction
- [x] Installation guide
- [x] Workspace creation guide
- [x] Git setup guide
- [x] Local-first concepts
- [x] Collections documentation
- [x] Environments documentation
- [x] Migration guides (Postman, Insomnia, Auk)
- [x] Local-first workflow guide

### In Progress 🔄

- [ ] Git sync detailed guides
- [ ] Workspace management guides
- [ ] Storage documentation
- [ ] Additional best practices guides

### Planned 📋

- [ ] Video tutorials
- [ ] Advanced topics
- [ ] API reference
- [ ] Cookbook/recipes
- [ ] Community contributions

## Support

Need help?

- **Documentation:** Browse the docs at [auk.mamahuhu.dev](https://auk.mamahuhu.dev)
- **GitHub Issues:** Report issues at [github.com/mamahuhu-io/auk/issues](https://github.com/mamahuhu-io/auk/issues)
- **Discussions:** Join discussions on GitHub

## License

This documentation is licensed under the MIT License.

Based on [Hoppscotch Documentation](https://github.com/hoppscotch/hoppscotch) which is also MIT licensed.

---

**Maintained by:** [mamahuhu.io](https://mamahuhu.io)

**Last Updated:** 2026-02-20
