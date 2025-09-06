Salesforce Lead Management Project

This project contains two main features implemented in Apex:

Daily Lead Report (Batch Apex + Scheduler)

Sends a daily email to the System Administrator with the number of Leads created today.

Attaches a CSV file containing Lead details (Id, Name, Company, Email, CreatedDate).

Lead REST API

A REST resource for creating Lead records.

Bulkified to accept multiple Leads in a single request.

Prevents duplicate insertion based on Email.

Sends email notifications for success or failure.
