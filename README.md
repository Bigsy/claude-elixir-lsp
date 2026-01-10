# Elixir LSP Plugin for Claude Code

Adds Elixir Language Server Protocol support to Claude Code.

## Prerequisites

Install elixir-ls via Homebrew:

```bash
brew install elixir-ls
```
Make sure you can run `elixir-ls` from the cmdln and it starts without error (you dont need to keep it running just test it runs)
(Requires Elixir/Erlang - install with `brew install elixir` if needed)

## Installation

```bash
# Add the marketplace
/plugin marketplace add Bigsy/claude-elixir-lsp

# Install the plugin
/plugin install elixir-lsp
```

Or via CLI:

```bash
claude plugin marketplace add Bigsy/claude-elixir-lsp
claude plugin install elixir-lsp
```

## Supported File Extensions

- `.ex` - Elixir
- `.exs` - Elixir scripts
- `.heex` - Phoenix HEEx templates
- `.eex` - EEx templates
- `.leex` - LiveView EEx templates
