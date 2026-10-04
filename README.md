# instagram-telegram-n8n-automation
An n8n automation workflow for connecting Instagram Direct messages with Telegram, enabling sales teams to receive customer messages and send replies back to Instagram.

# Instagram ↔ Telegram n8n Automation

An automation workflow built with **n8n** to connect Instagram Direct messages with Telegram.

This system allows sales teams to receive customer messages from Instagram directly in Telegram and send their replies back to Instagram through an automated workflow.

## Features

* Instagram Direct → Telegram
* Telegram → Instagram replies
* Customer identification
* Support for text messages
* Support for voice messages
* Automated message routing
* Webhook-based communication
* n8n workflow automation

## Workflow

Instagram → n8n → Telegram → Sales Expert → n8n → Instagram

## Technologies

* n8n
* Instagram Graph API
* Telegram Bot API
* Webhooks
* JSON

## How It Works

1. A customer sends a message through Instagram Direct.
2. Instagram sends the event to the n8n webhook.
3. n8n processes the incoming message.
4. The message is forwarded to the sales expert through Telegram.
5. The sales expert replies to the customer from Telegram.
6. n8n processes the reply.
7. The response is sent back to the customer's Instagram Direct.

## Project Structure

* `WorkFlow.json` — Main n8n workflow
* `Screenshot 2026-09-30 160535.png` — Workflow screenshot

## Security

Sensitive credentials, API tokens, passwords, and private configuration values should not be included in this repository.

## Future Improvements

* Improved conversation history
* Better customer management
* AI-assisted responses
* Advanced sales analytics
* Improved Telegram interface

## License

This project is provided for educational and development purposes.
