# Installation Guide

This workshop will use `curl` to fetch data from an API and `jq` to parse and transform those results.

NOTE: If you're coming from a Windows world, know that we're going to be making heavy use of Unix pipes. Please consider using [WSL (Windows Subsystem for Linux)](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

## Install curl

You probably already have `curl` installed, let's check:

```bash
curl --version
```

If you are missing it, check out the [official curl downloads page](https://curl.se/download.html).

## Install jq

There is a chance that you might already have `jq` installed. Let's check:

```bash
jq --version
```

I'll be using version `1.6` in the workshop.

If you don't have it installed, the quickest way to install is via Homebrew:

```bash
brew install jq
```

For more installation options, see the [official jq download page](https://stedolan.github.io/jq/download/)

Let me know if you have any questions, and very much looking forward to hanging out with you!
