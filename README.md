[![test](https://github.com/yegor256/qpdf-action/actions/workflows/test.yml/badge.svg)](https://github.com/yegor256/qpdf-action/actions/workflows/test.yml)

This GitHub action installs [`qpdf`](https://github.com/qpdf/qpdf):

```yaml
- uses: yegor256/qpdf-action@latest
```

## How to Contribute

In order to test this action, just run:

```bash
$ make test
```

This should build a new Docker image and then try to use it
in order to render a simple `test.tex` document. You need to have
[Docker](https://docs.docker.com/get-docker/) installed.
