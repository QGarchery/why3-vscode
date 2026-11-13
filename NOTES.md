# Publishing

Bump `version` in `package.json` and push.

Run the Publish workflow from the Actions tab.
It starts only through `workflow_dispatch` and publishes that version to the Marketplace.

Open VSX, from the repository root:

```
npx ovsx publish -p <token>
```
