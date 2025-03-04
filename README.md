# Discord Multi-Voice (A useful Self-Afk selfbot)

A Discord selfbot client that allows you to join multiple voice channels through commands.

## Features

-   Join voice channels with the `Voice` command
-   Check Discord API latency with the `Ping` command
-   Colorful console logging with the `Logs` utility

## Installation

To install dependencies:

```bash
bun install
```

## Configuration

Create a .env file in the root directory with your Discord token:

```
TOKEN=your_discord_token_here
```

## Usage

To run the bot:

```bash
bun run start
```

### Available Commands

-   `&voice [link]` - Join a Discord voice channel using a channel link
-   `&ping` - Check your latency to the Discord API

## Docker Support

You can also run this project using Docker:

```bash
# Build the image
docker build -t discord-multi-voice .

# Run the container (replace with your Discord token)
docker run -e TOKEN=your_discord_token_here discord-multi-voice
```

This project uses [Bun](https://bun.sh), a fast all-in-one JavaScript runtime.
