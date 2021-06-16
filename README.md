# flame-format-action

Opinionated Github action for code format validation

How to use it

```yml
jobs:
  dartdoc:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: subosito/flutter-action@v1
        with:
          channel: 'stable'
      - uses: flame-engine/flame-format-action@v1
```
