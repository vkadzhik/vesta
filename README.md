# Vesta — live prototype

Working prototype of the money-transfer flow for **Vesta**, a mobile banking app concept.

Designed by Kadzhik Vardanyan · Figma + Higgsfield AI.

Live: https://vkadzhik.github.io/vesta/

## What it covers

- Happy path: Home → recipient → amount → confirm with Face ID → receipt → balance updates
- Edge states: no search results (pay by card / invite), not enough money, $3,000 daily limit, Face ID failure with passcode fallback, no connection with retry, declined transfer, inter-bank transfer in processing
- The side panel can simulate Face ID failure, going offline and a bank decline
- Analytics events from the tracking plan are logged live in the side panel (no data leaves the page)

Demo data only, no real payments.
