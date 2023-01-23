# [DEMO] Onboard a public action to ASML Marketplace

This repository and contents were created following the documentation "[Creating a Docker container action](https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action)" from GitHub Docs.
This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: vineeth-asml/onboard-actions-demo@v2
with:
  who-to-greet: 'Mona the Octocat'

