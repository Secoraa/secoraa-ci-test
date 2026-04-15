# Secoraa CI/CD Scanner Test

Test repository for the Secoraa API Security Scanner GitHub Action.

## Setup

1. Add secrets in Settings → Secrets → Actions:
   - `SECORAA_API_KEY` — API key from Secoraa platform
   - `SECORAA_PLATFORM_URL` — `https://secoraa-backend.onrender.com`

2. The scan runs on every PR to main, or manually via Actions → Run workflow.
