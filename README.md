# HTML_QnA_MS_Learn

## Overview

`HTML_QnA_MS_Learn.html` is a web application that integrates with Azure Bot Framework to provide a chat interface. Users can interact with a bot to get answers to their questions. This example demonstrates how to use the Bot Framework Web Chat component to create a full-featured chat interface on a web page.

## Prerequisites

Before using the application, ensure you have the following:

1. **Azure Bot Service**: An active Azure Bot Service with a Direct Line channel configured.
2. **Direct Line Secret**: The secret key for your Direct Line channel.

## Files

- **HTML_QnA_MS_Learn.html**: The main HTML file containing the structure and logic for the web chat application.

## Setup

1. **Clone the Repository**: Clone or download the repository containing the `HTML_QnA_MS_Learn.html` file to your local machine.

2. **Update the Direct Line Secret**:
   - Open the `HTML_QnA_MS_Learn.html` file in a text editor.
   - Locate the line that initializes the Direct Line secret:
     ```javascript
     directLine: window.WebChat.createDirectLine({ secret: 'your_direct_line_secret' })
     ```
   - Replace `'your_direct_line_secret'` with your actual Direct Line secret key.

## Usage

1. **Open the HTML File**: Open the `HTML_QnA_MS_Learn.html` file in a web browser.

2. **Interact with the Bot**:
   - The web page will load a chat interface.
   - You can type your questions or messages in the input box and press Enter to send them to the bot.
   - The bot's responses will be displayed in the chat interface.

## Customization

You can customize the appearance and behavior of the chat interface by modifying the HTML, CSS, and JavaScript in the `HTML_QnA_MS_Learn.html` file. Refer to the [Bot Framework Web Chat documentation](https://github.com/microsoft/BotFramework-WebChat) for more details on customization options.

## Troubleshooting

If you encounter any issues, consider the following steps:

- **Check Console Logs**: Open the browser's developer console (F12 or right-click and select "Inspect") to see any error messages.
