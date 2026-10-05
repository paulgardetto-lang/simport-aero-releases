# SimPort Aero — update channel

This is SimPort Aero's one update channel for all its products. It holds **finished, tested installers only**.
It never holds program code: each product's code lives in its own private repository.

## Where the downloads are
On the **[Releases](https://github.com/paulgardetto-lang/simport-aero-releases/releases)** page. No sign-in is needed.

## How releases are named
`<product>-v<version>`, for example `wind-tunnel-v1.2.0`, `metars-map-v2.0.1` or `space-station-v1.0.0`.
Each release holds that product's Windows installers (Kiosk and Desktop versions) and a short list of what changed.

The **"Source code" downloads** that GitHub adds to every release contain only this README. There is no program
code here.

A release marked **Pre-release** with a name starting `channel-test` is only a test of the channel and is not a
product.

## Rules for this repository
- Only `README.md` and the check in `.github/` may be stored here. The **channel check** fails if anything else
  is added.
- Installers are attached to releases, never committed as files.
- Only installers that have passed their product's tests are published.
