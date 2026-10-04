# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

This repository is a university research project ("Trabajo de investigación universitario") for an application that uses LoRa. It currently has no source code, build system, tests, or dependencies; the only file besides this one is `README.md`. Existing project text is in Spanish.

Because nothing is in place yet, there are no build, lint, or test commands, and no target platform, language, or hardware has been chosen. Don't assume a stack. Ask the user or take it from the code they add.

## Keeping this file current

When the first code lands, update this file with:
- The build, flash/deploy, lint, and test commands, including how to run a single test.
- The overall architecture. For a LoRa project this usually means how the end-node firmware, the gateway, and any backend or app fit together, the radio parameters and payload format they share, and where each part lives in the repo.
