# FF GLORY Website (mobile-first reference design)

## Run
1. Download and extract the ZIP.
2. Open `index.html` in a browser on your phone or computer.
3. Enter any username and a password with at least 4 characters. This is only a demo login.

## Files
- `index.html`: login page and dashboard
- `style.css`: mobile-first neon/cyber design, network-style background, cards and responsive layout
- `app.js`: demo interactions for login, menu, amount choices and feature popups

## Important
This is a visual front-end prototype. Login does not verify users or provide secure sessions. Account creation is not implemented. Top-up does not charge money. All server/status numbers are illustrative. Before public launch, use secure server-side authentication, a database, server-side validation and an authorized payment provider. Never place payment secrets in browser JavaScript.


## QR preview
The provided `payment-qr.jpg` is shown after a valid amount is entered and Continue is pressed. The amount is displayed beside the QR, but this static QR does not necessarily encode the amount. For auto-filled amount and confirmed payment status, integrate a payment provider's authorized dynamic QR/API on a secure backend.
