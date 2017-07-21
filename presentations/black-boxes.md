## Peering into Black Boxes: What’s Really Inside Containers?


## Abstract

Containers are a useful means for packaging up and deploying applications. One of the proposed benefits of containers is an increased ability to create immutable infrastructure that guarantees the contents of your application wherever it is instantiated. However, the real world is full of exceptions like the ability to use docker exec, access shared data volumes, mounting volumes with read+write permissions, and various application architecture quirks that make true immutability difficult to maintain. In this world, application and configuration drift still happen and we need tools to help identify drift wherever it occurs. This talk will introduce Lumogon, a new open-source tool from Puppet, Inc., and demonstrate how to use Lumogon to identify and address drift in a container application.
 
In this talk we’ll:
 
* Briefly cover the container landscape to talk about base images, immutability, and other common container practices
* Introduce a new open-source tool, Lumogon, and highlights its capabilities
* Use Lumogon to query running containers without knowing anything about them ahead of time
* Use the data provided by Lumogon to track and remediate drift in a container application


## Tyler Pace
