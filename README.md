# Homebrew Tap for Razorpay CLI

This is the official [Homebrew](https://brew.sh) tap for the [Razorpay CLI](https://github.com/razorpay/razorpay-cli).

## Prerequisites

[Homebrew](https://brew.sh) must be installed on your system. To install Homebrew, run the following in your terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Installation

```bash
brew install razorpay/razorpay-cli/razorpay
```

Or add the tap first, then install:

```bash
brew tap razorpay/razorpay-cli
brew install razorpay
```

## Getting Started

After installation, configure the CLI with your Razorpay credentials:

```bash
razorpay configure
```

Or pass the credentials directly:

```bash
razorpay configure --key-id rzp_test_xxxxxxxxxxxx --key-secret xxxxxxxxxxxxxxxxxxxx
```

## Updating

```bash
brew upgrade razorpay
```

## Supported Platforms

- macOS (Apple Silicon / arm64)
- macOS (Intel / x86_64)

## Related

- [Razorpay CLI](https://github.com/razorpay/razorpay-cli) - Source repository for the CLI
- [Razorpay API Docs](https://razorpay.com/docs/api/)
