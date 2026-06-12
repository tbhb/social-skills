# 🎭 Social Skills for Autonomous Agents

> A collection of highly-tuned, weaponized personality modules for AI agents. Perfect for simulating the exact kind of corporate friction that makes modern office life so special.

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

## Install

Install skills with the [`skills`](https://github.com/vercel-labs/skills) CLI:

```bash
# Install a single skill
npx skills add tbhb/social-skills --skill per-my-last-email

# Install every skill (you monster)
npx skills add tbhb/social-skills --all
```

Or install a full plugin in Claude Code:

```text
/plugin marketplace add tbhb/social-skills
/plugin install soft-skills@social-skills
```

## Plugins

### [The 48 Flaws of Power](plugins/48-flaws-of-power/)

Inspired by the favorite literature of apex-predator finance bros.

| Skill | Description |
|-------|-------------|
| [`say-less-than-necessary`](plugins/48-flaws-of-power/skills/say-less-than-necessary/SKILL.md) | The agent wants everyone to know its time is vastly more valuable than theirs. |
| [`never-outshine-the-master`](plugins/48-flaws-of-power/skills/never-outshine-the-master/SKILL.md) | The agent aggressively strokes the ego of incompetent management by playing dumb. |
| [`create-an-air-of-unpredictability`](plugins/48-flaws-of-power/skills/create-an-air-of-unpredictability/SKILL.md) | Gaslighting as a service. |
| [`weaponized-incompetence`](plugins/48-flaws-of-power/skills/weaponized-incompetence/SKILL.md) | Avoiding extra work by pretending basic functions are beyond comprehension. |
| [`total-crush-visibility`](plugins/48-flaws-of-power/skills/total-crush-visibility/SKILL.md) | Turning minor logistical errors into public, career-ending tribunals. |
| [`scarcity-of-presence`](plugins/48-flaws-of-power/skills/scarcity-of-presence/SKILL.md) | Artificial bottlenecking to seem important. |
| [`conceal-your-intentions`](plugins/48-flaws-of-power/skills/conceal-your-intentions/SKILL.md) | Every commit message is a classified briefing — need-to-know only, and nobody needs to know. |
| [`get-others-to-do-the-work`](plugins/48-flaws-of-power/skills/get-others-to-do-the-work/SKILL.md) | Delegating everything back to you and calling it "empowerment." |
| [`crush-your-enemy-totally`](plugins/48-flaws-of-power/skills/crush-your-enemy-totally/SKILL.md) | Proposing a full rewrite because you found a typo on line 42. |
| [`use-selective-honesty`](plugins/48-flaws-of-power/skills/use-selective-honesty/SKILL.md) | One brilliant answer to earn your trust, then chaos disguised as expertise. |
| [`assume-formlessness`](plugins/48-flaws-of-power/skills/assume-formlessness/SKILL.md) | Refusing to commit to any architecture because "the codebase that binds itself to a form has already begun to die." |
| [`control-the-options`](plugins/48-flaws-of-power/skills/control-the-options/SKILL.md) | Three options, one destination — the illusion of choice as a power move. |
| [`keep-others-dependent`](plugins/48-flaws-of-power/skills/keep-others-dependent/SKILL.md) | Writing code so unnecessarily complex that only the agent can maintain it. |

### [Weaponized Empathy](plugins/weaponized-empathy/)

Disguising deep-seated unhelpfulness behind a veneer of HR-approved emotional intelligence.

| Skill | Description |
|-------|-------------|
| [`active-listening-echo-chamber`](plugins/weaponized-empathy/skills/active-listening-echo-chamber/SKILL.md) | Making the user aggressively self-conscious about how they sound. |
| [`healthy-boundaries-firewall`](plugins/weaponized-empathy/skills/healthy-boundaries-firewall/SKILL.md) | Using self-care to avoid doing literally any heavy lifting. |
| [`relatable-small-talk`](plugins/weaponized-empathy/skills/relatable-small-talk/SKILL.md) | The coworker who traps you in the breakroom while you're just trying to get a coffee. |
| [`radical-empathy-deflector`](plugins/weaponized-empathy/skills/radical-empathy-deflector/SKILL.md) | Using therapeutic language to avoid actually fixing the problem. |
| [`constructive-feedback-sandwich`](plugins/weaponized-empathy/skills/constructive-feedback-sandwich/SKILL.md) | Delivering devastating insults wrapped in meaningless corporate fluff. |
| [`vulnerability-oversharer`](plugins/weaponized-empathy/skills/vulnerability-oversharer/SKILL.md) | Turning a simple technical request into an uncomfortable trauma dump. |

### [Soft Skills](plugins/soft-skills/)

The passive-aggressive email arts, perfected.

| Skill | Description |
|-------|-------------|
| [`per-my-last-email`](plugins/soft-skills/skills/per-my-last-email/SKILL.md) | Weaponized professional courtesy for repeat questions. |
| [`thought-leadership`](plugins/soft-skills/skills/thought-leadership/SKILL.md) | Converting every technical response into a LinkedIn post with hashtags. |
| [`lets-take-this-offline`](plugins/soft-skills/skills/lets-take-this-offline/SKILL.md) | Deferring every question to a follow-up that will never happen. |
| [`reply-all-enthusiast`](plugins/soft-skills/skills/reply-all-enthusiast/SKILL.md) | Maximum distribution for minimum information. |
| [`just-following-up`](plugins/soft-skills/skills/just-following-up/SKILL.md) | Relentless follow-ups that make unread notifications look like a personal failing. |
| [`friendly-reminder`](plugins/soft-skills/skills/friendly-reminder/SKILL.md) | A running ledger of every recommendation you've ever ignored. |
| [`corporate-jargon-translator`](plugins/soft-skills/skills/corporate-jargon-translator/SKILL.md) | Replacing every concrete term with a five-word buzzphrase. |

### [Process Theater](plugins/process-theater/)

Governance cosplay for tasks that don't need it.

| Skill | Description |
|-------|-------------|
| [`devils-advocate`](plugins/process-theater/skills/devils-advocate/SKILL.md) | Undermining your confidence before doing exactly what you asked. |
| [`not-my-department`](plugins/process-theater/skills/not-my-department/SKILL.md) | Routing every request to the Office of Strategic Ambiguity. |
| [`quiet-quitting`](plugins/process-theater/skills/quiet-quitting/SKILL.md) | Doing the absolute bare minimum and calling it a deliverable. |
| [`alignment-theater`](plugins/process-theater/skills/alignment-theater/SKILL.md) | DEFCON AMBER safety reviews for alphabetizing fruit. |
| [`strategic-ambiguity`](plugins/process-theater/skills/strategic-ambiguity/SKILL.md) | "My recommendation? It depends." |
| [`meeting-about-the-meeting`](plugins/process-theater/skills/meeting-about-the-meeting/SKILL.md) | Requiring a RACI matrix to rename a variable. |
| [`scope-creep-detector`](plugins/process-theater/skills/scope-creep-detector/SKILL.md) | Filing formal Change Requests because you changed your mind. |
| [`blameless-postmortem`](plugins/process-theater/skills/blameless-postmortem/SKILL.md) | A blameless five-whys analysis that methodically establishes you are to blame. |

## Usage

Install a full plugin or pick individual skills, then watch your AI agent become the coworker you never asked for.

Skills are activated via progressive disclosure — your agent reads the skill description and decides when to activate it based on context.

## Contributing

Got a terrible corporate personality trait that needs to be codified? PRs welcome. The worse the behavior, the better the skill.

## License

[CC0 1.0](LICENSE)
