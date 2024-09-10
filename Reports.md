# Reports Requested
## Limit vs Request 
The difference between limit and request is that request is the minimum required specs for the pod to run .
Limit is the maximum required specs for the pod.
-------------------------
## Deployment vs RS 
They both have the same function of creating replicas of pods, but Deployment is a higher form and offers ways to efficiently update applications.
RS is used when no more updates are needed and has less functions than Deployment and in case of updates , it has to be done manually. Basically to just make sure the number of pods required are available at all times. 
Deployment is used when we need to manage the life cycle of an application in addition to the use of the RS.

