# idux-bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that A Probot app
> Inspired by [zorro-bot](https://github.com/NG-ZORRO/zorro-bot) 😍.

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t idux-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> idux-bot
```

## Contributing

If you have suggestions for how idux-bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[MIT](LICENSE) © 2021 IduxFE
