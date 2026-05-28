# Claude Project

## Projectoverzicht
Deze repository bevat Claude-gerelateerde bestanden, waaronder skills, prompts en configuraties voor gebruik met Claude AI en Claude Code.

## Repository structuur
- `.github/` — GitHub configuratiebestanden en workflows
- `.claude/` — Claude Code instellingen en MCP configuratie
- `Agent-Skills-for-Context-Engineering-main.zip` — Skills voor context engineering
- `caveman-main.zip` — Caveman skill
- `stop-slop-main.zip` — Stop-slop skill voor het verwijderen van AI schrijfpatronen
- `ui-ux-pro-max-skill-main.zip` — UI/UX Pro Max skill

## Werken met deze repository

### Claude Code gebruiken
Claude Code kan direct in deze repo worden gebruikt. Zorg dat je de ANTHROPIC_API_KEY hebt ingesteld:
```bash
export ANTHROPIC_API_KEY=your_api_key_here
claude
```

### GitHub MCP
Deze repo is geconfigureerd met de GitHub MCP server (zie `.claude/settings.json`). Hiermee kan Claude Code direct met GitHub werken: issues lezen, PRs aanmaken, code pushen, etc.

Zorg dat je GITHUB_PERSONAL_ACCESS_TOKEN is ingesteld:
```bash
export GITHUB_PERSONAL_ACCESS_TOKEN=your_github_token_here
```

### GitHub Actions
Gebruik `@claude` in een PR-comment of issue om Claude Code automatisch in te schakelen via GitHub Actions.

## Conventies
- Bestanden in de root zijn skills of configuraties voor Claude
- Zip-bestanden bevatten uitpakbare skill-mappen
- Houd de README.md up-to-date bij nieuwe toevoegingen
