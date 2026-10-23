# Emit Homebrew tap

Homebrew formula for [Emit](https://github.com/bwbensonjr/emit), a Scheme compiler with a JIT
REPL and standalone native executables. Apple Silicon macOS; built from source against `llvm@22`
and `bdw-gc`.

```sh
brew install bwbensonjr/emit/emit
emit --version
emit doctor
```

`Formula/emit.rb` is rendered in bwbensonjr/emit from `packaging/homebrew/emit.rb.in` and a
published release's identity, and arrives here as a pull request only after that release passed
the channel acceptance checks (see the Emit repository's `docs/RELEASE-PIPELINE.md`). Change the
template there rather than editing the formula here; `brew test-bot` checks each pull request.
