# Grass Airdrop Eligibility Checker

A small, browser-based tool for checking a wallet's Grass airdrop allocation across epochs. It shows adjusted and original token totals, tier details, and possible sybil flags.

**[Open the live checker](https://cathisses.github.io/grass_checker/)**

## Run locally

No build step or dependencies are required. Clone the repository and serve the directory with any static web server:

```bash
git clone https://github.com/cathisses/grass_checker.git
cd grass_checker
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) and enter a wallet address.

The app fetches allocation data from the Grass API through the AllOrigins CORS proxy. It is an unofficial community tool; always verify important allocation information with official Grass sources.

## License

[MIT](LICENSE)
