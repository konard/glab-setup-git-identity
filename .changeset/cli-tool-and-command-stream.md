---
'glab-setup-git-identity': minor
---

Add CLI tool and update library to use command-stream

- Add `glab-setup-git-identity` CLI command with all `glab auth login` options
- Update README.md to match gh-setup-git-identity structure with "Instead of manually running" section
- Refactor library to use command-stream for shell command execution
- Add support for all glab auth login options: --hostname, --token, --stdin, --git-protocol, --api-protocol, --api-host, --use-keyring, --job-token
- Add lino-arguments dependency for CLI argument parsing
- Update TypeScript definitions with new options (apiProtocol, apiHost, jobToken, stdin)
