# friendly-reminder

> A GitHub App built with [Probot](https://github.com/probot/probot) that A friendly reminder which remind you that its time to release !

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
docker build -t friendly-reminder .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> friendly-reminder
```

## Contributing

If you have suggestions for how friendly-reminder could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2020 F Martino <florence.martino.fm@gmail.com>