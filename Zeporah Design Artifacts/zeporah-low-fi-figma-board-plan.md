# Zeporah Low-Fidelity Figma Board Plan

This document translates the low-fidelity production spec into a Figma-ready working board structure so the wireframes can be created in an orderly, reviewable sequence.[cite:9][cite:12][cite:17]

The plan is organized to support a gated product-design workflow: board setup first, frame inventory second, drawing sequence third, and review passes last.[cite:26]

## Board setup

Create one Figma file for low-fidelity wireframes and split it into pages that mirror the product architecture rather than internal workflow-document labels.[cite:9][cite:16]

### Recommended Figma pages

| Page | Purpose |
|---|---|
| 00 Foundations | Notes, principles, component key, navigation model [cite:16][cite:9] |
| 01 Entry and onboarding | Welcome, privacy, setup, helper invite, completion [cite:9] |
| 02 Home and guidance | Recent loss home, life-after-loss home, welcome back, stage transitions [cite:17][cite:9] |
| 03 People and permissions | Members, roles, access editing, invite states [cite:9] |
| 04 Tasks and updates | Task list/detail, assignment, updates feed, update preview [cite:9][cite:12] |
| 05 Private information | Documents, notes, contacts, decision log, expense ledger [cite:17][cite:16] |
| 06 Pause and support | Pause, smaller step, support options, support requests, urgent help [cite:12] |
| 07 Settings and trust | Privacy defaults, reminders, partner settings, audit summary [cite:9][cite:12] |
| 08 Review and flows | End-to-end stitched flows, branch reviews, comments, unresolved questions [cite:26] |

## Foundation page

The first page should not contain polished design. It should function as a working reference layer that keeps the low-fi effort consistent while screens are being drawn.[cite:26][cite:16]

### Frames to create on 00 Foundations

- Product principles: private by default, one primary action per screen, plain language, no alarmist UX.[cite:9][cite:16][cite:17]
- Primary navigation model: Home, People and tasks, Find support, Private information, Settings.[cite:9][cite:16]
- Role key: Coordinator, Co-Coordinator, Helper, Viewer.[cite:9]
- Access key: Only me, Selected people, Shared, Request only.[cite:9]
- Template key: setup, dashboard, list, detail, review, pause-support.[cite:9][cite:12]
- Annotation key: purpose, role, trust cue, branch, open question.[cite:26]

## Page-by-page frame checklist

Each screen should be created as a named frame with a left-side annotation rail or adjacent note card containing purpose, primary action, trust cues, and branches.[cite:26][cite:9]

### 01 Entry and onboarding

| Order | Frame name | Screen ID | Notes |
|---|---|---|---|
| 1 | Welcome / direct entry | LF-01 | Default first-touch screen for direct users [cite:17] |
| 2 | Partner invitation landing | LF-02 | Optional sponsor path [cite:9] |
| 3 | Family invitation landing | LF-03 | Existing coordinator invite path [cite:9] |
| 4 | Privacy overview | LF-04 | 20-second trust explainer [cite:9] |
| 5 | Language and accessibility | LF-05 | Presentation preferences first [cite:9] |
| 6 | Create account / sign in | LF-06 | Private-space access gate [cite:9] |
| 7 | Verification code | LF-07 | Email or phone verification [cite:9] |
| 8 | What Zeporah can and cannot do | LF-08 | Boundary-setting screen [cite:9][cite:17] |
| 9 | Start or join workspace | LF-09 | Branch confirmation [cite:9] |
| 10 | Choose role | LF-10 | Operational role only [cite:9] |
| 11 | Minimal setup | LF-11 | Essential inputs only [cite:9][cite:17] |
| 12 | What feels most helpful right now | LF-12 | Need-selection and overwhelm path [cite:9] |
| 13 | Name workspace | LF-13 | Shared label with privacy reminder [cite:9] |
| 14 | Privacy baseline | LF-14 | Private-by-default settings [cite:9] |
| 15 | Privacy receipt | LF-15 | Trust summary [cite:9] |
| 16 | Invite helper now or later | LF-16 | Delegation prompt [cite:9] |
| 17 | Invitation preview | LF-17 | Scope confirmation [cite:9] |
| 18 | Support preferences | LF-18 | Matching preferences only [cite:9] |
| 19 | Optional partner connection | LF-19 | Sponsor-relationship explanation [cite:9] |
| 20 | Setup review / calm completion | LF-20 | One-next-step completion screen [cite:17][cite:9] |

### 02 Home and guidance

| Order | Frame name | Screen ID | Notes |
|---|---|---|---|
| 1 | Home / recent loss | LF-21 | Primary MVP dashboard [cite:17] |
| 2 | Home / life after loss | LF-22 | Follow-through dashboard [cite:17] |
| 3 | Welcome-back state | LF-23 | Re-entry state [cite:9] |
| 4 | First things first card detail | LF-24 | Expanded roadmap item [cite:17] |
| 5 | Stage switch confirmation | LF-25 | Safe stage adjustment [cite:9] |

### 03 People and permissions

| Order | Frame name | Screen ID | Notes |
|---|---|---|---|
| 1 | People list | LF-26 | Active and pending members [cite:9] |
| 2 | Person detail | LF-27 | Role and access detail [cite:9] |
| 3 | Change access | LF-28 | Permission editing form [cite:9] |
| 4 | Permission review | LF-29 | Current vs proposed [cite:9] |
| 5 | Remove access | LF-30 | Revocation confirmation [cite:9] |
| 6 | Pending invite detail | LF-31 | Expiry, resend, cancel [cite:9] |

### 04 Tasks and updates

| Order | Frame name | Screen ID | Notes |
|---|---|---|---|
| 1 | Task list | LF-32 | Today, This week, Later, Completed [cite:9] |
| 2 | Task detail | LF-33 | Work, delegate, or pause [cite:12][cite:9] |
| 3 | Create or edit task | LF-34 | Task authoring form [cite:9] |
| 4 | Assign task | LF-35 | Narrow delegation flow [cite:12] |
| 5 | Assignment preview | LF-36 | Task-only share preview [cite:12] |
| 6 | Updates feed | LF-37 | Family communication stream [cite:9] |
| 7 | Write family update | LF-38 | Compose update [cite:9] |
| 8 | Update audience preview | LF-39 | Audience confirmation [cite:9] |

### 05 Private information

| Order | Frame name | Screen ID | Notes |
|---|---|---|---|
| 1 | Private information hub | LF-40 | One-place hub [cite:16][cite:17] |
| 2 | Documents list | LF-41 | Secure document area [cite:17][cite:9] |
| 3 | Document detail | LF-42 | Metadata and visibility [cite:9] |
| 4 | Private notes | LF-43 | Private note list [cite:9] |
| 5 | Contacts directory | LF-44 | Important contacts [cite:17] |
| 6 | Decision log | LF-45 | Shared decisions and follow-up [cite:17][cite:16] |
| 7 | Expense ledger | LF-46 | Practical costs tracking [cite:17] |

### 06 Pause and support

| Order | Frame name | Screen ID | Notes |
|---|---|---|---|
| 1 | Compassionate pause menu | LF-47 | Cross-product entry point [cite:12] |
| 2 | Smaller-step planner | LF-48 | Break down work [cite:12] |
| 3 | Ask someone I trust | LF-49 | Family-help path [cite:12] |
| 4 | Save / hide / return later | LF-50 | Preserve work and reduce pressure [cite:12] |
| 5 | Support options | LF-51 | Show up to four resources [cite:12][cite:9] |
| 6 | Resource detail | LF-52 | Explain one support option [cite:12] |
| 7 | Request a connection | LF-53 | Controlled support request [cite:12] |
| 8 | Share preview | LF-54 | Explicit consent step [cite:12][cite:9] |
| 9 | Request sent | LF-55 | Confirmation state [cite:12] |
| 10 | Request status | LF-56 | Limited status updates [cite:12] |
| 11 | Urgent-help boundary | LF-57 | Explicit emergency limitations [cite:12][cite:9] |

### 07 Settings and trust

| Order | Frame name | Screen ID | Notes |
|---|---|---|---|
| 1 | Settings home | LF-58 | Settings index [cite:9] |
| 2 | Privacy defaults | LF-59 | Default sharing controls [cite:9] |
| 3 | Support and recommendation preferences | LF-60 | Matching controls [cite:9][cite:12] |
| 4 | Reminder preferences | LF-61 | Quiet-hours and frequency [cite:9][cite:12] |
| 5 | Partner connection settings | LF-62 | Sponsor relationship mode [cite:9] |
| 6 | Audit history summary | LF-63 | Trust-event overview [cite:9][cite:12] |

## Annotation model

Every frame should include a compact annotation block so the wireframes remain useful for product and future prototype planning instead of becoming unlabeled boxes.[cite:26]

Use this annotation stack on every frame:
- Purpose.
- Primary user role.
- Primary action.
- Secondary actions.
- Trust cue(s).
- Main branch / next screen.
- Open question, only if unresolved. [cite:26][cite:9]

## Flow stitching page

The review page should assemble the most important end-to-end journeys as stitched horizontal flows so gaps become obvious before mid-fidelity work begins.[cite:26]

### Required stitched flows

1. Direct new user to first dashboard: LF-01 → LF-04 → LF-05 → LF-06 → LF-07 → LF-08 → LF-09 → LF-10 → LF-11 → LF-12 → LF-13 → LF-14 → LF-15 → LF-16 → LF-18 → LF-20 → LF-21.[cite:9][cite:17]
2. Invite helper flow: LF-21 → LF-26 → LF-16 or LF-31 → LF-17.[cite:9]
3. Task-to-pause-to-support flow: LF-32 → LF-33 → LF-47 → LF-48 or LF-49 or LF-51 → LF-53 → LF-54 → LF-55 → LF-56.[cite:12][cite:9]
4. Private information flow: LF-21 → LF-40 → LF-41 or LF-43 or LF-45 or LF-46.[cite:17][cite:16]
5. Welcome-back flow: LF-23 → LF-21 or LF-22.[cite:9]

## Production sequence

The lowest-risk way to build the board is to complete frames in structured batches rather than moving randomly across the product.[cite:26]

### Batch 1: onboarding spine

Create LF-01 through LF-20 first because they define the privacy model, initial role logic, and first-time setup promise for the rest of the product.[cite:9][cite:17]

### Batch 2: dashboard and first-work screens

Create LF-21 through LF-25 and LF-32 through LF-33 next because they define the user's first meaningful working experience after setup.[cite:17][cite:12]

### Batch 3: collaboration and private information

Create LF-26 through LF-31 and LF-40 through LF-46 after the dashboard is stable because these sections inherit the trust and visibility logic set earlier.[cite:9][cite:16]

### Batch 4: compassionate pause and support

Create LF-47 through LF-57 after task detail is stable because these screens are cross-product interventions that depend on established task and permission context.[cite:12]

### Batch 5: settings and trust review

Create LF-58 through LF-63 last because they consolidate rules established elsewhere rather than inventing new primary behavior.[cite:9]

## Review passes

The low-fidelity board should go through four review passes before it is declared complete.[cite:26]

| Pass | Focus | Questions |
|---|---|---|
| Pass 1 | Structural coverage | Do all required screens exist, and do branches connect cleanly? [cite:26] |
| Pass 2 | Trust and privacy | Does every sensitive screen explain who can see what and what is shared? [cite:9][cite:12] |
| Pass 3 | Role logic | Are Coordinator, Helper, and Viewer differences actually represented? [cite:9][cite:12] |
| Pass 4 | Emotional fit | Does the product remain calm, dignified, and non-alarmist across all key flows? [cite:16][cite:17] |

## Low-fi done criteria

The Figma low-fidelity board should be considered complete when the following are true.[cite:9][cite:12][cite:17]

- All 63 planned frames exist.[cite:9]
- The five stitched flows exist on the review page.[cite:26]
- Every frame includes annotation.[cite:26]
- Every privacy-sensitive action has a review or visibility cue.[cite:9][cite:12]
- Recent loss and life-after-loss home variants are both represented.[cite:17]
- The compassionate-pause layer clearly appears as part of the product system rather than a separate module.[cite:12]
- No unresolved product-structure issues block mid-fidelity layout work.[cite:26]
