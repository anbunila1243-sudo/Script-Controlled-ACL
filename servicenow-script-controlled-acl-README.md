# Script-Controlled ACL – Restrict Record Access Based on User and Field Conditions

## Project Overview

This project implements Script-Controlled Access Control Lists (ACLs) in ServiceNow to restrict access to records based on specific field values and user conditions.

The ACL scripts evaluate the required conditions before allowing a user to access or modify a record.

## Technologies Used

- ServiceNow
- JavaScript / ServiceNow Scripting
- Access Control Lists (ACL)
- Users and Roles
- Custom Tables

## Project Components

### 1. Users and Roles
Created the required users and roles in ServiceNow and assigned roles to users for access testing.

### 2. Tables
Created the required custom table and fields used for implementing and testing the ACL rules.

### 3. READ ACL
Implemented a Script-Controlled READ ACL to allow record access only when the configured conditions are satisfied.

### 4. CREATE ACL
Implemented a CREATE ACL to control whether a user can create records based on the required access conditions.

### 5. WRITE ACL
Implemented a WRITE ACL to restrict modification of records according to the configured user and field conditions.

### 6. DELETE ACL
Implemented a DELETE ACL to control whether a user is allowed to delete records.

## Testing

The ACL rules were tested using the created users and roles.

The project verifies both:
- Access granted when the required conditions are satisfied.
- Access denied when the required conditions are not satisfied.

## Result

The ServiceNow application successfully uses Script-Controlled ACLs to enforce record-level access control based on user conditions and field values.

## Project Demo

Demo link will be added after the project demonstration video is uploaded.

## GitHub Repository

This repository contains the project documentation and supporting files for the ServiceNow Script-Controlled ACL project.
