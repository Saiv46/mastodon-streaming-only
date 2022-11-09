# mastodon-streaming-only
Mastodon Streaming API server, but extracted from main repository

It's basically https://github.com/mastodon/mastodon with only files needed to **run** Streaming API server.

## Setup
1. Clone this repository and install dependencies
(I recommend using [pnpm](https://github.com/pnpm/pnpm) as fast and efficient alternative to NPM or Yarn)
```sh
git clone https://github.com/Saiv46/mastodon-streaming-only.git
cd mastodon-streaming-only
pnpm i
```

2. Read Mastodon's .env file and run Streaming API server
```sh
set -a; source .env; set +a
pnpm start
```
