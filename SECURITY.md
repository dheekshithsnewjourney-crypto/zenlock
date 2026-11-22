# Security policy

## Report a problem in private

If you find a security problem in ZenLock, do not open a public issue.

1. Open the [private report form](https://github.com/dheekshithsnewjourney-crypto/zenlock/security/advisories/new).
2. Describe the problem and the steps to see it.
3. Send the report.

You will get an answer within 7 days. When the fix is live, the report can be made public, with credit to you if you want it.

## What is in scope

- The ZenLock Android app (`com.dheekshith.zenlock`)
- The code in this repository

## Supported versions

Only the live version, built from `main`, gets fixes.

## How the app handles your data

- ZenLock has no account, no server and no internet code. Settings stay on the phone, in device-protected storage.
- It reads which app is in front (Usage Access) and, if you allow it, notification counts. It sends neither anywhere.
- Device owner is a strong role. Read "Before you install" in the README.
