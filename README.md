# Windmill Airgapped Resource Types

This repository's purpose is to allow instances without internet connection to
setup resource types

## Quickstart

After cloning this repository

1. Download the wmill CLI
2. add the admins workspace

```
deno install --unstable -A https://deno.land/x/wmill/main.ts
wmill workspace add
^ fill the details to add your instance admins workspace
wmill sync push --raw
```
