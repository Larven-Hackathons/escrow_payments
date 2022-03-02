# Larven Hackathons Digital

# Payment System Design

# Document

### INTRODUCTION

## Overview

The System Design Document describes the system requirements, operating
environment, system and subsystem architecture, files and database design,
input formats, output layouts, human-machine interfaces, detailed design,
processing logic, and external interfaces.

## Purpose and Scope

This section provides a brief description of the Systems Design Document’s
purpose and scope.

1. Assure quality of the products
2. Building trust between the customer and the seller
3. Reducing transaction charges (Updates)

## Stakeholders

This section provides the organization code and title of the key points of
contact (and alternates if appropriate) for the information system development
effort.

```
INDUSTRY NAME/COMPANY
Entrepreneurs
Government BOT, TRA
```

```
Banks NMB, CRDB
Mobile Networks Vodacom, Airtel
Product Consumers End users and other companies
```
## Project References

This section provides a bibliography of key project references and
deliverables that have been produced before this point.

1. Tunzaa
2. Selcom
3. AzamPay
4. Nilipe
5. Mobile Networks (General)
6. Banks

### SYSTEM ARCHITECTURE

In this section, describe the system and/or subsystem(s) architecture for the
project. References to external entities should be minimal, as they will be
described in detail in the External Interfaces Section.

## System Hardware Architecture

In this section, describe the overall system hardware and organization.
Include a list of hardware components (with a brief description of each item)


and diagrams showing the connectivity between the components. If
appropriate, use subsections to address each subsystem.

1. Web Browser(Not hardware specific)
2. Smartphones

## System Software Architecture

In this section, describe the overall system software and organization. Include
a list of software modules (this could include functions, subroutines, or
classes), computer languages, and programming computer-aided software
engineering tools (with a brief description of the function of each item). Use
structured organization diagrams/object-oriented diagrams that show the
various segmentation levels down to the lowest level. All features on the
diagrams should have reference numbers and names. Include a narrative that
expands on and enhances the understanding of the functional breakdown. If
appropriate, use subsections to address each module.

**Languages**

1. JavaScript
2. SQL

**Tools**

1. Git(Github)
2. React Native
3. MySQL
4. Firebase


### FILE AND DATABASE DESIGN

Interact with the Database Administrator (DBA) when preparing this section.
The section should reveal the final design of all database management system
(DBMS) files and the non-DBMS files associated with the system under
development. Additional information may add as required for the particular
project. Provide a comprehensive data dictionary showing data element
name, type, length, source, validation rules, maintenance (create, read, update,
delete (CRUD) capability), data stores, outputs, aliases, and description. Can
be included as an appendix.

## Database Management System Files

This section reveals the final design of the DBMS files and includes the
following information, as appropriate (refer to the data dictionary):

- Refined logical model; provide normalized table layouts, entity
relationship diagrams, and other logical design information
- A physical description of the DBMS schemas, sub-schemas, records,
sets, tables, storage page sizes, etc.

**Entities**

1. Transactions
    ● From
    ● To
    ● Date
    ● Amount
    ● Product


### EXTERNAL INTERFACES

External systems are any systems that are not within the scope of the system
under development, regardless whether the other systems are managed by
the State or another agency. In this section, describe the electronic
interface(s) between this system and each of the other systems and/or
subsystem(s), emphasizing the point of view of the system being developed.

## Interface Detailed Design

For each system that provides information exchange with the system under
development, there is a requirement for rules governing the interface. This
section should provide enough detailed information about the interface
requirements to correctly format, transmit, and/or receive data across the
interface. Include the following information in the detailed design for each
interface (as appropriate):

- The data format requirements; if there is a need to reformat data
before they are transmitted or after incoming data is received, tools and/or
methods for the reformat process should be defined
- Specifications for hand-shaking protocols between the two systems;
include the content and format of the information to be included in the
hand-shake messages, the timing for exchanging these messages, and the
steps to be taken when errors are identified
- Format(s) for error reports exchanged between the systems; should
address the disposition of error reports; for example, retained in a file, sent to
a printer, flag/alarm sent to the operator, etc.
- Graphical representation of the connectivity between systems,
showing the direction of data flow
- Query and response descriptions


If a formal Interface Control Document (ICD) exists for a given interface, the
information can be copied, or the ICD can be referenced in this section.


### SYSTEM INTEGRITY CONTROLS

Sensitive systems use information for which the loss, misuse, modification of,
or unauthorized access to that information could affect the conduct of State
programs, or the privacy to which individuals are entitled.

Developers of sensitive State systems are required to develop specifications
for the following minimum levels of control:

- Internal security to restrict access of critical data items to only those
access types required by users
- Audit procedures to meet control, reporting, and retention period
requirements for operational and management reports
- Application audit trails to dynamically audit retrieval access to
designated critical data
- Standard Tables to be used or requested for validating data fields
- Verification processes for additions, deletions, or updates of critical
data

Ability to identify all audit information by user identification, network terminal
identification, date, time, and data accessed or changed.


