---
title: Summon
---

# The entry host Summon

The very first connection to any DELab resource should be made to `summon`:

  `ssh USERNAME@summon.delab.i.hpi.de`

It is a good starting point for looking around, checking that login works, storage is available and so forth.

**`summon` can always be used without a reservation.**

`summon` can also be used to connect to other [DELab machines](/docs/resources) 
with `pdsh` or use `tmux`/`screen` for longer-running sessions.

(In the future, this will be the host to use when submitting SLURM-jobs)

## The sibling host Conjure

A very similar host to `summon` is `conjure`. It is virtually identical but 
has access to the BMC network of the lab. Access is only possible with special 
permissions.
