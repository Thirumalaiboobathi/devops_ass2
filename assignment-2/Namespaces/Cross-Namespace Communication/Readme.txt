Why Only FQDN Works:
-DNS in Kubernetes is namespace-scoped by default.

-The client pod is in the dev namespace.

-backend-service is in the prod namespace.

-So the short name backend-service resolves only within prod, not from dev.

