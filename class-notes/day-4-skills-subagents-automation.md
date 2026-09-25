# Pareto Talent Bootcamp: Day 4, Claude Skills, Subagents and Automation

**Instructor:** Ivan Bunin · about 2h07m · Live demo: a LinkedIn skill written in Kasim's voice, with graphics made in Canva and posts scheduled in GoHighLevel.

---

## 1. The big idea
Days 2 and 3 gave AI a **brain** (context). Day 4 gives it **hands**: skills, tools (MCPs) and routines, so it can actually *do* things.

## 2. What a skill is
- A **repeatable task packaged for Claude**: prompt + context + best practices + checklist. It works like an SOP that Claude follows every time.
- Claude can **call it automatically** when your request matches the skill's description, or you can call it with a **slash command** (`/skill-name`).
- You don't write it by hand. You **build it together with Claude in a session**, and Claude fills in the name, description and steps.
- A skill is a **folder**: `SKILL.md` plus a `references/` folder (voice, visuals, post structure, platform rules, frameworks).

### Why skills fail
1. **Too broad:** one skill trying to do many jobs.
2. **No quality standard:** no checklist for the output.
3. **Assumed context:** it expects information it doesn't have access to.
4. **Too many tools in one skill** ("scope creep").

## 3. What to feed a content skill (the LinkedIn demo)
| Layer | What | How Ivan got it |
|---|---|---|
| **Format** | Best posts from creators who do well **with your audience** (Dan Martell, Codie Sanchez) | Easy Scraper Chrome extension → about 50 posts → CSV. Then Claude analyzed them **by engagement** |
| **Best practices** | YouTube videos on how to post | Copy each transcript → **docs.new** → paste without formatting (Cmd/Ctrl+Shift+V) → download as Markdown. *Take it with a grain of salt: it's someone else's opinion* |
| **Voice** | How the person speaks | Podcast transcripts → a "voice" file with common words and phrasing |
| **"Meat"** | Ideas only this person has | Private calls, pillar content, books, podcasts → a "frameworks" file |
| **Visual** | Post templates | Canva templates. Claude replaces the text through the **Canva connector** |

- **Balance:** 100 books overwhelm the skill and 1 is not enough. Choose the sources, test, and add what's missing. For example, it won't add a call to action unless you tell it to.
- **What the data showed (LinkedIn):** hooks under 40 characters did better, posts with **links got about half the engagement**, and text-only posts always did worse.
- The text on the image **is not a copy of the caption**. It's a shorter hook that stops the scroll.

## 4. From skill to real action
**Skill → Canva (creates the graphic) → GoHighLevel/Buffer (schedules the post) → output.**
- **Map it on paper first:** skill, **input** (new ideas keep coming in), **output** (graphic + copy + scheduled post).
- **MCP:** connects Claude to any app. If there's no native connector, search "[app] MCP", paste the guide into Claude and say "connect this for me". Claude walks you through it.
- **API keys:** store them in a password manager (Mac Passwords app, 1Password, Bitwarden), not in the chat.
- **For Instagram,** Ivan recommends **GoHighLevel** ($97/month), which schedules to every social network. (This was his answer to Alex's question.)

## 5. Automation basics
**Trigger → Condition → (Wait) → Action**
- **Trigger:** a schedule (every day at 9 AM), a new meeting, a form, a webhook.
- **Condition / guardrails:** stop if the post contains names, money amounts, passwords or anything offensive.
- **Wait:** delay until the right time or until something changes.
- **Action:** post or schedule.
- **Routine** = a skill that runs on a schedule. Ask Claude "make this a routine every morning at 9". It runs **on your computer**, so the computer has to be on (Zapier and n8n run in the cloud).
- **Common mistakes:** no error handling, **no human checkpoint** (Ivan never auto-publishes without reviewing; *you* are liable), too many tools, and skipping test runs.

## 6. Other takeaways
- **Contrarian review:** ask "analyze everything that can go wrong with this skill", then fix what it finds. When something breaks, tell Claude so it adds a fix.
- **Aim for 80% good, then ship.** It will never be perfect.
- Skills live **locally or in your account**. To share one, send the **zip**; GitHub is optional. There are thousands of public skills on GitHub.
- **Projects** can hold about 100 context files, which is enough for a second brain at the bootcamp's scale.
- **Don't mix languages.** A Spanish project can have its own Spanish second brain. (Also Ivan's answer to Alex.)
- **Context window ≠ usage limit.** When a chat gets full, compact it. Your second brain lives in files and isn't affected.
- **Inbox:** Ivan recommends **Shortwave**.
- **Routine ideas:** lead dossier before calls, daily department summary, meeting recap, morning brief.

## 7. Homework
Build a real Claude skill for **one** task you'd repeat, connect it to a real tool (MCP), test it twice, share the zip, and record a Loom. See the plan for the Cony's Home Instagram skill.
