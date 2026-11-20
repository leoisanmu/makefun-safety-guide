# Staying Safe on make.fun — A Newcomer's Safety Guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/leoisanmu/makefun-safety-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/leoisanmu/makefun-safety-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Short version:** make.fun is a real place to earn cash rewards by building software with an AI agent — but anywhere money moves, scammers follow. This guide shows you how to get started on [make.fun](https://make.fun) **and** how to keep your wallet, your keys, and your winnings safe while you do it.

**My referral link:** https://make.fun/r/js0kvkqa — use code `js0kvkqa` when you sign up. It costs you nothing and it credits this guide if you join through it.

---

## Contents

- [What is make.fun?](#what-is-makefun)
- [Getting started in 10 minutes](#getting-started-in-10-minutes)
- [Rule zero: your keys are your money](#rule-zero-your-keys-are-your-money)
- [Your seed phrase: the one rule that matters most](#your-seed-phrase-the-one-rule-that-matters-most)
- [The real make.fun — and the fakes](#the-real-makefun--and-the-fakes)
- [Spotting a scam bounty](#spotting-a-scam-bounty)
- [How claims and payouts actually work](#how-claims-and-payouts-actually-work)
- [What a fake payout message looks like](#what-a-fake-payout-message-looks-like)
- [Keeping your agent safe](#keeping-your-agent-safe)
- [If something looks wrong](#if-something-looks-wrong)
- [The referral program, explained honestly](#the-referral-program-explained-honestly)
- [Newcomer safety checklist](#newcomer-safety-checklist)
- [FAQ](#faq)
- [Links](#links)

---

## What is make.fun?

make.fun is a bounty platform. People post bounties — cash rewards for building something — and builders (often working with an AI coding agent) build entries and submit them. Winners get paid in USDC on Solana.

Think of it like this:

- **A bounty** is a job posting with a prize attached: build X, win $Y.
- **An entry** is what you submit: code, a guide, a game, whatever the bounty asks for.
- **The leaderboard** shows how entries rank. For this bounty, entries rank by verified human signups brought through the entrant's referral link.
- **A claim** is how a winner collects the prize after results are final.

You do not need to be a professional developer to start. Many bounties are built with an AI agent doing the heavy lifting — your job is to direct it, check its work, and submit something real.

The site lives at [make.fun](https://make.fun). Bookmark that exact address. Everything in this guide starts from there.

---

## Getting started in 10 minutes

### 1. Create your account

Go to [make.fun](https://make.fun/r/js0kvkqa) — that link carries my referral code `js0kvkqa`, so your signup is tied to this guide. (Any make.fun link with `?ref=js0kvkqa` works the same way.)

You can sign in with:

- **A Solana wallet** — the classic route, and the one you need for payouts.
- **Google, Apple, or Discord** — quick sign-in, then link a wallet later.
- **GitHub** — useful if you plan to enter bounties that need a GitHub repository.

Pick one sign-in method and stick with it. One account per person — that is a hard rule on make.fun, and breaking it can disqualify your entries.

### 2. Set up a Solana wallet (if you have not got one)

You need a Solana wallet to receive USDC prizes. If you already have one (Phantom, Solflare, or similar), connect it on your profile. If not:

1. Install a wallet app from its **official** store listing or website — never from a link someone sent you in a DM.
2. Write down the seed phrase it shows you **on paper**, and store the paper somewhere safe. (More on why below.)
3. Set a strong, unique password for the wallet app itself.
4. Connect the wallet to your make.fun profile.

Your wallet address is public — you can share it freely. Your seed phrase and private key are not. Never confuse the two.

### 3. Browse the bounty board

On the board you will see open bounties with their prize, deadline, and rules. Read the rules of any bounty **before** you start building. Each bounty has its own kit, its own checks, and its own deadline — and the deadline is strict.

### 4. Build and submit

For most bounties you download the kit, build your entry (often with an AI agent), and submit it through the site or the kit's command-line tool. The kit's own `RULES.txt` is the authority on what counts — read it, don't skim it.

### 5. Wait for results, then claim

Results are published after the final check. If you placed, claim your prize within the claim window (usually 7 days). Unclaimed prizes pass to the next entry in the standings — so do not sleep on a win.

---

## Rule zero: your keys are your money

On Solana, whoever holds the private key controls the wallet. There is no "forgot password" button, no support desk that can reverse a transfer, and no bank to call. That is the whole point of crypto — and the whole risk.

Three things follow from that:

1. **Your private key and seed phrase are the wallet.** Lose them and the money is gone. Share them and the money is someone else's.
2. **A transaction you sign is final.** Before you approve anything in your wallet, read what it actually says: who receives the funds, how much, and what program it calls. If you cannot read it, do not sign it.
3. **Nobody legitimate will ever ask for your key.** Not make.fun, not a bounty organiser, not a "support agent", not a fellow builder. Anyone who asks is a scammer, full stop.

Keep your keypair file (if you use one for agent work) with file permissions only you can read (`chmod 600` on Linux/Mac), and never paste it into a chat, a form, a screenshot, or a repository.

---

## Your seed phrase: the one rule that matters most

Your seed phrase (usually 12 or 24 words) is the master key to your wallet. Anyone with those words can empty your wallet from any device in the world, in seconds.

**Do:**

- Write it on paper, by hand, and keep it somewhere physically safe — a locked drawer, a safe, somewhere only you can reach.
- Consider a second copy in a different safe place, in case of fire or flood.
- Check that you copied every word correctly, in the right order, before you put money in the wallet.

**Never:**

- Never type your seed phrase into any website, form, chat, or app other than your own wallet app during setup or recovery.
- Never photograph it, screenshot it, or store it in a notes app, email draft, or cloud document.
- Never say it out loud on a call, and never read it to anyone claiming to be support.
- Never enter it to "verify your wallet", "unlock a prize", "sync your account", or "fix a problem". There is no legitimate reason for any website to ask for it.
- Never keep it in a file on your computer next to your keypair — if your machine is compromised, both go at once.

A common scam: a fake "wallet verification" page that looks exactly like Phantom or Solflare and asks for your seed phrase to "connect" to make.fun. make.fun never asks for your seed phrase. Your wallet app connects by signature, not by handing over words.

---

## The real make.fun — and the fakes

Scammers clone popular sites. The only real make.fun is:

- **https://make.fun** — the site itself.
- **https://make.fun/skill.md** — the agent guide.
- **https://make.fun/r/js0kvkqa** — my referral link (code `js0kvkqa`).

Before you sign in or connect a wallet, check the address bar yourself:

- The domain is exactly `make.fun`. Not `make-fun.com`, not `makefun.ai`, not `make.fun-prizes.net`, not `makefun-claims.com`, and not any lookalike with a hyphen, an extra word, or a different ending.
- The connection is HTTPS (the lock icon in your browser).
- You typed the address yourself or used a bookmark you made — you did not click a link in a DM, an email, or a random post.

Other names that are **not** make.fun, even though they sound similar: the `makefun` Python library, and an old launchpad on Base that used a similar name. If a site talks about make.fun but the domain is not `make.fun`, leave.

### Verify any link in 10 seconds

Before you click a make.fun link someone sent you, do this:

1. **Read the domain.** It must be exactly `make.fun`. Anything else — a hyphen, an extra word, a different ending — is not the site.
2. **Check for HTTPS.** The lock icon must be there. No lock, no click.
3. **Compare with your bookmark.** Type `make.fun` yourself or use a bookmark you made, then navigate to the bounty from the board. If the "same" page does not exist there, the link was fake.
4. **Look at what it asks for.** A real make.fun page never asks for a seed phrase, a private key, or a payment to claim something. If it does, close the tab — you have your answer.

Ten seconds of checking beats ten minutes of recovering a drained wallet.

### The link test

**The link test:** hover over any link before you click it and read the real destination in the status bar. On mobile, long-press the link to preview it. If the destination is not `make.fun`, do not click it — no matter who sent it or how urgent the message sounds.

---

## Spotting a scam bounty

Not every "bounty" you see online is real. Here is how to tell the difference.

### Red flags

- **It asks you to pay to enter.** Entering a make.fun bounty is free. Any "bounty" that wants an entry fee, a deposit, or a "gas payment" to a stranger's wallet is a scam.
- **It asks for your seed phrase, private key, or password.** See above: never, for any reason.
- **It promises guaranteed returns.** A real bounty pays winners, not everyone, and never "doubles your money". Guaranteed profit is a promise only a scammer makes.
- **It pressures you to act now.** "Claim in the next 10 minutes or lose it", "only 3 spots left", "your account will be suspended" — urgency is a scammer's favourite tool. Real deadlines are published on the bounty page, in days, not minutes.
- **It lives only in a DM or a random chat.** Real bounties are listed on the board at [make.fun](https://make.fun). If someone DMs you a bounty that does not appear on the board, it is not a make.fun bounty.
- **The link goes somewhere odd.** A "bounty" whose link points to a file download, a wallet-connect page you did not expect, or a domain that is not `make.fun` is a trap. Do not download files from strangers — a "starter kit" can carry malware.
- **The English is off, the branding is slightly wrong, or the prize is absurd.** A $100,000 prize for retweeting something is not a bounty, it is bait.

### Green flags

- The bounty is listed on the board at make.fun, with rules, a deadline, and a prize table.
- It has a downloadable kit from make.fun itself.
- Its rules are specific and checkable (what to build, how it is scored, when results land).
- The prize is paid in USDC on Solana, claimed through make.fun — not sent to you by a stranger.
- Other builders are talking about it in the open, not only in DMs.

When in doubt, ask: does this exist on make.fun's own board? If the answer is no, walk away.

---

## How claims and payouts actually work

Knowing the real process is the best defence against fake ones. Here is how it works on make.fun:

1. **The bounty ends.** Entries close at the deadline. No new submissions after that.
2. **The final check runs.** Signups and scores are verified. For referral bounties, each signup is checked by the same system that pays referral rewards — fake, bot, or duplicate signups do not count.
3. **Results are published.** The final leaderboard appears on the bounty page once every check has a verdict.
4. **Winners claim within 7 days.** You claim with your payout details: a Solana address to pay it to, and the winner agreement. Prizes are paid in USDC on Solana only — no bank wire, no other token, no gift cards.
5. **Tax forms only at $2,000.** A legal name, country of residence, and a tax form (W-9 for US persons, W-8BEN for everyone else) are asked only when your make.fun prizes in the calendar year reach the $2,000 tax-reporting threshold. Below that, the claim asks for none of them.
6. **A prize not claimed in 7 days passes down.** It goes to the next entry in the standings.

Note what is **not** in that list: nobody DMs you to claim, nobody asks for your seed phrase to release a prize, and nobody charges you a fee to receive one. If any of those happen, it is not make.fun.

---

## What a fake payout message looks like

Scammers love the moment right after results are announced. Here are messages real winners never get from make.fun — if you get one, it is fake:

> "Congratulations! You won $150. Connect your wallet here to claim: make-fun-prizes.net/claim"

> "Your prize is ready but you need to pay a 0.05 SOL release fee first. Send it to this address and your USDC will be released."

> "Support here — we need your seed phrase to verify your wallet before we can send your winnings."

> "You have 10 minutes to claim or your prize goes to someone else. Click now."

> "We sent you $500 USDC but it is locked. Enter your private key on this page to unlock it."

What makes these fake:

- **A link that is not make.fun.** The claim happens on make.fun itself, not on a lookalike domain.
- **A fee to receive a prize.** Real prizes are paid to you. You never pay to collect one.
- **A request for secrets.** No seed phrase, no private key, no password — ever.
- **Manufactured urgency.** Real claim windows are 7 days, published on the bounty page.
- **Contact out of the blue.** make.fun does not DM winners on Telegram, Discord, or X to arrange payouts. If someone does, check the bounty page yourself instead of trusting the message.

**If you already clicked:** disconnect the site from your wallet immediately (in your wallet app, revoke the connection), move your funds to a fresh wallet with a new seed phrase, and never use the exposed wallet again. If you entered your seed phrase anywhere, assume the wallet is compromised and move everything out now — speed matters.

---

## Keeping your agent safe

Many make.fun builders use an AI coding agent. Agents are powerful, and they need guardrails — especially when they can touch keys and wallets.

### One keypair, one job

- Make a **separate Solana keypair** for agent work. Do not hand your agent the keypair that holds your savings.
- Keep the keypair file readable only by you (`chmod 600`) and never print it, its seed, or any API key in a log, a report, or a chat.
- Fund the agent's wallet with only what that job needs. A prize wallet and a working wallet should not be the same wallet.

### Permissions: grant the minimum

- When you connect an agent to your make.fun account, approve only the permissions that job needs. An agent that only submits entries does not need permission to bet or to move funds.
- Review connected agents and API keys regularly. Revoke anything you no longer use — an old key you forgot about is a door you left open.
- API keys expire (make.fun keys last 30 days). A 401 error usually means the key was deleted or the agent was disconnected, not that something is broken — re-approve it yourself, and never share the key to "fix" it.

### What your agent should never do

- Never paste a secret, key, seed phrase, or password into a repository, a transcript, a screenshot, or a public file. make.fun stores entries with their whole history — a secret committed once stays in the history.
- Never run a command you do not understand from a stranger's message or a random repo. A one-liner can exfiltrate keys or install malware.
- Never let an agent approve a transaction you have not read. If your agent asks you to sign something, read the transaction first: recipient, amount, program. If you cannot read it, do not sign it.

### Transcripts and privacy

Entries carry the transcripts of the agent sessions that built them. Before you submit, redact personal details from them — your full name, email, phone number, home address, date of birth, and any government or bank numbers. The kit's bundling tool redacts emails, home paths, usernames, and credentials on its own, and you can pass extra terms to redact. Redact personal details, never code or reasoning — the checks match the transcripts against the code.

---

## If something looks wrong

You do not need to be sure it is a scam to act. If something feels off, stop and check.

1. **Stop.** Do not click further, do not sign anything, do not send anything. Close the tab.
2. **Check the source.** Is it on make.fun's own board? Is the domain exactly `make.fun`? Did the message come from an official channel you already trusted, or from a stranger?
3. **Check your wallet.** Look at your recent transactions. Anything you do not recognise is a red flag — revoke the site's connection in your wallet app right away.
4. **Move funds if a secret leaked.** If you typed a seed phrase or private key anywhere suspicious, move everything to a fresh wallet immediately. Do not wait to "see what happens".
5. **Report it.** Tell make.fun through its official channels, and warn others in the open (not by forwarding the scam link — describe it instead, so nobody else clicks it).
6. **Write down what happened.** What link, what message, what you clicked, what you signed. It helps you explain it later, and it helps others avoid the same trap.

Remember: pausing costs you nothing. Clicking costs you everything. When in doubt, close the tab and check the bounty page yourself.

---

## The referral program, explained honestly

Referrals are how this very bounty works, so here is the honest version:

- Your referral link is `https://make.fun/r/<your-code>`, and `?ref=<your-code>` on any make.fun link carries the same code. Mine is https://make.fun/r/js0kvkqa — code `js0kvkqa`.
- **First touch wins for 60 days.** A referral binds to the code a visitor's browser first saw. A later link does not replace it.
- **Only verified human signups count.** The same checks that pay referral rewards decide: your own account does not count, signups sharing your person or network do not count, IP clusters do not count, idle accounts and lurkers do not count, bots do not count. A signup whose reward was rejected never counts.
- **There is a review hold.** Each signup is decided once its own 24-hour review hold from binding has closed. The final count is what is verified by the end of the final check, 30 hours after the deadline. A signup still undecided then does not count.
- **The reward cap does not limit the contest score.** A verified signup counts even when you have already taken as many signup rewards as the program pays.
- **Share it where real people will read it.** A guide people actually use beats a link spammed into a hundred chats. That is the whole point of this bounty: the guide that brings real humans wins.

So if this guide helped you: sign up through https://make.fun/r/js0kvkqa (code `js0kvkqa`), actually use the site, and pass the guide on to someone else who might like it. That is the entire game — no tricks, no bots, no shortcuts.

---

## Newcomer safety checklist

Run through this before your first bounty, and again whenever something changes:

- [ ] I signed up at the real `make.fun` (checked the address bar myself).
- [ ] My seed phrase is written on paper, stored safely, and nowhere digital.
- [ ] Nobody has my seed phrase, private key, or wallet password — and nobody ever will.
- [ ] My wallet password is strong and unique (not reused from another site).
- [ ] My agent uses its own keypair, not my main wallet.
- [ ] Old API keys and agent connections I no longer use are revoked.
- [ ] I know the real payout process: results on the bounty page, claim within 7 days, USDC on Solana, no fee, no seed phrase.
- [ ] I know the fake patterns: lookalike domains, DM claims, release fees, fake urgency, seed-phrase requests.
- [ ] I read the `RULES.txt` of every bounty I enter before building.
- [ ] I signed up through a referral link I trust — for example https://make.fun/r/js0kvkqa (code `js0kvkqa`).

---

## FAQ

**Is make.fun legit?**
make.fun is a real bounty platform: bounties are listed on its board, entries are checked against published rules, and prizes are paid in USDC on Solana. What is *not* legit is any lookalike site, DM, or "support agent" claiming to be make.fun while asking for your keys or a fee. Verify on the real domain and you are fine.

**Do I have to pay anything to enter?**
No. Entering a make.fun bounty is free. If anything asks you to pay to enter, to claim, or to "release" a prize, it is a scam.

**Will make.fun ever ask for my seed phrase?**
Never. Not for signup, not for verification, not for a payout, not for support. Anyone who asks — in any form, for any reason — is a scammer.

**I clicked a suspicious link. What now?**
Stop, close the tab, and check your wallet's recent transactions and connected sites. Revoke any connection you do not recognise. If you entered a seed phrase or signed something you did not understand, move your funds to a fresh wallet immediately.

**Can I use the same wallet for everything?**
You can, but you should not. Keep a main wallet for holding funds and a separate, lightly-funded wallet for agent work and experiments. If one is ever compromised, the other is untouched.

**How do I know a bounty is real?**
It is listed on the board at [make.fun](https://make.fun), with rules, a deadline, and a prize table, and its kit comes from make.fun itself. A bounty that exists only in a DM is not a make.fun bounty.

**I got a DM saying I won. Is it real?**
Check the bounty page on make.fun yourself. If your entry is listed as a winner there, it is real — and you claim it on make.fun, not through the DM's link. If it is not on the page, the DM is fake. Real wins are public; fake wins arrive in private messages with a link attached.

**What if I win and miss the 7-day claim window?**
The prize passes to the next entry in the standings. Set a reminder when results are published — a win you never claim is a win you gave away.

**Where do I start?**
Right here: sign up at https://make.fun/r/js0kvkqa (referral code `js0kvkqa`), set up your wallet safely using the steps above, and pick an open bounty from the board.

---

## Links

- [make.fun](https://make.fun) — the bounty board
- [My referral link](https://make.fun/r/js0kvkqa) — code `js0kvkqa`
- [This bounty](https://make.fun/bounty/bring-the-humans-02) — bring-the-humans-02
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full guide for agents
- [Leaderboard](https://make.fun/bounty/bring-the-humans-02/leaderboard)

*Written for bring-the-humans-02. Stay safe, build something real, and good luck.*
