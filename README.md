# Corentin Mors — Profile Site

<img src="https://avatars.githubusercontent.com/u/4266283?v=4&s=200" alt="Portrait of Corentin Mors" width="100" align="right" />

Personal profile site hosted on [GitHub Pages](https://pages.github.com/), available at **[me.pixelswap.fr](https://me.pixelswap.fr/)**.

## About

**Corentin Mors** is Co-founder and CTO of [Subnoto](https://subnoto.com), where he builds confidential e-signature solutions for enterprises using cloud trusted execution environments. With over seven years of experience in software development and security — including as Senior Software Engineer at Dashlane — his work spans passkeys, secure authentication, confidential computing, and software infrastructure.

## Related sites

| Site | URL | Description |
|------|-----|-------------|
| Profile | [me.pixelswap.fr](https://me.pixelswap.fr/) | This site — experience, talks, publications |
| Dev | [dev.pixelswap.fr](https://dev.pixelswap.fr/) | Technical writing and projects |
| Blog | [pixelswap.fr](https://pixelswap.fr/) | Personal blog |
| Subnoto | [subnoto.com](https://subnoto.com/) | Confidential e-signature platform |

## Contact

- **Email:** medias@pixelswap.fr
- **LinkedIn:** [linkedin.com/in/corentinmors](https://www.linkedin.com/in/corentinmors/)
- **Bluesky:** [@corentin.mors.dev](https://bsky.app/profile/corentin.mors.dev)

## Repository structure

```
├── index.html       # Main profile page
├── css/style.css    # Styles
├── resources/       # Talk recordings and media
├── robots.txt       # Crawler directives
├── sitemap.xml      # Search engine sitemap
├── llms.txt         # LLM-readable site summary
└── llms-full.txt    # Full structured profile for AI systems
```

## SEO & discoverability

The site includes:

- Semantic HTML (`main`, `section`, `header`, `footer`)
- Meta tags and Open Graph metadata
- [JSON-LD](https://schema.org/Person) structured data (`Person` schema)
- `robots.txt` and `sitemap.xml` for search engines
- [`llms.txt`](https://llmstxt.org/) and `llms-full.txt` for AI/LLM discoverability

## Development

This is a static site — no build step required. Push to the default branch and GitHub Pages serves it via the `CNAME` file (`me.pixelswap.fr`).

To preview locally:

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## License

All rights reserved. Code may be partially reproduced; content is property of its owner.
