# GitPulse

**GitHub developer intelligence, in your browser.**

GitPulse explores public GitHub profiles and presents developer activity, repositories, growth, technical insights, comparisons, visualizations, and shareable summaries in an interactive dashboard.

**Live app:** https://gitpulse-drab.vercel.app

## Features

- Public GitHub developer profile exploration
- Growth, intelligence, and technical analysis views
- Repository explorer and comparison tools
- History and universe visualizations
- Developer passport sharing and exports
- Light and dark themes
- Browser-based experience without an application server

## Getting started

Visit the [live app](https://gitpulse-drab.vercel.app), enter a public GitHub username, and explore the available tabs.

For local development, clone the repository and serve the root directory with a static web server:

```bash
git clone https://github.com/SACHITH31/gitpulse.git
cd gitpulse
python -m http.server 8000
```

Then open http://localhost:8000. You can also use any other static HTTP server.

## Technology

GitPulse is implemented in a single `index.html` file with HTML, CSS, and vanilla JavaScript. It retrieves public data from the GitHub API. Some visual resources load from external services.

## Limitations and privacy

- GitHub API rate limits apply. Public unauthenticated API requests have stricter limits.
- Insights are derived from the public GitHub data available at request time; they are not authoritative measures of developer ability.
- Some preferences and application data are stored in the browser. See the app's Privacy tab for controls.
- No GitHub access token is required for the documented public-profile workflow.

## Project structure

```text
.
├── index.html   # Application markup, styles, and scripts
└── README.md    # Project documentation
```

Additional community and maintenance files may be added alongside these.

## Contributing

Bug reports and suggestions are welcome through [GitHub Issues](https://github.com/SACHITH31/gitpulse/issues). See [CONTRIBUTING.md](CONTRIBUTING.md) for development guidance.

## Releases

See [CHANGELOG.md](CHANGELOG.md) for documented changes. A formal semantic-versioned release has not yet been established; do not assume the current deployment corresponds to `v1.0.0`.

## License

No open-source license has been selected yet. Until a license is explicitly added, copyright law generally reserves reuse and redistribution rights to the copyright holder.
