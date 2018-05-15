---
description: Worked fine in development. Oops! problem now...
---

# Deploy

The deploy command lets you deploy your amber project in a Heroku like fashion. This works as proof of concept but isn't currently very configurable. In most cases Amber is super easy to deploy via multiple methods Docker, Chef, Capistrano, or manual git checkout and compile.

### `amber deploy`

```text
amber deploy [OPTIONS] [SERVER_SUFFIX]

Arguments:
  SERVER_SUFFIX  # Name of server.
                 (default: production)

Options:
  -b, --branch   # Branch to use. Default master.
                 (default: master)
  --init
  -k, --key      # API Key for service
  --no-color     # Disable colored output
  -s, --service  # Deploy to cloud service: digitalocean | heroku | aws | azure
                 (default: digitalocean)
  -t, --tag      # Tag to use. Overrides branch.
```

## Example Usage

* [See deploy example video](https://www.youtube.com/watch?v=EhOPNKNjdBw)
