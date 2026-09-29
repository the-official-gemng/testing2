# Office Hours Booking

A web app for booking after-school office hour periods with teachers, built and maintained by the Programming Club.

## Features (planned)

- [ ] Teachers publish available office hour slots
- [ ] Students browse and book / cancel a slot
- [ ] Prevent double-booking
- [ ] Confirmation (email or in-app)
- [ ] Teacher/admin dashboard

See [docs/requirements.md](docs/requirements.md) for details.

## Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) (App Router) + TypeScript
- **Styling:** Tailwind CSS
- **Backend / DB / Auth:** TBD, to be decided by the club (see the "Decide backend" issue)
- **Hosting:** TBD (Vercel is the easiest fit for Next.js)

## Getting Started

Requirements: [Node.js](https://nodejs.org/) 20 or newer, and Git.

```bash
# 1. Clone the repo
git clone https://github.com/<owner>/office-hours-booking.git
cd office-hours-booking

# 2. Set up environment variables
cp .env.example .env.local
# then open .env.local and fill in the values (ask a maintainer)

# 3. Install dependencies and run
npm install
npm run dev
```

Open http://localhost:3000 in your browser.

> First-time setup only: if the repo does not contain a Next.js project yet, a maintainer runs
> `npx create-next-app@latest . --typescript --tailwind --app --eslint`
> in the repo root and commits the result. Everyone else just pulls.

## How to Contribute

Read [CONTRIBUTING.md](CONTRIBUTING.md). Short version: pick an issue, make a branch, open a pull request.

## Team

- Maintainers: @your-username, @co-leader-username
- Members: Programming Club

## Privacy

This project may handle student and teacher information. Never commit real names, emails, schedules, or credentials. Use fake data for development.
