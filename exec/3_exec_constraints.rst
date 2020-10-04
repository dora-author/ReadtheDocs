**********************
3. Constraints
**********************

3.1 Limitations
===============
* Application Recovery Actions
    * Recovery action that  is connected with PHM is not supported in this version
    * Only restart action is supported
* OS limitation
    * Real time scheduling is not supported in Linux
    * There is no real time patch for linux in docker environment. 
* Deterministic  client
    * Only supporting periodic activation, not Event-triggered activation.
* Resource Management:
    * Heap memory management.

      Not supporting of the configurations of heap memory for the process.
    * MEMORY management

      Not supporting of the management of MEM usage.
* No Security Supports
    * Trusted Platform

      The current version does not support Trusted Platform.
      The various mode (like strict, monitor ant etc.) is not supported in this version.
* User mode

  When executing the EM, if user level is not root mode, “Permission denied” exception will be generated. Please change the user level into root level.
.. warning:: If when EM is executed as root. Please execute other daemons like “someipdaemon” should be executed as root also. 


3.2 Assumptions
===============
No restrictions to assumptions


3.3 Dependencies to other Functional Clusters
=============================================
There are many dependencies between Execution Manager and other Functional Clusters.
Specifically, PHM and SM is very tightly coupled with EXEC. 
In this version, all interfaces with PHM and SM are not implemented. 



