# Pareto Talent Bootcamp: Day 3, Second Brain Systems

**Instructor:** Ivan Bunin (CEO, Pareto Talent)
**Length:** about 2h10m (theory, a live demo, and Q&A)

---

## 1. The main idea in one paragraph

A better prompt does not make AI useful. **Context** does. A study of 350 entrepreneurs found that the average founder keeps about **14 different systems/processes in their head**. A **Second Brain** gets that knowledge out of the founder's head and into a structured knowledge base that AI can navigate. You then connect that knowledge base to the founder's apps, so the AI can **act** on it and not just talk. Your job as an EA is to build and maintain this system.

---

## 2. The two-layer architecture

| Layer | What it is | Examples | Where it lives |
|---|---|---|---|
| **Context layer** (static) | Everything the AI should *know* | SOPs, org charts, contracts, strategy docs, transcripts, books, podcasts | A **folder** of Markdown files, usually a Google Drive folder synced to your computer |
| **Action layer** (dynamic) | Everything the AI can *do* | Gmail, Calendar, CRM (GoHighLevel), Stripe, Slack, Fathom, Plaud | **Connectors / MCP / API** inside Claude |

- **Interface:** Claude (Desktop app, preferably **Claude Code**). You connect the folder (context) and the connectors (actions) in the same session.
- **Output:** Claude can turn all of this into **Artifacts**: small web pages/apps such as reports, KPI dashboards, and morning briefs. They are shareable by link and usually better than a PDF or a Doc.
- **Context multiplication:** the action layer can *feed* the context layer. For example, "go through my last 10 calls and save the key points to my second brain". **This doesn't happen automatically.** Connecting Gmail doesn't mean Claude "knows" your email. It only acts when you ask, or when a scheduled **routine** runs (Ivan has a "Daily Extract" routine at 8 AM).

---

## 3. What goes into the context layer

1. **SOPs (Standard Operating Procedures):** written step-by-step instructions for how something is done, so the result is the same every time. Most founders keep these in their head, and **writing them down is part of your job**. Rule of thumb: *if you do something twice, it needs an SOP.* An SOP is one of the best things you can give AI, because the AI then follows *your* process and doesn't have to guess.
2. **Company / founder info:** org charts (who does what), so the AI can say "ask this person".
3. **Contracts and offers:** what's promised to clients and team, the terms, and whether something violates them.
4. **Strategy docs:** quarterly/annual goals and strategy session transcripts, so the AI can say "this is outside our strategy".
5. **Books, podcasts, interviews:** material the company already produced.
6. **Call transcripts.**

---

## 4. Access and trust (the soft skill part)

- Founders often **won't give you everything on day 1** (especially Gmail). They worry you lack context and can't write in their voice. **The second brain fixes both problems.**
- **Always give the reason and the benefit when you ask for access.** Not *"Can I have your Gmail?"* but *"If I get Gmail access I can extract everything into the second brain, get you to inbox zero, and leave you only the emails that are real tasks."* That makes the request a trade.
- **Build access in stages:**
  1. **Early:** read-only, limited to the task at hand (ask for an export or a screenshot instead of full access).
  2. **As trust grows:** explain that limited access means you can't see the big picture or be proactive. Then you get the second brain, Gmail, and more.
  3. **Later:** sensitive or irreversible things like financials, client-facing systems, and mass emails.
- Treat the business like the founder's baby: present a plan, get approval, then act. Many founders have been burned before, and you earn trust through repeated results.

---

## 5. How the folder is structured (the "Obsidian model")

Ivan borrows **three ideas** from Obsidian, a Markdown knowledge-base app:

1. **Front matter:** a small table at the **top of each Markdown file** with fields like category, created/updated date, version, status (active/archived), audience, and related files. It lets the AI understand what a file is about **without reading the whole file**, which saves tokens.
2. **Wiki links** (`[[Other File]]`): links between files. If the marketing file mentions the sales script, it links to it, so the AI knows a related doc exists. This is how the AI "connects dots". For example, it remembered that a contact in Buenos Aires had offered to babysit when Ivan planned a trip there.
3. **MOC (Map of Content):** a README / table of contents **inside every folder** that lists what's in the folder. **Claude builds these automatically.**

**How the AI navigates:** enter folder → read the MOC → open the right file → read its front matter → follow wiki links only if they're relevant. It reads file by file and never loads everything at once, which makes it efficient.

**About Obsidian:** Obsidian is **optional**. It's only a *viewer* that shows the folders and the "graph" of linked notes (the "brain"). The second brain itself is just a folder of structured Markdown files. "Obsidian second brain" is a misleading term.

**Markdown** is the best format for AI and is very lightweight. Ivan's whole company brain is only about 200 MB.

---

## 6. Step-by-step build (what Ivan demoed)

1. **Create a folder.** Google Drive (install **Google Drive for Desktop** so it syncs locally) if it will be shared with the founder/team, or a plain local folder if it's just for you. Log in with the corporate account the founder gives you.
2. **Install Obsidian** (optional, for visualization).
3. **Open the Claude Desktop app → Claude Code.** Claude Code is paid and more powerful because it can create folders/files and run commands. The first time, it asks you to install **Git** (one-time setup; a tutorial video was shared).
   - *Free alternative:* in Claude chat, go to **Customize → Connectors** and add the **File System** connector (lets Claude create files/folders) or the **Google Drive** connector (can create files, maybe not folders). Some students got a "server disconnected" error, and Ivan admitted he hadn't fully tested chat. Cowork mode can also open a folder.
4. **Point Claude Code at the folder** (Open Folder → select it → "trust workspace").
5. **Pick a permission mode.** There are 5 modes: *Auto*, *Manual* (approve everything), *Accept edits*, *Plan* (thinks deeply and proposes a plan first, good for big projects), and *Bypass permissions* (does everything without asking; Ivan used this). Model choice: don't overthink it, and avoid the most expensive models if you're on a limited plan.
6. **Paste the Second Brain prompt** Ivan shared. There are **two versions**:
   - **Company** second brain (the one he demoed)
   - **Entrepreneur-as-a-person** second brain (covers multiple businesses, personal docs, taxes, travel, etc.)
7. **Answer the intake interview (a "reverse interview")**, where Claude asks the questions. **Dictate, don't type** (Wispr Flow or the built-in mic). The sections cover: company name/what it does/stage/revenue/12-month goal → business model/ICP/sales cycle → headcount, departments, leadership, key people → key clients/investors/advisors → meetings and reporting cadence → tools (Gmail, Slack, Notion, CRM, Stripe…) → what to include, sensitive data, jargon → "what lives in your head the most?" It takes about 10–15 min if you know the answers, up to about 1 hour if you don't.
   - You can answer many of these yourself (from the website, Slack, etc.). Skip what you don't know.
   - Or **interview the founder on a recorded call** and feed the transcript to Claude.
   - **There is no universal template.** Every second brain is unique, and that's why the interview matters.
8. **Claude proposes a plan** (folder structure, MOCs, templates with front matter and links, an extraction to-do list). Nothing is created yet. You say *"go ahead and build everything"*, and it creates the full structure (about 71 folders in the demo) plus a **CLAUDE.md** file with rules for how to treat the folder as a second brain.
9. **Open it in Obsidian** (Manage Vaults → Open folder as vault) to see the graph.
10. **Populate the context.** Drag files **into Claude** (not into the folder) and say *"process this and save it in my second brain"*. Ivan's demos: a YouTube interview transcript, SOPs exported as PDF, a contractor agreement, and a CSV of Stripe/GoHighLevel transactions ("analyze LTV, average vs median, most popular products, save to second brain").
11. **Connect apps (action layer)** and extract from them. Example: *"You're connected to my Fathom. Go through my last 10 calls, extract only the processed insights (not raw transcripts), and save them to my second brain."* You can run several sessions in parallel.
12. **Automate with Routines** (scheduled tasks in Claude), for example a daily extract of promises, tasks, and ideas from Slack, Fathom, Plaud, Gmail, and iMessage.

> **Golden rule:** *You are the librarian, not the shelver.* Never drag files into the folders yourself. Always go through Claude, so it can pick the location, write the front matter, and create the links. Files you add by hand are "unaccounted for" and confuse the AI.

---

## 7. The six ways a second brain breaks

1. **Unused action layer:** connectors are installed but you never pull info from them.
2. **Broken navigation:** fix it by asking Claude to "analyze my folder structure, find orphaned files and broken links".
3. **Manual filing:** you drop files in by hand, so the AI doesn't know about them.
4. **Notes never linked:** ask Claude now and then to "go through all context and interlink it" (monthly routine or manual; Ivan has only done it twice).
5. **One brain, many audiences:** confidentiality problems (see below).
6. **Access problems.**

---

## 8. Key Q&A takeaways

- **Every folder has its own MOC**, built automatically.
- **Multiple chats/sessions are fine.** They all share the same context and connectors, which also cuts down on hallucination between sessions. For long sessions, have Claude write a **handover document** into the second brain for the next session.
- **Keeping personal info out:** the CLAUDE.md file tells Claude not to write to the brain unless you ask.
- **When to split into multiple second brains:** based on **who needs access**. Personal (taxes, travel) is separate from company. Split departments only if they shouldn't see each other's info. Default: **one second brain per company**. You can connect two brain folders to one session.
- **Old context is never auto-deleted.** Store what might be useful later, but **no trash data** (for example, don't dump all emails, since about 80% is spam).
- **Claude can mis-file things,** but you fix it by asking. There's no need to start over.
- **Codex (ChatGPT)** can probably do the same. **Cost:** tokens are rarely a problem. **Storage:** tiny, since it's all text.
- **Personalize Claude:** Ivan's custom instructions: lead with the answer, be direct, no "great question", short dense paragraphs, push back when I'm wrong.

---

## 9. Where this leads (the "Jarvis" demos)

- A **Telegram assistant** that tells Ivan his daily priorities, which content performed well (a clip with Kasim got 10× median views), and answers *"What did Juan Cruz ask me for on today's call?"* by searching Fathom.
- An **Artifact dashboard** of promises made, each linked back to its source (call/email).
- **Voice "deep work" agent** that walks through tasks, creates follow-ups, and checks Slack.
- **LinkedIn posts** written in his voice, with AI images, posted automatically.
- **None of this works without the foundation:** proper context plus proper connectors.

**Coming next:** Day 4: agents, routines, automations, more connectors. Friday: GoHighLevel + AI. Next week: marketing, image/video generation, inbox management.

---

## 10. Homework: build a starter Second Brain for sample founder **Kasim Aslam**

Kasim Aslam is Pareto Talent's co-founder (named in class as leadership next to Ivan). Ivan said he would check whether the in-class version was doable on the free plan. The slide is the **revised, free-plan-friendly version**, so the Claude **Project** replaces a live Drive/Claude Code connection.

| # | Task | What it means / how to do it |
|---|---|---|
| 1 | **Folder architecture as a ZIP → Google Drive** | Paste the Second Brain prompt into Claude (free chat) and ask it to *design the folder structure for Kasim and generate it as a downloadable .zip*: folders, MOC files, templates, CLAUDE.md. Download, unzip, and drag the whole structure into Google Drive. |
| 2 | **Run an intake from mined material** | Run the intake interview, but answer it with material you *mined* about Kasim (podcast/YouTube transcripts, his website, LinkedIn, interviews, scraping, the tools from Day 2). You play the founder's role using real source material. |
| 3 | **Populate the context layer with ≥ 5 documents** | Markdown files with front matter and wiki links. They must include: **(a)** at least one on **identity, offer, or pricing** (who Kasim is, what his company sells, prices); **(b)** at least one on **team / key people**; **(c)** at least one **long-form** piece: a full transcript, a podcast, or a written history. |
| 4 | **Upload the same .md files to a Claude Project** | In claude.ai, go to Projects → New Project ("Kasim Aslam Second Brain") → add the Markdown files to Project Knowledge (and optionally paste the CLAUDE.md rules into the Project instructions). This stands in for a live Drive connection on the free plan. |
| 5 | **Run the retrieval test and record it** | Ask **3 questions you already know the answers to**. Screen-record it. The recording must show Claude **finding the right file** (citing/naming which document it pulled from), not just giving a plausible-sounding answer. Tip: add "tell me which file you got this from" to each question. |
| 6 | **Quick tutorial for the founder** | A short guide (Loom/video, a doc, or a Claude Artifact) that explains to Kasim, as a non-technical founder, what his second brain is, how it's organized, how to ask it questions, and how new info gets added. |

**Submit at:** bootcamp.paretotalent.com/homework. Also post it in **#Homework** on Slack and share one thing you liked about the class in **#General**.
