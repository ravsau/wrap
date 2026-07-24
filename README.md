# wrap

Ask any Claude Code session one question before you close it: safe to stop, or
is something still unfinished?

`/wrap` reviews only the current conversation and answers:

- `STOP` — safe to close, with any loose threads listed so you don't lose them
- `CONTINUE` — something here is still worth finishing now

It does not scan your backlog, other sessions, or invent more work.

## Install

```bash
git clone https://github.com/ravsau/wrap.git
cd wrap
./install.sh
```

Then run `/wrap` in any session. Start a new session if the command does not
appear immediately.

## Install from the plugin marketplace

```text
/plugin marketplace add ravsau/wrap
/plugin install wrap@saurav-claude-tools
/reload-plugins
```

Then run `/wrap:wrap` (plugins are namespaced; the installer above
gives you the bare `/wrap`).

## License

MIT
