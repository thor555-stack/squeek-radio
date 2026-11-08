# Squeek Radio

Live generative music and a stream overlay, played by Squeektoshi's wheel on Squeekchain.

- Wheel running: tempo and filter follow the real RPM from the Squeekchain API.
- Wheel resting: a slow sleep drone. Naps are music too.
- New Squeek block: bell chime. New settled round: bass drop.
- Notes are seeded from the live block height and work counter, so every run is its own song.

## Stream overlay (OBS)
Browser Source: `<site>/?overlay=1&autoplay=1`, tick "Control audio via OBS".

## Data
Reads `https://api.squeekchain.com/v1/status` in the browser every 5 seconds. No wallet, no signing.

<!-- SQUEEKCHAIN_REPO_LINE -->

squeekchain-project: fe85e5b6-2683-4897-b3e6-7e2e1f6dce04
