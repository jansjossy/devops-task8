# DevOps Internship - Task 8: CI/CD with GitHub Actions
**User:** Janzj

## 1. Pipeline Configuration
- **Workflow File:** `.github/workflows/ci.yml`
- **Triggers:** Push and Pull Request events.
- **Job:** `build-and-test` runs on `ubuntu-latest`.

## 2. Execution Analysis
- **Success Test:** Pipeline passed when `index.html` was present, confirming the environment setup and script execution worked.
- **Failure Test:** Pipeline correctly identified the missing file and failed with **Exit Code 1**. This demonstrates how CI prevents broken code from being accepted.

## 3. Evidence
<img width="960" height="1020" alt="Screenshot 2026-01-29 110912" src="https://github.com/user-attachments/assets/88b881a3-5761-4a8d-89c3-5760595f0b0d" />
<img width="960" height="1020" alt="Screenshot 2026-01-29 111121" src="https://github.com/user-attachments/assets/c20c1234-2fde-4847-9ae8-c416b007cffc" />


<img width="960" height="1020" alt="Screenshot 2026-01-29 110742" src="https://github.com/user-attachments/assets/b99dc410-5d64-4271-82a7-d11ccefba648" />

# 4. Terminal
<img width="960" height="1020" alt="Screenshot 2026-01-29 110722" src="https://github.com/user-attachments/assets/06f63e73-5d73-4bc1-bf5b-b655051f8a7b" />
<img width="960" height="1020" alt="Screenshot 2026-01-29 110717" src="https://github.com/user-attachments/assets/bcfad85e-d037-417d-bb30-46ac3ecf9046" />
<img width="960" height="1020" alt="Screenshot 2026-01-29 110710" src="https://github.com/user-attachments/assets/6c5c0580-a3af-4064-90f1-e5dae73fa76e" />
