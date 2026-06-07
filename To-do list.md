## Current Stage (Based on Topics Covered)

You should currently implement only the following files:

### 1. Client.java

Implement:

* clientId
* clientName
* email
* phone
* city

Tasks:

* Constructors
* Getters and Setters
* toString()

---

### 2. ClientService.java

Implement using an array 

Features:

* Add Client
* View All Clients
* Search Client by ID
* Update Client
* Delete Client

Use a fixed-size array such as:

Client[] clients = new Client[100];

---

### 3. Custom Exceptions

Implement:

* ClientNotFoundException.java
* DuplicateClientException.java
* InvalidClientDataException.java

Use:

* throw
* throws
* try-catch

---

### 4. Main.java

Important:

The project execution starts from Main.java.

You must implement:

public static void main(String[] args)

inside Main.java.

Run Main.java to test the application.

All client operations should be invoked through the menu present in Main.java.

Implement:

* Menu Driven Program
* User Input
* Calling Service Methods
* Exception Handling

Menu:

1. Add Client
2. View Clients
3. Search Client
4. Update Client
5. Delete Client
6. Exit

---
What you should be working after completion ?

When you run Main.java, you should be able to:

*Add a client

*View all clients

*Search a client by ID

*Update client details

*Delete a client

*Handle invalid operations through custom exceptions

*Exit the application


## Files to Leave Empty for Now

The following files will be completed after future topics are taught:

### After Inheritance

* CorporateClient.java
* IndividualClient.java

### After Packages

* Proper package organization

### After Collections

* Convert array-based storage to ArrayList

* SearchService.java

* ReportService.java

### After File Handling

* clients.txt

* Save Client Data

* Load Client Data

### After Utility Classes

* ValidationUtil.java

* InputUtil.java

---

## What Should Run Now?

You should be able to run:

Main.java

and successfully perform:

✓ Add Client

✓ View Clients

✓ Search Client

✓ Update Client

✓ Delete Client

✓ Handle Exceptions

using only arrays and classes.
