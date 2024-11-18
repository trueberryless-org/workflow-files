# `workflow-files`

Provide single point of truth for workflow files.

## Project structure

```yaml
├── .changeset/
│   ├── config.json # Configuration for changeset
│   └-─ README.md
├── .github/
│   ├── workflows/
│   │   ├── release.yaml # Create changeset if desired
│   │   └-─ sync.yaml # Create PRs on target repos when triggered by changeset
├── worflow-files/ # Actual files which get synced to target repos
│   ├── deployment.yaml
│   ├── publish.yaml
│   ├── release.yaml
│   └-─ welcome-bot.yaml
├── .gitignore
├── LICENCE
├── package.json
├── pnpm-lock.yaml
├── README.md
└── repos.json # List target repos with sync options
```

## License

Licensed under the MIT License, Copyright © trueberryless-org.

See [LICENSE](/LICENSE) for more information.
