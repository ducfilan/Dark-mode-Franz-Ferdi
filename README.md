# Dark mode for Franz services (Facebook Messenger, Slack etc.)

## Installation
1. Copy the `darkmode.css` file to the corresponding `recipe` (service) folder. For example: below's `[service folder]` means `messenger` or `slack` etc.:
  * Mac: `~/Library/Application Support/Franz/recipes/[service folder]`
  * Windows: `%appdata%/Franz/recipes/[service folder]`. Press `Windows`+`R` to open the `Run` dialog and paste this path, for example: `%appdata%/Franz/recipes/messenger`.
  * Linux: `~/.config/Franz/recipes/[service folder]`
2. Reload Franz
3. Open Franz's Settings (`Ctrl`+`,`) > Select `Your services` tab > Select the service that you want to change to dark mode and toggle the `Enable Dark Mode` setting.
4. Reload your service to see changes

## Current supporting services
1. Facebook Messenger
2. Facebook Workplace Chat (Facebook at work)
3. Slack
4. Google Calendar
5. Whatsapp

## References
* [slack-night-mode](https://github.com/laCour/slack-night-mode) by [@laCour](https://github.com/laCour)

---
_P/s: Gmail, Telegram and Skype is natively supported. You can change to dark mode in their settings._
