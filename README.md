# Configs

Configuration files to make setups easier

## Files

### 1. Brewfile

*Install all necessary apps for your new mac in one go.*

You will need:

* Homebrew installed

Run `brew bundle` in the same folder as your *Brewfile* is in.

#### Errors

In case you error out on `zsh: could not find brew command` you will need to
modify your `~/.zshrc` file with

```bash
export PATH=/opt/homebrew/bin:$PATH
```
