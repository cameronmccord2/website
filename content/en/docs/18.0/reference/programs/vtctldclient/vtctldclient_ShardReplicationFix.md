---
title: ShardReplicationFix
series: vtctldclient
commit: b5b3114ab9371f882762dd66ae0efc5af3a3dbc0
---
## vtctldclient ShardReplicationFix

Walks through a ShardReplication object and fixes the first error encountered.

```
vtctldclient ShardReplicationFix <cell> <keyspace/shard>
```

### Options

```
  -h, --help   help for ShardReplicationFix
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

