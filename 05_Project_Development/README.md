# Project Development

## Project Title
Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Development Platform
ServiceNow

## Development Tool
Flow Designer

## Development Process

### Step 1: Create the Flow
A new Flow is created in ServiceNow Flow Designer.

- Flow Name: Standard Laptop Task
- Application: Global
- Run As: System User
  
<img width="1366" height="566" alt="Screenshot 2026-09-23 171818" src="https://github.com/user-attachments/assets/012519bb-4843-4bde-abf0-5de6267bb4db" />


### Step 2: Configure the Trigger
The flow is configured with a Service Catalog trigger.

 <img width="1366" height="578" alt="Screenshot 2026-09-23 182300" src="https://github.com/user-attachments/assets/68e3c2cf-6d5d-4982-b85c-2329df339326" />

### Step 3: Add the Action
The "Create Catalog Task" action is added to the flow.

<img width="1366" height="768" alt="Screenshot 2026-09-23 182438" src="https://github.com/user-attachments/assets/e9c3146f-a1c9-45ed-bc01-9ceb1afd466e" />


### Step 4: Configure the Catalog Task
The Catalog Task is configured using the following values:

- Request Item: Requested Item Record
- Table: Catalog Task
- Short Description: Laptop need to Configured
- Description: Laptop need to Configured
- Assignment Group: Hardware
- Approval: Approved

- <img width="1366" height="768" alt="Screenshot 2026-09-23 182438" src="https://github.com/user-attachments/assets/e9c3146f-a1c9-45ed-bc01-9ceb1afd466e" />

### Step 5: Save and Activate the Flow
The configured flow is saved and activated so that it can process the Standard Laptop service request.

<img width="1366" height="573" alt="Screenshot 2026-09-23 173829" src="https://github.com/user-attachments/assets/c31500ef-9eb5-4696-b816-e6df0892599e" />


### Step 6: Assign the Flow to Standard Laptop
The Standard Laptop service catalog item is opened under Maintain Items
The existing process engine automation is replaced with the newly created "Standard Laptop Task" flow.

<img width="1366" height="566" alt="Screenshot 2026-09-23 173602" src="https://github.com/user-attachments/assets/f4066e46-acbe-484b-b393-76aeefb82cb3" />


### Step 7: Place a Standard Laptop Order
The Service Catalog is opened and the following options are selected:

1. Service Catalog
2. Hardware
3. Standard Laptop
4. Order Now

<img width="1366" height="768" alt="Screenshot 2026-09-23 172241" src="https://github.com/user-attachments/assets/2679334e-3e96-4f61-9578-013c81702a02" />


### Step 8: Approve the Request
The generated request is opened and the Approvers section is accessed. The request is then approved.

 <img width="1366" height="562" alt="Screenshot 2026-09-23 172606" src="https://github.com/user-attachments/assets/d245ff0b-f9ed-4132-bee7-3786b68ce978" />

### Step 9: Verify the Catalog Task
After approval, the Requested Item is opened and the Catalog Tasks section is checked.

The generated task should show:

- Short Description: Laptop need to Configured
- Assignment Group: Hardware

- <img width="1366" height="768" alt="Screenshot 2026-09-22 185128" src="https://github.com/user-attachments/assets/c6fd3d6a-09b3-4d9f-adc8-bcd41630102a" />


## Development Outcome

The developed workflow automates the creation and assignment of a Catalog Task after approval of a Standard Laptop request. The task is assigned to the Hardware group for laptop configuration.
