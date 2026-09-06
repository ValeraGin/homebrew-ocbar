# ValeraGin/ocbar

Homebrew tap для [ocbar](https://github.com/ValeraGin/ocbar) — клиента
Cisco AnyConnect (OpenConnect) для macOS с SSO через WKWebView, split DNS,
split tunneling, супервизором и меню в строке состояния.

```bash
brew tap ValeraGin/ocbar
brew install --HEAD ocbar
sudo ocbar install        # один раз: привилегированный хелпер, sudoers, агент
```

`brew upgrade ocbar` — это и есть автообновление.

Формула собирает программу из исходников на вашей машине. Так сделано
намеренно: у проекта нет Apple Developer ID, а собранное локально не
получает карантина, поэтому Gatekeeper не мешает запуску.

Требуется macOS 13+ и Command Line Tools (полный Xcode не нужен).
