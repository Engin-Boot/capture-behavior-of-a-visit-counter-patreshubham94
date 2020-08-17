# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

  Given: Patients visits the hospital.
  
  When: Hospital staff needs visit information of patients.
  
  Then: Display them visit information of patients separately.
  In one table show visit information of working days.
  And in other table show visit information of holidays.

## Scenario: Compute parking slots to reserve for visiting specialists

  Given: Hospital have parking slot.
  And specialist doctors visit the hospital.
  
  When: specialist doctors visit the hospital for some emergency.
  
  Then: Find and compute the empty parking slots.
  And reserve then for specialist.
