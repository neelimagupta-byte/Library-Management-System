# Library-Management-System
A C - based Library management system with book issue and return functions using file handling.

---

##  Features
- Add new books
- Display all books
- Search books by name or ID
- Update book details
- Delete books
- Issue books to students
- Return books and update records

---

##  File Structure
- `library.c` → Source code
- `library.dat` → Stores book records (ignored in Git)
- `issue.dat` → Stores issued book records (ignored in Git)
- `temp.dat` / `temp_issue.dat` → Temporary files for update/delete operations (ignored in Git)

---

## Tech Stack
- **Language**: C
- **Libraries**: `<stdio.h>`, `<string.h>`, `<ctype.h>`
- **Concepts**: Structures, File Handling, Switch-case, Loops

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/neelimagupta-byte/library-management-system.git
