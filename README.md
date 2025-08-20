# Simple Messenger Bot

A simple Messenger bot built using Node.js, Express, and WebSocket.

## Features
* Control panel to start and stop the bot
* Group name locking and nickname locking functionality
* WebSocket-based communication between the control panel and the bot

## Requirements
* Node.js
* Express
* WebSocket
* ws3-fca (Facebook Messenger API library)

## Installation
1. Clone the repository
2. Run `npm install` to install dependencies
3. Start the bot using `node main.js`

## Usage
1. Open the control panel at `http:                 
2. Select your cookie file and enter the prefix and admin ID
3. Start the bot
4. Use the bot's functionality in your Messenger group

           
* `!groupnamelock on <group_name>`: Locks the group name
* `!nicknamelock on <nickname>`: Locks the nickname for all group members

        
* Make sure to replace the `ws3-fca` library with your own Facebook Messenger API implementation if necessary.
* This bot is for educational purposes only and should not be used for malicious activities.
