# TCB DCM Presets

## How to use a preset

Take these steps to enable a preset:

1. Install this package as a dev dependency:

   ```terminal
   dart pub add --dev tcb_dcm_presets
   ```

   or:

   ```terminal
   flutter pub add --dev tcb_dcm_presets
   ```

2. For DCM configuration add the `extents` entry:

   ```yaml
   dart_code_metrics:
     extends:
       - package:tcb_dcm_presets/presets/tcb_main.yaml
   ```

[DCM configuration](https://dartcodemetrics.dev/docs/getting-started/configuration).
