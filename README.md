# Domino apt repository

Ubuntu 22.04+ / amd64 and arm64.

```sh
curl -fsSL https://raw.githubusercontent.com/KJaebye/domino-apt/main/domino.sources | sudo tee /etc/apt/sources.list.d/domino.sources >/dev/null
sudo apt update
sudo apt install domino-proxy
```

Signing key fingerprint: `61ADCFADCDBE96102419F2797501FC6C688FCF00`

Packages install the CLI only. Configuration and services remain user-managed.


## Signing key replacement

The previous signing passphrase is unavailable. This replacement is not authenticated by the old key. Existing users must explicitly install the updated source configuration over HTTPS before updating.

Previous fingerprint: `8704BE99B201383E16246ED9099855D35D066EE8`

Current fingerprint: `61ADCFADCDBE96102419F2797501FC6C688FCF00`

```sh
curl -fsSL https://raw.githubusercontent.com/KJaebye/domino-apt/main/domino.sources | sudo tee /etc/apt/sources.list.d/domino.sources >/dev/null
sudo apt update
```

No software packages were rebuilt or replaced.
