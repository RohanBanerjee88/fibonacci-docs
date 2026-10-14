# Fibonacci Documentation

The documentation for Fibonacci (the platform, its REST API and the Python SDK), built with [Mintlify](https://mintlify.com).

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
├── changelog.mdx          # What changed, newest first
├── favicon.svg            # Site favicon
├── logo/
│   ├── light.svg          # Logo for light mode
│   └── dark.svg           # Logo for dark mode
├── getting-started/       # Quickstart, authentication, connecting your tools
├── guides/                # Workflows, tools, developer workflows, governance, external agents
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

Tool names, parameters and API paths must match the backend (fibonacci-mainframe):
`GET /api/v1/tools` lists every tool with its schema, and `/docs` on the API lists
every endpoint. In MDX, keep `{{templates}}` and `<`/`>` inside backticks or code
blocks; bare ones break the page.

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
