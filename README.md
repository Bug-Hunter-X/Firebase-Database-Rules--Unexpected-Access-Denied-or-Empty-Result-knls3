# Firebase Database Rules Debugging

This repository demonstrates a common Firebase database error related to restrictive or misconfigured security rules. The error manifests as an unexpected 'Permission denied' or an empty result when attempting to access data, even with valid authentication.

The `firebaseBug.js` file contains code that attempts to read data from the database.  The `firebaseBugSolution.js` file shows how to correctly configure rules and handle potential errors.

**Problem:** Incorrectly configured Firebase rules prevent data access.

**Solution:** Review and adjust Firebase rules to permit the required read/write operations for authenticated users.