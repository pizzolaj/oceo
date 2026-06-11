# OCEO 2.0 — Vice Chair Walkthrough
### Speaking notes for the design review

*Spoken lines are in quotes. Square brackets are your screen cues. Parentheticals are the requirement each screen ties back to — drop them in only if challenged.*

---

## Opening (before you share the screen)

"Thank you. What I'm going to show you today is OCEO 2.0 — the relationship platform we've designed for the Office of the CEO.

Everything in it comes from one thing you told us in the workshop: you need *everything we know about a client, in a concise one- or two-pager* — accurate, and fast. And you want to *talk to it* the way you'd talk to a person, not dig through five systems.

So I've organized the walkthrough around your three moments: **before a meeting, during the meeting, and after it.** Let me start where your day starts."

*(Anchors: Personas §1 — "need to know everything we know about the client in a one/two-pager"; Design Principles §19.)*

---

## 1. Portfolio Landing — "your home base"

**[Open: Portfolio Landing]**

"This is your home. Notice the first thing isn't a wall of data — it's **what needs your attention**: an overdue task, a meeting in a few days with no brief yet, a client you met yesterday that still needs a note.

Below that is **your book** — every client you cover, sorted by revenue. And an important point: you only ever see *your* coverage clients. The platform is permission-aware by design."

*(Anchors: Screen #1 Portfolio Landing; Permission model §13 — "VC sees only their coverage clients"; Issue Identification §2.)*

> Transition: "Let's open a client."

---

## 2. Client 360 — "the one-pager you asked for"

**[Open: Client 360 — Northwind Holdings]**

"This is the heart of it — the single client page. At the top: who they are, what they're worth to CIBC across the year, your coverage role, and the lines of business we're active in.

Right beneath it is an **AI situation summary** — the headline of what's happening with this client. And every figure is **cited to the system it came from**, so you can rely on it in the room.

Everything else — holdings, the relationship map, notes and tasks, interaction history, deals, cases — sits in tabs, so the page stays a *one-pager* instead of a scrolling marathon.

The piece that's genuinely new is **Connections** — subsidiaries, the family office, the executives, and lateral ties like vendors and competitors. That's the relationship picture no single system gives you today."

*(Anchors: Screens #2–9; Header fields §3.1; Cited AI / source links §7 + §19; "one/two-pager mentality" §19.1; Connections 3-tier model §11.)*

> Transition: "Now — the part that replaces the ChatGPT habit."

---

## 3. CAI — "your grounded assistant"

**[Open: Ask CAI]**

"Today, the team preps with ChatGPT. The problem is it doesn't know CIBC's own interaction history, and nothing you put into it is secure.

This is **CAI** — the same conversational feel, but every answer is grounded in our internal systems, cited, and **nothing leaves the bank**.

You can ask it anything across your book — *'who haven't I met with in 90 days,' 'summarize this relationship,' 'draft talking points for my meeting'* — and it answers with its sources attached. It's available on every screen, and it keeps your past conversations.

We've also given it the option to bring in the **public web** when you want market context — clearly separated and still cited — and a **deeper research mode** for when you want a fuller brief."

*(Anchors: Personas §1 — "current practice uses ChatGPT but lacks CIBC-specific interaction history"; AI = conversational, cited §19.3. Note for you: web search + deep research are enhancements beyond the original brief, added at the client's request.)*

> Transition: "That's walking in prepared. Here's how the meeting itself is supported."

---

## 4. Meeting Prep (AI) — "one click, not a project"

**[Reference: the Meeting Prep button on Client 360]**

"Before a meeting, one button assembles the brief: last interactions, the client's objectives, the balance sheet, deal history and pipeline, talking points — all with links back to source.

One click. Modeled on the Capital Markets CEO briefing note your team already trusts. The aim is your **48-hour brief turnaround** — OCEO curates it, you consume it."

*(Anchors: Meeting Prep §7 — "one-click generation," contents list; Flow A SLA §8 — "48 hours for a complete brief.")*

---

## 5. During the meeting — "answer on the spot"

**[Stay on Client 360]**

"In the room, this same profile is live. So when a client asks a cross-LOB question, you can answer it then and there, instead of *'let me get back to you.'* On mobile, this is the condensed version you'd glance at between meetings — that's a fast-follow."

*(Anchors: Flow B §8 — "answer cross-LOB questions in real time"; Mobile eCRM §2; Mobile screens #19–21 are next-phase.)*

> Transition: "And after the meeting, the system carries the follow-through."

---

## 6. Notes & Tasks — "capture and assign"

**[Open: Tasks]**

"After a meeting, the platform **nudges** you to capture notes — and turns follow-ups into tasks you can assign.

Here's the task view: what's overdue, what's due this week, what's waiting on someone else. Status at a glance, not buried inside notes the way it is today."

*(Anchors: Flow C §8 — structured notes + task assignment; post-meeting nudge §19.6; Task List #15.)*

---

## 7. The RM loop — "email, not another login"

**[Open: RM touchpoints email]**

"When a task goes to a relationship manager who doesn't live in the CRM, they get an **email they can act on** — no login required — and their response loops the status back automatically.

Email stays the channel, exactly as you asked — we're not adding another tool people have to check."

*(Anchors: Task notifications §14; RM has no CRM login §1; "email is the preferred channel" §19.7; Email screens #22–23.)*

---

## 8. Executive Dashboard — "the portfolio view" *(fast-follow)*

**[Open: Dashboard]**

"Stepping up a level — your whole book in one table, sortable by revenue, with financials and concentration at a glance.

I'll flag this honestly: this is more a portfolio-management and OCEO tool than a daily Vice Chair need — which is why we've sequenced it as a fast-follow rather than day-one."

*(Anchors: Dashboard fields + sortable-by-revenue §4; MoSCoW — Executive Dashboard is "Could Have / Next.")*

---

## 9. Global Search — "find anything"

**[Open: Global Search]**

"And tying it all together — search across everything: clients, people, deals, notes. With fuzzy matching that understands parent and portfolio companies, so you don't need the exact legal name."

*(Anchors: Fuzzy search §4 + Screen #24.)*

---

## Close

"So that's the arc: **walk in prepared, answer anything in the room, and let the system carry the follow-up.**

None of this is net-new data — it's what's already across ECIF, the CRMs, CMCR and the rest, *aggregated, cited, and shaped* into the one-pager and the conversation you told us you wanted.

One note on what you're seeing today: the names and numbers on screen are illustrative sample data — the *structure, the fields, and the data sources* are all drawn straight from the requirements. Happy to go as deep as you'd like on any screen."

---

## If they ask — quick anchors

- **"Is it secure / where does the data come from?"** → "Everything is grounded in CIBC's internal systems and cited to source — ECIF, the LOB Salesforce orgs, CMCR, CEAS. Unlike ChatGPT, nothing leaves the bank."
- **"How current is the data?"** → "Each section shows an 'as of' date and the source it pulled from, so you always know how fresh it is."
- **"Will OCEO see my private notes?"** → "No. The permission model separates executive/sensitive notes from what OCEO can see — that's built into the design." *(§13, §15)*
- **"Why is it red?"** → "It's CIBC's brand red, used as an accent on a neutral, executive base — calm to read for long sessions, unmistakably ours."
- **"What's day-one vs. later?"** → "Day-one is the client one-pager, CAI, notes, tasks and the RM loop. The dashboard and the mobile experience are the fast-follow." *(MoSCoW §2)*
