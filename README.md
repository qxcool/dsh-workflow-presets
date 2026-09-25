# dsh-workflow-presets

DeepSeek Harness plugin bundle: workflow-style agent presets (Claude Code, Codex, and
friends) declared as `dsh-agent-preset` bundle lines so they can be installed into any
DSH profile like a normal plugin.

## Install

```bash
dsh plugin --profile web add git+https://github.com/qxcool/dsh-workflow-presets.git#v1.0.0
```

The bundle ships its own `cordis.patch.yml` with all preset declaration rows.
Edit presets by changing the patch and running `plugin_manager install_bundle` again.
