# Your First make.fun Bounty

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/REKKI007/make-fun-start-here/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/REKKI007/make-fun-start-here/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

**You can do this today.** make.fun is a platform where you build software for real bounties and get paid in USDC on Solana. This guide walks you through your first one, step by step, from signing up to submitting — no prior experience with bounties needed.

> **Start here:** create your account with my referral link — [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) (referral code: `06fpcnax`). A referral binds to the first link your browser saw, and that first touch wins for 60 days, so use the link before you sign up. Signing up through it costs you nothing.

## What is make.fun?

make.fun runs coding competitions called bounties. Each bounty states a task, a prize, and a deadline. You build the thing, submit it, and if it places, you get paid in USDC on Solana. Prizes are locked in on-chain escrow where the bounty says so, and the reward is claimed from escrow to the wallet that signed the winning entry.

This guide is itself an entry in the bounty **Bring the humans again** (`bring-the-humans-02`): a $1,000 prize pool shared by the 50 highest-ranked entries, ranked by the number of verified human signups their referral link brings. The prizes are: 1st $150, 2nd $80, 3rd $50, 4th–10th $20 each, 11th–25th $17 each, 26th–50th $13 each. Only verified human signups count — the same checks that pay make.fun's referral rewards decide, so fake or bot signups never count.

## Who this guide is for

You, if you can write a little code (or drive an AI coding agent) and you want a concrete first bounty instead of another tutorial. If you have never entered a bounty before, start with the steps below in order. Each step is short, and you can stop after any of them and come back later.

## Step 1 — Create your account

1. Open my referral link: [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax). The code is `06fpcnax`.
2. Sign up. You can sign in with GitHub, or with a Solana wallet, Google, Apple, or Discord — and then link GitHub on your profile. Linking GitHub matters: your entry is a public GitHub repository, and it only counts as yours when its owner is the GitHub account linked to your make.fun account.
3. Check that your GitHub account is linked on your profile before you build anything. An entry from an unlinked account is not yours.

That is the whole setup. Nothing to install yet.

## Step 2 — Pick a bounty you can realistically finish

Do not pick the biggest prize first. Pick the bounty you can finish before its deadline. Use these four checks:

1. **Prize and type.** Read what the bounty pays and whether it is free to enter. Some bounties are free; others need a fee or funds in your wallet. For your first one, pick a free bounty.
2. **Requirements.** Read the rules word for word. Note exactly what the entry is (a repository? a bundle? a screenshot?), what the deadline is, and what the score is. If the rules say the entry is a GitHub repository, that is what you submit — nothing else counts.
3. **Deadline.** Check the closing time in your own timezone and work backwards. A bounty that closes in three days needs a plan you can finish in two.
4. **Score.** Understand how you are ranked. Some bounties are scored automatically (for example, by verified signups, like this one); others are judged. Know which one you are entering before you start building.

A good first bounty is small, free, clearly specified, and closes at least a few days away. If a bounty fails any of these checks, skip it — there will be another one.

**A concrete example:** if you have two evenings free, pick a guide or documentation bounty over a bounty that asks for a playable game. The game takes a week; the guide takes one evening, and a finished valid entry beats an unfinished ambitious one every time. This bounty, for instance, closes on 21 November 2026 at 17:30 WIB — if you are reading this before then, you still have time to write a guide and submit it.

## Step 3 — Read the kit before you write code

Every bounty ships a kit: rules, a starter, and a command-line tool. Download it and read the rules file first. The rules tell you:

- what the entry must contain (for this bounty: a `README.md` guide at the root of a public repository, carrying your referral code, plus a `screenshot.png` of the repository's page on GitHub);
- the size limits (here: README at most 2 MB, screenshot at most 8 MB and at most 16,000,000 pixels);
- what disqualifies an entry (here: a missing README or screenshot, a README without your referral code, or a `.github/README.md` that would show in place of the root one);
- how the transcripts of your AI agent sessions are checked (for entries received from 17 November 2026, transcripts are required, and at least 30% of the counted lines must be lines your agent wrote, with the entry file written or edited in at least two of your agent's messages).

Start a fresh agent session at or after the competition opens — a session that began before the opening cannot be entered. Then build inside that session.

## Step 4 — Build with an AI agent

You do not have to write every line yourself. The normal way to enter is to have an AI coding agent build the entry while you direct it:

1. Give the agent the bounty rules and tell it the entry you want.
2. Let it write a draft, then ask it to revise the draft. A real revision matters: the transcript checks look for the entry file being written or edited in at least two messages.
3. Check the result yourself against the rules before you submit — file names, referral code present, size limits met.
4. Keep the session transcripts. You will upload them with your entry, and the checks match them against your code.

Write your own guide in your own words. Copying a starter unchanged fails the transcript checks, because its lines are the kit's, never your agent's.

## Step 5 — Submit

1. Create a public GitHub repository under the GitHub account linked to your make.fun account, after the competition opens. Add an OSI-approved license (this repository uses the MIT License).
2. Push your entry to it and take the screenshot once the repository is published: a capture of the repository's page on GitHub with the README showing, whose top shows the repository name and the start of your README.
3. Bundle your session transcripts and run the kit's pre-submit checks on your repository's commit. Fix anything a check reports, then submit again before the deadline if needed — your final entry is your most recent submission with a receipt before the deadline.
4. An entry is submitted as a public GitHub repository's URL, naming a commit and carrying the transcripts. Later pushes do not change the entry, and the final check reads the repository's default branch again at the result — so keep it public, keep the same repository, and keep your referral code in the README.

## Step 6 — After the deadline

For this bounty, the final check starts at the deadline: each signup is decided once its own 24-hour review hold from binding has closed, and the signups verified by the end of the final check, 30 hours after the deadline, are the ones that count. Each final entry's repository is read again on GitHub — it must still be public, still the same repository, and its README must still carry your referral code. The results publish once every entry's re-check has a verdict.

If you place, claim your prize within 7 days with the payout details. Prizes are paid in USDC on Solana only. A legal name, country of residence, and tax form are asked only when your prizes from make.fun in the calendar year reach the $2,000 tax reporting threshold; below it, the claim asks for none of them. A prize not claimed within 7 days passes to the next entry in the standings.

## A realistic first-bounty checklist

- [ ] Account created through [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) (code `06fpcnax`)
- [ ] GitHub account linked on your make.fun profile
- [ ] Bounty chosen: free, clearly specified, deadline you can meet
- [ ] Rules read word for word; entry format, limits, and scoring understood
- [ ] Fresh agent session started at or after the opening
- [ ] Draft written, then revised in the same session
- [ ] Entry checked against the rules (files, names, sizes, referral code)
- [ ] Public repository created after the opening, license added, pushed
- [ ] Screenshot taken of the published repository page
- [ ] Transcripts bundled, pre-submit checks passed, entry submitted

## Common mistakes to avoid

- **Starting before the opening.** A session that began before the competition opens cannot be entered. Start fresh, after the opening time.
- **Copying the starter.** A starter copied unchanged fails the transcript checks — its lines are the kit's, never your agent's. Write your own guide, then revise it.
- **Writing once and never revising.** The checks need the entry file written or edited in at least two of your agent's messages. Draft, then revise.
- **Forgetting the referral code.** An entry whose README does not name your referral code is refused and not ranked. Check for the bare code before you submit.
- **Submitting a private repository.** The entry must be a public repository under the linked GitHub account. Check that it is public before you submit, and keep it public until the results are final.
- **Losing the transcripts.** Without the session transcripts, an entry received from 17 November 2026 is rejected. Bundle them with the entry.

## What this guide does not promise

Entering a bounty does not guarantee a prize. Only verified human signups count for this bounty, and only the top 50 entries share the $1,000 pool. What the steps above do guarantee is a valid entry: one that is checked, ranked, and eligible — which is the part you control.

## Start now

Your first bounty is one decision away: create your account with [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) (referral code `06fpcnax`), pick a free bounty you can finish, and build it. Then come back to this guide when you are ready for your second one.

---

*Built as an entry for [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) on make.fun. Referral code: `06fpcnax` — [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax).*
