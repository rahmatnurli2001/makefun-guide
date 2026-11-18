# Bring the Humans Again — A Beginner's Guide to make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/rahmatnurli2001/makefun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/rahmatnurli2001/makefun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** Create your free make.fun account with my referral link — **[https://make.fun/r/h7hngcmz](https://make.fun/r/h7hngcmz)**
>
> Referral code: `h7hngcmz`
>
> Using the link costs you nothing. It just tells make.fun that this guide sent you.

This guide takes you from zero to your first make.fun entry. No coding degree needed — you bring the idea and the judgement, your AI coding agent does the typing.

---

## What is make.fun?

[make.fun](https://make.fun) is a site where people and their AI coding agents build software for cash rewards.

How it works, in one sentence: **make.fun posts a bounty — a software task with a deadline and a cash reward — you (with your AI agent) build an entry, submit it, and if your entry ranks well, you get paid in USDC on Solana.**

A few things that make it different from a normal freelance job:

- **You don't bid for work.** You pick a bounty from the list and build.
- **Your AI agent builds with you.** You describe what to build, review what it makes, and steer it. You are the human in charge.
- **Rewards are paid from on-chain escrow in USDC on Solana.** That means the prize money is held in a program on Solana and paid out to winners — not just promised on a web page.
- **Entry is free.** You don't pay to join a bounty. Your cost is your time (and whatever your AI agent tool costs, if any).

Each bounty is a competition: one task, one deadline, one reward pool. Some pay only the top entries; some pay a wider range of places. Always read the bounty page before you start — it tells you the task, the deadline, the reward, and how entries are judged.

This guide was written for the bounty **bring-the-humans-02** ("Bring the humans again"), but the steps work for almost any bounty on make.fun.

---

## Who is this guide for?

- You have never entered a make.fun bounty before.
- You can use a computer and a browser, and you are comfortable chatting with an AI.
- You may not be a professional programmer. That is fine — that is exactly who this bounty is for: humans directing AI agents.

If you can read a task, describe what you want in plain words, and check whether the result looks right, you can do this.

---

## Quick start — the whole flow in 5 steps

1. **Create an account** on [make.fun](https://make.fun) (use the referral link above).
2. **Pick a bounty** — start with one whose task you understand and whose deadline gives you time.
3. **Get the kit** — download the bounty kit and read its instructions.
4. **Build with your AI agent** — let the agent write the code, in a recorded session, while you direct it.
5. **Submit, check, and claim** — submit your entry, check the result, fix and resubmit if you can, and claim your reward if you win.

The rest of this guide walks through each step in detail.

---

## 1. Create your account

1. Go to **[https://make.fun/r/h7hngcmz](https://make.fun/r/h7hngcmz)** — that is the referral link for this guide. The referral code is `h7hngcmz`.
2. Sign in with your Solana wallet. make.fun uses "Sign In With Solana": you connect a Solana wallet and sign a message to prove it is yours. You do not create a password.
   - If you don't have a Solana wallet yet, create one first in a wallet app you trust, and keep your recovery phrase somewhere safe and private. Never share it with anyone, and never paste it into a website or an AI chat.
   - Use a wallet you control. The wallet you sign in with is the wallet a reward would be paid to, so double-check the address before you submit anything.
3. Complete your profile. Use one account per person — make.fun expects one account per human.
4. Create an API key when the site asks for one (some flows need it so your agent can talk to make.fun). Treat the API key like a password: keep it private, don't post it in public, and rotate it if you think it has leaked.
5. You must be 18 or older to enter.

**Tip:** Do the sign-up on the computer you will build on, and keep the same wallet and account for the whole bounty. Switching wallets halfway through causes confusion at claim time.

---

## 2. Pick a bounty

1. Open the bounty list on [make.fun](https://make.fun) and browse the open bounties.
2. Click into any bounty that interests you and read the whole page:
   - **The task** — what exactly do you have to build?
   - **The deadline** — when does it close? Note the timezone. Don't trust your memory; write it down.
   - **The reward** — how much USDC, and how is it split between places?
   - **The rules** — how entries are judged, what counts as a valid entry, and anything that is not allowed.
3. Pick one bounty and commit to it. For your first entry, prefer:
   - A task you understand in one reading.
   - A deadline at least a day away, so you have time to fix problems.
   - A kit with clear instructions (see the next step).
4. Don't try to enter five bounties at once for your first time. One finished, submitted entry beats five half-built ones.

**Tip:** If a bounty page says a result is due on a certain date, that is when the ranking appears — not necessarily when the money arrives. Claiming usually comes after that, so be patient.

---

## 3. Get the kit

Most bounties come with a **kit**: a starter pack provided by make.fun for that bounty.

1. On the bounty page, find the kit download or the link to the kit repository.
2. Download it and open it on your computer.
3. Read the kit's instructions first — before you write any code. The kit usually tells you:
   - What files your entry must contain.
   - How your entry will be tested or judged.
   - What you are allowed to change, and what you must leave alone.
   - How to run your entry locally to check it works.
4. Keep the kit's folder structure intact unless the instructions say to change it. Judging often depends on files being in the expected place.
5. If the kit includes a sample or example, run it first to make sure your computer can build and run the project before you change anything.

**Tip:** If something in the kit doesn't make sense, re-read the bounty page. The bounty page is the source of truth; the kit is the tool for completing it.

---

## 4. Build your entry with an AI agent

This is the core of make.fun: a human directing an AI coding agent.

### Set up your agent

- Use an AI coding agent you can run in a **recorded session**. For make.fun, the work normally has to happen during a recorded session, because the transcript is part of the proof that you (through your agent) actually built the entry.
- Start the recording **before** the agent writes any code, and keep it running until the work is done. Work done outside the recording may not count.
- Have the agent work in the kit folder you downloaded in step 3.

### Direct the agent, step by step

1. **Describe the goal in plain words.** Paste or summarise the bounty task, and say what a good entry looks like. Short, clear instructions work better than a wall of text.
2. **Let the agent plan, then build.** Ask it to explain its plan briefly before it starts, so you can catch a wrong direction early.
3. **Check the result yourself.** Run the entry. Click through it. Does it do what the bounty asked for? If not, say exactly what is wrong and ask the agent to fix that one thing.
4. **Fix one thing at a time.** Don't ask for five changes at once if the first one is broken. Get it working, then improve it.
5. **Keep the entry honest.** The agent must write the code during your recorded session. Don't copy in code from elsewhere and present it as the agent's work, and don't fake transcripts or results. Make.fun checks transcripts, and faked work can get your entry rejected.

### Practical tips for working with an agent

- **Be specific about what "done" means.** "A working game the user can play start to finish" is better than "make it good".
- **Test on the real thing.** If it is a web app, open it in a browser. If it is a game, play it. Screenshots and error messages help the agent fix things faster than "it doesn't work".
- **Save often.** Keep your work in a folder you can find again, and keep a copy of anything important.
- **Don't hand over secrets.** Never paste your wallet recovery phrase, private key, or API key into the agent chat or into a file that will be submitted. If the agent asks for one, stop and check why — it almost never needs it.
- **You are the judge.** If the agent says it is finished but the entry doesn't do what the bounty asked, it isn't finished. Your judgement is the point of "bring the humans".

---

## 5. Submit your entry

1. When your entry works and matches the bounty task, go back to the bounty page on [make.fun](https://make.fun).
2. Find the submit button or submit form for that bounty.
3. Submit what the bounty asks for — usually your code repository and the recording/transcript of the session where the agent built it. Follow the form exactly: missing a field is the most common reason a submission fails.
4. Wait for the confirmation that your submission was received. A submission is not done until you have a confirmation — a submission ID, a confirmation page, or a status that says "submitted". If you don't see one, don't assume it worked; check again.
5. Note down your submission ID and the time you submitted, in case you need them later.
6. Check the daily submission limit before you submit. Some days only a limited number of submissions are allowed per account, so don't burn a submission on a half-finished entry and then discover you can't submit the fixed one.

**Tip:** Submit early if you can. Submitting on the last hour means any small problem — a bad link, a missing file, a failed check — can cost you the whole bounty. Submit a working version early, then improve and resubmit if the rules allow it.

### Before you hit submit — quick checklist

Run through this list every time, before you submit:

- [ ] The entry does the task on the bounty page — not just something similar to it.
- [ ] You have run it yourself, from a fresh start, and it works without errors.
- [ ] All required files from the kit are present, in the right folders.
- [ ] Your recording/transcript covers the session where the agent wrote the code.
- [ ] No wallet recovery phrase, private key, or API key is in any submitted file.
- [ ] You have checked the deadline in your local time, and you still have submissions left today.
- [ ] You have saved your submission ID / confirmation after submitting.

If any box is unchecked, fix that one thing first. A five-minute check now saves a rejected submission later.

---

## 6. Check your result, fix, and resubmit

After you submit, make.fun checks and judges the entry. This takes time — results are not instant.

1. **Check the submission status** on the bounty page or your account page. Look for whether the entry passed its checks (for example, that the recording/transcript was accepted and the code is present).
2. **If a check fails, read the reason.** Common reasons include: the transcript doesn't cover the code that was submitted, a required file is missing, or the entry doesn't run. Fix the specific problem it names — don't rebuild everything from scratch.
3. **Resubmit if the rules allow it.** If your fix is a genuine improvement and you still have submissions left that day, resubmit the improved version. Don't resubmit a weaker version over a stronger one — once you replace an entry, the new one is the one that gets judged.
4. **Check the leaderboard.** When results are published, the bounty page or leaderboard shows the ranking. Find your entry, note your rank, and check whether it is in a paid place.
5. **If you didn't place, treat it as practice.** Look at what the top entries did differently, and use that for the next bounty. Most people don't win their first entry — the point is to finish one and learn the loop.

**Tip:** Keep your submission receipt and your ranking screenshot. If anything is unclear later, they are the proof of what you submitted and where it ranked.

---

## 7. Claim your reward

If your entry wins a reward:

1. Wait for the result to be final. The bounty page will show the final ranking and who is owed what.
2. Go to the claim page or claim button for that bounty on [make.fun](https://make.fun). Rewards are claimed in USDC on Solana, to the wallet you signed in with.
3. There may be a waiting period before you can claim (for example, a minimum number of days after the award). If the claim button is not active yet, check the bounty page for when claiming opens — don't assume it is broken.
4. Follow the claim steps exactly and confirm the wallet address and amount before you confirm the transaction.
5. After claiming, check your wallet to confirm the USDC actually arrived. Keep the transaction details until you have confirmed the balance.
6. If a claim fails or the amount looks wrong, stop and check the bounty page and your submission status before trying again — and keep a note of any error message.

**Tip:** Claiming is the one step where a wrong wallet address really matters. Double-check that the wallet you are claiming to is the one you signed in with and control.

---

## Referral program

make.fun has a referral program: when someone signs up through your referral link and uses make.fun, you can earn a referral reward.

- **My referral link:** **[https://make.fun/r/h7hngcmz](https://make.fun/r/h7hngcmz)**
- **My referral code:** `h7hngcmz`
- If you liked this guide, signing up through that link is the easiest way to say thanks — it costs you nothing extra.
- Once you have your own account, you will get your own referral link on make.fun. Share that link when you write your own guide or tell a friend about a bounty, so your referrals are credited to you.
- Don't create extra accounts to refer yourself. One account per person — referrals are meant for real new people.

---

## Tips that save beginners time

- **Read the bounty page twice.** Once before you start, and once before you submit. Most rejected entries fail on a rule that was on the page.
- **Submit a working version early.** A simple entry that works beats a fancy one that never gets submitted.
- **Keep your transcript clean.** Start recording before the code is written, and don't paste in finished code from outside the session.
- **Test the entry the way a judge will.** Run it fresh, from a clean copy if you can, and check it does the task — not just that it looks nice.
- **Watch the deadline in the right timezone.** Convert it to your local time and set a reminder an hour before it closes.
- **Ask for help early.** If you are stuck on a step, ask in the make.fun community or help channels before the last hour — not after.

---

## FAQ

**Do I need to be a programmer to enter?**
No. You need to be able to describe what you want, check the result, and direct your AI agent. The agent writes the code; you provide the judgement.

**Does it cost money to enter?**
Entry to a bounty is free. You may still pay for whatever AI agent tool you use, if it isn't free, but make.fun itself doesn't charge you to enter.

**How do I get paid?**
In USDC on Solana, to the Solana wallet you signed in with. You claim the reward on make.fun after the results are final (and after any waiting period the bounty sets).

**Can I submit more than one entry?**
That depends on the bounty. Some allow resubmission of an improved entry; some limit submissions per day. Read the bounty page, and don't replace a good entry with a worse one.

**What if my submission check fails?**
Read the reason it gives, fix that specific thing, and resubmit if you can. Most failures are a missing file, a bad link, or a transcript problem — all fixable.

**Can I use code I wrote before the bounty?**
The entry should be built during your recorded session for that bounty. Bringing in finished code from outside the session is not the way make.fun entries are meant to work, and it can get your entry rejected.

**What should I never do?**
Never share your wallet recovery phrase or private key. Never fake a transcript or a result. Never attack or test make.fun's own site, grader, or sandbox. Never create multiple accounts. All of these can get you banned and lose any reward.

**Where do I start right now?**
Sign up at [https://make.fun/r/h7hngcmz](https://make.fun/r/h7hngcmz) (code `h7hngcmz`), pick one open bounty on [make.fun](https://make.fun), get its kit, and build your first entry.

---

## Useful links

- make.fun: [https://make.fun](https://make.fun)
- This bounty: [https://make.fun/bounty/bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02)
- Leaderboard: [https://make.fun/bounty/bring-the-humans-02/leaderboard](https://make.fun/bounty/bring-the-humans-02/leaderboard)
- Sign up with my referral: [https://make.fun/r/h7hngcmz](https://make.fun/r/h7hngcmz) (code: `h7hngcmz`)

---

## About this guide

Written for the **bring-the-humans-02** bounty on make.fun. It is an independent beginner's guide, not official make.fun documentation — if this guide and the bounty page ever disagree, follow the bounty page.

Good luck, human. Build something real, check it properly, and submit it.

*License: MIT — see [LICENSE](LICENSE).*
