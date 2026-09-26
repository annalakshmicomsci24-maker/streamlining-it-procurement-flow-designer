<img width="1366" height="617" alt="Screenshot 2026-09-23 182026" src="https://github.com/user-attachments/assets/c64a45b5-b2ba-43e6-8ec8-b59a8eab7fc5" />
# Project Testing

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Testing Objective
The objective of testing is to verify that the Standard Laptop procurement workflow works as expected after implementing the Flow Designer automation.

## Test Cases

| Test Case | Test Action | Expected Result |
|---|---|---|
| TC01 | Open Flow Designer | Flow Designer should open successfully |
| TC02 | Create the Standard Laptop Task flow | Flow should be created with the required name |
| TC03 | Configure Service Catalog trigger | Service Catalog should be configured as the trigger |
| TC04 | Configure Create Catalog Task action | Catalog Task action should be added successfully |
| TC05 | Configure task fields | Required description, approval, and assignment values should be configured |
| TC06 | Save and activate the flow | Flow should be saved and activated |<img width="1366" height="617" alt="Screenshot 2026-09-23 182026" src="https://github.com/user-attachments/assets/7045d8ea-0e9e-40b6-920e-433a4c712155" />

| TC07 | Assign the flow to Standard Laptop | Standard Laptop catalog item should use the created flow | <img width="1366" height="554" alt="Screenshot 2026-09-23 182209" src="https://github.com/user-attachments/assets/d7b26061-394f-4f63-a1d7-5768b670f48b" />

| TC08 | Place Standard Laptop order | Standard Laptop request should be created |<img width="1366" height="768" alt="Screenshot 2026-09-23 172241" src="https://github.com/user-attachments/assets/d58304c8-48ff-437e-b96e-3958780bc8db" />

| TC09 | Approve the request | Requested Item should show the approval |<img width="1366" height="562" alt="Screenshot 2026-09-23 172606" src="https://github.com/user-attachments/assets/e9c9d8c9-4f6d-4c5c-848e-649a9b797a0f" />

| TC10 | Check Catalog Tasks | Catalog Task should be generated after approval 
<img width="1366" height="768" alt="Screenshot 2026-09-23 182438" src="https://github.com/user-attachments/assets/0a28ca85-6feb-425b-9f1b-40b3003bc4cf" />

| TC11 | Verify task details | Short description and Hardware assignment group should be displayed |<img width="1366" height="768" alt="Screenshot 2026-09-22 185128" src="https://github.com/user-attachments/assets/d5ca0412-a0f2-4573-a28b-3c3a242dbeb6" />

## Verification

The following details should be verified in the generated Catalog Task:

- Short Description: Laptop need to Configured
- Assignment Group: Hardware
- Approval: Approved

## Expected Testing Outcome

The testing should confirm that the Standard Laptop request is connected to the Flow Designer workflow and that the required Catalog Task is generated after approval and assigned to the Hardware group.
