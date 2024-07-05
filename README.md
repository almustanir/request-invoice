# Request-Ease

**Request-Ease** is a decentralized payments and invoicing management system built on top of the Request Network. It enables users to create invoices and accept payments in various forms, offering a seamless experience for handling crypto transactions.

## Features 🛠️

With Request-Ease, you can:

- **Create Invoices**: Generate invoices with detailed party information, payment options, and invoice specifics.
- **Accept Payments**: Receive payments through various methods:
  - Native Cryptocurrencies: ETH, MATIC, etc.
  - ERC20 Tokens: DAI, USDC, etc.
  - Bitcoin
  - Fiat Currencies: USD, EUR, etc.
  - Superfluid Streams

Invoices adhere to the `rnf_invoice-0.0.3` schema standard by the Request Network.

### Invoice Creation

The invoice creation process is streamlined and validated using `Zod` and `React Hook Form`, ensuring data accuracy and reliability. Invoices can also be downloaded as PDFs using `@react-pdf/renderer`.

### Payment Methods

Payments can be made through:
- Smart contract proxies
- Token swaps
- Direct payments

## Demo Video 🎥

Experience Request-Ease in action by watching our [demo video](https://youtu.be/wjhLFYQTIpc).

## Tech Stack 🧑🏼‍💻

Request-Ease leverages modern technologies to deliver a robust and intuitive user experience:

- **Frontend**: Built with Next.js and styled using Tailwind CSS and shadcn UI components.
- **Integration**: Seamlessly integrates with `@requestnetwork/request-client.js` for handling payment requests and processing.

## Getting Started 🚀

Request-Ease is organized as a turborepo and is divided into the following:

- **apps/www**: The web application powered by Next.js.

### Installation

To get started with development, follow these steps:

1. **Install dependencies**:

   ```bash
   npm install
   ```
2. **Configure environment variables: Populate the .env.local file in apps/www with the necessary environment variables.**

  ```bash
    NEXT_PUBLIC_WALLETCONNECT_ID="your_walletconnect_project_id"
  ```
3. **Run The Application**
  ```bash
  npm run dev
  ```
