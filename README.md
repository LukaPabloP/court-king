# Court King

A queue manager for pickup basketball. Teams scan a QR code at the court, register, and challenge the winner. The winner stays on, the next team in the queue comes in.

**Live:** https://lukapablop.github.io/court-king/

## The problem

On a busy outdoor court nobody knows who is up next. Court King gives every team at the court the same live view on their phone.

## Features

- Register a team with one tap, no account needed
- Challenge the current winner and join the queue
- Live view of the current game, the queue, all teams and the game history
- Tap the winning team to end a game, the next challenger starts automatically
- Changes show up on every phone in real time
- German and English, switchable in the app
- QR code for quick access at the court

## Tech stack

A single HTML file with plain JavaScript and CSS, Firebase Realtime Database for live sync, hosted on GitHub Pages.

## Run it locally

Open `index.html` in a browser. To use your own database, replace the Firebase config in `index.html` with the one from your Firebase project.
