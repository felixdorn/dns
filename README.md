# DNS

This repository holds the octoDNS configuration for Forevue and related services.

## Get up & running
```bash
cp .env.example .env
# Edit the .env and your email & token
source .env

python -m venv env
source env/bin/activate
pip install -r requirements.txt

octodns-sync --config-file=config.yaml # add --doit to well, do it
```