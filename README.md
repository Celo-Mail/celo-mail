# Celo Mail

## Secure Payment Notifications

![](https://user-images.githubusercontent.com/19412160/110847421-e6848e80-827a-11eb-9946-0636ebedc4be.png)

![Screen Shot 2021-03-11 at 3 04 51 PM](https://user-images.githubusercontent.com/19412160/110847656-2cd9ed80-827b-11eb-9ccc-73e961434632.png)

Celo Mail is a simple and secure way to recieve email notifications whenever you recieve a payment. Emails are encrypted with Advanced Encryption Standard (AES), a encryption chosen by the U.S. government to protect classified information. The same technology used to encrypt classified information is also used to purchase a coffee on Celo.

## Development

Install

```bash
yarn
```

Create `.env` in root with these variables

```
CUSD_ADDRESS=0x874069Fa1Eb16D44d622F2e0Ca25eeA172369bC1
WEB3_SOCKET=wss://alfajores-forno.celo-testnet.org/ws
AES_KEY=[1, 2, 3]
EMAIL_HOST=smtp.mail.com
EMAIL_PORT=587
EMAIL_USERNAME=sending@email.com
EMAIL_PASS=super-secure-password
```

Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/](http://localhost:3000/api/qr). This endpoint can be edited in `pages/api/qr.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

