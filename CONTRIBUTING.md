# Contributing

Bug reports and examples of wrong or unclear verdicts are welcome. For behavior
changes, [open an issue](https://github.com/ravsau/wrap/issues) first with the
session state, the verdict you got, and the verdict you expected. Strip private
transcripts and secrets from examples.

Design rules to preserve:

- Review only the current conversation.
- One verdict: STOP or CONTINUE.
- Never scan other sessions or turn this into backlog management.

Validate before a PR:

```bash
claude plugin validate . --strict
claude plugin validate ./plugins/wrap --strict
```

Contributions are MIT-licensed.
