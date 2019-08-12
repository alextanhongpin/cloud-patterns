# cloud-patterns
Applying cloud patterns in application design in distributed system. A lot of materials I found online on cloud patterns seems to be oversimplified, and does not provide enough details. Hence I create this repo to explore them myself by putting them in production when possible and writing down how I approach each problem.

## References

- https://docs.microsoft.com/en-us/azure/architecture/patterns/


## Patterns

Most of these patterns can be found on Wiki of Azure's Cloud Design Patterns.

- ambassador
- anti-corruption layer
- bulkhead
- cache-aside
- circuit-breaker
- cqrs
- compensating transaction
- competing consumers
- compute resource consolidation
- event sourcing
- external configuration store
- federated identity
- gatekeeper
- index table
- leader election
- map reduce
- materialized view
- pipes
- filters
- priority queues
- publisher-subscriber
- queue-based load leveling
- retry
- scheduler agent supervisor
- sharding
- sidecar
- strangler
- throttling
- valet key


There are some that are not mentioned here, especially those related to monitoring/logging/metrics gathering as well as canary release/load balancing. But I suppose those are more DevOps related than architecture.
