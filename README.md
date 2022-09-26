# Yente on Render

Pieces for [self-hosting](https://www.opensanctions.org/docs/self-hosted/) [Open Sanctions'](https://opensanctions.org) Yente application on Render. Includes a [`render.yaml` blueprint](https://render.com/docs/infrastructure-as-code) to use as the description of your services.

The Yente service is set to be a [Private Service](https://render.com/docs/private-services), so is only accessible within **your** private Yente network by services **in the same region**.

## Usage

1. Fork this repo (there may be changes to this repo that you do not want automatically synced)
2. In your Render account visit the "Blueprints" page
3. Add a new blueprint instance and connect it to the forked repo

Render will create the services and Yente will begin importing data. The Yente endpoints may take a few minutes to become available.

## Important

This requires a [bulk data license](https://www.opensanctions.org/licensing/) from Open Sanctions.

The steps above will incur charges to your Render account.

The approach put forward in this repo is an example of how to get this running, but is not necessarily the best approach. Use at your own risk.