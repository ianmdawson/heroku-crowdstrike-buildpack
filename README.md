# heroku-crowdstrike-buildpack

This is a Heroku buildpack for installing the CrowdStrike Falcon sensor on a dyno.

## Usage

Add the buildpack to your Heroku app:

```bash
heroku buildpacks:add https://github.com/kielikone/heroku-crowdstrike-buildpack.git
```

Set the following environment variables:

- `CROWDSTRIKE_CLIENT_ID`
- `CROWDSTRIKE_CLIENT_SECRET`
- `CROWDSTRIKE_CID`
- `CROWDSTRIKE_CLIENT_ID`


