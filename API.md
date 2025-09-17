# AAMCORPORATION™ Public API (v1.0.0)

- `/status` → service, version, time, endpoints
- `/manifest` → anchor hashes, supply, timestamp
- `/genesis` → genesis hash, signature, total_supply
- `/pubkey` → node public key (PEM)
- `/fingerprints` → hashes of manifest/genesis/founders

Quick verify:
curl -s https://525926121dc7.ngrok-free.app/status | jq .
curl -s https://525926121dc7.ngrok-free.app/manifest | jq .
curl -s https://525926121dc7.ngrok-free.app/genesis  | jq .
