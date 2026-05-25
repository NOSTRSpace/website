# nostr.space Website

Static website for [nostr.space](https://nostr.space).

## Relays

- Production: `wss://relay.nostr.space` — [relay.nostr.space](https://relay.nostr.space/)
- Development: `wss://dev-relay.nostr.space` — [dev-relay.nostr.space](https://dev-relay.nostr.space/)

## Tech Stack

Pure HTML + CSS. No frameworks, no build step.

## Workflow

- `develop` → deployed to [dev.nostr.space](https://dev.nostr.space)
- `main` → deployed to [nostr.space](https://nostr.space)
- Pushes to `develop` open an auto-release PR to `main`.

## License

[MIT](LICENSE)
