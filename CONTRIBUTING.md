# Contributing to ZenLock

Thank you for your help. Bug reports and ideas are the most useful help.

## Report a bug or suggest an idea

1. Open [a new issue](https://github.com/dheekshithsnewjourney-crypto/zenlock/issues/new/choose).
2. Choose "Bug report" or "Idea".
3. Fill in the form. Do not paste private data; issues are public.

For a security problem, follow [SECURITY.md](./SECURITY.md) instead.

## Change the code

1. Fork the repository and make a branch from `main`.
2. Set it up:
   ```bash
   Open the folder in Android Studio and let Gradle sync
   ```
3. Make your change. Keep it small and about one thing.
4. Run the checks:
   ```bash
   ./gradlew assembleDebug
   ```
5. Open a pull request and fill in the template.

## Rules for every change

- Every promise on the website and in the README must be true in the product.
- Do not weaken or skip a test to make it pass.
- Never put secrets in code or in git history.
- A change must never trap a user with no way out after the timer ends. Test a full session, a reboot during a session, and the end of the timer.

## Code of conduct

Everyone who takes part follows the [code of conduct](./CODE_OF_CONDUCT.md).
