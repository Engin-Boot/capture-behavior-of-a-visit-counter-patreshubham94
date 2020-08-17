# Visit-counter technical needs

## Scenario: Recover across restarts of the server that runs the visit-counter

  Given: Server stores the visitor count information.
  And it may fall.
  
  When: Server falls. And when server restarts.
  
  Then: Recover the lost information and keep record intact.

## Scenario: Reconcile counts if the sensor is offline for a while

  Given: Counting sensor at door maintains visitor count.
  
  When: When sensor goes offline.
  
  Then: Restart the counting process from where it left.
