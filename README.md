# Renovate Configuration

Centralized configuration for Renovate.

## Usage

Please use the latest tag as a reference from the [latest release](https://github.com/juancarlosjr97/one-renovate-configuration-to-rule-them-all/releases/latest).

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>juancarlosjr97/one-renovate-configuration-to-rule-them-all#0.5.1"]
}
```

## Configuration

The Renovate configuration is available on the [default.json](./default.json).

## Presets

| Name | Usage | Purpose |
|------|-------|---------|
| `presets/internal-tooling-circular` | `github>juancarlosjr97/one-renovate-configuration-to-rule-them-all//presets/internal-tooling-circular#main` | Prevents circular dependency update churn among the four core internal tooling repositories. Intended **only** for those repos. See [docs/INTERNAL_USAGE.md](./docs/INTERNAL_USAGE.md) for full details. |
