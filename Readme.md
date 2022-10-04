<h1 align="center">My Rust Copier Template</h1>

This repository contains my rust copier template, copier is a project templating tool, I use this repository for my rust projects, it contains a cli mode and a lib mode.

## Requirements

- [copier](https://copier.readthedocs.io/en/stable/)
- git

## Usage

```bash
copier copy gh:natir/copier-rust {project_name}
```

Answer question and start code !

I recommend to fork this repository or just copy the project to adapt it to your needs.

## Dependency

Lib mode (19/120 no-dev/dev dependencies in total):
- thiserror  = "1"
- log        = "0.4"
- criterion  = "0.3" (dev)
- stderrlog  = "0.4" (dev)

Cli mode (63/123 no-dev/dev dependencies in total):
- clap       = "3"
- anyhow     = "1"
- stderrlog  = "0.4"

## Version

This project **try** to follow [Semantic Versioning 2](https://semver.org/)
