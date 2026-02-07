# Release Blaster - 9 Day Sprint

## Day 1 (Feb 5) - Foundation

- [x] Create kaijutools org
- [x] Create kaijutools/projects (meta repo)
- [ ] Create kaijutools/integrations (OSS)
- [x] Create shipit/release-blaster-backend (private)
- [ ] Create shipit/release-blaster-frontend (private)
- [ ] Setup Supabase project
- [x] Deploy backend to Cloud Run (hello world)
- [ ] Deploy frontend to Vercel (landing page)
- [ ] Write blog: "Building Release Blaster: Day 1"
- [ ] Tweet: Day 1 progress

## Day 2 (Feb 6) - App Store Connect

- [ ] Research: App Store Connect API (JWT auth)
- [ ] Build: Backend POST /api/apps/:id/connect/appstore
- [ ] Build: Store encrypted credentials in Supabase
- [ ] Build: Fetch releases from App Store
- [ ] Build: Frontend connection form
- [ ] Test: End-to-end connection flow
- [ ] Extract: App Store adapter to kaijutools/integrations
- [ ] Commit: to OSS repo with README
- [ ] Tweet: Day 2 progress

## Day 3 (Feb 7) - Stripe Integration

- [ ] Research: Stripe API (OAuth or API key)
- [ ] Build: Backend POST /api/apps/:id/connect/stripe
- [ ] Build: Fetch revenue data by date range
- [ ] Build: Frontend Stripe connection form
- [ ] Build: Data pipeline (sync every hour)
- [ ] Build: Revenue timeline chart
- [ ] Extract: Stripe adapter to kaijutools/integrations
- [ ] Write blog: "Day 3 Update - Integrations Working"
- [ ] Tweet: Day 3 progress

## Day 4 (Feb 8) - Revenue Attribution

- [ ] Build: Release impact calculator (before/after comparison)
- [ ] Build: Statistical significance test (t-test)
- [ ] Build: Confidence scoring algorithm
- [ ] Build: Backend GET /api/releases/:id/impact
- [ ] Test: Verify math with sample data
- [ ] Build: Frontend display (big number + confidence)
- [ ] Extract: Algorithm to kaijutools/release-analysis
- [ ] Tweet: Day 4 progress

## Day 5 (Feb 9) - Claude API Integration

- [ ] Setup: Claude API credentials
- [ ] Build: Backend function to call Claude
- [ ] Write: Prompt template for release analysis
- [ ] Build: Structured output parsing
- [ ] Build: Response caching (don't regenerate)
- [ ] Handle: API errors, rate limits, timeouts
- [ ] Build: Frontend display (summary + insights)
- [ ] Write blog: "The Revenue Attribution Algorithm"
- [ ] Tweet: Day 5 progress

## Day 6 (Feb 10) - Polish Core Flow

- [ ] Build: Dashboard (list of releases)
- [ ] Build: Release detail view (full analysis)
- [ ] Build: Settings page (manage connections)
- [ ] Add: Loading states everywhere
- [ ] Add: Empty states (no data yet)
- [ ] Add: Error states (connection failed)
- [ ] Apply: Kaiju branding (logo, colors)
- [ ] Tweet: Day 6 progress

## Day 7 (Feb 11) - Firebase/Crashlytics

- [ ] Research: Firebase API or Sentry
- [ ] Build: Backend POST /api/apps/:id/connect/firebase
- [ ] Build: Fetch crash data by date range
- [ ] Build: Crash rate calculator (per session)
- [ ] Integrate: Crash data into release analysis
- [ ] Update: Claude prompt to include crashes
- [ ] Test: Analysis mentions crash spikes
- [ ] Extract: Firebase adapter to kaijutools/integrations
- [ ] Tweet: Day 7 progress

## Day 8 (Feb 12) - Launch Prep

- [ ] Write: Landing page copy (clear value prop)
- [ ] Record: 2-minute demo video (Loom)
- [ ] Write: HN launch post (draft)
- [ ] Write: Twitter launch thread (draft)
- [ ] Prepare: Screenshots for launch
- [ ] Setup: PostHog or Simple Analytics
- [ ] Setup: Sentry error tracking
- [ ] Write blog: "48 Hours to Launch"
- [ ] Tweet: Day 8 progress

## Day 9 (Feb 13) - Soft Launch

- [ ] Fix: Top 3 critical bugs
- [ ] Test: Have 3 friends sign up and try it
- [ ] Fix: Based on their feedback
- [ ] Launch: Soft launch on Twitter (personal network)
- [ ] Email: 10 mobile dev friends (beta testers)
- [ ] Monitor: Signups, errors, feedback
- [ ] Triage: What's broken? What's confusing?
- [ ] Tweet: Day 9 progress

## Day 10 (Feb 14) - LAUNCH DAY

- [ ] Fix: Top 3 bugs from yesterday
- [ ] Fix: Top 2 UX issues from yesterday
- [ ] Test: Happy path works perfectly
- [ ] Post: Hacker News
- [ ] Post: Twitter thread (full launch)
- [ ] Post: r/reactnative
- [ ] Post: IndieHackers
- [ ] Write blog: "I Built Release Blaster in 9 Days"
- [ ] Monitor: Comments, signups, feedback
- [ ] Respond: To every question/comment

## BLOCKED / QUESTIONS

(Add items here when stuck)

## NOTES

- Moving to Houston: Feb 15-25 (10 days blocked)
- Must ship by Feb 14 EOD
- Blog all at: shipatwarp.com
- Product at: kaiju.tools

## DONE

(Move completed days here for motivation)
