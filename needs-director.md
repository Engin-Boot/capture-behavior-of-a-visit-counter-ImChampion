# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

Given I have a database of all the patient visiting.
When a patient enters in hospital it is added to the databases. 
And according to the number of patients on specific days like in between working days and holidays,
we need to choose the number of staff member required on days according to number of patients.
Then the patients would be happy with hospital service.


Scenario: Compute parking slots to reserve for visiting specialists.

Given I have database of number of parking slots and the average number of visiting specialists on working days and holidays.

When a visiting specialist visits a hospital. 
On computing how many specialist visits hospital on average on specific days we will be able to compute how many slots to reserve for visiting specialists.

Then the visiting specialist would not have any problem related to parking. 

