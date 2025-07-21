# maestro-ui

# Start an DEFAULT iOS or Android emulator using Maestro

maestro start-device --platform android
maestro start-device --platform ios

## Start with a SPECIFIC OS for Android or iOS simulator using Maestro

maestro start-device --platform ios --os-version 17
maestro start-device --platform android --os-version 33

## Run test (.yaml) file

maestro test android-flow.yaml

## To generate a report

maestro test --format junit myFolderWithTests
maestro test --format html myFolderWithTests

## To record your flow execution

maestro record <YourFlow.yaml> -- local