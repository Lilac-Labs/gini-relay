# Third-Party Notices

This project (`gini-relay`) is licensed under the MIT License (see `LICENSE`).

It interoperates with — and in one place contains code derived from — the
third-party components listed below. Each is licensed under the Apache License,
Version 2.0 ("Apache-2.0"). The full text of Apache-2.0 is available at
<https://www.apache.org/licenses/LICENSE-2.0>. Neither upstream project ships a
separate `NOTICE` file, so the attributions reproduced here are taken from each
project's source.

---

## frp — fatedier/frp

- Copyright 2017 fatedier <fatedier@gmail.com>
- License: Apache License, Version 2.0
- Homepage: <https://github.com/fatedier/frp>
- Usage: the `frpc` binary is downloaded at runtime by
  `scripts/postinstall.ts` and supervised by the client. It is not bundled or
  redistributed in this repository.
- Derived code: `src/client/runner/platform.ts` contains a platform-to-release
  mapping derived from frp's Apache-2.0 Bun wrapper for `frpc`. That portion
  remains subject to Apache-2.0 and retains attribution accordingly.

## Caddy — caddyserver/caddy

- Copyright 2015 Matthew Holt and The Caddy Authors
- License: Apache License, Version 2.0
- Homepage: <https://github.com/caddyserver/caddy>
- Usage: run as a stock, unmodified component of the server stack via
  `docker compose` (see `docker-compose.yml` and `Caddyfile`). It is not bundled
  or redistributed in this repository.
