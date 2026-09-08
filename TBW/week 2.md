# Grammar Essentials + The Style of Technical Writing — Notes (v2, Expanded)

## PART A: GRAMMAR FOUNDATIONS

### 1\. Phrases

A **phrase** is a group of related words that does **not** contain both a subject and a verb, and acts as a single part of speech.

|Type|Description|Example|
|-|-|-|
|Noun phrase|Noun + modifiers|*The final year project report* is due Friday.|
|Verb phrase|Main verb + helping verb(s)|The system **has been tested** thoroughly.|
|Prepositional phrase|Preposition + object|The bug was found **in the login module**.|
|Gerund phrase|-ing verb acting as noun|**Debugging the server** took two hours.|
|Participial phrase|-ing/-ed verb acting as adjective|**Running low on memory**, the app crashed.|
|Infinitive phrase|to + verb|The team plans **to deploy the update tonight**.|

> Key idea: a phrase is \*\*incomplete\*\* — it can't stand alone as a sentence.

### 2\. Clauses

A **clause** contains both a **subject** and a **verb**.

#### a) Independent Clause (IC)

* Expresses a complete thought.
* Can stand alone as a sentence.
* Example: *The server crashed.*

#### b) Dependent Clause — Subordinate type

**Structure:** subordinating conjunction + independent clause

* Has a subject + verb but **cannot** stand alone.
* Begins with a subordinating conjunction (because, although, when, since, if, while, unless…).
* Example: *because the server crashed* (incomplete on its own)

#### c) Dependent Clause — Relative type

**Structure:** relative pronoun (who, which, that, whom, whose) + independent clause

* Has a subject + verb but **cannot** stand alone.
* Begins with a relative pronoun and typically modifies a noun right before it.
* Example: *which crashed twice last week* (incomplete on its own — needs a noun to attach to, e.g., "The server, **which crashed twice last week**, was replaced.")

> \*\*Difference between the two dependent-clause types:\*\* Subordinate clauses answer \*why/when/if/although\* questions about the whole sentence. Relative clauses describe/identify a specific noun. Test: if you can replace the clause-starter with "who/which/that" and it points at a noun right next to it, it's relative; if it answers a "why/when/condition" question about the action, it's subordinate.

**Three common dependent clause functions:**

|Type|Function|Example|
|-|-|-|
|Noun clause|Acts as a noun|**What the tester found** surprised the team.|
|Adjective (relative) clause|Modifies a noun|The module **that failed** needs review.|
|Adverb clause|Modifies a verb/clause (time, cause, condition)|**Although the code compiled**, it crashed at runtime.|

### 3\. Conjunctions

#### a) Coordinating Conjunctions — join equal (independent) elements

**FANBOYS**: For, And, Nor, But, Or, Yet, So

* Example: *The code compiled, **but** it failed the test cases.*
* Example: *We can refactor the module, **or** we can rewrite it.*

#### b) Subordinating Conjunctions — join a dependent clause to an independent clause

Common ones: because, although, since, if, when, while, unless, after, before, whereas, even though

* Example: *The system crashed **because** memory usage exceeded the limit.*
* Example: *We will deploy the patch **unless** new bugs appear.*

#### c) Correlative Conjunctions — work in pairs to link matching elements

Common pairs: either…or, neither…nor, both…and, not only…but also, whether…or

* Example: *The error occurred **either** due to a null pointer <b>or</b> a memory leak.*
* Example: *The report was **not only** late <b>but also</b> incomplete.*
* Rule of thumb: whatever grammatical form follows the first word of the pair must also follow the second (parallel structure) — e.g., *not only late (adjective) but also incomplete (adjective)*, not *not only late but also it was incomplete*.

### 4\. Sentence Structures (built from clauses)

|Sentence Type|Structure|Example|
|-|-|-|
|**Simple**|1 independent clause|*The program crashed.*|
|**Compound**|2+ independent clauses joined by a coordinating conjunction, **or** a semicolon if the clauses are closely related|*The program crashed, and the logs were lost.* / *The program crashed; the logs were lost.*|
|**Complex**|1 independent clause + 1+ dependent clause, in either order|*The program crashed because the memory was full.* / *Because the memory was full, the program crashed.* (Note: when the dependent clause comes first, it's followed by a comma.)|
|**Compound-Complex**|2+ independent clauses + 1+ dependent clause|*The program crashed because the memory was full, and the team had to restart the server.*|

**Quick test:**

* Simple = 1 subject-verb unit, complete thought.
* Compound = two complete thoughts joined (both can stand alone).
* Complex = one complete thought + one incomplete (dependent) thought — clause order can flip, comma rule changes with it.
* Compound-complex = combination of both.

\---

## PART A-EXTRA: PRONOUN REFERENCE — FULL DETAILED BREAKDOWN

### Pronoun

##### Personal Pronouns



Subject: I, you, he, she, it, we, they

Object: me, you, him, her, it, us, them



##### Possessive Pronouns



Possessive adjectives (determiners): my, your, his, her, its, our, their

Possessive (standalone): mine, yours, his, hers, its, ours, theirs



##### Reflexive Pronouns



myself, yourself, himself, herself, itself, ourselves, yourselves, themselves



##### Intensive Pronouns (same words as reflexive, used for emphasis)



myself, yourself, himself, herself, itself, ourselves, yourselves, themselves



##### Demonstrative Pronouns



this, that, these, those



##### Interrogative Pronouns



who, whom, whose, which, what



##### Relative Pronouns



who, whom, whose, which, that

##### 

##### Indefinite Pronouns



Singular: anyone, anybody, anything, everyone, everybody, everything, someone, somebody, something, no one, nobody, nothing, each, either, neither, one, another

Plural: both, few, many, several, others

Singular or plural (context-dependent): all, any, more, most, none, some



##### Reciprocal Pronouns



each other, one another

##### 

##### Archaic/Formal Pronouns (rare, mostly historical or dialectal)



thou, thee, thy, thine, ye

### Why this matters

A pronoun (it, this, that, they, which, he, she) is a **stand-in** for a noun (its "antecedent"). The reader's brain automatically tries to match the pronoun to the *nearest logical noun*. In technical writing this isn't a style nitpick — a misread pronoun in a safety manual, contract, or requirements document can cause real damage, lawsuits, or bugs, because the reader silently picks the *wrong* antecedent and never realizes it.

There are **three distinct ways** a pronoun reference can go wrong, and one "gold standard" of how it should look. Learning to tell them apart is the actual skill — not just avoiding pronouns.

\---

### THE BASELINE: Clear (Correct) Reference

The pronoun has **exactly one** possible antecedent, and it is **close by**.

> ✅ \*The client sent a request to the server, and the server responded within 200ms.\*
(No pronoun used — full noun repeated because both nouns are "server-like" and could confuse.)

> ✅ \*The manager reviewed the report, and she approved it.\*
("She" = only one female-referenced noun in the sentence: "manager." "It" = only one non-human noun: "report." Both are unambiguous.)

**How to identify a clear reference:** Cover up everything except the pronoun and ask "if I had to point to ONE word in this sentence that this pronoun means, could I point to exactly one, instantly, with no hesitation?" If yes → correct usage.

\---

### ERROR TYPE 1: Ambiguous Reference

**Definition:** The pronoun has **two or more grammatically valid antecedents**, and the reader cannot tell which one is meant.

> ❌ \*The server sent data to the client, but it crashed.\*
> — "It" could logically be the server OR the client. Both are singular, non-human nouns sitting right before the pronoun.

> ❌ \*Ali told Ahmed that his code had a bug.\*
> — "His" could refer to Ali's code or Ahmed's code. Both are male nouns in the sentence.

**How to identify Ambiguous Reference (the test):**

1. Locate the pronoun.
2. List every noun before it that matches its grammatical category (singular/plural, person/thing, gender).
3. If **two or more nouns qualify equally**, it is ambiguous.

**How to correct it:**

* Replace the pronoun with the specific noun.
* Or restructure the sentence so only one noun can be "it."

> ✅ \*The server sent data to the client, but the client crashed.\*
> ✅ \*Ali told Ahmed that Ahmed's code had a bug.\* (or restructure: \*Ali pointed out a bug in Ahmed's code.\*)

\---

### ERROR TYPE 2: Broad / Vague Reference

**Definition:** The pronoun (usually **this, that, which, it**) doesn't refer to any single noun at all — it refers to an **entire idea, clause, or situation** mentioned earlier. Grammatically there's no "candidate noun" competing; the problem is that there's **no noun candidate at all**, just a vague cloud of meaning.

> ❌ \*The team missed the deadline and lost the client's trust, which really hurt morale.\*
> — What does "which" refer to? Not "trust," not "deadline" alone — it means "the whole situation of missing the deadline and losing trust." That's not a noun; that's an idea.

> ❌ \*The server kept restarting and dropping connections, and it was very frustrating for the users.\*
> — "It" = the entire ongoing situation, not one noun.

**How to identify Broad/Vague Reference (the test):**

1. Locate the pronoun.
2. Try to substitute a single noun in its place.
3. If the only thing you can substitute is a **summary phrase describing the whole preceding clause** (e.g., "this situation," "this problem," "this failure") — rather than one existing word already in the sentence — it's broad/vague reference.

**Key distinguishing feature vs. Ambiguous Reference:** In *Ambiguous Reference*, there are too many candidate nouns (a "too many suspects" problem). In *Broad/Vague Reference*, there are zero candidate nouns (a "no real suspect" problem) — the pronoun is pointing at an idea, not a word.

**How to correct it:**

* Insert an explicit summary noun right after the pronoun ("this problem," "this delay," "this failure").
* Or rewrite the sentence to state the idea directly instead of using a pronoun.

> ✅ \*The team missed the deadline and lost the client's trust — this failure really hurt morale.\*
> ✅ \*The server's repeated restarts and dropped connections frustrated the users.\* (pronoun removed entirely)

\---

### ERROR TYPE 3: Remote / Implied (Indefinite) Reference

**Definition:** The pronoun refers to an antecedent that is either **never actually stated as a noun** (only implied), or is **too far away** in the text for the reader to reasonably trace back to it.

> ❌ \*In the report, they say the system is unstable.\*
> — Who is "they"? No noun anywhere in the sentence names a group. It's implied ("the authors of the report"?) but never stated.

> ❌ \*I like using Python because it's what my company uses, but sometimes they change frameworks without warning.\*
> — "They" has no stated antecedent — "company" is singular and was never described as a group of people ("they" doesn't grammatically match "company" as a collective noun here, and no other plural noun exists).

> ❌ (Remote example) \*The engineering team spent three weeks designing the new authentication module, running extensive tests, documenting the API, and coordinating with the frontend team before the final release. It failed within a day.\*
> — "It" is meant to refer to "the new authentication module," but so many words and clauses have piled up in between that the reader has lost track of the original noun.

**How to identify Remote/Implied Reference (the test):**

1. Locate the pronoun.
2. Search backward for a **matching noun that was actually written down** (not just implied by context).
3. If you find **no such noun at all**, OR you find one but it's **several sentences / a long clause away**, it's remote/implied.

**Key distinguishing feature vs. the other two:** Ambiguous = too many candidates nearby. Broad/Vague = zero candidates, points at an idea. Remote/Implied = the candidate noun technically doesn't exist in the text (only in the writer's head), or exists but is buried too far back to be usable.

**How to correct it:**

* Name the real antecedent explicitly, even if it means introducing a new noun that was only implied before.
* If the antecedent exists but is too far away, repeat the noun near the pronoun instead of relying on memory.

> ✅ \*In the report, the auditors state the system is unstable.\*
> ✅ \*I use Python because my company's tech stack is built on it, but the architecture team sometimes changes frameworks without warning.\*
> ✅ \*...before the final release. The authentication module failed within a day.\* (noun repeated instead of "it")

\---

### SIDE-BY-SIDE COMPARISON TABLE

|Feature|Ambiguous Reference|Broad/Vague Reference|Remote/Implied Reference|
|-|-|-|-|
|**Root problem**|Too many valid antecedents|Zero noun antecedents — refers to a whole idea|Antecedent missing, or too far away|
|**Typical pronouns involved**|it, he, she, his, her|this, that, which, it|they, it, this|
|**Diagnostic question**|"Which noun — A or B?"|"Can I point to ONE existing noun, or only to 'the whole situation'?"|"Is there any noun in the text this could mean? How far back?"|
|**Example**|*The server sent data to the client, but it crashed.*|*We missed the deadline, which hurt morale.*|*In the report, they say the system is unstable.*|
|**Fix strategy**|Name the specific noun|Add a summary noun after the pronoun|State the real antecedent explicitly|
|**Corrected version**|*...but the client crashed.*|*...— this delay hurt morale.*|*...the auditors state...*|

### Quick 3-Step Universal Correction Method

1. **Find** the pronoun.
2. **Trace** it back — ask "what single, already-written noun does this replace?"
3. **Diagnose and fix:**

   * Multiple valid nouns found → **Ambiguous** → name the specific one.
   * No noun found, only an idea/situation → **Broad/Vague** → add a summary noun.
   * No noun found at all, or too far back to trust → **Remote/Implied** → state the antecedent explicitly.

> \*\*Rule for high-stakes technical writing\*\* (safety instructions, legal/contract clauses, requirements specs): when in doubt, \*\*repeat the full noun\*\* rather than use a pronoun at all. Clarity beats elegance when the cost of misreading is high.

\---

## PART B: THE SEVEN Cs OF COMMUNICATION

*(A complementary framework to SCOPE — not from your course material, but useful for comparison.)*

|C|Meaning|Example Fix|
|-|-|-|
|**Clarity**|Message is easy to understand, one idea per sentence|"The system works well" → "The system processed 1,000 requests/sec without errors."|
|**Conciseness**|No unnecessary words|"Due to the fact that" → "Because"|
|**Concreteness**|Specific, supported by facts/figures|"Recently" → "On March 5, 2024"|
|**Correctness**|Grammatically accurate, correct facts/terms|Proper grammar, accurate technical terms|
|**Coherence**|Logical flow; ideas connect smoothly|Use transitions (however, therefore, as a result)|
|**Completeness**|All necessary information included (who, what, when, where, why, how)|Meeting notice should include date, time, place, purpose|
|**Courtesy**|Polite, respectful, considerate tone|"Please review by Friday" instead of "Do this by Friday."|

> Note: your course teaches \*\*SCOPE\*\*, not the 7 Cs. This is included only as a reference model — don't confuse the two in an exam.

\---

## PART C: SCOPE — The Style of Technical Writing (Full Diagnostic Guide)

**S-C-O-P-E** = Simplicity, Clarity, Objectivity, Precision, Economy

### Why diagnosis is hard

Real flawed sentences almost never break just *one* SCOPE rule — they usually break two or three at once. The skill isn't memorizing five definitions; it's being able to look at a messy sentence and correctly assign **which word or phrase belongs to which category**, because each category is fixed differently.

### THE FIVE PRINCIPLES — Full Definitions with Contrast

#### S — Simplicity (governs: word choice / vocabulary)

**Diagnostic question:** *Is any individual word too complicated, too informal, or unnecessarily technical for the audience?*
Violations: colloquialisms, slang, jargon (undefined), clichés, gobbledygook, gender-biased pronouns.

> ❌ \*The app totally freaked out; the guy said the code went nuts.\* (informal/slang)
> ❌ \*Utilization of the aforementioned methodology facilitated amelioration.\* (gobbledygook)
> ✅ \*The application failed during deployment; the engineer reported a system error.\*

**How to tell it's a Simplicity issue and not a Clarity issue:** Simplicity is about the *difficulty of a single word*, in isolation — you could replace just that one word and fix it, without touching sentence structure. If replacing one word fixes it, it's Simplicity. If you'd have to reorganize or add missing information, it's Clarity.

#### C — Clarity (governs: sentence structure + amount of detail)

the detail is completely absent or untraceable

**Diagnostic question:** *Would a reader honestly say "Huh?" — not because the words are hard, but because the sentence is vague, disorganized, or has an unclear pronoun?*
Violations: vague words (recently, some, a lot), missing 5W1H info, unclear pronoun reference, poor paragraph/document organization.

> ❌ \*The program runs faster now.\* (vague — this specific example is BOTH a Clarity issue \[no context of comparison] and overlaps with Precision — see below)
> ✅ \*After optimization, execution time decreased from 3.2s to 1.8s.\*

**How to tell it's Clarity and not Simplicity:** The words themselves might all be simple and correct — the problem is the reader still can't picture what's being described because information is missing or the structure is jumbled.

**How to tell it's Clarity and not Precision:** This is the trickiest overlap. Ask: *is the problem "I don't know what you mean" (Clarity) or "I know what you mean, but I want the exact number" (Precision)?*

* "The team fixed some bugs" → Clarity problem (which bugs? how many? — the sentence itself doesn't communicate a complete idea)
* "The team fixed several critical bugs" → Precision problem (we understand the sentence, but "several" should be a number)

#### O — Objectivity (governs: tone / vocabulary + structure)

**Diagnostic question:** *Does this sentence contain a personal opinion, emotion, or judgment instead of a fact?*
Violations: "I think/believe/feel," emotional adjectives (amazing, terrible, disappointing), absolute claims without evidence, unnecessary first-person voice.

> ❌ \*I think the algorithm is really amazing.\*
> ✅ \*The algorithm demonstrates improved efficiency based on reduced execution time.\*

**How to tell it's Objectivity and not any other category:** This is the *easiest* one to isolate — objectivity issues are about **whose voice is speaking** (a feeling vs. a fact), and they don't care about word difficulty, sentence length, or level of detail. A sentence can be simple, clear, precise, AND economical, and still fail Objectivity purely because it contains "I think" or "amazing."

Test: strip the sentence down — does it contain a **feeling word** or a **first-person opinion phrase**? If yes → Objectivity, regardless of anything else going on in the sentence.

#### P — Precision (governs: vocabulary + length, specifically around facts/numbers)

some detail is present, but it's vague/non-exact (a fuzzy quantifier, comparative, or time reference standing in for a real number). The information exists — it's just not measurable.

**Diagnostic question:** *Is there a vague quantity, time, or comparison word that should be replaced with an exact fact or figure?*
Violations: vague adjectives/adverbs of degree (a lot, several, recently, faster, better, many), comparisons without a stated baseline ("better" — better than what?).

> ❌ \*The system runs faster now.\*
> ✅ \*The system now responds in 1.2 seconds, down from 3.5 seconds.\*

**How to tell it's Precision and not Economy:** Precision issues are usually about **too little information** (a vague word standing in for a fact). Economy issues are the opposite — **too many words** saying too little. A sentence can be wordy AND vague at the same time — that's both Precision and Economy failing together.

> ⚠️ \*\*Caution repeated:\*\* Precision does not mean inventing numbers you don't have. If you don't have the data, say so, or use cautious/hedged language (see Objectivity's modality point) rather than fabricating a figure.

#### E — Economy (governs: length of text)

**Diagnostic question:** *Could this exact same meaning be said in fewer words?*
Violations: redundancy, prepositional pile-ups, unnecessary passive voice, shun/camouflaged words, nominalizations (turning verbs into nouns), "there is/there are" openers, buried main verb.

> ❌ \*We are of the opinion that a decision should be made regarding the possibility of implementation.\* (17 words)
> ✅ \*We believe we should decide whether to implement this.\* (9 words)

**How to tell it's Economy and not Simplicity:** Economy is about the **total word count / structure of the sentence**, not the difficulty of individual words. "Due to the fact that" uses only simple, common words — none of them are hard to understand — but the *phrase as a whole* is bloated. That makes it an Economy issue, not a Simplicity issue, even though no single word looks complicated.

\---

### MASTER DIAGNOSTIC FLOWCHART (use this in order on any flawed sentence)

1. **Does it contain "I think/believe/feel," an emotional word, or an unsupported absolute claim?**
→ Yes: **Objectivity** violation. Fix: remove opinion, use evidence/facts, use modality if uncertain.
2. **Does any single word look hard, slangy, clichéd, jargon-y, or gender-biased?**
→ Yes: **Simplicity** violation. Fix: swap that one word/phrase for a simpler, formal, neutral equivalent.
3. **Is there a vague quantity/time/comparison word standing in for a fact ("recently," "faster," "many," "some")?**
→ Yes: **Precision** violation. Fix: replace with an exact number, date, or measurable fact (only if you actually have it).
4. **Even with simple words and specific facts, is the sentence still confusing — unclear pronoun, missing who/what/when/where/why/how, or badly organized?**
→ Yes: **Clarity** violation. Fix: restructure, answer the missing question, fix pronoun reference, or choose the correct organizational pattern (spatial/chronological/importance/comparison/problem-solution).
5. **Is the sentence longer than it needs to be — redundant phrases, unnecessary passive voice, nominalizations, "there is/are," buried verb?**
→ Yes: **Economy** violation. Fix: cut redundancy, activate the verb, un-bury the subject-verb pair, remove filler phrases.

> A sentence can trigger \*\*multiple "yes" answers\*\* — that's normal. Fix them in the order above (Objectivity and Simplicity first, since they're usually single-word/phrase swaps; Clarity and Economy often require restructuring the whole sentence, so do those last).

\---

### FULL WORKED EXAMPLE (multi-violation diagnosis)

> \*\*Original:\*\* \*"I think that due to the fact that the system, which we recently upgraded, is now really much better, we should proceed with the aforementioned deployment strategy for our clients."\*

**Step-by-step diagnosis:**

|Phrase|Violation|Category|Why|
|-|-|-|-|
|"I think"|Personal opinion, no evidence|**Objectivity**|Presents a claim as feeling, not fact|
|"due to the fact that"|Wordy phrase for "because"|**Economy**|Same meaning, 5 words → 1 word|
|"aforementioned"|Pompous/gobbledygook word|**Simplicity**|Hard, stiff, unnecessary word|
|"recently"|Vague time reference|**Precision**|No exact date given|
|"really much better"|Vague comparison, no baseline/number|**Precision**|"Better" compared to what, by how much?|
|Overall sentence|Long, buries the actual recommendation|**Clarity + Economy**|Reader has to work to find the real point|

**Corrected version:** *"The system, upgraded on March 3, 2024, now processes requests 40% faster. We recommend proceeding with the deployment strategy for our clients."*

Notice: the fixed version is shorter (Economy ✔), uses plain words (Simplicity ✔), states an exact date and percentage (Precision ✔), removes personal opinion (Objectivity ✔), and clearly separates the fact from the recommendation (Clarity ✔).

\---

### QUICK REFERENCE SUMMARY TABLE (SCOPE)

|Principle|Governs|Core Question|Typical Trigger Words|Fix Direction|
|-|-|-|-|-|
|Simplicity|Single word difficulty|Is this ONE word too hard/informal/biased?|slang, clichés, jargon, "aforementioned"|Swap the word|
|Clarity|Structure + missing info|Would the reader say "Huh?" even with simple, specific words?|unclear pronouns, missing 5W1H, bad order|Restructure / add missing info|
|Objectivity|Tone / voice|Is this a feeling or a fact?|"I think," "amazing," "terrible"|Remove opinion, cite evidence|
|Precision|Facts/numbers|Is a vague quantity/comparison standing in for a real fact?|"recently," "faster," "many," "several"|Insert exact figure (if available)|
|Economy|Total length|Could this be said in fewer words with the same meaning?|"due to the fact that," "there is/are," passive voice, nominalizations|Cut, activate verbs, un-bury subject|

\---

## PART D: Source Materials Covered

These notes consolidate and expand content from:

1. **Week 2 – The Style of Technical Writing (manual/document)** — SCOPE principles with examples and activities (simplicity, clarity, objectivity, precision, economy; pronoun reference; numbers as words/digits; that vs. which).
2. **Week 2 – The Style of Technical Writing (revised slide deck)** — condensed SCOPE framework tied to 3 core levers (vocabulary, length, structure), with classroom activities and comparison examples.

Grammar sections (phrases, clauses, conjunctions, sentence types) and the expanded pronoun-reference / SCOPE diagnostic frameworks in this version were built to support the source material, since the original documents assumed this grammar knowledge rather than teaching it directly.

