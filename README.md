# Brightspace/setup-node

This action is the same as [actions/setup-node](https://github.com/actions/setup-node), except with safe-chain configured.

## Usage

```yml
- uses: Brightspace/setup-node@main
  with:
    node-version-file: .nvmrc
```

For a list of the available options, refer to [the inputs in this workflow](https://github.com/Brightspace/third-party-actions/blob/actions/setup-node/action.yml#L5).
