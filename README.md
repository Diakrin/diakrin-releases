# Diakrin releases

Signed release files for installing Diakrin in your own cloud account with the [Diakrin CLI](https://github.com/Diakrin/diakrin-cli):

```sh
curl -fsSL https://diakrin.com/cli/install.sh | sh
diakrin init
diakrin self-hosted versions
```

Each release holds a signed `release.json` and the infrastructure bundle it pins. The CLI verifies the signature against Diakrin's pinned key before using anything here, so this repository does not need to be trusted. Nothing is built or edited by hand in this repository; the files are published by Diakrin's release workflow.
