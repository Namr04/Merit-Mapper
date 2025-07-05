=>Merit Mapper

Merit Mapper is a database-driven system designed to manage the college admission process based on student merit, category, and preferences. It simulates real-world centralized counseling, supporting multiple admission rounds, document uploads, and seat allotments.

=>Features

- Merit-based seat allocation (General/SC/ST)
- College & branch preference mapping
- Multi-round counseling system
- Document upload tracking with validations
- Helpdesk assignment per student
- Secure, normalized database (BCNF)

 =>Schema Highlights

- `Student`, `College`, `Branch`, `Choices`, `Allotment`, `Document`, `Payment`, `Helpdesk`, `Round`
- All relations are normalized up to BCNF ensuring data integrity and minimal redundancy

 Tech Stack

- Database: MySQL / PostgreSQL
- Design: ER Diagram ➝ BCNF Schema
- Tools: dbdiagram.io / Lucidchart

Sample Use Cases

- Allocate seats based on rank and category
- Track pending documents or payments
- View seat matrix updates round-wise
- Helpdesk support per student

---

A powerful and scalable backend for real-world admission systems.
