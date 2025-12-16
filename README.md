```sh
sops -d secrets.enc.yaml > secrets.yaml
uv run esphome dashboard .
```
