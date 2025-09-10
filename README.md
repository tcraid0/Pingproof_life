# PingProof.life

A simple check-in timer. If you don't check in, it posts your message on Nostr and tags the contact you choose. Runs entirely in your browser.

## How it works

- Generate or import keys
- Add contact's npub
- Write a message
- Set a timer (1 min to 72 hours)
- If the timer runs out while the tab is open, the message is posted and the contact is tagged

## Notes

- Runs entirely in your browser (frontend only, no servers)
- Keys never leave your device (stored in localStorage)
- Uses nostr-tools
- Hobby project. Not a substitute for emergency services

## Run locally

1. Clone this repo
2. Open `index.html` in a browser
3. Done

## License

MIT

## Disclaimer

**Hobby project. Not a substitute for emergency services. Use responsibly.**

## Contributing

Issues and pull requests welcome, but response times may vary.
