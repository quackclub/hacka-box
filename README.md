<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/4658208/60469862-2e40bf00-9c2c-11e9-87f7-afe164648de4.png">
  <h3 align="center">hacka-box</h3>
  <p align="center">Update a pinned gist to contain your weekly <s>WakaTime</s> Hackatime stats. (Based off of <a href="https://github.com/matchai/waka-box">waka-box</a>)</p>
</p>

---

## Setup

### Prep work

1. Create a new public GitHub Gist (https://gist.github.com/)
1. Create a token with the `gist` scope and copy it. (https://github.com/settings/tokens/new)
1. Create a Hackatime account (https://hackatime.hackclub.com/signin)
1. In your Hackatime profile settings (https://hackatime.hackclub.com/my/settings/profile), under privacy, ensure `Allow public stats lookup` is checked.
1. In your access settings, copy the existing Hackatime API Key (https://hackatime.hackclub.com/my/settings/access)

### Project setup

1. Fork this repo
2. Go to the repo Settings > Secrets
3. Add the following environment variables:
   - GIST_ID: The ID portion from your gist url: (e.g. **https://gist.github.com/matmanna/<JUST_THIS_PART_THE_GIST_ID>**)
   - GH_TOKEN: The GitHub token generated above.
   - WAKATIME_API_KEY: The API key for your Hackatime account.
   - WAKATIME_API_URL [OPTIONAL]: A wakatime-compatible API URL (defaults to Hackatime!)

