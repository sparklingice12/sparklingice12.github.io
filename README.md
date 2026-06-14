# dev.gary — Personal Portfolio

A VS Code-themed personal portfolio site built with React and TypeScript.

**Live:** https://sparklingice12.github.io/

## Tech Stack

- React 18 + TypeScript
- Material UI (MUI)
- React Router (HashRouter for GitHub Pages)
- Markdown-driven content pages
- GitHub Actions for CI/CD → GitHub Pages

## Development

```bash
npm ci
npm start
```

Opens at http://localhost:3000

## Deployment

Automatically deploys to GitHub Pages on every push to `main` via GitHub Actions.

Manual deploy:

```bash
npm run deploy
```

## Project Structure

```
src/
├── app/
│   ├── components/   # Reusable components (MDContainer)
│   ├── hooks/        # Custom hooks (page tracking)
│   ├── layout/       # App shell (sidebar, tabs, footer)
│   └── pages/        # Page components and route config
public/
└── pages/            # Markdown content files
```

## License

MIT
