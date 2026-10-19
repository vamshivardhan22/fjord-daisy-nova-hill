# Loan Against Property Voice Qualification Demo

A web-based demonstration for a Loan Against Property (LAP) qualification workflow. The application models a guided customer conversation, collects qualification details, and tracks whether a case can proceed, should be transferred, or must stop based on the configured rules.

## Features

- Guided qualification conversation for LAP enquiries.
- Capture of property type, ownership, original documents, requested loan amount, occupation and income mode, estimated property value, and requested tenure.
- Handling for cases that fall outside the configured eligibility rules.
- Loan-amount cap flow that offers the supported limit and continues only when accepted.
- Call-flow state management and customer response parsing.
- TypeScript implementation with automated tests for the qualification engine.

## Tech stack

- TypeScript
- React
- TanStack Start / Router
- Vite
- Zod
- Vitest (tests)

## Getting started

Requirements: Node.js and npm.

```bash
git clone https://github.com/vamshivardhan22/fjord-daisy-nova-hill.git
cd fjord-daisy-nova-hill
npm install
npm run dev
```

Use the local URL printed by the development server.

## Verification

The repository defines scripts for automated tests, TypeScript checks, and a production build.

```bash
npm test
npm run typecheck
npm run build
```

The build command also runs the database migration script. Configure the required environment and database settings for the intended run mode before building.
## Important notes

This is a demonstration of a qualification flow, not a lending decision engine. Rules and wording should be confirmed against the applicable business policy before use with real customers. Do not enter real customer or financial data into an unapproved demo environment.

## Related project

The related full interface and submission workspace is available in [lilac-sage-lunar-wave](https://github.com/vamshivardhan22/lilac-sage-lunar-wave). A focused qualification-engine repository is available at [home-credit-lap-qualify-desk](https://github.com/vamshivardhan22/home-credit-lap-qualify-desk).

## Skills demonstrated

TypeScript, React, state-based conversation flows, business rule implementation, form handling, automated testing, and responsive web application development.
