# Hyperliquid API Specification

This repository contains the OpenAPI 3.1.1 specification for the Hyperliquid HTTP API, generated from the [Hyperliquid API documentation](https://hyperliquid.gitbook.io/hyperliquid-docs/for-developers/api).

## Overview

Hyperliquid is a decentralized exchange (DEX). This specification covers:

- **Info Endpoint** (`POST /info`) - Read-only queries for market data, account information, and historical data
- **Exchange Endpoint** (`POST /exchange`) - Signed trading actions and account operations

## Usage

This OpenAPI specification can be used to:

- Generate client libraries in various programming languages
- Validate API requests and responses
- Generate API documentation
- Set up API mocking for development and testing


## Development

Linting of the OpenAPI specification is done using [Spectral](https://github.com/stoplightio/spectral).

```
npx @stoplight/spectral-cli lint openapi.yml
```
