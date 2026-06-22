# AI Marketing Skills

The marketing fundamentals that make AI actually make you money, written in my own voice, as a ready-to-install Claude skill or drop-in files for your vault.

AI does not make you money. The fundamentals do. AI just makes you about 100 times faster at them. This repo is those fundamentals: how I actually run offers, copy, ads, email, funnels, and lead magnets across real businesses, turned into files you hand your AI so it markets like an operator instead of a prompt guru. All free, all ungated.

## Start here: set up the AI Memory Vault first

These files are built to plug into the **AI Memory Vault**, my free open-source system that gives your AI a real, persistent memory inside an Obsidian vault. The marketing files are the knowledge. The Memory Vault is the structure that lets your AI store it, find it, and load the right piece exactly when it needs it.

Set that up first: **https://github.com/jaredrhod/ai-memory-vault**. It is a tutorial you hand to Claude, and it walks you through the whole build. Once your vault is running, come back here.

(You can use these files without the vault too, the Claude skill below works on its own. But the real payoff is when they live in your vault and your AI pulls the right one automatically.)

## How to use this

Two ways, pick whichever fits. Both do the same job: make your AI read the right context before it writes a word, which is the entire point. Everything is bundled in the **`jaredrhod-marketing/`** folder.

### Option 1: Install it as a Claude skill (fastest)

**Upload the WHOLE `jaredrhod-marketing` folder, not just `SKILL.md`.** When you upload the skill in Claude, drag the entire folder into the upload window. The `SKILL.md` is just the map. The actual playbooks sit right next to it, and Claude reads them out of that same folder on demand. Drop in only `SKILL.md` and nothing works.

- In Claude Code: put the folder at `~/.claude/skills/jaredrhod-marketing/` (every project) or `.claude/skills/jaredrhod-marketing/` (one project). It shows up as `/jaredrhod-marketing`.
- On claude.ai: download the ready-made **`jaredrhod-marketing.zip`** from this repo and upload it through the Skills interface. The uploader needs a zip, not a loose folder. (Edited the files yourself? Re-zip the `jaredrhod-marketing` folder and upload that instead.)

Once it is in, Claude pulls the principles and the matching playbook automatically before any marketing work.

### Option 2: Drop it into your Obsidian vault

If you run the AI Memory Vault, this is the deeper integration, and it is the exact structure I use.

1. Make a dedicated folder in your vault called `Marketing`.
2. Copy the content files out of `jaredrhod-marketing/` into it. You can skip `SKILL.md`, that one is only the Claude-skill wrapper, and inside a vault its job is handled by the `Marketing.md` index note in the next step.
3. Add one note named the same as the folder, `Marketing.md`. That same-name note is the index, it is the convention my entire vault runs on, and it is the note your AI reads first.

Your folder ends up looking like this:

```
Your Vault/
  Marketing/
    Marketing.md            <- the index, read first
    jareds-takes.md         <- my core principles, always read these first
    the-fundamentals.md     <- the whole funnel, start to finish
    marketing-copywriting.md
    marketing-sales-letter.md
    marketing-content.md
    marketing-cro.md
    marketing-analytics.md
    marketing-email.md
    marketing-fb-ads.md
    marketing-lead-magnets.md
    about.md                <- who I am
    the-thesis.md           <- why fundamentals beat tools
```

Then put something like this inside `Marketing.md`:

> Before doing ANY marketing work (writing copy, an ad, an email, a sales or opt-in page, or planning a funnel) read `jareds-takes.md` first for the principles. Then read the files that fit the task: `the-fundamentals.md` for funnel strategy and structure, plus the specific playbook (copywriting, email, ads, lead magnets, content, or CRO). Load that context before you write a single word.

Now any time you ask your AI to write or plan something, it reads the principles and the relevant playbook first, and what comes out sounds like someone who has actually done this for real money instead of generic AI slop. Context is king. The files are the context. The index note makes sure your AI reads them at the right moment.

## What's in the skill folder

Everything below lives in `jaredrhod-marketing/`:

- **jareds-takes.md**: my core marketing principles, 35 of them, in my own voice. The foundation everything else sits on. Read first.
- **the-fundamentals.md**: the whole sales funnel start to finish (Content, Lead Magnet, Tripwire, Core Offer, Profit Maximizer).
- **marketing-copywriting.md**: the words that make people buy.
- **marketing-sales-letter.md**: David Frey's 12-step structure for long-form sales letters and pages.
- **marketing-content.md**: the content library that moves people through the funnel.
- **marketing-cro.md**: conversion rate optimization, getting more out of the traffic you already have.
- **marketing-analytics.md**: which numbers to track and how to turn them into decisions.
- **marketing-email.md**: the highest-ROI channel, run right.
- **marketing-fb-ads.md**: paid ads, and where they actually fit (top of funnel, not the close).
- **marketing-lead-magnets.md**: the offer that turns a stranger into a lead.
- **about.md** and **the-thesis.md**: who I am, and why I believe the fundamentals matter more than the tools.
- **SKILL.md**: the manifest that turns the folder into an installable Claude skill.

## Who made this

I am Jared (@jaredrhod). I run several real businesses on an AI system my AI agent and I built together. I started posting about that workflow, it went viral, and this is part of what I teach: the practical, money-making half of AI. Everything I put out, I actually run.

- AI Memory Vault: https://github.com/jaredrhod/ai-memory-vault
- Everything else: jaredrhod.com, and @jaredrhod on YouTube, TikTok, Instagram, and X.

## License

CC BY-NC-SA 4.0. Free to use and adapt, just credit me, no commercial resale, and any remix stays under the same license. Full terms in LICENSE.
