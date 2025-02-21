# Expo Go Build Failure with Native Module on Physical Device

This repository demonstrates a bug encountered when using a specific native module within an Expo project and running it on a physical device using Expo Go. The error only manifests on physical devices and provides limited debugging information.

## Bug Description

The project uses a native module (details below) which functions correctly during development but fails to build when deployed to a physical device via Expo Go. The error message is not very descriptive, making it difficult to pinpoint the exact cause.

## How to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Attempt to run the project on a physical device using `expo start` and selecting the physical device in Expo Go.

## Solution

The solution is described in `bugSolution.js`, which demonstrates a workaround that addresses the issue.