# User Stories

- US-1 (Must) Registration
  - As a Student, I want to create an account, so that I can apply to jobs.
  - Acceptance:
    - Given valid details, When I submit, Then the account is created and I see success.
    - Given a duplicate email, When I submit, Then I see an error and my input remains.

- US-2 (Must) Login
  - As any user, I want to log in, so that I can access my dashboard.
  - Acceptance: valid → success; invalid → error; role‑based access after login.

- US-3 (Must) Browse jobs
  - As a Student, I want to view job listings, so that I can find opportunities.
  - Acceptance: show title/company/location/type/deadline; newest first.

- US-4 (Should) Search & filter
  - As a Student, I want to narrow results, so that I can find relevant roles.
  - Acceptance: filter by title/company/location/type; clear filters resets list.

- US-5 (Must) Apply to job
  - As a Student, I want to submit a resume URL and note, so that reviewers can evaluate me.
  - Acceptance: one active application per job; success confirmation on submit.

- US-6 (Must) Post job (TPO)
  - As a TPO, I want to create a job, so that students can apply.
  - Acceptance: required fields validated; job appears immediately.

- US-7 (Should) Edit job (TPO)
  - As a TPO, I want to correct details, so that the post stays accurate.
  - Acceptance: edits persist and reflect in listings.

- US-8 (Must) Close job (TPO)
  - As a TPO, I want to close a job, so that no new applications are accepted.
  - Acceptance: status shows Closed; apply blocked with notice.

- US-9 (Should) Review applications (Company)
  - As a Company, I want to view applicants, so that I can shortlist.
  - Acceptance: list shows candidate, resume link, note, submission time.

- US-10 (Could) Manage users (Admin)
  - As an Admin, I want to enable/disable accounts, so that access stays controlled.
  - Acceptance: disabled users cannot log in; admin sees current status.

