# Actions

Action to install the (legacy) rtools40 bundle. This version was preinstalled on GitHub Actions until april 2023.

To use it add this to your workflows:

```yml
  - if: runner.os == 'windows'
    uses: r-windows/install-rtools@master
```
