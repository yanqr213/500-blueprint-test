# SunEnergyXT 500 Blueprint Test

This repository contains a test-only Home Assistant blueprint for validating the SunEnergyXT 500 Home Assistant integration and entity mapping.

It is intentionally separate from the production blueprint repository so plugin tests can import and iterate on this blueprint without replacing the production blueprint.

## Import URLs

Raw:

```text
https://raw.githubusercontent.com/yanqr213/500-blueprint-test/main/blueprints/automation/sunenergyxt/sunenergyxt_plugin_test_zero_feed_in.yaml
```

CDN:

```text
https://cdn.jsdelivr.net/gh/yanqr213/500-blueprint-test@main/blueprints/automation/sunenergyxt/sunenergyxt_plugin_test_zero_feed_in.yaml
```

## Notes

- Blueprint name: `SunEnergyXT 500 Series - Plugin Test Zero Feed-in`
- The control logic is copied from the current meter-type setup blueprint in `yanqr213/500-blueprint`.
- The SunEnergyXT device selector still expects the Home Assistant integration domain `sunenergyxt`, so it is compatible with the plugin repo that keeps `domain: sunenergyxt`.
