# SNOW-Problem-Management

- Problem Management helps to identify the cause of an error in the IT infrastructure that is usually reported as occurrences of related incidents. Resolving a problem means fixing the error that will stop these incidents from occurring in the future.

- Problem resolution and elimination of root cause often calls for applying a change to the configuration item in the existing IT environment. 

- The Service-Now platform supports the Problem Management process with capabilities to record problems, create knowledge from problems, request changes, assign to appropriate groups, escalate, and manage through to resolution and reporting!

## Flowchart
![image](https://user-images.githubusercontent.com/12488769/148684515-d2f01c49-616b-4c0d-8c9f-f61ed53f9bb9.png)

## Process
1. Logging - A problem can be generated in a number of ways.
- An IT staff member can generate one manually using Problem Create New or by clicking New from the problem record list.
- An IT staff member can generate a problem from an incident. 
- If an appropriate inbound email action is configured, a problem can be generated from an email.

2. Assignment - A problem can be assigned to a user or group. This can be done manually, or using an assignment rule.

3. Investigating & Updating 
- If the problem management team has a problem model process for dealing with certain problems, they can be codified in the system using workflows. This allows for standardization and automation of the process. 
-As a problem is updated, email notifications will be sent to concerned parties. If inbound email actions are specified, the problem can be updated via email.
- The platform has an in-built system of Escalations rules which can ensure that problems are handled speedily (via SLA).

4. Resolution:
- If a problem needs a change in order to be resolved, it is possible to request a change, which will be then resolved using the change management process. 
- Once a change has been requested, the problem will appear on a related list on the change item's form. 
- Once the problem is associated with a change item, change the Problem State to Pending Change. 

- It is possible to create a business rule that will close the problem automatically if the change it is associated with is closed. 
- This automates the process of closing problems that are Pending Change.
-  It is also possible to create a business rule that will automatically close all incidents associated with the problem if the problem is closed. 

- If a problem's cause has been determined but there is no permanent fix, changing the Problem State to Known Error communicates this fact to the IT staff. 
- This helps reduce the time spent on incidents dealing with the known problem by making known errors easy to find, automatically creating a list of Known Errors.




