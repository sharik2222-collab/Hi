# UAE FM Job Search Automation Toolkit

A single-page, browser-based toolkit to run a focused UAE facilities management (FM / IFM) job search. It helps you:

- build repeatable job-board searches for UAE FM roles,
- monitor target FM employers and direct career pages,
- track applications locally in your browser,
- export your tracker to CSV, and
- generate tailored recruiter or hiring-manager outreach messages.

> Scope note: this project is designed for facilities management job hunting in the UAE, including Facilities Manager, FM Supervisor, MEP / Hard FM Engineer, Soft Services Manager, HSE / QHSE FM, and CAFM / Helpdesk Coordinator roles.

## How to use it

Open the static page in your browser:

```bash
xdg-open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Daily workflow

1. **Build searches** for your role cluster and emirate.
2. **Open each generated job-board link** and save alerts on the third-party job sites.
3. **Add shortlisted roles** to the local application tracker.
4. **Tailor your CV** using the keyword bank before applying.
5. **Copy a LinkedIn outreach message** and send it to a relevant recruiter, hiring manager, or FM operations leader.
6. **Follow up** on tracked applications after 4 days, then again after 10 days if there is no response.

## Recommended weekly targets

- 25 quality applications or direct career-page submissions.
- 25 recruiter / hiring-manager messages.
- 10 referral conversations with UAE FM professionals.
- 2 CV variants: one for hard FM / MEP and one for soft services / operations.

## Included UAE FM target-company map

The page includes direct links or search prompts for companies commonly associated with UAE FM hiring, including:

- Emrill
- Imdaad
- Khansaheb FM
- Farnek
- Enova
- EFS
- Transguard
- Al Shirawi

Always verify job authenticity before sharing personal documents, passport details, or payment information.

## Data storage

The application tracker uses `localStorage`, so your data stays in your browser. Export CSV weekly if you need a backup or plan to change devices.

## Customization ideas

- Add your preferred recruitment agencies to the target-company table.
- Update the ATS keyword bank for your exact FM specialization.
- Add salary expectations, visa status, or notice-period columns to the tracker.
- Create separate CV variants for Dubai, Abu Dhabi, and UAE-wide searches.
