# Kiyesi

Kiyesi checks the health and security of your Linux servers and tells you, in plain words, what to fix and how.

- **One command to start:** `curl -fsSL https://get.kiyesi.dev | sh`, then `sudo kiyesi scan`. A scan sends nothing anywhere until you connect the server.
- **Read-only:** the agent never changes a file, a setting or a container, opens no port, and masks passwords and tokens before anything leaves the server.
- **The code that runs on your machines is public:** [Kiyesi/agent](https://github.com/Kiyesi/agent), the agent, the command line and the browser snippet, copied there with each release.
- **On a Mac:** `brew install kiyesi/tap/kiyesi`.

[Website](https://kiyesi.dev) · [Docs](https://docs.kiyesi.dev) · [Security](https://docs.kiyesi.dev/security/report-a-flaw/) · security@kiyesi.dev
