# 🚀 Cursor Rules Starter Kit

> **Production-ready `.cursor/rules/` templates for AI-assisted development.**  
> Stop configuring. Start coding with proper AI assistance in 60 seconds.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Cursor AI](https://img.shields.io/badge/Cursor-AI%20Editor-blue)](https://cursor.com)

---

## 🎯 Why This Exists

Cursor AI is incredible, but configuring rules for optimal AI assistance is time-consuming:

- ❌ Fragmented documentation
- ❌ Outdated `.cursorrules` examples (old format)
- ❌ No comprehensive starters for popular stacks
- ❌ Trial and error to find what works

**This kit solves that.** Copy these tested rules and get AI that actually understands your project.

---

## 📦 What's Included

| Stack | Description | Status |
|-------|-------------|--------|
| [Next.js + TypeScript + Tailwind](#nextjs) | Modern React framework | ✅ Ready |
| [Python + FastAPI](#python) | Backend API development | ✅ Ready |
| [AI/LLM Development](#ai-llm) | Building with AI APIs | ✅ Ready |
| [General Best Practices](#general) | Universal standards | ✅ Ready |

---

## ⚡ Quick Start

### Option 1: Copy Individual Rules

1. Navigate to `.cursor/rules/` in this repo
2. Copy the rule file you need
3. Paste into your project's `.cursor/rules/` directory
4. Restart Cursor or reload

### Option 2: Clone the Whole Kit

```bash
# Clone just the rules directory
git clone https://github.com/jamesships/cursor-rules-starter-kit.git
cp -r cursor-rules-starter-kit/.cursor/rules/* your-project/.cursor/rules/
```

### Option 3: Use as Git Submodule

```bash
git submodule add https://github.com/jamesships/cursor-rules-starter-kit.git .cursor-kit
ln -s .cursor-kit/.cursor/rules .cursor/rules
```

---

## 📁 Rule Structure

Each rule follows the official Cursor MDC format:

```
.cursor/
└── rules/
    ├── nextjs-typescript.mdc
    ├── python-fastapi.mdc
    ├── ai-development.mdc
    └── general-practices.mdc
```

Rule files include:
- YAML frontmatter (description, globs, alwaysApply)
- Markdown instructions for the AI
- Stack-specific conventions and patterns

---

## 🔧 Rules Reference

<a name="nextjs"></a>
### Next.js + TypeScript + Tailwind

**File:** `.cursor/rules/nextjs-typescript.mdc`

Perfect for:
- Next.js 13+ App Router projects
- TypeScript with strict mode
- Tailwind CSS styling
- Server Components & Actions

Key behaviors:
- Prefers server components by default
- Uses modern TypeScript patterns
- Follows Tailwind best practices
- Implements proper error handling

<a name="python"></a>
### Python + FastAPI

**File:** `.cursor/rules/python-fastapi.mdc`

Perfect for:
- REST API development
- Async Python patterns
- Pydantic data validation
- SQLAlchemy/database integration

Key behaviors:
- Type hints everywhere
- Async-first approach
- Proper dependency injection
- OpenAPI documentation

<a name="ai-llm"></a>
### AI/LLM Development

**File:** `.cursor/rules/ai-development.mdc`

Perfect for:
- OpenAI/Anthropic API integration
- LangChain projects
- Prompt engineering
- AI agent development

Key behaviors:
- Structured prompt formatting
- Error handling for API calls
- Token optimization awareness
- Safety and rate limiting

<a name="general"></a>
### General Best Practices

**File:** `.cursor/rules/general-practices.mdc`

Universal rules for:
- Git commit message formatting
- Code documentation standards
- File naming conventions
- Error handling patterns

---

## 🆚 Old Format vs New Format

This kit uses the **NEW** `.cursor/rules/*.mdc` format, not the deprecated `.cursorrules` file.

| Feature | Old `.cursorrules` | New `.cursor/rules/*.mdc` |
|---------|-------------------|---------------------------|
| Multiple rule files | ❌ | ✅ |
| Per-file glob patterns | ❌ | ✅ |
| YAML frontmatter | ❌ | ✅ |
| Conditional application | ❌ | ✅ |
| Version controlled | ⚠️ Single file | ✅ Organized structure |

---

## 🤝 Contributing

Found a better pattern? Have a stack not covered?

1. Fork this repo
2. Add your rule to `.cursor/rules/`
3. Update this README
4. Open a PR

---

## 📊 Roadmap

- [ ] Vue.js + Nuxt rules
- [ ] Rust development rules
- [ ] Go + Gin/Echo rules
- [ ] Ruby on Rails rules
- [ ] React Native / Expo rules

---

## 📄 License

MIT License - Use freely, attribution appreciated.

---

## ⭐ Star This Repo

If these rules save you time, please star ⭐ to help others discover it!

---

*Built with 🤖 by developers who were tired of configuring AI assistants.*
