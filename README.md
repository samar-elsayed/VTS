# VTS ( Vacation Tracking System )


# Vision:
A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.

# Functional Requirements:
- Implements a flexible rules-based system for submitting, validating and verifying leave time requests
- Enables manager approval (optional)
- Provides access to requests for the previous calendar year, and allows requests to be made up to a year and a half in the future
- Uses e-mail notification to request manager approval and notify employees of request status changes
- Enables the HR and system administration personnel to override all actions restricted by rules, with logging of those overrides
- Keeps activity logs for all transactions
- Allows managers to directly award personal leave time (with system-set limits)

# Non-functional requirements:
- Provides a Web service interface for other internal systems to query any given employee’s vacation request summary.
- Should provide Web service interface to HR department legacy systems to retrieve required employee information and changes.
- Uses existing hardware and middleware.
- Service will be implemented as an extension to the existing intranet portal system, and uses the portal’s single-sign-on mechanisms for all authentication.

# Constraints:
- Uses existing hardware and middleware
- Is implemented as an extension to the existing intranet portal system, and uses the portal’s single-sign-on mechanisms for all authentication
- The available vacantion balance is determined per vacation type & requestor role type
- Vacation available calendar dates should be up to a year and a half in the future
- Mandatory vacation request information should be complete and correct

-----------
# UseCases:

### 1- Manage Time


### FlowChart:

<img width="736" height="2625" alt="image" src="https://github.com/user-attachments/assets/48483c9e-fde3-4979-80df-9ea1dac30792" />


### Sequence Diagram:

<img width="2076" height="1278" alt="image" src="https://github.com/user-attachments/assets/00f7f556-626d-49ee-a352-30a8f38a73f3" />


