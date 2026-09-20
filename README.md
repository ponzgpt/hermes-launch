> [!NOTE]
> **Moved.** This is now `field-guide/` in **[ponzgpt/hermes-contributions](https://github.com/ponzgpt/hermes-contributions)**, together
> with the three other things I built around Hermes Agent. Live at
> **<https://hermes-contributions.technoir.cloud/field-guide/>**; `launch.technoir.cloud` now redirects there.
>
> This repository is archived and read-only. It is kept rather than deleted so that nothing
> already linking here breaks.
>
> The price table that lived here was a promotional snapshot and went out of date without
> saying so. The version in the new repo is generated from the live Nous Portal catalogue and
> re-checked on every build.

# Hermes Field Guide

An independent, practical guide to Hermes Agent for technically curious people with some computer experience and little agent-infrastructure experience.

The guide is written for Javier's own learning first, then shared with classmates as an early reader test and possible ICP signal. It is not official Nous Research documentation.

## Current status

- Version: `0.1`
- Reviewed against: official Hermes documentation index on 2026-09-13
- Public site: https://launch.technoir.cloud/
- Official source of truth: https://hermes-agent.nousresearch.com/docs/
- Model prices: dated snapshot; verify the live Nous Portal catalogue before spending money

## Editorial and pricing rule

The official documentation and live model catalogue win. Changes should be reviewed against the generated machine-readable index before publication. Examples must not contain credentials, tokens or connection strings. Price points are illustrative combinations, not guarantees or financial advice.

## Check and deploy

```bash
./scripts/check.sh
./scripts/deploy.sh
```

See [DEPLOYMENT.md](DEPLOYMENT.md).
