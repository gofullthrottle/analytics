# Documentation

This project uses [Fumadocs](https://fumadocs.vercel.app/) for documentation.

## Quick Start

### Option 1: Add to Existing Next.js Project

```bash
# Install Fumadocs
npm install fumadocs-ui fumadocs-core fumadocs-mdx

# Install MDX dependencies
npm install @mdx-js/loader @mdx-js/react

# Create content directory
mkdir -p content/docs
```

### Option 2: Create Standalone Docs Site

```bash
# Create new Fumadocs project
npx create-fumadocs-app docs-site

# Or with specific template
npx create-fumadocs-app docs-site --template contentlayer
```

## Directory Structure

```
docs/
├── README.md           # This file
├── content/            # MDX content (if using Fumadocs in this repo)
│   └── docs/
│       ├── index.mdx   # Docs homepage
│       └── ...
└── architecture/       # Architecture Decision Records (ADRs)
    └── README.md
```

## Writing Documentation

### MDX Files

Create `.mdx` files in `content/docs/`:

```mdx
---
title: Getting Started
description: How to get started with this project
---

# Getting Started

Your content here...
```

### Frontmatter Options

```yaml
---
title: Page Title           # Required
description: SEO description
icon: Rocket                # Lucide icon name
full: true                  # Full-width layout
---
```

## Fumadocs Features

- **Search**: Built-in full-text search
- **Dark Mode**: Automatic theme support
- **MDX**: Full MDX support with components
- **TypeScript**: First-class TypeScript support
- **Syntax Highlighting**: Code blocks with Shiki
- **Table of Contents**: Auto-generated TOC

## Resources

- [Fumadocs Documentation](https://fumadocs.vercel.app/)
- [Fumadocs GitHub](https://github.com/fuma-nama/fumadocs)
- [MDX Documentation](https://mdxjs.com/)
