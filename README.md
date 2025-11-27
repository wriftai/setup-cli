# WriftAI CLI Action

## About

This GitHub Action sets up the [`WriftAI CLI`](https://github.com/wriftai/cli) on GitHub Actions runners.

This action supports  `ubuntu-latest`, `windows-latest`, and `macos-latest` GitHub Actions runners, and will install either specified version or latest available of the `WriftAI CLI` on the runner environment. 

Once installed, the CLI can be used in subsequent workflow steps.

---

## Usage

### Install the latest version
 
```yaml
steps:
  - uses: wriftai/setup-cli@v1
```

### Install a specific version

```yaml
steps:
  - uses: wriftai/setup-cli@v1
    with:
      version: v0.31.0
```

### Run CLI commands after setup

```yaml
steps:
  - run: wriftai models get --owner user-001 --name my-model
```

---

## Inputs

| Name      | Type   | Description                                 | Default  | Required |
| --------- | ------ | ------------------------------------------- | -------- | -------- |
| `version` | String | WriftAI CLI version to install, or `latest` | `latest` | false    |

---

## Outputs

| Name      | Type   | Description                                  |
| --------- | ------ | -------------------------------------------  |
| `version` | String | WriftAI CLI version installed                |

---

## Contributing 
Coming soon.

## Releases 
To publish a new version, manually create a tag and release from the repository. Also ensure that `Publish to Marketplace` is checked when creating a release. 

## License 
Copyright (c) Sych Inc. All rights reserved. 

Distributed under the terms of the [Apache 2.0 license](./LICENSE).