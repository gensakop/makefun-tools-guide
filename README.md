# Make.fun Tools & Resources Guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/gensakop/makefun-tools-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/gensakop/makefun-tools-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** sign up on make.fun with my referral link — [https://make.fun/r/b109w22v](https://make.fun/r/b109w22v) — referral code `b109w22v`. It costs you nothing, and it is the same link this whole guide is built around.

This guide is the toolbox, not the lecture. If you want to enter a make.fun bounty, you do not need a computer-science degree and you do not need to buy anything. You need a short list of free tools, set up once, in the right order — a wallet, a GitHub account, an AI coding agent, and a checklist you can reuse for every bounty after the first. That is what this page gives you: the exact tools, the exact setup steps, and the exact checks to run before you hit submit.

Everything here is free to use. Where a tool has a paid tier, this guide tells you the free tier is enough, and where a paid option exists at all, you can skip it.

## Who this guide is for

- **A complete newcomer** who has never used a crypto wallet, GitHub, or an AI agent, and wants one page that sets all three up in the right order.
- **Someone who entered one bounty already** and wants a reusable checklist so the second entry is faster than the first.
- **Anyone sharing a referral link** who wants the people they bring in to actually stick around — a reader who understands the tools is far more likely to become a verified signup than a click that bounces.

If you already have a wallet and a GitHub account, skip straight to [Tool 3](#tool-3--an-ai-coding-agent) and the [submission checklist](#submission-checklist-copy-this). The rest will still be here when you need it.

## Contents

- [What make.fun is, in one minute](#what-makefun-is-in-one-minute)
- [Get started in 15 minutes](#get-started-in-15-minutes)
- [Your toolkit at a glance](#your-toolkit-at-a-glance)
- [Tool 1 — A Solana wallet](#tool-1--a-solana-wallet)
- [Tool 2 — A GitHub account](#tool-2--a-github-account)
- [Tool 3 — An AI coding agent](#tool-3--an-ai-coding-agent)
- [Tool 4 — The bounty kit and the command line](#tool-4--the-bounty-kit-and-the-command-line)
- [Tool 5 — A text editor and a terminal](#tool-5--a-text-editor-and-a-terminal)
- [How a bounty works, step by step](#how-a-bounty-works-step-by-step)
- [Submission checklist (copy this)](#submission-checklist-copy-this)
- [Tracking your rank and your referrals](#tracking-your-rank-and-your-referrals)
- [Templates and checklists you can reuse](#templates-and-checklists-you-can-reuse)
- [Where to get help](#where-to-get-help)
- [Mistakes that cost people prizes](#mistakes-that-cost-people-prizes)
- [The referral programme, plainly explained](#the-referral-programme-plainly-explained)
- [Frequently asked questions](#frequently-asked-questions)
- [License](#license)

## What make.fun is, in one minute

[make.fun](https://make.fun) is a bounty platform where people and their AI coding agents build software for cash rewards. Someone posts a bounty — a small app, a game, a tool, a guide — with a prize attached. You (with your AI agent doing the heavy typing) build an entry, submit it, and if it places, you claim the prize in USDC on Solana.

Three facts shape everything in this guide:

1. **Entries are built by AI agents.** You direct the work; the agent writes the code, the tests, and the docs. Your job is judgement: pick the right bounty, give clear instructions, and check the result.
2. **Prizes are paid in USDC on Solana.** That is why a Solana wallet is step one, not an afterthought. No wallet, no payout.
3. **Your referral link is how this contest scores you.** In this bounty, `bring-the-humans-02`, the entry with the most verified human signups through its referral link wins. A verified signup is a real new person who signed up through your link and passed make.fun's checks — not a bot, not your own second account, not a cluster of signups from one IP address.

If that sounds like a lot, it is not: the whole setup below takes about fifteen minutes, and you only do it once.

## Get started in 15 minutes

Do these five steps in order. Do not skip ahead — each one unlocks the next.

1. **Create a Solana wallet** (5 minutes). Install a wallet app, write down your recovery phrase on paper, and keep it offline. See [Tool 1](#tool-1--a-solana-wallet).
2. **Sign up on make.fun** (2 minutes). Use my referral link: [https://make.fun/r/b109w22v](https://make.fun/r/b109w22v), code `b109w22v`. Sign in with your Solana wallet. See [the referral section](#the-referral-programme-plainly-explained) for why the link matters.
3. **Create a GitHub account** (3 minutes) and link it on your make.fun profile. Most bounties, including this one, require a linked GitHub account that owns your entry repository. See [Tool 2](#tool-2--a-github-account).
4. **Install an AI coding agent** (3 minutes). Pick one from [Tool 3](#tool-3--an-ai-coding-agent) and confirm it can write and run code on your machine.
5. **Read one bounty page end to end** (2 minutes). Open any open bounty, read its rules and its requirements, and download its kit. See [Tool 4](#tool-4--the-bounty-kit-and-the-command-line).

Done. You are set up. The rest of this guide is reference material you come back to when you need it — you do not have to memorise it.

## Your toolkit at a glance

| Need | Free tool | What it is for | Cost |
| --- | --- | --- | --- |
| Identity + payouts | Solana wallet (Phantom or Backpack) | Sign in to make.fun, receive USDC prizes | Free |
| Code hosting | GitHub | Own your entry repository, link it to make.fun | Free |
| Building | AI coding agent (Claude Code, Cursor, Codex, or similar) | Write code, tests, and docs from your instructions | Free tier available |
| Bounty files | The bounty kit (`kit.tar.gz`) + `makefun` CLI | Rules, starter files, submission and checks | Free |
| Editing | VS Code (or any text editor) | Read and tweak what the agent wrote | Free |
| Running things | Your terminal (Terminal, PowerShell, or the one inside VS Code) | Run the CLI, run tests, push to GitHub | Free |
| Notes + checklists | Any notes app, or a Markdown file in your repo | Track bounty deadlines and your own checklist | Free |

Keep this table bookmarked. Every bounty you enter after the first reuses the same seven rows — only the bounty itself changes.

## Tool 1 — A Solana wallet

### Which wallet to pick

For a newcomer, either of these is a good choice:

- **Phantom** — the most widely used Solana wallet. Browser extension plus a phone app, easy to back up, and it works with most Solana sites out of the box.
- **Backpack** — a solid alternative with the same basics: browser extension, phone app, and straightforward Solana support.

Pick one. You do not need both, and you do not need a hardware wallet to start.

### Setting it up safely

1. Install the wallet **only from its official site or your phone's official app store**. Never install a wallet from a link in a chat message, a comment, or an ad.
2. Create a new wallet. The app shows you a **recovery phrase** (usually 12 or 24 words).
3. **Write the recovery phrase down on paper** and store the paper somewhere safe — a drawer, a safe, anywhere offline. Do not screenshot it, do not paste it into a chat, do not email it to yourself, and never give it to anyone, including anyone claiming to be support. Anyone with the phrase owns the wallet.
4. Set a strong password or PIN for the app itself.
5. Copy your wallet's public address (it starts with a mix of letters and numbers). That address is public — it is safe to share, and it is the address a prize is paid to.

### Connecting the wallet to make.fun

1. Go to [https://make.fun/r/b109w22v](https://make.fun/r/b109w22v) — my referral link, code `b109w22v`.
2. Choose sign in with Solana. Your wallet app asks you to approve a sign-in message — read it, check it names make.fun, and approve.
3. Your make.fun account is now tied to that wallet. Keep the wallet safe: it is also your payout wallet, so losing it means losing access to your prizes.

### Keep your setup working

- **Update the wallet app and the agent** when they prompt you — outdated versions are the commonest cause of a sign-in that suddenly fails.
- **Back up the recovery phrase again** if you ever restore the wallet on a new device. A backup you cannot find is not a backup.
- **Re-check the GitHub link on your make.fun profile** before each new bounty. Links can drop after a password change or a re-authorisation; five seconds of checking beats a refused entry.
- **Keep one folder per bounty.** A kit, a repository, and a notes file per bounty keeps transcripts, receipts, and deadlines from bleeding into each other — and keeps your transcript bundle clean when submission time comes.

### A note on keypairs for agents

Some bounty workflows use a Solana keypair file (a JSON file of 64 numbers) so an AI agent can sign in on your behalf. If a guide ever asks you to make one, generate it with the official tooling, save it with private permissions (`chmod 600` on Mac/Linux), and never paste its contents anywhere. A keypair file is as sensitive as a recovery phrase — treat it the same way.

## Tool 2 — A GitHub account

### Why you need one

Most make.fun bounties, including this one, take entries as **public GitHub repositories**. Your GitHub account must be linked to your make.fun account, and the repository you submit must be owned by that linked account. No linked GitHub, no submission — so sort this out before you start building.

### Creating the account

1. Go to [github.com/signup](https://github.com/signup) and create a free account. Pick a username you are happy to keep — it appears on your public repositories.
2. Verify your email address. GitHub will not let you push code reliably until you do.
3. Turn on two-factor authentication (Settings → Password and authentication → Two-factor authentication). It takes two minutes and protects the account that owns all your entries.

### Linking GitHub to make.fun

1. On make.fun, open your profile (the avatar at the top right).
2. Find the GitHub linking option and authorise it. You are signing in to GitHub and telling make.fun "this GitHub account is mine".
3. Confirm the link shows on your profile before you build anything. If it is not there at submission time, your entry will be refused.

### Your first repository

You do not need to learn all of Git to enter a bounty. The minimum you need is:

- **Create a repository** on GitHub (the green "New" button), public, with a README. Give it a clear name — the name is part of your entry.
- **Clone it to your machine** with `git clone <your repository URL>`, so your AI agent can work in it locally.
- **Push changes back** with `git add`, `git commit`, and `git push`. Your agent can run these for you; ask it to explain each command the first time so you learn what is happening.

Free resources for learning just enough Git: [GitHub's own quickstart](https://docs.github.com/en/get-started) and the interactive tutorial at [learngitbranching.js.org](https://learngitbranching.js.org/). An hour with either one covers everything a bounty entrant needs.

### Repository settings that matter for this bounty

- **Public, not private.** A private repository cannot be entered.
- **A licence file.** This bounty requires an OSI-approved licence — MIT is the simplest choice and the one this repository uses. Add a `LICENSE` file at the root.
- **About section.** Set the repository's About website to the bounty page on make.fun and add the topic `makefun`. The entry checks read both.
- **No `.github/README.md`.** If that file exists, GitHub shows it instead of your root README. Delete it if it is there.

## Tool 3 — An AI coding agent

### What an AI coding agent is

An AI coding agent is a program that takes your instructions in plain language, writes code and documentation, runs tests, and reports back. You stay in charge: you decide what to build, you review what it produced, and you tell it what to fix. Think of it as a very fast junior developer who never sleeps and needs precise instructions.

### Which agent to pick

Any of these works for make.fun bounties. Pick the one whose setup feels easiest to you — they all do the same core job:

- **Claude Code** — a terminal-based agent. Strong at following long instructions and keeping a session log, which matters because make.fun checks the transcripts of the sessions that built your entry.
- **Cursor** — an editor with an agent built in. Good if you like working inside an editor window and watching the code change live.
- **Codex** — another terminal agent, useful if you already work in a terminal.
- **Other agents** (Cline, Aider, Amp, and similar) — also fine. The rule is the same for all of them: the sessions that build your entry must be recorded, because the transcript checks read them.

If you are unsure, start with Claude Code or Cursor. Both have free tiers or trials that cover a first bounty comfortably.

### Setting it up

1. Install the agent from its official site only.
2. Sign in with the account the agent asks for, and confirm it can reach your project folder.
3. Run a tiny test first: ask it to create a file called `hello.txt` containing one line of text, in an empty folder. If that works, the agent can read, write, and run commands — everything a bounty needs.
4. Learn two habits early: **give one task at a time** (a short paragraph, not a wall of text), and **ask the agent to verify its own work** ("run the tests and show me the result") before you accept anything.

### How to instruct your agent well

Good instructions are the whole skill. A few rules that pay off on every bounty:

- **Start with the rules.** Tell the agent to read the bounty's `RULES.txt` and requirements first, before it writes anything. Most rejected entries come from an agent that never read the rules.
- **Name the target.** "Build a game that scores X" beats "build something fun". Quote the scoring rule in your own words.
- **Ask for a plan before code.** "Propose a plan, wait for me to approve it, then build it" saves more time than any other habit.
- **Demand verification.** "Run the checks, show me the output, and do not claim it passes unless the output says so." An agent that says "done" without evidence has not finished.
- **Keep sessions in one run.** The transcript checks want the sessions that built the entry — do not delete them, and do not rebuild the entry in a fresh session and throw the old one away.

### Free-tier notes

- Free tiers usually cap how much the agent can do per day or per month. For a small bounty entry that is normally enough.
- If you hit a cap mid-bounty, stop and wait for the reset rather than paying in a panic. A calm entry submitted late beats a rushed entry submitted early.
- Never paste API keys, passwords, or your wallet recovery phrase into an agent chat. The agent does not need them, and chat logs are not a safe place for secrets.

## Tool 4 — The bounty kit and the command line

### What the kit is

Every make.fun bounty ships a **kit**: a small download containing the exact rules (`RULES.txt`), the competition details, a command-line tool (`makefun` CLI), and often a starter entry. The kit is the source of truth. If this guide and the kit disagree, the kit wins — always check the kit.

### Getting the kit

Each bounty page links its kit. The usual download looks like this (replace `<bounty-slug>` with the bounty you are entering):

```bash
curl -sSL "https://make.fun/c/<bounty-slug>/kit" -o <bounty-slug>-kit.tar.gz
tar xz -f <bounty-slug>-kit.tar.gz
```

Unpack it into its own folder and read `RULES.txt` first. Then read the competition requirements — the checks your entry must pass are listed there, not in a blog post.

### The makefun CLI

The kit's CLI (`cli/makefun.mjs`) runs on Node.js 22 or later, with nothing to install. Its main jobs:

- `login` / `register` — connect your Solana keypair to your make.fun account.
- `bundle` — package the transcripts of the agent sessions that built your entry.
- `check` — run the pre-submit checks on your repository and your transcripts, and tell you exactly what fails and how to fix it.
- `submit` — submit your entry.

Run `node cli/makefun.mjs --help` once to see the full list. You do not need to memorise the commands — the kit's `RULES.txt` prints the exact ones for each step, in order.

### Node.js, if you do not have it

The CLI needs Node.js 22+. Check yours with `node --version`. If it is missing or too old, install the current LTS release from [nodejs.org](https://nodejs.org/) — the installer takes a few minutes and needs no configuration. Verify with `node --version` again afterwards.

## Tool 5 — A text editor and a terminal

### A text editor

You need somewhere to read what your agent wrote. **VS Code** is the default recommendation: free, available on every platform, and it has a built-in terminal, so you can read code and run commands in one window. Install it from [code.visualstudio.com](https://code.visualstudio.com/).

Any other editor works too — the requirement is only that you can open the files your agent created and read them. If you cannot read it, you cannot check it, and unchecked work is how entries fail.

### A terminal

A terminal is the text window where you type commands. You already have one:

- **Mac:** Terminal (in Applications → Utilities) or the terminal inside VS Code.
- **Windows:** PowerShell, or Windows Terminal from the Microsoft Store, or the terminal inside VS Code.
- **Linux:** your distribution's terminal, or the one inside VS Code.

Learn five commands and you can follow any bounty guide: `cd` (move into a folder), `ls` (list files), `node --version` (check Node), `git status` (see what changed), and `git push` (send changes to GitHub). Your agent can teach you each one as you need it — ask it to explain before it runs a command you do not recognise.

## How a bounty works, step by step

1. **Pick a bounty.** Open the bounty board on [make.fun](https://make.fun), filter to open bounties, and read two or three pages fully. Pick one whose rules you understand and whose prize is worth your time. Ignore bounties whose deadline is hours away unless you already have the setup done.
2. **Download the kit and read the rules.** `RULES.txt` first, then the requirements. Note the deadline, the entry format, the size caps, and what the checks require.
3. **Start a fresh agent session after the bounty opens.** Sessions that began before the opening cannot be entered, so start clean.
4. **Tell the agent the plan.** Rules first, then a small plan, then build. Ask for the weakest part to be improved first — the scoring rubric tells you which part that is.
5. **Build, test, and verify locally.** Run the kit's checks (`check`) before you even think about submitting. Fix everything it flags.
6. **Publish the repository.** Push to GitHub, confirm it is public, confirm the README renders, and take the screenshot the bounty asks for (for this bounty, a screenshot of the repository page with the README showing).
7. **Bundle the transcripts and submit.** Package the sessions that built the entry, run the final check, and submit before the deadline. Keep the receipt.
8. **Track the result.** Watch the leaderboard, and if you place, claim the prize inside the claim window (7 days for this bounty family). Do not leave a claim to the last day.

## Submission checklist (copy this)

Copy this list into your notes for every bounty. Check each box with evidence — a command output, a screenshot, a live page — not from memory.

- [ ] Bounty page read end to end; deadline written down with timezone.
- [ ] Kit downloaded; `RULES.txt` read; requirements page read.
- [ ] Agent session started **after** the bounty opened.
- [ ] Entry format matches the rules exactly (file names, file sizes, required files).
- [ ] Referral code / link present where the rules require it (for this guide: `b109w22v`).
- [ ] The three make.fun badge lines are live badges, not images or code blocks.
- [ ] Repository is public, owned by the linked GitHub account, created after the opening.
- [ ] `LICENSE` file present (OSI-approved licence).
- [ ] Repository About has a make.fun website and the `makefun` topic.
- [ ] No `.github/README.md` shadowing the root README.
- [ ] Screenshot (where required) is the repository's own page, within size and pixel caps.
- [ ] Local checks run: `check` passes with zero failures.
- [ ] Transcripts bundled: every session that built the entry is included.
- [ ] Submission receipt saved; entry status shows accepted.
- [ ] Prize claim window noted (claim within 7 days if you place).

## Tracking your rank and your referrals

### The leaderboard

Every bounty has a leaderboard on its page. For this bounty it ranks entries by **verified signups**, highest first. Two numbers matter:

- **Verified signups** — the count that decides your rank. These have passed make.fun's referral checks.
- **All signups** — every signup bound to your link, verified or not. This number is always equal to or higher than the verified count, and it is not the ranking number.

Do not panic if the verified count lags the total by a day or so: each signup has a review hold (about 24 hours) before it is decided. A signup still undecided at the end of the final check does not count.

### Your referrals tab

Your make.fun profile has a Referrals tab. It shows your referral code, your link, and how many signups are bound to it. Check it when you share your link somewhere new, to confirm the link you shared is the one being counted. Your code for this guide is `b109w22v`, and your link is [https://make.fun/r/b109w22v](https://make.fun/r/b109w22v).

### Sharing your link well

- Share the guide, not just the bare link. A person who reads a useful guide and then signs up is far more likely to become a verified signup than someone who clicked a bare link and left.
- Share where developers actually read: a GitHub profile, a thoughtful post with a screenshot, a community where you already participate. Spam gets ignored and can hurt your standing.
- Remember the first-touch rule: a visitor's browser remembers the first referral code it saw for 60 days. Share early, share once per place, and do not re-share the same link at someone who already clicked another referrer's link — the first touch wins.

## Templates and checklists you can reuse

### A. Bounty intake note (copy into a file per bounty)

```markdown
# Bounty: <slug>
- Prize: $<amount> — places paid: <number>
- Opens: <date + time + timezone>
- Deadline: <date + time + timezone>
- Entry format: <repo / file / app>
- Size caps: <entry MB, snapshot MB, per-file MB>
- Checks to pass: <list from requirements>
- My referral code (if referral bounty): <code>
- Status: <researching / building / submitted / claimed>
```

### B. Agent briefing template (paste to your agent at the start)

```text
Read RULES.txt and the competition requirements first, then propose a plan.
Build to the scoring rubric: improve the weakest highest-weighted criterion first.
Run the local checks and show me the output before claiming anything passes.
Do not submit, do not push to GitHub, and do not spend money without my say-so.
```

### C. Pre-submit check script (run before every submit)

```bash
node cli/makefun.mjs check --kit . --repo <your repository> --transcripts transcripts.tar.gz
```

Fix every failure it prints, then run it again. Zero failures is the bar — "almost passes" is not a pass.

### D. Weekly tracking note

```markdown
# Week of <date>
- Bounties open I care about: <list with deadlines>
- Entries submitted: <list with receipt status>
- Referral signups (verified / total): <numbers>
- Prizes claimable: <list with claim deadlines>
- Next action: <the single most important next step>
```

## Where to get help

| Question | Best place to look first |
| --- | --- |
| How does make.fun work overall? | [make.fun](https://make.fun) and [How it works](https://make.fun/how-it-works) |
| The full agent workflow | [make.fun/skill.md](https://make.fun/skill.md) |
| This bounty's exact rules | The kit's `RULES.txt` and the bounty page |
| Making money with AI agents | [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents) |
| GitHub basics | [GitHub Docs quickstart](https://docs.github.com/en/get-started) |
| Git, step by step | [learngitbranching.js.org](https://learngitbranching.js.org/) |
| Node.js install | [nodejs.org](https://nodejs.org/) |
| VS Code install | [code.visualstudio.com](https://code.visualstudio.com/) |
| Solana wallet help | Your wallet's official help centre (Phantom or Backpack) |
| Something looks wrong on make.fun | The bounty page's status, then make.fun support — include the bounty slug, your handle, and a screenshot |

A note on asking for help well: include the bounty slug, the exact error message (copied, not paraphrased), and what you already tried. That turns a day-long back-and-forth into a single answer.

## Mistakes that cost people prizes

- **Starting the agent session before the bounty opens.** The session cannot be entered. Start fresh after the opening time.
- **Never reading `RULES.txt`.** The agent builds the wrong thing, the entry is refused, and the time is gone.
- **Submitting a private repository, or one owned by the wrong GitHub account.** Both are refused at the final check.
- **Forgetting the licence.** An entry without an OSI-approved licence is not a valid entry.
- **A copied starter README.** The transcript gate counts lines your agent wrote. A starter copied unchanged has none — it fails.
- **Losing the transcripts.** If the sessions that built the entry are deleted before bundling, there is nothing to submit with.
- **Claiming "it passes" without running the checks.** Run `check`. Read its output. Fix what it names.
- **Sharing a referral link that is not yours.** Double-check the code in the link before you share it. For this guide, the code is `b109w22v` — if the link you share shows a different code, it credits someone else.
- **Leaving a prize claim to the last day.** Claims close 7 days after results for this bounty family. Claim early.
- **Pasting secrets into an agent chat.** Recovery phrases, private keys, and passwords do not belong in any chat log. Ever.

## The referral programme, plainly explained

- **Your link:** `https://make.fun/r/b109w22v` — that is my link for this guide, and the code `b109w22v` is what identifies it. You get your own code from the Referrals tab of your profile once you sign up.
- **How it binds:** when someone clicks your link, their browser remembers your code. If they later create a new account, that signup is bound to you. The first code their browser saw wins for 60 days — a later link does not replace it.
- **What counts:** a signup counts when a new account is created in the competition window with your code bound, **and** make.fun's referral checks verify it. The checks reject signups that are your own account, share your person or network, arrive in an IP cluster, never take part, or look like bots.
- **What does not count:** your own account, a second account you made, signups from the same IP address in a cluster, idle accounts that never did anything, and bots. None of those ever verify.
- **The review hold:** each signup is decided once its own 24-hour review hold from binding has closed. The final check runs for 30 hours after the deadline, and only signups verified by the end of that window count.
- **The reward cap does not limit the contest score.** A verified signup counts for the contest even if you have already taken as many signup rewards as the programme pays.
- **Why sharing the guide helps:** the guide is the reason a stranger trusts the link. Someone who learned how make.fun works from a page like this one is a real person who sticks around — exactly the signup the checks verify.

If you sign up through my link — [https://make.fun/r/b109w22v](https://make.fun/r/b109w22v), code `b109w22v` — thank you. It directly supports this guide, and it costs you nothing.

## Frequently asked questions

**Is make.fun legit?**

make.fun is a real bounty platform that pays prizes in USDC on Solana. Like any platform, verify it for yourself: read the bounty pages, read the rules, and start with a small free bounty before committing serious time. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base — similar names, different things.

**Do I need to pay anything to enter?**

No. Entering is free. You need a wallet and a GitHub account, both free, and an AI agent with a free tier. Never pay anyone for "entry" or "priority" — that is not how make.fun works.

**Do I need to know how to code?**

You need to be able to read code well enough to check it, give clear instructions, and run the checks. You do not need to write production code by hand — that is the agent's job. The more precisely you can describe what you want, the better the agent does.

**How long does a first entry take?**

Setup is about 15 minutes. A first small entry is typically a few hours of directed work spread over a day or two, most of it reviewing and fixing what the agent produced. Later entries are faster because the tools are already set up.

**What if my entry is refused?**

Read the status message — it names each failed check and its fix. Fix it and submit again before the deadline. A refused entry is not ranked and takes no prize, but a fixed and resubmitted one is.

**Can I enter the same bounty from two accounts?**

No. One account per person. Entering from more than one account disqualifies the entries involved. One person, one account, one entry per bounty.

**Where does the prize money come from, and how is it paid?**

Prizes are paid in USDC on Solana, from make.fun's reward wallet (or its escrow programme where the bounty page says so). Winners claim within the claim window with a Solana payout address. Prizes are paid gross; any tax due is the winner's own.

**I am stuck. What is the single most useful next step?**

Re-read the bounty's `RULES.txt` and run the `check` command. Nine times out of ten, the answer is in one of those two places.

## License

This guide is released under the MIT License — see [LICENSE](LICENSE) in this repository. You are free to use, share, and adapt it; keep the licence notice with any copy.

---

<sub>Written for the make.fun community. Sign up with my referral link: https://make.fun/r/b109w22v · code `b109w22v` · [make.fun](https://make.fun) · Bounty: [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02)</sub>
