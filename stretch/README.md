# Cassandra stretch cluster 
Stretching Cassandra across kubernetes clusters

NOTE:
This is not a standard configuration, and may be an anti-pattern. This document is being written for a specific requirement/ architectural constraint.

## Install Cassandra in stretch mode

```
1. Run cassandra on host network
2. Set CASSANDRA_SEEDS to a list of endpoints
3. Edit `cassandra` endpoint object and enumerate the list of endpoints in the stretch cluster
```