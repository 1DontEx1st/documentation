---
id: logs
title: Logs
---

Like any other integration this logs to the `home-assistant.log` file.

To enable `debug` logging, add this to your `configuration.yaml`:

```yaml
logger:
  default: info
  logs:
    hacs: debug
```
