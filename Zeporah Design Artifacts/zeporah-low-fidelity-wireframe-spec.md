# Zeporah Low-Fidelity Wireframe Production Spec

Zeporah's low-fidelity wireframes should prove the product structure, trust model, role boundaries, and first-session clarity before any mid- or high-fidelity visual decisions are made.[cite:9][cite:12][cite:17]

The goal of this phase is to produce a complete grayscale wireframe package that is sufficient to begin structured layout design, review flow coverage, and validate core product logic for the Family Coordinator and related helper roles.[cite:17][cite:9][cite:26]

## Phase objective

The low-fidelity phase should answer four product questions: what the core MVP flow is, what each major screen contains, how privacy and sharing are communicated, and how the product supports families through overwhelm without losing progress or control.[cite:9][cite:12][cite:17]

This phase is complete when the wireframes can support design review without any open uncertainty about page purpose, main actions, major branches, or role-based visibility differences.[cite:9][cite:12][cite:26]

## Product constraints

The low-fidelity set should be optimized for the Georgia-first MVP centered on a Family Coordinator handling responsibilities after a death, while still preserving the broader family-workspace model, support escalation rules, and role-based collaboration system defined in the wider workflow materials.[cite:17][cite:9]

Every screen should reinforce the same operating principles: private by default, one primary action per screen where possible, clear role boundaries, plain language, and no automatic sharing with a sponsor or partner organization.[cite:9][cite:16]

## Required templates

The wireframe system should use a limited set of reusable templates so the product reads as one calm, coherent workspace rather than a collection of unrelated pages.[cite:9][cite:16]

| Template ID | Template name | Usage | Required blocks |
|---|---|---|---|
| T1 | Setup screen | Onboarding and preferences | Header, title, reassurance text, input area, primary action, soft exit [cite:9] |
| T2 | Dashboard screen | Home and stage-specific priorities | Reassurance banner, 3 to 5 priority cards, later section, quick actions [cite:17][cite:9] |
| T3 | List screen | People, tasks, documents, contacts | Header, filter or tabs, list items, add action [cite:9][cite:17] |
| T4 | Detail screen | Task, person, document, resource detail | Summary block, access label, main content, contextual actions, related items [cite:9][cite:12] |
| T5 | Review / preview | Sharing, permissions, support requests | Summary panel, will share / will not share split, explicit confirmation [cite:9][cite:12] |
| T6 | Pause / support | Overwhelm, smaller-step, return-later | Acknowledgment text, practical choices, no forced disclosure [cite:12] |

## Required component kit

The low-fidelity component kit should include the trust and coordination primitives that appear repeatedly across the product, even if they are represented only as grayscale boxes, chips, and labels at this stage.[cite:9][cite:12]

- App header with back affordance and title.[cite:9]
- Primary navigation with Home, People and tasks, Find support, Private information, and Settings.[cite:9][cite:16]
- Primary card and secondary card.[cite:17]
- Role badges for Coordinator, Co-Coordinator, Helper, and Viewer.[cite:9]
- Access labels such as Only me, Selected people, Shared, and Request only.[cite:9]
- Task row with assignee, timing, state, and visibility.[cite:9][cite:12]
- “Why are we asking?” helper disclosure for sensitive optional fields.[cite:9]
- “Will be shared / Will not be shared” preview module.[cite:9][cite:12]
- Save, Not now, Return later, and Hide for now actions.[cite:12][cite:9]
- Urgent-help boundary alert block reserved for explicit safety cases only.[cite:12][cite:9]

## Screen groups

The completed low-fidelity package should be organized into seven groups so it is easy to review, assign, and later translate into mid-fidelity work.[cite:26][cite:9]

| Group | Range | Purpose |
|---|---|---|
| Entry and onboarding | LF-01 to LF-20 | Create or join a private family workspace [cite:9] |
| Home and guidance | LF-21 to LF-25 | Show the next right actions by stage [cite:17][cite:9] |
| People and permissions | LF-26 to LF-31 | Manage helpers, roles, and access [cite:9] |
| Tasks and updates | LF-32 to LF-39 | Coordinate responsibilities and communication [cite:9][cite:16] |
| Private information | LF-40 to LF-46 | Hold documents, contacts, decisions, notes, and expenses [cite:17][cite:16] |
| Pause and support | LF-47 to LF-57 | Preserve progress, reduce burden, and request support [cite:12] |
| Settings and trust | LF-58 to LF-63 | Control privacy, reminders, partner connection, and audit visibility [cite:9][cite:16] |

## Screen inventory

### Entry and onboarding

| Screen ID | Screen name | Template |
|---|---|---|
| LF-01 | Welcome / direct entry | T1 [cite:17] |
| LF-02 | Partner invitation landing | T1 [cite:9] |
| LF-03 | Family invitation landing | T1 [cite:9] |
| LF-04 | Privacy overview | T5 [cite:9] |
| LF-05 | Language and accessibility | T1 [cite:9] |
| LF-06 | Create account / sign in | T1 [cite:9] |
| LF-07 | Verification code | T1 [cite:9] |
| LF-08 | What Zeporah can and cannot do | T1 [cite:9][cite:17] |
| LF-09 | Start or join workspace | T1 [cite:9] |
| LF-10 | Choose role | T1 [cite:9] |
| LF-11 | Minimal setup | T1 [cite:9][cite:17] |
| LF-12 | What feels most helpful right now | T1 [cite:9] |
| LF-13 | Name workspace | T1 [cite:9] |
| LF-14 | Privacy baseline | T5 [cite:9] |
| LF-15 | Privacy receipt | T5 [cite:9] |
| LF-16 | Invite helper now or later | T1 [cite:9] |
| LF-17 | Invitation preview | T5 [cite:9] |
| LF-18 | Support preferences | T1 [cite:9] |
| LF-19 | Optional partner connection | T5 [cite:9] |
| LF-20 | Setup review / calm completion | T5 [cite:9][cite:16] |

### Home and guidance

| Screen ID | Screen name | Template |
|---|---|---|
| LF-21 | Home / recent loss | T2 [cite:17][cite:9] |
| LF-22 | Home / life after loss | T2 [cite:17] |
| LF-23 | Welcome-back state | T2 [cite:9] |
| LF-24 | First things first card detail | T4 [cite:17] |
| LF-25 | Stage switch confirmation | T5 [cite:9] |

### People and permissions

| Screen ID | Screen name | Template |
|---|---|---|
| LF-26 | People list | T3 [cite:9] |
| LF-27 | Person detail | T4 [cite:9] |
| LF-28 | Change access | T1 [cite:9] |
| LF-29 | Permission review | T5 [cite:9] |
| LF-30 | Remove access | T5 [cite:9] |
| LF-31 | Pending invite detail | T4 [cite:9] |

### Tasks and updates

| Screen ID | Screen name | Template |
|---|---|---|
| LF-32 | Task list | T3 [cite:9] |
| LF-33 | Task detail | T4 [cite:12][cite:9] |
| LF-34 | Create or edit task | T1 [cite:9] |
| LF-35 | Assign task | T1 [cite:12] |
| LF-36 | Assignment preview | T5 [cite:12] |
| LF-37 | Updates feed | T3 [cite:9] |
| LF-38 | Write family update | T1 [cite:9] |
| LF-39 | Update audience preview | T5 [cite:9] |

### Private information

| Screen ID | Screen name | Template |
|---|---|---|
| LF-40 | Private information hub | T2 [cite:16][cite:17] |
| LF-41 | Documents list | T3 [cite:17][cite:9] |
| LF-42 | Document detail | T4 [cite:9] |
| LF-43 | Private notes | T3 [cite:9] |
| LF-44 | Contacts directory | T3 [cite:17] |
| LF-45 | Decision log | T3 [cite:17] |
| LF-46 | Expense ledger | T3 [cite:17] |

### Pause and support

| Screen ID | Screen name | Template |
|---|---|---|
| LF-47 | Compassionate pause menu | T6 [cite:12] |
| LF-48 | Smaller-step planner | T6 [cite:12] |
| LF-49 | Ask someone I trust | T6 [cite:12] |
| LF-50 | Save / hide / return later | T6 [cite:12] |
| LF-51 | Support options | T3 [cite:12][cite:9] |
| LF-52 | Resource detail | T4 [cite:12] |
| LF-53 | Request a connection | T1 [cite:12] |
| LF-54 | Share preview | T5 [cite:12][cite:9] |
| LF-55 | Request sent | T5 [cite:12] |
| LF-56 | Request status | T4 [cite:12] |
| LF-57 | Urgent-help boundary | T6 [cite:12][cite:9] |

### Settings and trust

| Screen ID | Screen name | Template |
|---|---|---|
| LF-58 | Settings home | T3 [cite:9] |
| LF-59 | Privacy defaults | T1 [cite:9] |
| LF-60 | Support and recommendation preferences | T1 [cite:9][cite:12] |
| LF-61 | Reminder preferences | T1 [cite:9][cite:12] |
| LF-62 | Partner connection settings | T1 [cite:9] |
| LF-63 | Audit history summary | T3 [cite:9][cite:12] |

## Detailed screen production table

The table below is the direct blueprint for drawing the low-fidelity wireframes.[cite:26]

| ID | Screen | Purpose | Primary action | Key content blocks | Trust cues | Main branches | Roles |
|---|---|---|---|---|---|---|---|
| LF-01 | Welcome / direct entry | Start a private family workspace | Create a private family space | Headline, reassurance text, 3-value bullets | Private by default; save and return later [cite:17][cite:9] | Sign in, privacy explainer | Public / new user |
| LF-02 | Partner invitation landing | Start from sponsor invitation without implied sharing | Continue | Invitation summary, optionality copy, partner intro | Sponsor cannot see workspace by default [cite:9] | Privacy overview, save for later, wrong invitation | Invited public user |
| LF-03 | Family invitation landing | Join a family space with clear limits | Continue | Inviter, offered role, access preview | You will only see what is shared [cite:9] | Review access, decline | Invited public user |
| LF-04 | Privacy overview | Explain privacy model quickly | Continue | Family space vs organization diagram, short explainer | Exact review before any support sharing [cite:9] | Back, full summary | Any entering user |
| LF-05 | Language and accessibility | Set presentation preferences before details | Continue | Language, text size, simpler explanation, fewer reminders | Why are we asking? disclosures [cite:9] | Skip for now | Any entering user |
| LF-06 | Create account / sign in | Secure account access | Continue securely | Email or phone choice, login link | Secure your private space [cite:9] | Existing account, help | Any entering user |
| LF-07 | Verification code | Verify email or phone | Verify | Code field, resend, use different method | Message does not include family details [cite:9] | Invalid / expired states | Any entering user |
| LF-08 | What Zeporah can and cannot do | Set product boundaries | I understand, continue | Can / cannot blocks, emergency note | No medical, legal, tax, financial, or emergency advice [cite:9][cite:17] | Return | Any entering user |
| LF-09 | Start or join workspace | Confirm branch into create or join | Create my family space / Accept invitation | Branch-specific summary | Organization cannot view private workspace [cite:9] | Private use, decline, back | Invited or direct user |
| LF-10 | Choose role | Set operational role | Continue | Role cards, concise explanations | Does not determine legal authority [cite:9] | Back | New workspace user / invitee |
| LF-11 | Minimal setup | Gather only what helps begin | Continue | Loved one nickname, stage, optional location and relationship | Share only what helps us begin [cite:9][cite:17] | Save later, skip optional | Coordinator / starter |
| LF-12 | What feels most helpful right now | Seed guidance and support needs | Continue | Need cards, optional multi-select | Nothing goes to partner automatically [cite:9] | Overwhelm branch, skip | Coordinator / starter |
| LF-13 | Name workspace | Create safe shared label | Continue | Name field, suggestions | Shared-device privacy reminder [cite:9] | Use generic name | Coordinator |
| LF-14 | Privacy baseline | Establish defaults before sharing | Keep these private defaults | Defaults list, helper default, partner access model | Only you can see your space initially [cite:9] | Review and customize | Coordinator |
| LF-15 | Privacy receipt | Confirm trust settings | Continue | Privacy summary card | Partner access: none by default [cite:9] | Review access | Coordinator |
| LF-16 | Invite helper now or later | Offer delegation without pressure | Invite someone | Invite prompt, role options | You choose what they can see [cite:9] | Later, no one for now | Coordinator |
| LF-17 | Invitation preview | Confirm helper scope before send | Send invitation | Recipient, role, permissions, expiry, note | Will be able to / will not be able to [cite:9] | Edit access, cancel | Coordinator |
| LF-18 | Support preferences | Set support matching preferences | Save preferences | Local/virtual, faith/spiritual, cost, language, opt-out | Preferences do not share data by themselves [cite:9] | Skip for now | Coordinator |
| LF-19 | Optional partner connection | Explain sponsor relationship | Continue with this connection | Partner-boundary overview | Request-only support route [cite:9] | Use privately for now | Coordinator |
| LF-20 | Setup review / calm completion | End onboarding without pressure | Go to my next step | Role, stage, helper count, privacy, support, partner summary | You have started; that is enough for today [cite:17][cite:16][cite:9] | Review settings, save and leave | Coordinator |
| LF-21 | Home / recent loss | Surface today and this week priorities | Open top priority card | Reassurance banner, 3–5 priority cards, later section | Estate-heavy tasks deferred unless asked [cite:17][cite:9] | Invite helper, find support | Coordinator, scoped Co-Coordinator |
| LF-22 | Home / life after loss | Continue later-phase administration | Open top priority card | Timeline cards, follow-through tasks, reminders | Return when ready [cite:17][cite:16] | Support, later tasks | Coordinator, scoped Co-Coordinator |
| LF-23 | Welcome-back state | Re-enter gently after inactivity | Start with today | See what changed, not today | No need to catch up all at once [cite:9] | Home, changes view | Returning user |
| LF-24 | First things first card detail | Expand one roadmap item | Start this step | Task summary, why it matters, what can wait | One step at a time [cite:17][cite:16] | Task detail, support, pause | Coordinator |
| LF-25 | Stage switch confirmation | Confirm journey-stage change safely | Confirm stage change | Current vs new stage summary | Preserve data; do not notify others automatically [cite:9] | Keep current stage | Coordinator |
| LF-26 | People list | Manage collaborators | Invite someone | Active members, pending invites, access summaries | You choose what each person can see [cite:9] | Person detail, invitation | Coordinator, scoped Co-Coordinator |
| LF-27 | Person detail | View one member and their scope | Change access | Role, permissions, recent activity, status | Access can be changed or revoked [cite:9] | Remove access, resend invite | Coordinator, scoped Co-Coordinator |
| LF-28 | Change access | Edit permissions | Review changes | Access toggles, scope notes | Clear boundaries by content type [cite:9] | Permission review | Coordinator, scoped Co-Coordinator |
| LF-29 | Permission review | Confirm revised access | Confirm changes | Current vs proposed comparison | Recent-auth review for sensitive change [cite:9] | Back, notify affected user | Coordinator |
| LF-30 | Remove access | Revoke workspace visibility | Remove access | Reassignment prompt, warning copy | Immediate access end and audit record [cite:9] | Cancel | Coordinator |
| LF-31 | Pending invite detail | Manage outstanding invite | Resend invitation | Invite detail, expiry, offered role | No access before acceptance [cite:9] | Edit or cancel invite | Coordinator |
| LF-32 | Task list | Provide central coordination queue | Open task | Tabs for Today, This week, Later, Completed | Task visibility labels [cite:9] | Create task, filter | Coordinator, Co-Coordinator, Helper as permitted |
| LF-33 | Task detail | Work, delegate, or pause a task | Complete task / Continue | Summary, due context, visibility, related items | Who can see this task [cite:12][cite:9] | Assign, pause, support | Coordinator, Co-Coordinator, Helper as permitted |
| LF-34 | Create or edit task | Add responsibility to the plan | Save task | Title, category, assignee, due timing, visibility | Visibility set explicitly [cite:9] | Save later | Coordinator, Co-Coordinator, Helper as permitted |
| LF-35 | Assign task | Delegate one specific task | Review assignment | Person choice, scope, related items | No broader sharing by default [cite:12] | Assignment preview | Coordinator, Co-Coordinator |
| LF-36 | Assignment preview | Confirm task-only share | Send assignment | Task summary, recipient, visibility | Exact task scope preview [cite:12] | Save draft, cancel | Coordinator, Co-Coordinator |
| LF-37 | Updates feed | Share selected family updates | Post update | Updates list, audience snippets | Shared updates are selected, not assumed [cite:9] | Write update | Coordinator, Co-Coordinator |
| LF-38 | Write family update | Compose update | Share update | Message field, audience selector | Audience preview before sending [cite:9] | Save draft, preview | Coordinator, Co-Coordinator |
| LF-39 | Update audience preview | Confirm update recipients | Confirm sharing | Recipient groups, exclusions | Selected audience only [cite:9] | Edit audience | Coordinator, Co-Coordinator |
| LF-40 | Private information hub | Gather important records in one place | Open a section | Documents, notes, contacts, decisions, expenses | One private place to hold what matters [cite:16][cite:17] | Open section, add item | Coordinator, scoped collaborators |
| LF-41 | Documents list | Organize files | Upload document | File rows, labels, filters | Only me / shared labels [cite:17][cite:9] | Document detail | Coordinator, scoped collaborators |
| LF-42 | Document detail | View and manage one file | Update visibility | Metadata, note, related tasks | Opening a doc does not trigger sharing [cite:9][cite:12] | Share, archive | Coordinator, scoped collaborators |
| LF-43 | Private notes | Capture thoughts privately | Add note | Notes list, add action | Private notes stay private unless shared [cite:9] | Share intentionally | Coordinator, scoped collaborators |
| LF-44 | Contacts directory | Keep important contacts together | Add contact | Contact rows, category, source | Contact info remains private unless shared [cite:17][cite:9] | Contact detail | Coordinator, scoped collaborators |
| LF-45 | Decision log | Record decisions and follow-up | Add decision | Decision rows, owner, next step | Prevent conflicting memories and confusion [cite:17][cite:16] | Decision detail | Coordinator, scoped collaborators |
| LF-46 | Expense ledger | Track practical costs | Add expense | Expense rows, status, receipt slot | Shared expense history is controlled [cite:17] | Expense detail | Coordinator, scoped collaborators |
| LF-47 | Compassionate pause menu | Let users pause without penalty | Choose one next option | Acknowledgment text, six practical paths | Progress saved; no one contacted automatically [cite:12] | Smaller step, ask someone, support, save later, hide, urgent help | All authorized users |
| LF-48 | Smaller-step planner | Reduce one task into manageable action | Choose this step | Up to three smaller options, split task path | One step is enough for now [cite:12] | Different options, save later | All authorized users |
| LF-49 | Ask someone I trust | Request narrow help | Send task / Save draft | Existing person, one-task invite, private request template | You decide what they can see [cite:12] | No-one-to-ask branch, support options | Authorized users |
| LF-50 | Save / hide / return later | Preserve work while creating space | Save preference | Reminder choices, self-return option | Hidden item stays private and recoverable [cite:12] | Return to dashboard | All authorized users |
| LF-51 | Support options | Show relevant support resources | Request connection / Contact independently | Up to four resource cards, why am I seeing this, source, cost, accessibility | Nothing shared unless you choose to send a request [cite:12][cite:9] | Save, hide, resource detail | Authorized users |
| LF-52 | Resource detail | Explain one resource fully | Request connection / Contact independently | Description, fit, logistics, source | Transparent source and scope [cite:12] | Save, hide | Authorized users |
| LF-53 | Request a connection | Create support request | Send my request / Send to Coordinator for approval | Request type, contact method, time, optional message | Explicit limit on what is not included [cite:12] | Save draft, cancel | Coordinator; constrained variants for others |
| LF-54 | Share preview | Obtain explicit consent before send | Confirm and send | Recipient, will share, will not share columns | Exact reviewed fields only [cite:12][cite:9] | Edit request, cancel | Authorized sender |
| LF-55 | Request sent | Confirm transmission | View request status | Confirmation, summary, next steps | No response-time promise unless configured [cite:12] | Return to task, status | Authorized sender |
| LF-56 | Request status | Show limited follow-up state | Return to my task | Plain status, review what I shared | No staff notes or queue detail [cite:12][cite:9] | Withdraw if available, other options | Authorized sender / Coordinator |
| LF-57 | Urgent-help boundary | Handle explicit urgent help safely | Call emergency services | Safety message, hospice line if configured | Zeporah cannot monitor emergencies [cite:12][cite:9] | Return to app | Any user |
| LF-58 | Settings home | Centralize controls | Open a setting area | Privacy, support, reminders, partner, audit links | Families stay in control [cite:16][cite:9] | Open subsections | Coordinator, scoped collaborators |
| LF-59 | Privacy defaults | Edit sharing defaults | Save changes | Default visibility settings | New items inherit controlled privacy [cite:9] | Back | Coordinator |
| LF-60 | Support and recommendation preferences | Adjust support matching rules | Save preferences | Need, cost, language, virtual/local, opt-out | Preferences do not equal referrals [cite:9][cite:12] | Back | Coordinator |
| LF-61 | Reminder preferences | Control timing and channel | Save preferences | Essential / gentle / none, quiet hours | Privacy-preserving reminders [cite:9][cite:12] | Back | User |
| LF-62 | Partner connection settings | Manage sponsor relationship | Save | Connected/private mode, visibility explanation | Partner path never equals workspace access [cite:9] | Re-enable or disable request route | Coordinator |
| LF-63 | Audit history summary | Show major trust events | View event detail | Invitations, access changes, support requests | Clear record without exposing private content [cite:9][cite:12] | Event detail | Coordinator |

## Role overlays

Every low-fidelity screen should show a role note in the annotation layer because collaboration and support authority differ materially by role.[cite:9][cite:12]

| Role | Low-fi annotation rule |
|---|---|
| Coordinator | Full workspace control, invitations, privacy settings, external support requests with consent preview [cite:9][cite:12] |
| Co-Coordinator | Elevated but configurable access; external request authority off by default unless granted [cite:9][cite:12] |
| Helper | Assigned or shared work only; may draft or request help but should not transmit externally by default [cite:9][cite:12] |
| Viewer | Read-only updates or selected support information; no editing or external request transmission by default [cite:9][cite:12] |

## Drawing order

The drawing sequence should front-load the highest-risk structural decisions and leave lower-risk detail areas for later in the low-fi pass.[cite:26]

1. Entry and onboarding: LF-01 to LF-20.[cite:9]
2. Home and guidance: LF-21 to LF-25.[cite:17]
3. People and permissions: LF-26 to LF-31.[cite:9]
4. Tasks and updates: LF-32 to LF-39.[cite:9][cite:12]
5. Private information: LF-40 to LF-46.[cite:17]
6. Pause and support: LF-47 to LF-57.[cite:12]
7. Settings and trust: LF-58 to LF-63.[cite:9]

## Completion checklist

The low-fidelity phase should be considered complete only when the following conditions are satisfied.[cite:9][cite:12][cite:17]

- Every screen in the core inventory exists as a wireframe.[cite:9]
- Every screen has one clear primary action.[cite:9][cite:16]
- Every trust-sensitive screen includes visibility or sharing cues.[cite:9][cite:12]
- Recent loss and life-after-loss home variants both exist.[cite:17]
- Coordinator, Helper, and Viewer differences are represented in annotations.[cite:9][cite:12]
- The pause/support layer is shown as cross-product, not isolated.[cite:12]
- No screen depends on alarmist, shame-based, or marketplace-style UX patterns.[cite:16][cite:17][cite:12]
- The package is sufficient to move directly into mid-fidelity layout refinement without unresolved product-structure questions.[cite:26]
