# Domino apt repository

Ubuntu 22.04+ / amd64 and arm64.

```sh
curl -fsSL https://raw.githubusercontent.com/KJaebye/domino-apt/main/domino.sources | sudo tee /etc/apt/sources.list.d/domino.sources >/dev/null
sudo apt update
sudo apt install domino-proxy
```

Signing key fingerprint: `8704BE99B201383E16246ED9099855D35D066EE8`

Packages install the CLI only. Configuration and services remain user-managed.
