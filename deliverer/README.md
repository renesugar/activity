# deliverer

This library is completely optional, provided only for convenience.

An extra utility that provides a simple mechanism to asynchronously deliver
federated messages from a `pub.Pubber` available from the `go-fed/activity/pub`
library.

It implements the `pub.Deliverer` interface.

The parent application may provide a way to persist delivery attempts in a way
that survives shutdown by implementing the new `DeliveryPersister ` interface.
The sky is the limit.
