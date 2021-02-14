# Installation Guide

This workshop will make heavy use of `curl` to fetch data from an API and `jq` to parse and transform those results.

NOTE: We are going to be making heavy use of Unix pipes, so if you are coming from a Windows world, please consider using [WSL (Windows Subsystem for Linux)](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

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

I'll be using version 1.6 in the workshop.

If you don't have it installed, the quickest way to install is via Homebrew:

```bash
brew install jq
```

For more installation options, see the [official jq download page](https://stedolan.github.io/jq/download/)

Looking forward to hanging out!
