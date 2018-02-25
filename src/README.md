# ManukaZeny

bitzeny miner (cpuminer wrapper)

# Install

cargo install --git https://github.com/miyagaw61/ManukaZeny

# Usage

### Export Slack Config

```
export RUSGIT_SLACK_URL=[slack-url]
export RUSGIT_SLACK_USERNAME=[slack-username]
```

### Prepare Json File


example:

```
{ "address": ["ABC", "IJK", "XYZ"] }
```

### Execute

manukazeny [json-file]
