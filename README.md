To reproduce the bug in serverleses-esbuild:

First ensure you are using the following versions:
- Yarn version: 3.3.1
- Serverless Framework Version: 3.27.0
- Serverless Plugin: 6.2.3
- Serverless SDK: 4.3.2
- Node: 18.13.0
- OS: Mac

1. Clone the repo
2. `yarn` to install dependencies
3. `yarn start`
4. Notice the error and the fact that offline mode does not start up.

```
Error: Command failed with exit code 1: yarn install --frozen-lockfile --non-interactive
➤ YN0050: The --non-interactive option is deprecated
```