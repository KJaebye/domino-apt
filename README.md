# Domino apt repository

Ubuntu 22.04+ / amd64 and arm64.

```sh
curl -fsSL https://downloads.oetree.cc/domino/domino.sources | sudo tee /etc/apt/sources.list.d/domino.sources >/dev/null
sudo apt update
sudo apt install domino-proxy
```

Signing key fingerprint: `61ADCFADCDBE96102419F2797501FC6C688FCF00`

Packages install the CLI only. Configuration and services remain user-managed.
