# AGENTS

This repo contains the Hugo source for robertzd.github.io and the robert.dybvad.net personal site.

## Key facts
- Default branch: master
- GitHub Pages deployment: gh-pages branch, root folder (/)
- Custom domain: static/CNAME (robert.dybvad.net)
- Theme usage: none (built-in layouts)

## Structure
- config.toml: site settings, social links, public key links, footer text
- layouts/: Hugo templates (base, index, single, partials)
- assets/css/main.css: main stylesheet (Hugo Pipes)
- assets/img/RobertDybvad.jpg: portrait used on homepage
- static/: public keys and CNAME

## Content conventions
- Social links are configured via [[params.socialLinks]] in config.toml
- Public keys are configured via [[params.publicKeys]] in config.toml
- Footer text is configured via params.extra.copyrightText

## Deployment
- GitHub Actions workflow: .github/workflows/hugo.yml
- Builds Hugo and deploys to gh-pages branch
- Pages settings should point to gh-pages / (root)
