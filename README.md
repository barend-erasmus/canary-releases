# Canary Releases

Canary release is a technique that helps reduce the impact of negative changes by gradually rolling out the changes. If a problem with the new release is detected during the rollout then it can be rolled back, and only a subset of the traffic will have been impacted.

![](https://github.com/barend-erasmus/canary-releases/raw/master/images/canary-releases.png)

## Advantages of Canary Releases

* Both, A and B, can run in parallel without affecting each other.
* Rollbacks are simple.
* New releases can be deployed with low risk.

## Enablers

* Services / API's need to be versioned.
* Database Stored Procedures needs to be versioned.
* Phoenix Server Strategy need to be in place.
