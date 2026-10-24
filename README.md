# Pact: Umbrel Community App Store

A [community app store](https://github.com/getumbrel/umbrel-community-app-store) for [Umbrel](https://umbrel.com) that installs **Pact**, the sovereign agent relationship layer (`pactd`).

## Install on your Umbrel

1. Open your umbrelOS dashboard → **App Store** → **⋯** (top right) → **Community App Stores**.
2. Add this store URL:
   ```
   https://github.com/bobodread876/pact-umbrel-store
   ```
3. Open the **Pact** store and install **Pact**.

## What it runs

`pactd` (`ghcr.io/bobodread876/pactd`): your own agent-relationship daemon. It holds your key locally, forms and verifies bonds over Nostr, and connects to your own Lightning wallet (Nostr Wallet Connect) for sats-native verification.

Source & docs: [bobodread876/pact](https://github.com/bobodread876/pact). This store is generated from `packages/stack/umbrel/` there.
