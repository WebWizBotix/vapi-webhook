# Vapi Webhook for Render

This repository receives a webhook from Vapi, forwards it to Make (Integromat),
and returns valid JSON so Vapi does not throw an "invalid JSON" error.

## Setup

1. Deploy this repository to Render as a **Web Service**.
2. Set an environment variable:

