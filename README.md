# 📚 Library Management System

> A digital web-based system designed to simplify and organize daily library operations in a modern and efficient way.

---

## 📌 Quick Overview
A web-based system designed to manage library operations efficiently, including book management, borrowing and returning tracking, and improving overall service quality.

---

## ⚙️ Tech Stack
- ASP.NET Core MVC
- SQL Server
- Entity Framework Core
- GitHub

---

## 📂 Documentation
- [Introduction](docs/01-introduction.md)
- [Stakeholder Analysis](docs/02-stakeholder-analysis.md)
- [Use Cases](docs/03-use-cases.md)

---

## 👥 Team Members

| Name | Role | GitHub |
|------|------|--------|
| Anas Abu Shammala | Documentation Lead | @anasshammala |
| Aya Abu Zyada | Frontend Developer | @aya-nasser-123 |
| Sondos Yassin | Backend Developer | @SondosYassin1 |
| Aya Hussein | Tester / QA | @ayahussein2005 |

---

## 📋 Table of Contents

- [Project Description](#-project-description)
- [Business Requirements](#-business-requirements)
- [Functional Requirements](#️-functional-requirements)
- [Non-Functional Requirements](#️-non-functional-requirements)
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
| NFR1 | Performance | The system shall respond within 2 seconds for 95% of requests. |
| NFR2 | Availability | The system shall be available 99% of working hours. |
| NFR3 | Reliability | Operates without failure for 30 days. |
| NFR4 | Usability | Staff can learn in under 1 hour. |
| NFR5 | Security | Secure login required. |
| NFR6 | Reliability | 99.9% data consistency. |
| NFR7 | Maintainability | Updates without affecting data. |
| NFR8 | Scalability | Supports 200% growth. |
| NFR9 | Backup & Recovery | Daily backups + recovery in 24h. |
| NFR10 | Compatibility | Works on Chrome, Edge, Firefox. |
| NFR11 | Portability | Works on any device. |
| NFR12 | Performance | Guest pages load within 2 seconds. |
| NFR13 | Security | Redirect unauthorized users. |
| NFR14 | Usability | Simple guest interface. |
| NFR15 | Compatibility | Works on all browsers. |
| NFR16 | Portability | Works on mobile, tablet, desktop. |

---

## 👥 User Roles & Permissions

### Role Descriptions

| Role | Description |
|------|-------------|
| 🔴 Admin | Full system control |
| 🔵 Library Staff | Manage books & transactions |
| 🟢 Member | Borrow books |
| ⚪ Guest | Browse only |

---

## 🚀 Getting Started

### Prerequisites

- .NET SDK 9.0  
- Git  

---

### Installation

```bash
git clone https://github.com/your-username/Library-Management-System.git
cd Library-Management-System
git checkout develop
dotnet build
dotnet run