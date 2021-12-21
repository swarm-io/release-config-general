# release-config-general
A semantic-release sharable configuration for releasing general code. This is a generic config that has no exec plugins. It performs a release with changelog, release notes, git plugin to commit the changelog, and github plugin to create a github release.
## Plugins

This shareable configuration use the following plugins:

- [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
- [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
- [`@semantic-release/changelog`](https://github.com/semantic-release/changelog)
- [`@semantic-release/git`](https://github.com/semantic-release/git)
- [`@semantic-release/github`](https://github.com/semantic-release/github)

## Install

```bash
$ npm install --save-dev semantic-release @swarm-io/release-config-general
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@swarm-io/release-config-general"
}
```

## Configuration

See each [plugin](#plugins) documentation for required installation and configuration steps.

