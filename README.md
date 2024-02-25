## Import your Monarch Money account data into ProjectionLab
Updates your [ProjectionLab](https://projectionlab.com/) account balances with the latest data from [Monarch Money](https://monarchmoney.com).

### How it Works
1. **Connects to APIs**: The Browser extension communicates with both Monarch Money and ProjectionLab's Plugin API.
2. **Fetches Monarch Data**: Your Monarch Money account balances are directly downloaded to your machine.
3. **Updates ProjectionLab**: The Browser extension updates your ProjectionLab account information using the `updateAccount()` [Plugin API](https://app.projectionlab.com/docs/module-PluginAPI.html#.updateAccount).

#### Prerequisites:
- Your Monarch Money account credentials (email and password - and MFA Code if enabled)
- ProjectionLab with Plugin API access enabled (see instructions below)

### How to Use
1. **Install the Extension**: Install the Monarch Money to ProjectionLab extension from the Chrome Web Store.
2. 