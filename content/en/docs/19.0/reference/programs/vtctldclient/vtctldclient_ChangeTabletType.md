---
title: ChangeTabletType
series: vtctldclient
commit: 0f751fbb7c64ca5280c5d4f58d038e1df5477c67
---
## vtctldclient ChangeTabletType

Changes the db type for the specified tablet, if possible.

### Synopsis

Changes the db type for the specified tablet, if possible.

This command is used primarily to arrange replicas, and it will not convert a primary.
NOTE: This command automatically updates the serving graph.

```
vtctldclient ChangeTabletType [--dry-run] <alias> <tablet-type>
```

### Options

```
  -d, --dry-run   Shows the proposed change without actually executing it.
  -h, --help      help for ChangeTabletType
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.
