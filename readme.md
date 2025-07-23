# README

In the root of your project, there is this file:

```bash
#!/bin/bash

# Big Beautiful Help Messaging
#
# This script is responsible for executing the command runner with the appropriate arguments.
#

set -e

PROJECT_SCRIPT_NAME=$(basename "$0") .project/runtime/command-runner "$@"
```