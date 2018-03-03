# ManukaZeny

bitzeny miner (cpuminer wrapper)

Details(Qiita): https://qiita.com/miyagaw61/items/f1a0aa265d3e41661914#%E8%B2%A2%E7%8C%AE

# Install

```
cargo install --git https://github.com/miyagaw61/ManukaZeny
```

# Usage

### Prepare Miner

https://github.com/macchky/cpuminer

```
export PATH=$PATH:/path/to/cpuminer
```

### Export Slack Config

```
export RUSGIT_SLACK_URL=[slack-url]
export RUSGIT_SLACK_CHANNEL=[slack-channel]
```

### Prepare Json File


example:

```
{ "addresses": ["ABC", "IJK", "XYZ"] }
```

### Execute

```
manukazeny [json-file]
```
