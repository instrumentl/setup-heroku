This is a small GitHub action that runs the Heroku installer to set up the `heroku` CLI, which is no longer available on ubuntu-24.04.

```yaml
- uses: instrumentl/setup-heroku@v1
  with:
    # Pass "latest" here to use whatever heroku has made the default; otherwise, you
    # can pass a specific version (e.g., '9.5.1') which must exactly match a version
    # string in the undocumented heroku-cli manifest
    version: 'latest'
```
