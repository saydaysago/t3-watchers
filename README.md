# t3-watchers

Scheduled GitHub Actions that wake a T3 Code thread through a signed T3 Connect webhook, once, when something happens. No model runs until the event.

| Workflow | Watches | Secrets |
|---|---|---|
| `watch-t3-discussion-42374.yml` | Maintainer reply on pingdotgg/t3code discussion #42374 | `T3_WATCH_HMAC`, `T3_WATCH_WEBHOOK_URL` (canonical copy: Infisical `/t3-watchers`) |
