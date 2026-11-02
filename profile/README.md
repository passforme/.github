<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://passforme.com/brand/logo/logo-gold-on-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://passforme.com/brand/logo/logo-brass-on-light.svg">
    <img src="https://passforme.com/brand/logo/logo-gold.svg" alt="passforme" width="440">
  </picture>
  <br>
  <strong>A password vault only you can open.</strong>
  <br>
  <sub>Terminal first &middot; synced by a server you run &middot; the server sees only ciphertext</sub>
</p>

passforme keeps logins, 2FA codes, recovery codes, cards, bank accounts,
API keys, SSH keys and Wi-Fi passwords in a vault encrypted on your own
device. Opening it takes your master password **and** a Secret Key that
never leaves your devices, so a copy stolen from the server, or from a
backup, cannot be guessed open. Sync, if you want it, goes through a
small server you run yourself, which stores ciphertext and nothing else.
Linux, open source under the AGPL-3.0.

```sh
curl -fsSL https://raw.githubusercontent.com/passforme/passforme/main/install.sh | sh
```

| | |
|---|---|
| [**passforme/passforme**](https://github.com/passforme/passforme) | The code, in Rust: the CLI, the vault format and cryptography, the sync server. Releases, the Docker image, how it works and why. |
| [**passforme/website**](https://github.com/passforme/website) | [passforme.com](https://passforme.com): the home page, the [command guide](https://passforme.com/guide) with every command and a tried example, and the [brand kit](https://passforme.com/brand). |

Also on [crates.io](https://crates.io/crates/passforme) (`cargo install passforme`)
and as [`ghcr.io/passforme/passforme-server`](https://github.com/passforme/passforme/pkgs/container/passforme-server).
Found a security problem? Write to **security@passforme.com**, not to an
issue: see the [security policy](https://github.com/passforme/passforme/security/policy).
