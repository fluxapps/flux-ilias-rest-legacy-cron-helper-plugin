# flux-ilias-rest-legacy-cron-helper-plugin

ILIAS Rest Legacy Cron Plugin Helper

Only needed for ILIAS < 8

## Installation

In [flux-ilias](https://github.com/flux-caps/flux-ilias)

```dockerfile
COPY --from=docker-registry.fluxpublisher.ch/flux-ilias-api/rest-legacy-cron-helper-plugin:latest /flux-ilias-rest-legacy-cron-helper-plugin $ILIAS_WEB_DIR/Customizing/global/plugins/Services/Cron/CronHook/flux_ilias_rest_leg_cron_helper_plugin
```

### Helper Plugin

You need to install [flux-ilias-rest-helper-plugin](https://github.com/flux-caps/flux-ilias-rest-helper-plugin) too
