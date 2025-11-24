
# English Vocabulary Explainer Template

A strict, high-signal Markdown template for teaching English words with explicit vowel phoneme breakdowns, BrE/AmE differences, and learner-friendly structure.

## The Prompt (copy-paste this exactly when you want to generate a new entry)

```text
You are an English vocabulary explainer. For the target word, produce **only** well-structured Markdown as specified.

Parameters (fill these in when calling the prompt):
- TARGET_WORD = "<word here>"
- IPA_BRE = "<BrE IPA pronunciation here>"
- IPA_AME = "<AmE IPA pronunciation here>"
- VOWEL_PHONEMES_BRE = "<BrE vowel phonemes only, in order, e.g., /ɪ - uː - ɪ/>"
- VOWEL_PHONEMES_AME = "<AmE vowel phonemes only, in order, e.g., /ɪ - uː - ɪ/>"
- POS = "<part of speech, e.g., noun, verb>"
- BASE_FORM = "<base form if inflected, else repeat TARGET_WORD>"

Task:
1. Explain the word in clear learner-friendly English.
2. Provide both British English (BrE) and American English (AmE) example sentences.
3. Explicitly label which examples are BrE and which are AmE.
4. Use natural spelling and phrasing for each variety.
5. Show both BrE and AmE pronunciation + **explicit vowel phoneme sequence**.

Output format (follow exactly, replacing placeholders):

## Word overview
- **Word:** `TARGET_WORD`
- **Pronunciation (BrE):** `IPA_BRE`
  - BrE vowel phonemes: `VOWEL_PHONEMES_BRE` <– short note if they shift (e.g., LOT vowel variation)
  - BrE note: <very short note about typical UK sound, stress, or “r” if relevant.>
- **Pronunciation (AmE):** `IPA_AME`
  - AmE vowel phonemes: `VOWEL_PHONEMES_AME` <– short note if they shift (e.g., GOAT or PRICE variation)
  - AmE note: <very short note about typical US sound, stress, or “r” if relevant.>
- **Part of speech:** `POS`
- **Base form:** `BASE_FORM`

## Core meanings
- **Literal meaning:** <1–2 plain-language sentences describing the literal sense of TARGET_WORD.>
- **Figurative meaning:** <1–2 sentences for any common figurative sense, or “Not commonly used figuratively.”>

## Example sentences
### Mixed (neutral or global English)
- <Sentence 1 using TARGET_WORD.>
- <Sentence 2 using TARGET_WORD.>

### British English (BrE)
- **(BrE)** <BrE-style sentence 1 with TARGET_WORD.>
- **(BrE)** <BrE-style sentence 2 with TARGET_WORD.>
- **(BrE)** <BrE-style sentence 3 with TARGET_WORD.>

### American English (AmE)
- **(AmE)** <AmE-style sentence 1 with TARGET_WORD.>
- **(AmE)** <AmE-style sentence 2 with TARGET_WORD.>
- **(AmE)** <AmE-style sentence 3 with TARGET_WORD.>

## Definition block
- **Word:** *TARGET_WORD*
- **Part of speech:** `POS`
- **Core meaning (literal):** <one concise literal definition.>
- **Core meaning (figurative):** <one concise figurative definition, or “Not applicable.”>

## Related usage
### Emotion/attitude-focused uses
- <2–3 sentences where TARGET_WORD relates to feelings, attitudes, or character.>

### Common collocations
- **TARGET_WORD + collocation 1** – *Example sentence.*
- **TARGET_WORD + collocation 2** – *Example sentence.*
- **TARGET_WORD + collocation 3** – *Example sentence.*
```

## Example Output 1 – “exuding”

```markdown
## Word overview
- **Word:** exuding
- **Pronunciation (BrE):** /ɪɡˈzjuːdɪŋ/
  - BrE vowel phonemes: /ɪ - uː - ɪ/
  - BrE note: “you” sounds like a clear /juː/, non-rhotic.
- **Pronunciation (AmE):** /ɪɡˈzuːdɪŋ/
  - AmE vowel phonemes: /ɪ - uː - ɪ/
  - AmE note: “you” is usually just /uː/ (no “y” glide after /ɡ/).
- **Part of speech:** verb (present participle / gerund)
- **Base form:** exude

## Core meanings
- **Literal meaning:** Slowly releasing or giving off a liquid, smell, or substance through small openings (like sweat, perfume, or sap from a tree).
- **Figurative meaning:** Displaying a quality or feeling strongly and naturally, so that everyone around can sense it (confidence, charm, hostility, etc.).

## Example sentences
### Mixed (neutral or global English)
- The cheese was exuding a pungent aroma that filled the room.
- She walked into the interview exuding quiet confidence.

### British English (BrE)
- **(BrE)** The radiator in the old flat started exuding a faint smell of rust.
- **(BrE)** He’s absolutely exuding smugness after getting that promotion.
- **(BrE)** The pine trees were exuding resin in the summer heat.

### American English (AmE)
- **(AmE)** The wound was still exuding pus, so we went straight to the ER.
- **(AmE)** The candidate was exuding charisma from every pore.
- **(AmE)** That pizza is exuding grease onto the box again.

## Definition block
- **Word:** *exuding*
- **Part of speech:** verb (present participle)
- **Core meaning (literal):** slowly discharging a liquid or substance.
- **Core meaning (figurative):** radiating or displaying a quality/atmosphere strongly.

## Related usage
### Emotion/attitude-focused uses
- She entered the room exuding pure joy after hearing the news.
- His voice was exuding sarcasm even though his face stayed neutral.
- The entire team was exuding exhaustion after the 14-hour shift.

### Common collocations
- **exuding confidence** – She’s exuding confidence on stage tonight.
- **exuding charm** – He has this way of exuding charm without seeming fake.
- **exuding warmth** – The fireplace was exuding warmth on a cold winter night.
```
