# Jarvis scheduler

Runs every ~15 minutes on GitHub Actions: wakes the Jarvis Memory service, reads your e-mail replies, and sends the creative
hourly check-in e-mail when it is due. No secrets are stored in this repository; they live in
Settings -> Secrets and variables -> Actions: `JM_URL`, `JM_OWNER_KEY`, `GMAIL_ADDRESS`, `GMAIL_APP_PASSWORD`.
