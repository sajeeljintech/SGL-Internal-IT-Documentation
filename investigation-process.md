---
description: >-
  When services are interrupted for a given customer, the following steps should
  be taken to investigate and repair the issue.
---

# Investigation Process

* RDS Customer Access Server
  * Guacamole to RDS Server as Administrator
    * This confirms that Server is running and has connectivity
* SGL Client Application
  * Start the Client Application for the customer in question
    * This confirms that it boots and connects to Server
* APP01 Application Server
  * Guacamole to APP01 server as Administrator
    * This confirms that Server is running and has connectivity
* SGL Server Application
  * Confirm that the 4D Server Application is running
    * Attempt to start Server Application if not running

