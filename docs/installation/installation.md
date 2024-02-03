# Setting up a new Voi Node

## New to Voi

Use this method if you are new to Voi and want to set up a new node.
During the process, you will be asked for a few details to set up your node,
and where we have automated as much as possible.

To set up a new Voi node, run the following command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/VoiNetwork/voi-swarm/main/install.sh)"
```

## Using an Existing Account/Address with Mnemonic

For installing with an existing account or mnemonic to Voi Swarm, use this method.
After installation, [update your name and GUID](../../updating/telemetry/#getting-your-telemetry-status)
for health rewards if setting up on a new server.

To import your account and set up a new Voi node, run the following command:

```bash
export VOINETWORK_IMPORT_ACCOUNT=1
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/VoiNetwork/voi-swarm/main/install.sh)"
```

???+ info
    Post-installation steps for migrating from a D13 based setup can be [found here](../migrating.md)