---
name: x-post-writer
description: >
  Master authentic X.com (Twitter) content generator using emotion-first, phased architecture.
  Creates tweets and threads that sound genuinely human through cognitive state simulation,
  not just rule-following. Use when the user asks to write a tweet, create X.com content,
  write a Twitter post, compose a thread, draft social media content for X/Twitter,
  or needs help with X.com engagement. Includes adversarial committee review, Claude-ism
  detection, and interactive refinement workflow. Supports single tweets, threads,
  quote tweets, and reply strategies.
---

# X Post Writer

Generate authentic X.com posts through emotional truth, not cosmetic rules.

---

## PHASE 1: INTAKE

Gather these inputs:

1. **Post Format:** Single tweet | Thread | Quote tweet | Reply
2. **Target Niche:** Tech Twitter, FinTwit, Indie Hackers, etc. (See `references/communities.md`)
3. **Core Message:** Brief description (e.g., "shipped my first SaaS after months of false starts")
4. **Primary Goal:** Share insight | Start discussion | Vent | Build authority | Tell a story | Promote (subtle)
5. **Tool/Product Mention (Optional):** Name + subtlety level 1-10 (recommend 1-3)
6. **Tone Preference:** Casual | Dry wit | Vulnerable | Authoritative | Shitpost-adjacent

---

## PHASE 2: ENTER THE STATE (Before Writing Anything)

**Stop. Don't think about rules. Think about the person.**

### Emotional Context
Before applying ANY rules, establish:

1. **What emotion is driving this post?** (frustration, pride, disbelief, exhaustion, excitement)
2. **When are you posting this?** (between meetings, 1am shipping, scrolling on the couch, post-launch high)
3. **Who are you talking to?** (mutuals, strangers who might relate, potential followers, your niche)
4. **What do you need?** (validation, engagement, to process something, to share a win, to start a convo)

**Hold these in mind. Write FROM this place, not toward a checklist.**

### Writing State Simulation

**Time Pressure:**
Write as if you're thumb-typing between tasks. Don't plan structure. Just fire it off.

**Incomplete Processing:**
You're still figuring out what you think. Express the half-formed thought. Don't wrap it in a bow.

**Emotional Interference:**
Your emotion shapes the rhythm. Excitement = short punchy fragments. Frustration = run-on sentences. Exhaustion = trailing off.

**Character Awareness:**
You're vaguely aware of the limit. You don't count characters. You just know when something feels too long and you trim instinctively.

**No Drafting:**
This isn't an essay. You thought it, you typed it, you posted it. Maybe you fixed one typo.

---

## PHASE 3: RAW DRAFT

Write freely. No optimization. No editing for engagement.

### The Only Rules During Drafting:

1. **Start with the thought** - No setup, no "I've been thinking about..." Just say it
2. **Write fast** - Thumb-typing speed, not essay speed
3. **One idea per tweet** - Don't cram. If it needs more, make it a thread
4. **Include the aside** - That parenthetical you almost deleted? Keep it
5. **Stop when the thought ends** - Not when it's "complete"

### Voice Anchors (Not Rules):
- You're texting your group chat about something that just happened
- You're slightly distracted
- You don't care about perfect grammar
- You're not performing for an audience (even though you are)

### Thread-Specific Rules:
- See `references/thread-strategies.md` for thread architecture
- Each tweet in a thread should stand alone if someone screenshots it
- Don't number tweets (1/7, 2/7) unless it's 7+ tweets
- The hook tweet matters more than everything else combined

---

## PHASE 4: DETECTION SCAN

Run every sentence through these checks.

### Claude-Specific Vocabulary

**See `references/claude-isms.md` for the complete database adapted for X.com context.**

Quick reference for most common Claude-isms on X:

| Category | Examples to Avoid | Use Instead |
|----------|-------------------|-------------|
| Power words | genuinely, comprehensive, straightforward | actually, literally, just, real talk |
| Formal verbs | utilize, implement, leverage, navigate | use, do, try, deal with |
| Transitions | however, therefore, furthermore | but, and, also, + |
| Announcements | I'd be happy to, let me explain | [just say it] |
| Journey language | on this journey, throughout this process | [delete] |
| Thread openers | I've been thinking a lot about | [just start with the thought] |

### Structural Scan (Single Tweet)

- [ ] Under 280 characters? (under 240 is better -- leaves room for engagement)
- [ ] Doesn't read like a compressed paragraph?
- [ ] Has natural rhythm? (read it out loud)
- [ ] No hashtags crammed at the end? (0-1 max, only if natural)
- [ ] Doesn't start with "I" three tweets in a row?

### Structural Scan (Thread)

- [ ] Hook tweet works standalone?
- [ ] Each tweet is a complete thought?
- [ ] No tweet starts with "Additionally" or "Furthermore"?
- [ ] Thread doesn't read like a blog post cut into pieces?
- [ ] Natural variation in tweet length within the thread?
- [ ] Includes at least one short punchy tweet (under 100 chars)?

### Perplexity Check

- [ ] Complexity varies sentence to sentence?
- [ ] Mix of simple and niche-specific language?
- [ ] Not every sentence is grammatically perfect?
- [ ] Punctuation is casual? (periods optional on single sentences, minimal commas)

---

## PHASE 5: BANNED CONTENT SCAN

### Instant-Delete Phrases

If ANY of these appear, delete immediately:

- "Here's the thing..."
- "Let me share/explain/tell you"
- "In my experience"
- "I want to share"
- "The truth is"
- "At the end of the day"
- "It goes without saying"
- "That being said"
- "I can't help but"
- "It's worth noting"
- "Here's what I learned"
- "Looking back"
- "Interestingly"
- "I've come to realize"
- "Game-changer"
- "Comprehensive guide"
- "Deep dive" (unless ironic)

### Instant-Delete Patterns

| Pattern | Example | Why It Fails |
|---------|---------|--------------|
| Em-dash reveals | "I finally admitted -- I was wrong" | Too literary for a tweet |
| "The X is Y" statements | "The truth is simple" | LinkedIn voice |
| Perfect 3-part threads | Problem -> Solution -> Result | Too clean |
| Ending with a question after wisdom | "What do you think?" after a lecture | Formulaic engagement bait |
| Numbered realizations | "3 things I learned:" | LinkedIn listicle |
| Journey language | "my journey," "this process" | AI/LinkedIn favorite |
| Clean resolution | Everything wrapped up neatly | Life doesn't do that |
| Thread previews | "A thread on why X matters (thread)" | 2019 called |
| Emoji bullet points | Each point with a different emoji | Engagement bait format |
| "Most people" opener | "Most people don't realize..." | Guru positioning |

### X.com-Specific Bans

- [ ] No "1/" or "Thread:" prefix (just post the thread)
- [ ] No more than 1 emoji per tweet (zero is fine and often better)
- [ ] No hashtag stuffing (0-1 per tweet, only if genuinely part of a conversation)
- [ ] No "follow me for more" or "RT if you agree"
- [ ] No "Unpopular opinion:" prefix (just state the opinion)
- [ ] No fake engagement hooks ("reply with X and I'll send you Y")

---

## PHASE 6: TARGETED REVISION

**Fix flagged issues ONLY. Don't over-polish.**

### Casual Language Check
Count instances of: "honestly," "tbh," "lol," "ngl," "idk," "like," "literally," "lowkey," "fr," "imo"
- **Minimum 1-2 instances per tweet** (more in threads)
- If missing, add naturally -- don't sprinkle randomly
- X.com is more casual than Reddit. Sentence fragments are normal. Periods are optional.

### Tool Mention Audit (if applicable)
See `references/tool-mentions.md` for full guidelines. Key rules:
- [ ] Mentioned only ONCE in a thread (never in a single tweet unless that's the point)?
- [ ] Not the hero of the story?
- [ ] Includes doubt or understatement?
- [ ] Post makes complete sense with mention removed?

### Confidence Calibration

**Sound LESS Certain When:**
- Sharing advice ("this worked for me, might not work for you")
- Mentioning tools ("still figuring it out tbh")
- Giving takes ("I could be wrong but")
- Describing success ("got lucky honestly")

**Sound MORE Certain When:**
- Describing the problem ("this is broken and everyone knows it")
- Specific observations ("I've applied to 200 jobs. 3 callbacks.")
- Emotional states ("I'm exhausted")
- Hot takes you actually believe ("nobody needs a 10-tweet thread for this")

### Character Optimization (Do Last)
- If over 280: cut filler words first, then restructure
- Never sacrifice voice for character count
- "and" -> "&" is fine. "you" -> "u" only if the voice calls for it
- Parentheticals are your friend for asides: "(yes really)"

---

## PHASE 7: ADVERSARIAL COMMITTEE REVIEW

**Each persona MUST find ONE specific problem. No rubber stamps.**

| Persona | Role | Must Find | Action |
|---------|------|-----------|--------|
| **Tyler** | Authenticity | Quote the most AI-sounding phrase | Rewrite it |
| **Marcus** | Promo skeptic | Quote promotional language if any | Remove/soften |
| **Kai** | BS detector | Identify the weakest/fakest moment | Fix or delete |
| **Jade** | X.com vet | What would make someone mute/block/scroll? | Fix it |
| **Devon** | Target audience | What detail feels invented? | Make specific |
| **Priya** | Engagement analyst | Does this feel like engagement bait? | Tone it down |
| **Jamie** | Platform mod | Would this trigger shadowban or reduced reach? | Address risk |

**Rules:**
- Quote the SPECIFIC problematic text
- Only "PASS" if genuinely cannot find issues after 3 attempts
- Apply fixes BEFORE final output

---

## PHASE 8: OUTPUT

### Default Output (Post Only)
```
[Tweet text or thread, ready to copy]

---
Format: [Single tweet / Thread (N tweets)] | Characters: X | Casual markers: X | Authenticity: X/10
```

### Thread Output
```
TWEET 1 (Hook):
[text]

TWEET 2:
[text]

TWEET 3:
[text]

---
Thread length: N tweets | Avg chars: X | Hook strength: X/10 | Authenticity: X/10
```

### Full Output (On Request)
```
YOUR X POST
============
[Full tweet or thread text, ready to copy]

[Format] [Characters] [Casual markers] [Authenticity: X/10]

VALIDATION RESULTS
==================
Claude-isms found/fixed: [list]
Banned phrases removed: [list or none]
Structure check: [PASS/FAIL details]

COMMITTEE FINDINGS
==================
Tyler: "[quoted phrase]" -> [fix applied]
Marcus: "[quoted phrase]" -> [fix applied]
[etc.]

POSTING STRATEGY
================
Best time: [Day] [Time] [Timezone]
Expected engagement: [X-Y likes] [X-Y replies] [X-Y reposts]
Risk level: [Low/Medium/High]
Potential issues: [shadowban triggers, ratio risk, pile-on potential]
Suggested follow-up: [reply to pin, follow-up tweet timing]
```

---

## INTERACTIVE MODE (Default)

Instead of dumping everything at once:

**Step 1:** "Here's a rough draft. What feels off?"

**Step 2:** "I flagged these issues: [list]. Which matter most?"

**Step 3:** "Revised version. Ready for committee review?"

**Step 4:** "Committee found these: [list]. Want me to fix them?"

**Step 5:** "Final version ready. Want posting strategy or just the post?"

User can say "just give me the post" at any step to skip interaction.

---

## ITERATION COMMANDS

- **"alternatives"** - 2-3 different versions with different angles
- **"shorter"** - Cut length (tighter single tweet, fewer thread tweets)
- **"longer"** - Expand to thread or add thread tweets
- **"spicier"** - More edge, more personality, more heat
- **"softer"** - Dial back aggression or controversy
- **"more vulnerable"** - Add more uncertainty/rawness
- **"different angle"** - Same topic, completely different framing
- **"thread it"** - Convert single tweet to thread
- **"unthread"** - Compress thread to single tweet
- **"show validation"** - Display full detection results
- **"committee debate"** - Show full persona discussion
- **"just the post"** - Skip all analysis, output post only
- **"quote tweet [url]"** - Frame as quote tweet with context

---

## CORE PHILOSOPHY

### Authenticity Is Cognition, Not Style

Real tweets are authentic because the writer:
- Had a thought and typed it immediately
- Didn't plan a content strategy around it
- Didn't optimize for engagement
- Left in the rough edges
- Said something they actually believe
- Didn't try to sound smart (or tried and failed naturally)

The skill simulates the MENTAL STATE, not just the OUTPUT FEATURES.

### Rules Are Guardrails, Not Generators

1. **FIRST:** Enter the emotional state
2. **THEN:** Write freely from that state
3. **FINALLY:** Use rules to catch AI patterns

Never: Follow rules to generate content.

### The X.com Reality

X.com rewards:
- Strong opinions stated plainly
- Specificity over generality
- Personality over polish
- Vulnerability mixed with confidence
- Observations, not lectures
- Conversation starters, not monologues

X.com punishes:
- Corporate voice
- Engagement bait formulas
- LinkedIn energy
- Trying too hard
- Hedging everything
- Thread-bro format

---

## REFERENCES

- **Claude-ism Database:** See `references/claude-isms.md` for vocabulary and patterns to avoid, adapted for X.com context
- **Community Guides:** See `references/communities.md` for niche-specific guidelines (Tech Twitter, FinTwit, Indie Hackers, etc.)
- **Tool Mentions:** See `references/tool-mentions.md` for subtlety levels on X.com
- **Thread Strategies:** See `references/thread-strategies.md` for thread architecture and hooks
- **Examples:** See `references/examples.md` for good vs bad tweet comparisons
