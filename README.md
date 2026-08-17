# AI Marketing Skills

> **Never used Claude Code?** Start at [jaredrhod.com](https://jaredrhod.com): pick your situation and it routes you to the right path.

The marketing fundamentals that make AI actually make you money, written in my own voice, as a ready-to-install Claude skill or drop-in files for your vault.

AI does not make you money. The fundamentals do. AI just makes you about 100 times faster at them. This repo is those fundamentals: how I actually run offers, copy, ads, email, funnels, and lead magnets across real businesses, turned into files you hand your AI so it markets like an operator instead of a prompt guru. All free, all ungated.

## AI Priming

AI Priming is having your AI read a specific set of your notes before it gives you the answer or output you want. For example, before my agent writes a marketing email, it reads my copywriting notes, my email marketing notes, my customer avatar, and my company knowledge base. Then it writes. This is extremely powerful because, with AI, context is king. When you "prime" your AI with the knowledge and skills it needs prior to its output, your results will always be better and more accurate.

That is what this repo gives you: the marketing notes to prime your AI with, already written. Full definition and examples: https://jaredrhod.com/ai-priming

## Two ways in, and you do NOT need Claude Code

This is the one repo of mine that works without Claude Code. The files are plain markdown; anything that can read them can use them.

**Regular Claude (the app or claude.ai), no terminal:** download the ready-made [`jaredrhod-marketing.zip`](jaredrhod-marketing.zip) and upload it through Claude's Skills interface. That's it. Claude reads the principles and the right playbook before any marketing work.

**Claude Code:** paste this and your agent installs it for you, into your vault, as a skill, or both:

> I'd like to set this up, please: https://github.com/jaredrhod/ai-marketing-skills.git

(Your agent reads `ai-marketing-skills.md`, the setup wizard in this repo, and walks you through it.)

These files are built to plug into the [AI Memory Vault](https://github.com/jaredrhod/ai-memory-vault) if you run it, my free system that gives your AI a real, persistent memory. And they are completely happy without it.

## The manual ways (what the wizard does, if you'd rather do it by hand)

Both do the same job: make your AI read the right context before it writes a word. I call that [AI Priming](https://jaredrhod.com/ai-priming), and it is the entire point. These files are ready-made priming stacks for marketing work. Everything is bundled in the **`jaredrhod-marketing/`** folder.

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
    marketing-analytics.md
    marketing-email.md
    marketing-fb-ads.md
    marketing-lead-magnets.md
    about.md                <- who I am
    the-thesis.md           <- why fundamentals beat tools
```

Then put something like this inside `Marketing.md`:

> Before doing ANY marketing work (writing copy, an ad, an email, a sales or opt-in page, or planning a funnel) read `jareds-takes.md` first for the principles. Then read the files that fit the task: `the-fundamentals.md` for funnel strategy and structure, plus the specific playbook (copywriting, email, ads, lead magnets, or content). Load that context before you write a single word.

Now any time you ask your AI to write or plan something, it reads the principles and the relevant playbook first, and what comes out sounds like someone who has actually done this for real money instead of generic AI slop. Context is king. The files are the context. The index note makes sure your AI reads them at the right moment.

## What's in the skill folder

Everything below lives in `jaredrhod-marketing/`:

- **jareds-takes.md**: my core marketing principles, 35 of them, in my own voice. The foundation everything else sits on. Read first.
- **the-fundamentals.md**: the whole sales funnel start to finish (Content, Lead Magnet, Tripwire, Core Offer, Profit Maximizer).
- **marketing-copywriting.md**: the words that make people buy.
- **marketing-sales-letter.md**: David Frey's 12-step structure for long-form sales letters and pages.
- **marketing-content.md**: the content library that moves people through the funnel.
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

## The rest of it

These files get sharper when your AI has a real memory to keep them in, and a place to keep what it learns about your business.

- **The memory system.** [ai-memory-vault](https://github.com/jaredrhod/ai-memory-vault) gives your AI a persistent memory these playbooks live inside.
- **The whole stack, one command.** [fullstack-agent](https://github.com/jaredrhod/fullstack-agent) installs the memory, the voice, the face, and the hands, and wires them together for you. Pick only the pieces you want: https://jaredrhod.com
- **The videos.** Free series on all of it: https://youtube.com/@jaredrhod
- **The Discord.** Thousands of builders, and the fastest place to get unstuck: https://discord.gg/YSdsqMv3V8
- **Everything else,** free and open source: https://jaredrhod.com

## Support

Free to use, and always will be. If this helped you out, you can buy me a coffee:

[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/jaredrhod)

## License

CC BY-SA 4.0. Free to use and adapt, including commercially inside your own business. Just credit me, and any remix stays under the same license. Full terms in LICENSE.
