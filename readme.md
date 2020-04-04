## Please note that this repo is now deprecated as of SDK37 release. Though the code here should still work, it is recommended to update to more modern versions of relevant libraries. Automated security PR's will still be merged, but this repo may disappear without notice.

# Expo SDK33 MobX Boilerplate

## How to start

1. Open the root directory of the project after cloning the repo
2. `yarn`
3. `expo start`
4. Open the expo mobile app and select the running project

## Notes

This is based on the `expo init` tab template but with MobX added for state management. The home screen has been modified to allow changing of 2 state variables to give you an idea of how it works.

The state store can be found in `stores/Application.State.Mobx.js`.

It also includes `mobx-persist` to allow state to be saved to `asyncStorage`.
