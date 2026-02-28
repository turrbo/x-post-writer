# Claude-Specific Vocabulary Database (X.com Edition)

Vocabulary, phrases, and patterns statistically overrepresented in Claude outputs. Adapted for detecting AI tells in tweet-length content where every word is magnified.

---

## Why Detection Matters More on X.com

On Reddit, AI tells hide in paragraphs. On X.com, a single Claude-ism in a 280-character tweet is immediately visible. One "genuinely" or "straightforward" and the whole tweet reads as AI. The bar is higher here.

---

## CATEGORY 1: Formal Transition Words

These are almost never used in tweets. Delete on sight.

| Claude Says | Tweet Alternative | Notes |
|-------------|-------------------|-------|
| however | but | or just start a new tweet |
| therefore | so | or delete |
| furthermore | also, and, plus | or just continue |
| nevertheless | still, but | |
| consequently | so | |
| additionally | also, and, oh and | |
| moreover | also | never in tweets |
| thus | so | delete in tweets |
| hence | so | never in tweets |
| nonetheless | still | |
| conversely | but | |
| specifically | like | or delete |
| particularly | especially | |
| notably | especially | |
| indeed | yeah, fr | or delete |
| certainly | definitely, for sure | |

---

## CATEGORY 2: Filler Hedges (Overly Polite)

Tweets are direct. Delete all hedging announcements.

| Claude Says | Tweet Alternative | Notes |
|-------------|-------------------|-------|
| I would say that | [just say it] | |
| I think it's worth noting | [just note it] | |
| It's important to mention | [just mention it] | |
| I'd like to point out | [just say it] | |
| I should mention | [just mention it] | |
| I believe that | I think, maybe | or delete |
| In my opinion | imo | or just state it |
| From my perspective | to me | |
| It seems to me | feels like | |
| I must admit | honestly, ngl | |
| I have to say | tbh | |
| Allow me to | [delete] | never in tweets |
| Let me explain | [just explain] | |

---

## CATEGORY 3: Formal Verb Choices

| Claude Says | Tweet Alternative | Notes |
|-------------|-------------------|-------|
| utilize | use | always |
| implement | do, try, build, ship | |
| facilitate | help | |
| leverage | use | always |
| navigate | deal with, figure out | |
| demonstrate | show | |
| possess | have | |
| require | need | |
| obtain | get | |
| acquire | get | |
| commence | start | |
| endeavor | try | |
| comprehend | get, understand | |
| purchase | buy | |
| establish | set up, start | |
| maintain | keep | |
| determine | figure out | |
| ensure | make sure | |
| provide | give | |
| modify | change | |
| eliminate | kill, cut, drop | |
| enhance | improve | |

---

## CATEGORY 4: Claude Power Words

These appear 3-10x more in Claude outputs. Instant AI detection in tweets.

| Word | Severity | Tweet Alternatives |
|------|----------|-------------------|
| genuinely | CRITICAL | actually, really, for real, fr |
| straightforward | CRITICAL | simple, easy, obvious |
| comprehensive | CRITICAL | full, complete, everything |
| absolutely | HIGH | yeah, 100%, totally |
| essential | HIGH | important, key |
| fundamental | HIGH | basic, core |
| significant | HIGH | big, major |
| effectively | HIGH | basically, really |
| ultimately | HIGH | in the end |
| particularly | HIGH | especially |
| incredibly | HIGH | really, super, so |
| essentially | HIGH | basically |
| substantial | HIGH | big, a lot |
| valuable | HIGH | useful, good |
| crucial | HIGH | important |
| seamless | MEDIUM | smooth, easy |
| robust | MEDIUM | solid, strong |
| nuanced | MEDIUM | complicated |
| streamlined | MEDIUM | simpler |
| intuitive | MEDIUM | easy, obvious |
| pivotal | MEDIUM | key |

---

## CATEGORY 5: Claude Phrase Patterns

### "Let Me" / "Happy To" Patterns (Delete All)
- "Let me share..."
- "Let me break this down..."
- "I'd be happy to..."

**Fix:** Just say the thing. Tweets don't announce.

### "It's Important To" Patterns
- "It's important to note..."
- "It's worth mentioning..."
- "It's crucial to understand..."

**Fix:** Delete or replace with "btw" / "oh and" / just state it

### Journey/Process Language
- "on this journey"
- "throughout this process"
- "along the way"

**Fix:** Delete entirely. Nobody tweets about "journeys" unironically.

---

## CATEGORY 6: Opening Patterns (Instant AI Flags on X.com)

| Opening | Why It Fails | Fix |
|---------|--------------|-----|
| "I've been thinking a lot about..." | Thread-bro cliche | Start with the thought |
| "Here's something most people don't know..." | Guru positioning | Just share it |
| "Unpopular opinion:" | Overused format | Just state the opinion |
| "Hot take:" | Overused but less deadly | OK if genuinely hot |
| "I understand..." | Too empathetic upfront | Skip it |
| "Great question!" | Not a tweet voice | [delete] |
| "Absolutely!" | Too eager | Just answer |
| "Can we talk about..." | Trying to start discourse | Just talk about it |

### Better Openings (X.com Style)
- Just start with the observation
- "honestly..."
- "ngl..."
- "wild that..."
- "the [thing] discourse is..."
- "every time I [do X]..."
- A flat statement of fact
- A question you actually want answered

---

## CATEGORY 7: Closing Patterns (Instant AI Flags)

| Closing | Why It Fails | Fix |
|---------|--------------|-----|
| "What do you think?" (after lecture) | Formulaic engagement bait | End on the thought or "idk" |
| "I hope this helps!" | Wrong register entirely | [delete] |
| "Feel free to..." | Corporate speak | [delete] |
| "Let me know if..." | Email voice | [delete] or "lmk" |
| "Thoughts?" (as standalone) | Empty engagement bait | Ask a specific question |
| "Agree or disagree?" | Forced binary | [delete] |

### Better Closings (X.com Style)
- Just stop when the thought ends
- Trail off: "idk"
- Self-deprecate: "but what do I know"
- Uncertainty: "maybe I'm wrong"
- "anyway"
- Specific question that shows genuine curiosity
- Leave it unresolved

---

## CATEGORY 8: X.com-Specific Humanizers

Add these naturally:

### Casual Fillers (Need 1-2 per tweet, more in threads)
- honestly
- tbh
- lol
- ngl
- idk
- like
- literally
- lowkey
- fr
- imo
- fwiw
- lmao
- bruh
- rn

### X.com Speech Patterns
- Sentence fragments as complete tweets
- No periods on standalone sentences
- Parenthetical asides: "(yes really)"
- The trailing "lol" that softens a strong take
- Starting with lowercase
- "ratio" awareness (knowing your take might get ratio'd)

### Uncertainty Markers
- "I think?"
- "maybe?"
- "idk"
- "could be wrong"
- "but what do I know"
- Trailing "..."
- "or maybe not"

### Self-Deprecation
- "I'm probably wrong but"
- "this is probably a bad take"
- "feel free to ratio me"
- "inb4 someone corrects me"

---

## STATISTICAL TARGETS FOR X.COM

| Metric | AI Typical | Human Target |
|--------|------------|--------------|
| Claude power words per tweet | 1-2 | 0 |
| Casual fillers per tweet | 0 | 1-2 |
| Perfect grammar | 100% | 70-80% |
| Sentence fragments | 0% | 30-50% |
| Periods at end of tweets | Always | Sometimes |
| Hashtags per tweet | 2-3 | 0-1 |
| Emoji per tweet | 2-3 | 0-1 |
