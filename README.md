# Bpool Liquidity Provision
Extract insights on bpool liquidity providers for ocean marketplace data assets

## Setup
You need to install `web3.py` if not already installed. The easiest way is through pip:

`pip install web3`

Most likely you will get an error when importing if you don't have the compatible version of `jsonschema`. You can install this via pip to and make sure you restart the notebook kernel:

`pip install --force-reinstall jsonschema==3.2.0`

## Input data
In the data folder there is the input transactions data downloaded from etherscan.io. If in the future you want to run this for a different pool you'll need to download this via the `Export transactions` button on the main page of the pool on etherscan.io.
