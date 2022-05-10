# SubQuery Starter Project for Terra

This fork was made to test out this PR: https://github.com/subquery/subql/pull/995

This is a starter project for Indexing Terra. It includes a simple blockhandler and an event handler. This project indexes all transfer events in bombay-12.

# Geting Started

### 1. Install dependencies

```shell
yarn
```

### 2. Generate types

```shell
yarn codegen
```

### 3. Build

```shell
yarn build
```

### 4. Run locally

```shell
yarn start:docker
```
