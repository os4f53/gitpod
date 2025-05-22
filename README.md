# Customized Development Environment for gitpod.io

## Updates
Whenever the Dockerfile or devcontainer.json are updated, it's a good idea to update running devcontainers.
```
gitpod env devcontainer rebuild
```

## Other steps
Check out automations.yaml which can initialize/start things in the devcontainer.
They can be applied with
```
gitpod automations update -s .gitpod/automations.yaml
```

