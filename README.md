# `@swc/cli` timing regression

- Node20 + npm
- swc 1.4.8 (latest)
- GitHub Action timings
- looks similar on local computer (& yarn4)

## `0.3.10` (latest)

https://github.com/bobaaaaa/swc-cli-bug/actions/runs/8355308408/job/22870145794

```
Successfully compiled: 2 files with swc (85.49ms)
```

## `0.1.65`

https://github.com/bobaaaaa/swc-cli-bug/actions/runs/8355345456/job/22870250651

```
Successfully compiled: 2 files with swc (13.6ms)
```