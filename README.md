<div align="center">
<a href="https://travelswap.xyz">
  <img width="400px" alt="Travelswap – Book Hotels, Resorts & Vacation Rentals with crypto today." src="https://travelswap.xyz/images/logo.png">
  <h1 align="center">Bounties</h1>
</a>
</div>


[https://travelswap.xyz](https://travelswap.xyz)

## Intro

TravelSwap is an online travel agency platform that allows users to search for and book hotels, resorts, and vacation rentals using cryptocurrencies such as Bitcoin, Ethereum, and other popular digital assets.

TravelSwap partners with community and brands in order to facilitate their travel. Partners include:
 - Pudgy Penguins
 - Token2049
 - Memeland
 - [and more](https://travelswap.xyz/sitemap/partners)
 
It also partners with crypto platforms/blockchains such as:
 - SUI
 - Brave

### 2024 Goals

 - Implement Multichain Reward Program
 - Add Flight

TravelSwap is lookiny for talent in order to scale the business and develop the platform.
We are currently seeking developers to assist us. As part of this, we offer bounties. Additionally, there is the possibility of a full-time position.

## Tech Stack

### Front-end

Whole booking / payment flow, handles all web3 related interactions.

- [Next.js](https://nextjs.org/) – framework
- [TypeScript](https://www.typescriptlang.org/) – language
- [Tailwind](https://tailwindcss.com/) – CSS
- [NextAuth.js](https://next-auth.js.org/) – auth
- [Turborepo](https://turbo.build/repo) – monorepo
- [Stripe](https://stripe.com/) – payments
- [Paypal](https://paypal.com/) – payments
- [Resend](https://resend.com/) – emails
- [Vercel](https://vercel.com/) – deployments

### Backend

The backend interacts with Gemini (fiat offramp) and Expedia (hotel provider). It exposes an API for the FE to consume.

- [Go](https://go.dev/doc/install)
- [Postgres](https://www.postgresql.org/) - database


## Work Packages

### Backend
 
~~##### Package 1 (Testing): Improve backend test coverage adding Integration Test and Unit tests. (In Progress)
 
Currently there's partial test coverage however this needs to be improved in order to stabilize the backend.~~

##### Package 2 (Dev Ops): Setup a more robust CI/CD pipeline.

Upon merging the backend runs a simple github action which builds and tests the project. Deployments are done manually.

##### Package 3 (Refactoring): Decouple service and interface. (In Progress)

Skilled Golang dev can possibly help restructure the backend making it more robust and expandable.

~~##### Package 4 (Database): Implement our own typeahead.

We currently use the location search typeahead api of Expedia. However this is not how Expedia intends it. There's a risk of them blocking our endpoints, and thus we need to build our own typeahead. This includes pulling all locations from Expedia's endpoint, storing it in a database and add a performant typeahead.~~


### Front-end

##### Package 1 (Testing): Setup E2E testing using Playwright.

Currently the front-end is quite vulnarable to bugs, due to missing E2E tests and low test coverage. Implement E2E with few implementations as basis.

##### Package 2 (Testing): Add more unit tests.

Currently there's partial test coverage however this needs to be improved in order to cover all FE logic.

##### Package 3 (Refactoring): Extract payment logic into own package. (In Progress)

We want to isolate the Payment logic into its own package. This way we can isolate the test better and at some point make it a plug and play solution.

##### Package 4 (Feature): Work on new features defined in our Trello.

There's many new features to be build. They are defined in are Trello and include things like:
 
 - Add native language translations

### Compensation

- range:  40 - 100 $/hr
- paid in: USDC

<br/>

**contact**
- twitter: @magiclars
- discord: magiclars
- github:  magiclars-off
