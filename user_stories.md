## Admin User Stories

### Story 1:

**Title:** Need the ability securely access into the portal to management operations

**As an** Admin,
**I need** log into the portal with my username and password,
**so that** I can manage the platform securely.

**Acceptance Criteria:**

```gherkin
Given I have a admin account
When I use the form to logging with my username and password
Then I can access securely to the management portal
```

**Priority:** High
**Story Points:** 5
**Notes:**
- Password validation should be strong

### Story 2:

**Title:** Need the ability to finish admin sessions securely

**As an**  Admin,
**I need** logout admin sessions,
**so that** I can finish manage operations securely.

**Acceptance Criteria:**

```gherkin
Given I have a logged in admin session  
When I use the function to loggout
Then the admin management session will finish securely 
```

**Priority:** High
**Story Points:** 3  
**Notes:**
- Session termination have to be confirmed

### Story 3:

**Title:** Need the ability to add doctor's profiles to the portal

**As an** Admin,
**I need** to create doctor accounts,
**so that** I can register the new personnel.

**Acceptance Criteria:**

```gherkin
Given I have a a new doctor account data
When I use the portal account management system
Then the new account will be registered into the database.
```

**Priority:** High
**Story Points:** 5
**Notes:**

### Story 4:

**Title:** Need the ability to delete doctor's profiles from the portal

**As an** Admin,
**I need** to delete doctor's accounts,
**so that** I can keep clear the accounts register of the systems.

**Acceptance Criteria:**

```gherkin
Given I have a have a doctor's account to delete
When I use the delete function from the management portal
Then the doctor's account will be remove from the accounts register```
```

**Priority:** Medium
**Story Points:** 3  
**Notes:**

### Story 5:

**Title:** Need the ability to get the number of appointments per month and track usage statistics

**As an** Admin,
**I need** to Run a stored procedure in MySQL CLI,
**so that** I can get the number of appointments per month and track usage statistics.

**Acceptance Criteria:**

```gherkin
Given I have a need to track usage statistics of appointments per month
When I use a stored procedure in MySQL CLI
Then the result allow me to write a statistics report
```

**Priority:** Low  
**Story Points:** 1  
**Notes:**

## Patient User Stories

### Story 1:

**Title:** Need the ability to view a list of doctors without registration

**As a** Patient,
**I need** view a list of doctors without logging in to,
**so that** I can explore options before registering.

**Acceptance Criteria:**

```gherkin
Given I have a access to the application portal without registration 
When I use view available doctor's profiles
Then the portal displays all the matching doctor's profiles
```

**Priority:** Medium
**Story Points:** 1  
**Notes:**

### Story 2:

**Title:** Need the ability to sign up using an email and password

**As a** Patient,
**I need** to sign up using my email and password,
**so that** I can book appointments.

**Acceptance Criteria:**

```gherkin
Given I have an valid email and password 
When I use sign up operation
Then the system will allow my registration as patient account
```

**Priority:** High  
**Story Points:** 5  
**Notes:**
- Need to strong validation of the account's password and email

### Story 3:

**Title:** Need the ability to log into the portal

**As a** Patient,
**I need** to log into the portal,
**so that** I can manage my bookings.

**Acceptance Criteria:**

```gherkin
Given I have a valid patient account
When I use it to log into the portal
Then the portal grants me access to manage my bookings.
```

**Priority:** High
**Story Points:** 3  
**Notes:**

### Story 4:

**Title:** Need the ability to log out of the portal

**As a** Patient,
**I need** log out of the portal,
**so that** I can secure my account.

**Acceptance Criteria:**

```gherkin
Given I am logged into the portal
When I use the log out function
Then the portal session will be finish securely
```

**Priority:** High  
**Story Points:** 3
**Notes:**

### Story 5:

**Title:** Need the ability ot log in and book an hour-long appointment

**As a** Patient,
**I need** to log in and book an hour-long appointment,
**so that** I can consult with a doctor.

**Acceptance Criteria:**

```gherkin
Given I have logged into the portal
When I use booking function for an doctor's appointment
Then the appointment will be confirmed and registered
```

**Priority:** Medium
**Story Points:** 3  
**Notes:**

### Story 6:

**Title:** Need the ability to view my upcoming appointments

**As a** Patient,
**I need** to view my upcoming appointments,
**so that** I can prepare accordingly.

**Acceptance Criteria:**

```gherkin
Given I have logged into the portal
When I use viewing upcoming appointments function
Then the portal will display my upcoming appointments
```

**Priority:** Medium
**Story Points:** 3  
**Notes:**


## Doctor User Stories

### Story 1:

**Title:** Need the ability to log into the portal

**As a** Doctor,
**I need** to log into the portal,
**so that** I can manage my appointments.

**Acceptance Criteria:**

```gherkin
Given I have a doctor account
When I use the log function 
Then the portal grants me access
```

**Priority:** High
**Story Points:** 3  
**Notes:**

### Story 2:

**Title:** Need the ability to log out of the portal

**As a** Doctor,
**I need** to log out of the portal,
**so that** I can protect my data.

**Acceptance Criteria:**

```gherkin
Given I have am logged into the portal
When I use the log out function 
Then the portal securely finish my session 
```

**Priority:** High
**Story Points:** 3  
**Notes:**

### Story 3:

**Title:** Need the ability to view my appointment calendar

**As a** Doctor,
**I need** to view my appointment calendar,
**so that** I can stay organized.

**Acceptance Criteria:**

```gherkin
Given I have a appointment calendar
When I use the view appointment calendar function 
Then the portal shows me the appointment calendar
```

**Priority:** Medium
**Story Points:** 3  
**Notes:**

### Story 4:

**Title:** Need the ability to mark my unavailability

**As a** Doctor,
**I need** to mark my unavailability,
**so that** I can to inform patients only the available slots.

**Acceptance Criteria:**

```gherkin
Given I have to mark my unavailability
When I use the mark unavailability function 
Then the system allows me to mark it
```

**Priority:** Medium
**Story Points:** 1  
**Notes:**

### Story 5:

**Title:** Need the ability to update my profile with specialization and contact information

**As a** Doctor,
**I need** to update my profile with specialization and contact information,
**so that** patients have up-to-date information.

**Acceptance Criteria:**

```gherkin
Given I have a profile up-to-date new information 
When I use the update profile's data function 
Then the portal updates my new information
```

**Priority:** Low
**Story Points:** 1  
**Notes:**

### Story 6:

**Title:** Need the ability to view the patient details for upcoming appointments

**As a** Doctor,
**I need** to view the patient details for upcoming appointments,
**so that** I can be prepared.

**Acceptance Criteria:**

```gherkin
Given I have an upcoming appointment
When I use the view appointment details function 
Then the portal shows me appointment details
```

**Priority:** Medium
**Story Points:** 3  
**Notes:**  