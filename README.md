# cloud-migrator
## Concept
automatically deploy to a cloud platform when your selfhosted website goes down

- website needs to be dockerized
- some kind of healthcheck needs to be done so that it knows when the site is down and needs migrating
- the real problem is knowing when the selfhosted node is back online
    - this could be done with some sort of healthcheck locally that then removes the cloud version
- another problem will be dns conflicts
  - some kind of mechanism needs to be made to automatically switch the dns to the cloud and visa versa. could be done with a cloudflare API????
