# pre-commit-shfmt hook

Single [pre-commit](http://pre-commit.com/) hook which runs
**[shfmt](https://github.com/mvdan/sh)** on shell script files (forked from
https://github.com/pecigonzalo/pre-commit-shfmt).

An example `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/fauust/pre-commit-fmt
  rev: master
  hooks:
    - id: shell-fmt
      args: ['-d', '-i', '2']
```

The **[shfmt](https://github.com/mvdan/sh)** tool must installed separately.

Enjoy the clean code!
