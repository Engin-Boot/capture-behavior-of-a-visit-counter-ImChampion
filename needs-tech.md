# Visit-counter technical needs

Scenario: Recover across restarts of the server 
that runs the visit-counter

Given: The server has real time backup available which stores
the visitor count.

When: The server restarts.

Then: Recover data and update server after it restarts.

Scenario: Reconcile counts if the sensor is offline for a while.

Given: There is a option to manually count. 

When: The sensor status changes to offline mode.

Then: It informs to count visitors manually and 
reconcile the count manually.
