# Visit-counter technical needs

Scenario: Recover across restarts of the server that runs the visit-counter

Given the server has real time backup available which stores
the visitor count.
When the server restarts.
Then recover data and update server after it restarts.

Scenario: Reconcile counts if the sensor is offline for a while.

Given there is a option to manually count.
When the sensor status changes to offline mode.
Then it informs to count visitors manually and reconcile the count manually.
