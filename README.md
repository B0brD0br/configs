# Configs

Configuration files to make setups easier

## Files

### 1. Brewfile

*Install all necessary apps for your new mac in one go.*

You will need:

* Homebrew installed

Run `brew bundle` in the same folder as your *Brewfile* is in.

#### Apps

1. Development

    * VSCode
    * Firefox / Brave
    * Postman
    * Font Victor Mono
    * Warp
    * PGAdmin
    * Docker
    * GitUp

2. Utils
    * BetterTouchTools
    * BetterSnapTools
    * Bear
    * Coconut Battery
    * AlDente
    * Anydesk
    * KAP
    * 1Password
    * DaisyDisk
    * Rocket

3. Social

    * Slack
    * WhatsApp
    * Telegram

4. Media

    * Spotify
    * VLC
    * Steam

#### Errors

In case you error out on `zsh: could not find brew command` you will need to
modify your `~/.zshrc` file with

```bash
export PATH=/opt/homebrew/bin:$PATH
```
