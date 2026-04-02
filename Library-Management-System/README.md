# 📚 Library Management System

> A digital web-based system designed to simplify and organize daily library operations in a modern and efficient way.

---

## 📋 Table of Contents

- [Project Description](#-project-description)
- [Business Requirements](#-business-requirements)
- [Functional Requirements](#-functional-requirements)
- [Non-Functional Requirements](#-non-functional-requirements)
- [User Roles & Permissions](#-user-roles--permissions)

---

## 📖 Project Description

**Library Management System** is a digital web-based system designed to simplify and organize daily library operations in a modern and efficient way. The system provides a structured approach for managing books, borrowing, and returning processes, while allowing staff to track book status accurately.

The project was created to address common challenges faced by traditional libraries, such as:
- Reliance on manual records
- Delayed returns and lost books
- Difficulties in maintaining accurate data

By converting these manual processes into a centralized digital system, the Library Management System helps reduce errors and improve overall operational efficiency.

The system supports **four types of users**: Admin, Library Staff, Members, and Guests — enabling faster transactions, reliable record keeping, and improved service quality for all library users.

---

## 📌 Business Requirements

| BR# | Business Requirement |
|-----|----------------------|
| BR1 | The library needs a single organized way to manage and organize all books. |
| BR2 | The library needs to keep accurate records of borrowed and returned books. |
| BR3 | The library needs to reduce the number of lost or misplaced books. |
| BR4 | The library needs a clear way to track book availability at any time. |
| BR5 | The library needs to manage borrowing and returning processes more efficiently than current manual practices. |
| BR6 | The library needs to monitor overdue books to reduce late returns. |
| BR7 | The library needs to achieve measurable improvement in data accuracy and eliminate duplicate records. |
| BR8 | The library needs to reduce the time required for staff to complete daily operations. |
| BR9 | The library needs to improve service speed for library users. |
| BR10 | The library needs to reduce human errors caused by manual record keeping. |
| BR11 | The library needs to store historical records of borrowing activities. |
| BR12 | The library needs to generate monthly and annual statistical reports showing borrowing trends, popular books, and usage patterns to support strategic planning. |
| BR13 | The library needs to improve overall organization of library resources. |
| BR14 | The library needs to manage library operations through a consistent and unified process. |
| BR15 | The library needs to track library usage and activity trends over time. |
| BR16 | The library needs to ensure books are returned within allowed periods. |
| BR17 | The library needs to improve accountability for borrowed items. |
| BR18 | The library needs to support library staff in handling daily workloads more effectively. |
| BR19 | The library needs to ensure staff can access current library information quickly during user interactions. |
| BR20 | The library needs to maintain clear records for auditing and review purposes. |
| BR21 | The library needs to reduce dependency on paper-based records. |
| BR22 | The library needs to improve communication with users regarding book availability and due dates. |
| BR23 | The library needs to provide a structured workflow for library operations. |
| BR24 | The library needs to improve service quality and user satisfaction. |
| BR25 | The library needs the ability to expand its services and manage increased usage over time. |

---

## ⚙️ Functional Requirements

| FR# | Requirement | Priority | Related BR |
|-----|-------------|----------|------------|
| FR1 | The system shall allow library staff to add new books to the library records. | `Must` | BR1, BR2, BR13 |
| FR2 | The system shall allow library staff to update existing book information. | `Must` | BR1, BR7, BR10 |
| FR3 | The system shall allow library staff to remove book records when necessary. | `Must` | BR1, BR3, BR13 |
| FR4 | The system shall allow users to view available books and their current status. | `Must` | BR4, BR9, BR22 |
| FR5 | The system shall allow library staff to record book borrowing transactions. | `Must` | BR2, BR5, BR17 |
| FR6 | The system shall allow library staff to record book return transactions. | `Must` | BR2, BR5, BR16 |
| FR7 | The system shall track overdue books and identify late returns. | `Must` | BR6, BR16, BR17 |
| FR8 | The system shall allow library staff to view borrowing history records. | `Should` | BR11, BR12, BR20 |
| FR9 | The system shall generate basic reports about library usage and activities. | `Should` | BR7, BR12, BR15 |
| FR10 | The system shall allow library staff to search for books by title, author, category, or ISBN. | `Must` | BR4, BR8, BR13 |
| FR11 | The system shall send automatic notifications to staff about overdue books. | `Should` | BR6, BR16, BR17 |
| FR12 | The system shall prevent borrowing of books that are already checked out. | `Must` | BR3, BR4, BR10 |
| FR13 | The system shall allow guests to browse available books without logging in. | `Must` | BR4, BR9, BR24 |
| FR14 | The system shall allow guests to search for books by title, author, or category. | `Must` | BR4, BR8 |
| FR15 | The system shall display book details to guests (title, author, category, availability status). | `Must` | BR4, BR22 |
| FR16 | The system shall allow guests to register a new account as a Member. | `Must` | BR24, BR25 |
| FR17 | The system shall prevent guests from accessing any private data or borrowing operations. | `Must` | BR5, BR17 |

---

## 🛡️ Non-Functional Requirements

| NFR# | Category | Requirement |
|------|----------|-------------|
| NFR1 | Performance | The system shall respond to all user actions within 2 seconds for at least 95% of requests during normal working hours. |
| NFR2 | Availability | The system shall be available for use 99% of library working hours, excluding scheduled maintenance. |
| NFR3 | Reliability | The system shall operate without critical failure for a minimum of 30 consecutive days under normal usage conditions. |
| NFR4 | Usability | The system shall allow new library staff to perform basic operations (add, borrow, return books) after no more than 1 hour of training. |
| NFR5 | Security | The system shall restrict access so that only authorized users can log in using a unique username and password. |
| NFR6 | Reliability | The system shall ensure that no book or borrowing record is lost or duplicated during normal operations or system updates, with 99.9% data consistency across all transactions. |
| NFR7 | Maintainability | The system shall allow system updates or rule changes to be applied without affecting existing data. |
| NFR8 | Scalability | The system shall support an increase of up to 200% in the number of books and users without performance degradation. |
| NFR9 | Backup & Recovery | The system shall perform daily automatic backups and allow data recovery within 24 hours in case of data loss. |
| NFR10 | Compatibility | The system shall operate correctly on modern web browsers (Chrome, Edge, Firefox) used on library computers. |
| NFR11 | Portability | The system shall be accessible from any device with a web browser without requiring additional software installation or configuration. |
| NFR12 | Performance | Guest-facing browsing and search pages shall load within 2 seconds without login. |
| NFR13 | Security | The system shall automatically redirect guests to the login page if they attempt to access any restricted page or operation. |
| NFR14 | Usability | The guest interface shall be simple and straightforward, requiring no instructions to navigate. |
| NFR15 | Compatibility | Guest-facing pages shall function correctly on all modern browsers (Chrome, Edge, Firefox). |
| NFR16 | Portability | Guests shall be able to access the system from any device (mobile, tablet, desktop) without installing any software. |

---

## 👥 User Roles & Permissions

### Role Descriptions

| Role | Description |
|------|-------------|
| 🔴 **Admin** | Manages the entire system: users, settings, and reports. |
| 🔵 **Library Staff** | Handles books: add, update, delete, record borrowing and returns. |
| 🟢 **Member** | Registers, logs in, views borrowing history, and borrows books. |
| ⚪ **Guest** | Browses available books only — no login required. |

### Permissions Matrix

| Permission | Admin | Library Staff | Member | Guest |
|------------|:-----:|:-------------:|:------:|:-----:|
| Add / Edit / Delete Books | ✅ | ✅ | ❌ | ❌ |
| Record Borrowing & Returns | ✅ | ✅ | ❌ | ❌ |
| View Available Books | ✅ | ✅ | ✅ | ✅ *(partial)* |
| Search Books | ✅ | ✅ | ✅ | ✅ *(partial)* |
| View Borrowing History | ✅ | ✅ | ✅ *(own only)* | ❌ |
| Generate Reports | ✅ | ✅ | ❌ | ❌ |
| Manage Users | ✅ | ❌ | ❌ | ❌ |
| System Settings | ✅ | ❌ | ❌ | ❌ |
| Register as Member | ❌ | ❌ | ❌ | ✅ |
| View Overdue Notifications | ✅ | ✅ | ❌ | ❌ |
| View Own Fines | ✅ | ✅ | ✅ *(own only)* | ❌ |

---

> 📁 This documentation was prepared by the project team as part of the graduation project requirements.

