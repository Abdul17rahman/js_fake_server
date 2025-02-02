# Fake Json server

Objective: Implement functionality to sync the local data of your “Dynamic Quote Generator” with a server and handle potential conflicts due to simultaneous edits or updates.

Task Description:

This task involves setting up a simple simulation of server interactions to sync local quote data and resolve conflicts. You’ll enhance the application’s robustness by ensuring that data remains consistent across different sessions and devices, simulating a real-world application environment.

Step 1: Simulate Server Interaction

Setup Server Simulation:
Use JSONPlaceholder or a similar mock API to simulate fetching and posting data.
Implement periodic data fetching to simulate receiving updates from a server.
Step 2: Implement Data Syncing

Data Syncing Logic:
Add functionality to periodically check for new quotes from the server and update the local storage accordingly.
Implement a simple conflict resolution strategy where the server’s data takes precedence in case of discrepancies.
Step 3: Handling Conflicts

Conflict Resolution:
Add a UI element or notification system to inform users when data has been updated or if conflicts were resolved.
Provide an option for users to manually resolve conflicts if desired.
Step 4: Testing and Verification

Ensure Comprehensive Testing:
Test the sync and conflict resolution functionalities thoroughly to ensure they work as expected.
Verify that changes are correctly merged, conflicts are handled appropriately, and no data is lost during the sync process.
