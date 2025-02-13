---
## work load of pods

* Pods will have one or more containers
* Each Pod gets an IP Address which is shared to the container
* Pods will two types of containers in it


    * containers : These are where we run our application images and they should run forever and they are created in parallel
                    - conatiners wil create at a time.

    * Init containers: They are created in a sequence and they are expected to finish in some finite time. Generally we do precondition checks over here  
                    - conatiners wil create one by one
                    - These represent checking for preconditions
                    