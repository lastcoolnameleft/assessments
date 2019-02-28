# Resiliency and High Availability

## Baseline

* What is your service's SLA?
* What is your service's SLO?

## BC/DR

See: https://azure.microsoft.com/en-us/features/resiliency/ 

* Do you need Availability Zones?
  * How many?
* Do you need multiple regions?
  * Which regions?
  * Hot/Cold?  Hot/Warm?  Hot/Hot?
* What is your criteria for initiating a failover?
* When is the last time you tested a failover?

# Failures

* Are there any SPOF (Single Points of Failure)?
* How do you detect when a disk is full?
* What do you do when a disk is full?
* How does your application react when a disk is full?