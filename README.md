# ValeraGin/ocbar

Homebrew tap for [ocbar](https://github.com/ValeraGin/ocbar) — an
AnyConnect-compatible VPN client for macOS built on OpenConnect: SAML
single sign-on with autofill and TOTP, split DNS, split tunneling, a
reconnecting supervisor and a menu bar app.

```bash
brew tap ValeraGin/ocbar
brew trust ValeraGin/ocbar     # third-party tap: Homebrew refuses untrusted formulae
brew install ocbar
sudo ocbar install             # once: privileged helper, sudoers rule, LaunchAgent
ocbar app start
```

Updates: `brew upgrade ocbar`, then `ocbar app stop && ocbar app start`.
Uninstall: `sudo ocbar uninstall`, then `brew uninstall ocbar`.

The formula builds from source on your machine (macOS 13+, Command Line
Tools). There is no Apple Developer ID; a locally built app is not
quarantined, so Gatekeeper does not block it.

---

Homebrew tap для ocbar — клиента OpenConnect для macOS. Установка — команды
выше; подробности по-русски — [README.ru.md](https://github.com/ValeraGin/ocbar/blob/main/README.ru.md).
