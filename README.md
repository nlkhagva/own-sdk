<div align="center">
  <h1>SDK</h1>
</div>

This package contains methods providing Saleor business logic for storefront. It handles Saleor GraphQL queries and mutations, manages Apollo cache and provides internal state to manage popular storefront use cases, like user authentication or checkout process.

Please take a look at [sample storefront](https://github.com/mirumee/saleor-storefront) which already uses Saleor SDK. For specific use cases you may also refer to [saleor-sdk/examples](https://github.com/mirumee/saleor-sdk/tree/add/examples/examples/react/typescript/src).

> :warning: **Note: Saleor SDK is still under heavy development and its API may change.**

## Table of Contents

- [Setup](#setup)
- [Features](#features)
- [Local development](#local-development)

## Setup

There are two ways to use SDK - making custom implementation or using React components and hooks, which already has that implementation ready.

### Using React

First install SDK as dependency to your project

```bash
npm i nlkhagva-sdk
```
