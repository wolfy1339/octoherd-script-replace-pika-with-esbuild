# octoherd-script-replace-pika-with-esbuild

> Octoherd script to replace Pika with ESBuild

[![@latest](https://img.shields.io/npm/v/octoherd-replace-pika-with-esbuild.svg)](https://www.npmjs.com/package/octoherd-replace-pika-with-esbuild)
[![Build Status](https://github.com/wolfy1339/octoherd-script-replace-pika-with-esbuild/workflows/Test/badge.svg)](https://github.com/wolfy1339/octoherd-script-replace-pika-with-esbuild/actions?query=workflow%3ATest+branch%3Amain)

## Usage

Minimal usage

```js
npx octoherd-replace-pika-with-esbuild@latest
```

Pass all options as CLI flags to avoid user prompts

```js
npx octoherd-replace-pika-with-esbuild@latest \
  -T ghp_0123456789abcdefghjklmnopqrstuvwxyzA \
  -R "wolfy1339/*"
```

## Options

| option                       | type             | description                                                                                                                                                                                                                                 |
| ---------------------------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--octoherd-token`, `-T`     | string           | A personal access token ([create](https://github.com/settings/tokens/new?scopes=repo)). Script will create one if option is not set                                                                                                         |
| `--octoherd-repos`, `-R`     | array of strings | One or multiple space-separated repositories in the form of `repo-owner/repo-name`. `repo-owner/*` will find all repositories for one owner. `*` will find all repositories the user has access to. Will prompt for repositories if not set |
| `--octoherd-bypass-confirms` | boolean          | Bypass prompts to confirm mutating requests                                                                                                                                                                                                 |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

## About Octoherd

[@octoherd](https://github.com/octoherd/) is project to help you keep your GitHub repositories in line.

## License

[ISC](LICENSE.md)
