---
name: User Story
about: develop an account microservice that can create, read, update, delete, and
  list customers
title: ''
labels: ''
assignees: ''

---

**As a** customer account manager
**I need** an account microservice
**So that** customers can be created, read, updated, deleted, and listed
      
### Details and Assumptions
    * A database model and a Python Flask-based REST API with an endpoint to create a customer account already exists.     

### Acceptance Criteria     
    gherkin 
    Given I have n customer records
    When I create another customer
    Then I have n+1 customer records
