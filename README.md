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
    * [VSCode](https://code.visualstudio.com/)
    * [Windsurf](https://windsurf.com/)
    * [Docker](https://www.docker.com/)
    * [GitUp](https://gitup.co/)
    * [PGAdmin](https://www.pgadmin.org/)
    * [Warp](https://www.warp.dev/)
    * [Postman](https://www.postman.com/)
    * [Stripe CLI](https://stripe.com/docs/stripe-cli)

2. Browsers
    * [Brave](https://brave.com/)
    * [Firefox](https://www.mozilla.org/en-US/firefox/developer/)
    * [Microsoft Edge](https://www.microsoft.com/en-us/edge)

3. Utils
    * [KAP](https://getkap.co/)
    * [DaisyDisk](https://daisydiskapp.com/)
    * [Coconut Battery](https://coconut-flavour.com/battery)
    * [BetterTouchTools](https://folivora.ai/)
    * [BetterSnapTools](https://folivora.ai/bettersnaptool)
    * [AlDente](https://apphousekitchen.com/aldente/)

4. Social
    * [Slack](https://slack.com/)
    * [WhatsApp](https://www.whatsapp.com/)
    * [Telegram](https://telegram.org/)

5. Media
    * [VLC](https://www.videolan.org/vlc/)
    * [Steam](https://store.steampowered.com/)

6. Fonts
    * [Victor Mono](https://fonts.google.com/specimen/Victor+Mono)

7. Misc
    * [Rocket](https://matthewpalmer.net/rocket/)
    * [Anydesk](https://anydesk.com/)
    * [1Password](https://1password.com/)
    * [Adobe Acrobat Reader](https://get.adobe.com/reader/)
    * [Transmission](https://transmissionbt.com/)
    * [Bear](https://bear.app/)

#### Errors

In case you error out on `zsh: could not find brew command` you will need to
modify your `~/.zshrc` file with

```bash
export PATH=/opt/homebrew/bin:$PATH
```
