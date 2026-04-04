# Week 1 QA Review

## Build Verification

- [x] Cloned fresh ✅
- [x] `dotnet build` passed ✅
- [x] Home page loaded ✅
- **Notes:**
  - Missing `.sln` file in the repository. Had to open `.csproj` manually to run the project in Visual Studio.
  - Project runs on .NET 9.0 as required.

## README Review

- **Issues found:**
  - Git Conflict detected in `README.md` between the Tech Stack section and documentation links — resolved manually.
  - Broken internal links in the Table of Contents for Business Requirements and Non-Functional Requirements sections.
  - Tech Stack was incomplete — only listed Back-End tools (EF Core, SQL Server). Missing Front-End tools (HTML5, CSS3, JavaScript, Bootstrap 5).

## Documentation Review (docs/)

| File                       | Status | Issues / Notes                                            |
| -------------------------- | ------ | --------------------------------------------------------- |
| 01-introduction.md         | ✅ OK  | Scope is clear and well-defined. Matches project goals.   |
| 02-stakeholder-analysis.md | ✅ OK  | All 4 roles (Admin, Staff, Member, Guest) are identified. |
| 03-use-cases.md            | ✅ OK  | Use cases are complete and well-detailed for all roles.   |

## Wireframe Review

- **Issues found:**
  - Wireframes for Landing, Login, and Register pages are present and well-organized under `docs/wireframes/`.
  - File naming convention (01-, 02-...) is clear and consistent.
  - Site Journey covers Guest and Member roles only — missing flows for Admin and Staff.
  - No wireframes exist for Admin Dashboard or Staff Management screens.

## Cross-Check: Stakeholders vs Wireframes

- **Mismatches found:**
  - Admin and Staff roles are defined in `02-stakeholder-analysis.md` and `03-use-cases.md` but have no corresponding wireframes.
  - Guest and Member flows are consistent between documentation and wireframes.

## Pull Request Management

- Received a Pull Request from Sondos requesting approval to delete a duplicate and unnecessary file from the repository to maintain a clean project structure.
- ✅ Reviewed the file and confirmed it was unnecessary.
- ✅ Approved the PR and it was successfully merged into the `develop` branch.

## Summary

- **Blocker issues (must fix before Week 2):**
  - Add missing `.sln` file to the repository — @SondosYassin1 notified.
  - Fix broken internal links in `README.md` — @anasshammala notified.
  - Update Tech Stack in README to include Front-End tools — @anasshammala notified.
- **Minor issues (can fix during Week 2):**
  - Complete wireframes for Admin and Staff roles - @aya-nasser-123 notified.

---

**Verified by:** @ayahussein2005 (QA Lead / Team Leader)
**Date:** April 4, 2026
