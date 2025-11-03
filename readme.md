# Go Twitter Bot

A simple Twitter bot written in Go that can post tweets using the Twitter API.

## Features

- OAuth 1.0a authentication with Twitter API
- Automated tweet posting
- Environment variable configuration
- Error handling and logging

## Prerequisites

- Go 1.x or higher
- Twitter Developer Account
- Twitter API Keys and Tokens

## Installation

1. Clone the repository:
```bash
git clone https://github.com/MuhammadAbdulMoiz/go-twitter-bot.git
cd go-twitter-bot
```

2. Install dependencies:
```bash
go mod download
```

## Configuration

1. Create a `.env` file in the root directory
2. Add your Twitter API credentials:
```env
CONSUMER_KEY=your_consumer_key
CONSUMER_SECRET_KEY=your_consumer_secret
ACCESS_TOKEN=your_access_token
ACCESS_TOKEN_SECRET=your_access_token_secret
```

## Usage

Run the bot:
```bash
go run main.go
```

## Dependencies

- [github.com/dghubble/go-twitter/twitter](https://github.com/dghubble/go-twitter) - Go Twitter REST API Client
- [github.com/dghubble/oauth1](https://github.com/dghubble/oauth1) - OAuth1 implementation
- [github.com/joho/godotenv](https://github.com/joho/godotenv) - Environment variable loader

## Project Structure

```
go-twitter-bot/
├── main.go         # Main application file
├── go.mod          # Go module file
├── go.sum          # Go module checksum
└── .env            # Environment variables (not in repo)
```

## Acknowledgments

- Thanks to the creators of the go-twitter library
- Twitter Developer Platform for providing the API

## Author

MuhammadAbdulMoiz

---
**Note:** Make sure to keep your API keys and tokens secret and never commit them to the repository.
