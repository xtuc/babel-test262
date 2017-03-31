# babel-test262

[![Greenkeeper badge](https://badges.greenkeeper.io/xtuc/babel-test262.svg)](https://greenkeeper.io/)

Tests are transpiled using babel-preset-env.

## Usage

### Run all tests

```bash
run_tests
```

### Run an entier test suite

```bash
run_tests built-ins
```

### Run a test suite with a folder

```bash
run_tests language asi
```

### Run a single test

```bash
run_tests language asi S7.9.2_A1_T1
```

It will then expend to `test262/test/language/asi/S7.9.2_A1_T1.js`

## Configuration

### Browser target

Export `TARGET_BROWSERS`.
