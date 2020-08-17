# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays.

Given I have a database of all the patient visiting.
When a patients enters hospital,entry will be noted in database.
According to the number of patients on specific days,
We will choose the number of staff member required.
Then the patients would be happy with hospital service.

Scenario: Compute parking slots to reserve for visiting specialists.

Given I have database of number of parking slots
and the number of visiting specialists on working days and holidays.
When a visiting specialist visits a hospital.
On computing the number of specialist visiting hospital on specific days,
We will be able to compute the number of slots to reserve for specialists.
Then the visiting specialist would not have any problem related to parking.
