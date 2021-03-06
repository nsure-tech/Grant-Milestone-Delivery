# Evaluation

- **Status:** Accepted
- **Application Document:**  [clickme](https://github.com/w3f/Open-Grants-Program/blob/master/applications/stable-asset.md)
- **Milestone:** 1
- **Kusama Identity:** [ESxS4A7GHMLzve4Mbc9t27RpXtVTnV3LtcMTtcnD26jcUHA](https://polkascan.io/pre/kusama/account/ESxS4A7GHMLzve4Mbc9t27RpXtVTnV3LtcMTtcnD26jcUHA)
- **Previously successfully merged evaluation:** All by semuelle

| Number | Deliverable | Accepted | Link | Evaluation Notes |
| ------ | ----------- | :------: | ---- |----------------- |
| 0. | Apache License 2.0 | <ul><li>[x] </li></ul> | [gh](https://github.com/nutsfinance/stable-asset/blob/c441c511bb4b403fe54346a58f66d52947c78d1b/LICENSE) | — |
| 1 | Documentation | <ul><li>[x] </li></ul> | [setup + testing](https://github.com/nutsfinance/stable-asset/blob/c441c511bb4b403fe54346a58f66d52947c78d1b/README.md), [client + API](https://github.com/nutsfinance/stable-asset/blob/c441c511bb4b403fe54346a58f66d52947c78d1b/client/README.md), [algorithm](https://docs.acoconut.fi/asset/acbtc/algorithm) | — |
| 2 | Substrate module: Stable Swap Substrate module | <ul><li>[x] </li></ul> | [gh](https://github.com/nutsfinance/stable-asset/blob/c441c511bb4b403fe54346a58f66d52947c78d1b/pallets/stable-asset/src/lib.rs#L571) | — |
| 3 | Testing | <ul><li>[x] </li></ul> | [gh](https://github.com/nutsfinance/stable-asset/blob/c441c511bb4b403fe54346a58f66d52947c78d1b/pallets/stable-asset/src/tests.rs) | Including automated test client and coverage report |  
| 4 | Docker | <ul><li>[x] </li></ul> | [gh](https://github.com/nutsfinance/stable-asset/blob/c441c511bb4b403fe54346a58f66d52947c78d1b/Dockerfile) | — |


## General Notes

89% test coverage on pallet. Very handy test client script. No inline documentation.
