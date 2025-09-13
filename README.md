# Local Medical Data Web App (Angular)

A local-only web application built with the latest **Angular** to securely manage and organize personal medical files (PDFs, images).  
All data is stored directly on the device — no server or cloud connection.

---

## Core Features
- **File Management**
  - Upload files (PDFs, images).
  - Store files locally in the app.
  - Categorize files with custom labels/tags.
  - Compress files to reduce memory usage.
  - Quick local search through stored files.

- **Security**
  - Global passkey to access the app.
  - Extra passkey layer for selected categories/files.
  - Full offline functionality.

- **Local AI (Browser-Only)**
  - Runs fully inside the browser.
  - No external API or internet connection required.

---

## Angular Focus Areas
- Signals
- Guards
- RxJS
- Unit Testing
- Component Lifecycles
- Zoneless Angular
- Schematics
- App Optimization

---

## Initial R&D Tasks (parallel for 2 members)
- [ ] **Tasks Management & Review of the code**: review existing boards like kanban or azure devops for github where we can put status to our tasks like (Ready to Start, Active, Paused etc).
- [x] **Market Research**: review existing medical data apps to analyze UX, UI patterns, and feature sets.
- [x] **UI Library Research**: evaluate Angular UI libraries that provide a file uploader out-of-the-box with drag-drop and custom handling.
- [ ] **Authentication / Security Research**: evaluate libraries or approaches for local authentication, encryption, and passkey protection.

---

## Next Development Tasks

### File Management (Member A)
- [ ] Implement file upload and local storage.
- [ ] Add categorization system.
- [ ] Add compression before storage.
- [ ] Implement local search.
- [ ] Write unit tests for file management.

### Security & AI (Member B)
- [ ] Implement global app passkey.
- [ ] Implement per-category/file extra passkey.
- [ ] Integrate local/offline AI.
- [ ] Write unit tests for security & AI.

---

## Shared Angular Learning
- Apply **signals** for state management.
- Use **guards** for route protection.
- Apply **RxJS** for async flows.
- Explore **lifecycles** in components.
- Configure **zoneless Angular**.
- Create **schematics** for scaffolding.
- Perform **build & performance optimization**.

---

## Team
- 2 Members (independent parallel tracks)

