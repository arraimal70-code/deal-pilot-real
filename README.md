# Deal Pilot Rewards

Deal Pilot Rewards is an Android prototype exploring affiliate deal sharing, reward tracking, purchase-proof review, and payout workflow design.

## Status: Prototype / Demo Only

This repository is published as a learning and portfolio project. It does **not** process real affiliate commissions, real payments, or real payouts. Do not enter real UPI, banking, or personal information into the current build.

## Current Features

- Deal discovery and browsing interface
- Affiliate-link generation simulation
- Reward wallet and purchase-proof submission workflow
- Admin, employee, and CEO dashboard simulations
- Local persistence using Room Database

## Tech Stack

- Kotlin
- Jetpack Compose
- Room Database
- Android Studio / Gradle

## Known Limitations

- Authentication and role access are demo-only and not production secure.
- No production backend or verified merchant affiliate conversion system is connected.
- Financial/payout screens are prototype flows only.
- Before any real-world deployment, the app requires secure authentication, server-side authorization, encrypted handling of sensitive data, fraud controls, consent and privacy safeguards.

## Why I Built It

I built Deal Pilot to understand how a deal-sharing and reward workflow could function, including the product, wallet, review, and operations sides of the system. The next step is to convert the prototype into a smaller, safer, measurable product for local retail use.

## Portfolio Direction

The stronger real-world direction for this project is a digital catalogue and enquiry-tracking platform for small local retailers, validated with actual users and measurable outcomes rather than simulated cashback operations.

## Run Locally

1. Open this project in Android Studio.
2. Let Gradle sync the project dependencies.
3. Create a local `.env` file only if required for future API integrations; never commit secret keys.
4. Run on an Android emulator or test device.

## Public Repository Hygiene

The repository intentionally excludes APK builds, keystores, secrets, and real-user data.

## Built By

Arnav Raimal
