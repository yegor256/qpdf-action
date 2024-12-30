# Qpdf Installer for GitHub Actions

[![test](https://github.com/yegor256/qpdf-action/actions/workflows/test.yml/badge.svg)](https://github.com/yegor256/qpdf-action/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yegor256/qpdf-action/blob/master/LICENSE.txt)

This GitHub action installs [`qpdf`](https://github.com/qpdf/qpdf):

```yaml
- uses: yegor256/qpdf-action@master
```

I'm sorry, but it works on Ubuntu only. If you know how to
make it work no MacOS and Windows, please, submit a pull
request, I will gladly accept it.

Also, there is no caching now. This means that every time it will
take about 10 minutes to install qpdf, on every single build. This is
terrible, but I don't know how to fix this. If you know, please
submit a pull request.
