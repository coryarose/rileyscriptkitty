# Riley Script Kitty Repository

This repository contains a simple web server that serves a free code repository to everyone except a user named Riley.

## Usage

1. Ensure you have Node.js installed.
2. Run `node index.js` to start the server.
3. Visit `http://localhost:3000/?user=YourName` in your browser.
   - Replace `YourName` with any name except `Riley` to access the repository.
   - If `user=Riley`, the server returns an access denied page.

The website is 100% free for all users except Riley.
