# Fibonacci SDK Documentation

This repository contains the documentation for the Fibonacci SDK, built with [Mintlify](https://mintlify.com).

## 🚀 Quick Start

### Local Development

1. Install the Mintlify CLI:
   ```bash
   npm i -g mintlify
   ```

2. Run the development server:
   ```bash
   mintlify dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Deployment

This documentation auto-deploys to Mintlify when you push to the `main` branch.

## 📁 Structure

```
├── docs.json              # Mintlify configuration
├── index.mdx              # Landing page
├── favicon.svg            # Site favicon
├── logo/
│   ├── light.svg          # Logo for light mode
│   └── dark.svg           # Logo for dark mode
├── getting-started/       # Getting started guides
├── guides/                # In-depth guides
├── sdk-reference/         # Python SDK reference
└── api-reference/         # REST API reference
```

## ✏️ Contributing

1. Create a new branch
2. Make your changes
3. Submit a pull request

### Adding a New Page

1. Create an `.mdx` file in the appropriate directory
2. Add frontmatter with `title` and `description`
3. Add the page to `docs.json` navigation

Example:

```mdx
---
title: 'My New Page'
description: 'Description of the page'
---

# My New Page

Content goes here...
```

## 📚 Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [MDX Syntax Guide](https://mdxjs.com/)
- [Fibonacci SDK](https://github.com/fibonacci-ai/fibonacci-sdk)

## 📄 License

MIT License - see LICENSE file for details.
