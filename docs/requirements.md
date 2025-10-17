
# Placement Support — Requirements v1.0

## Overview
This MVP helps students find and apply to campus roles, lets the TPO post and manage openings with deadlines, and lets companies review applications; Admin controls access.

## Scope
- In-scope (MVP): register/login, browse jobs, search/filter, apply with resume URL + note, TPO post/edit/close job, company view applicants.
- Out-of-scope (MVP): chat, interview scheduling, ATS sync, analytics, notifications beyond basic logs.

## Roles
Student, TPO, Company, Admin.

## Functional Requirements (FR)
FR-1 Registration; FR-2 Login/Logout; FR-3 Jobs List; FR-4 Search/Filter; FR-5 Apply to Job; FR-6 TPO Create Job; FR-7 TPO Edit Job; FR-8 Close Job; FR-9 Company View Applications; FR-10 Admin Enable/Disable; FR-11 Event Logs; FR-12 Basic Audit.

## Non-Functional Requirements (NFR)
Security (auth, password strength, least privilege), Privacy (minimal PII, resume links not public), Performance (<2s typical pages), Reliability (no duplicate apply on refresh), Maintainability (clear structure, run steps), Accessibility (keyboard navigation, alt text), Logging (who/what/when).

## Assumptions
Web-first, English UI, campus Wi‑Fi, weekly postings, moderate usage.

## Constraints
Single GitHub repo, simple stack, internship timeline.

## Risks & Mitigations
Employer verification → TPO approval; resume privacy → restricted links; scope drift → enforce MVP list.
