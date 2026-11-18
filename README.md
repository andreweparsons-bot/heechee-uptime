# heechee-uptime

A scheduled GitHub Actions check (every 15 minutes) on the Heechee services and web apps. The addresses are kept in the `UPTIME_URLS` repository secret, one per line. A failed run means a service is down, and GitHub emails the owner.
