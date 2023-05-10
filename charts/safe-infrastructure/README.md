# Safe Chart

This chart packages the Safe resources. The chart uses it's child charts [safe-config](https://github.com/safe-global/safe-config-service/charts/safe-config), [safe-transaction](https://github.com/safe-global/safe-transaction-service/charts/safe-transaction),  [safe-client-gateway](https://github.com/safe-global/safe-client-gateway/charts/safe-client-gateway).
This chart assumes that there is already an existing Postgres, Redis and RabbitMQ instance available in Kubernetes and the connection attribute should be passed in the values of the Helm Chart

## Parameters

