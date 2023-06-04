# Steps
## 1. Download venom binary for your OS
```bash
// macos m processors
curl -L  https://github.com/ovh/venom/releases/download/v1.1.0/venom.darwin-arm64 --output venom && chmod +x venom
```

## 2. Create a test fil, examples included: `tests.yaml`, `tests-activity.yaml`

## 3. Run the test
```bash
./venom run
```


# Endpoints tested
- https://api.rarible.org/v0.1/doc#tag/currency-controller 
  - https://api.rarible.org/v0.1/currencies/all 
  - https://api.rarible.org/v0.1/currencies/ETHEREUM:0x0000000000000000000000000000000000000000/rates/usd?at=2022-01-01T12:00:00Z
- https://api.rarible.org/v0.1/doc#tag/activity-controller/operation/getActivitiesByUsers
  - https://api.rarible.org/v0.1/activities/byUsers
-   https://api.rarible.org/v0.1/doc#tag/collection-controller/operation/getCollectionById
  - https://api.rarible.org/v0.1/collections/ETHEREUM:0xb66a603f4cfe17e3d27b87a8bfcad319856518b8