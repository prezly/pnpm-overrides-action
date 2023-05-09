# prezly/pnpm-overrides-action

Update package.json file defining `pnpm.overrides` for specific packages.

## Usage

```yaml
  steps:
    - uses: prezly/pnpm-overrides-action
      with:
        # List any packages with their versions to use for the override
        react: '16.8.0'
        react-dom: '16.8.0'
```
