# D-Wave Quantum Computer Video — Transcript & Fact-Check

**Source video:** [Facebook clip](https://www.facebook.com/share/v/18nmy1QZ4H/?mibextid=wwXIfr) (originally posted by MikeQEllis; the audio is excerpted from a longer 2013 talk by D-Wave founder Geordie Rose, also archived on YouTube as ["Quantum Computing: Artificial Intelligence Is Here"](https://www.youtube.com/watch?v=PqN_2jDVbOU))

**Speaker:** Geordie Rose, founder of D-Wave Systems (identified by the verbatim phrasing — "altar to an alien god," "shadows of these parallel worlds overlap with ours" — which match well-documented quotes from his talks ([Kubuntu Forums recap](https://www.kubuntuforums.net/forum/general/community-cafe/59838-), [Facebook quote post](https://www.facebook.com/Primal-Embodiment-224673624804949/photos/it-feels-like-an-altar-to-an-alien-god-geordie-roses-quote-one-of-the-pioneers-i/822941644978141/))).

---

## Clean transcript

> There are two of them. These are from our lab in Burnaby in British Columbia. From the outside, they look like giant black monoliths — big metal boxes about ten feet on a side, twelve feet tall. They have a fridge inside them, a refrigerator that cools these chips to almost absolute zero — just a wisp, a fraction of a degree above absolute zero. Hundreds of times colder than interstellar space. Amongst the coldest and most isolated and extreme conditions that humans have ever been able to engineer.
>
> These fridges, interestingly enough, are called pulse tube dilution refrigerators. They have a thing called a pulse tube which emits a sound roughly once per second that sounds eerily like a heartbeat. If you have the opportunity to stand next to one of these machines, it is an awe-inspiring thing — at least for me. It feels like an altar to an alien god. They really are impressive machines.
>
> At the heart of this big box is a tiny chip about the size of your thumbnail, and on this chip resides all of the wonder and magic that makes this thing go. In quantum mechanics, there's this concept that a thing can exist in two states which are "mutually exclusive" at the same time — and I'm using those words in quotes because the English language was developed before we had concepts to describe what these things actually are doing.
>
> Imagine that there really are parallel universes out there. Now imagine you have two that are exactly identical in every respect, all the way out to the horizon, down to the last little atomic detail of every single thing — with only one difference. And that's the value of a little thing called a qubit on this chip. It's a contraction of "quantum bit." That qubit is very much like a bit or a transistor in a conventional computer — it has two distinct physical states which we call zero and one. In a conventional computer, these are mutually exclusive: that device is either one or the other and never anything else. In a quantum computer, that device can be in this strange situation where these two parallel universes have a nexus — a point in space where they overlap.
>
> Every time you add one of these qubits, you double the number of these parallel universes that you have access to. By the time you get to a chip with about five hundred of these bits, you have something like 2^500 of these guys living in that chip. The way I think about it is that the shadows of these parallel worlds overlap with ours, and if we're smart enough, we can dive into them and grab their resources and pull them back into ours to make an effect in our world.
>
> This may sound very odd and bizarre, and in fact I am using language that a normal theoretical physicist probably wouldn't use. But what I'm telling you is absolutely correct and in line with the way that these things actually work. The doubling of the number of qubits on the chip has happened once a year for the past nine years, and it will continue to do so.

**Cut-in clip (Morpheus, *The Matrix*):** "All I'm offering is the truth, nothing more."

**Outro:** instrumental jingle.

---

## Fact-check

### The hardware description — accurate

| Claim | Verdict | Notes |
|---|---|---|
| D-Wave's lab is in Burnaby, BC | **True** | D-Wave Systems was founded in 1999 and is headquartered in Burnaby, British Columbia ([BTQ timeline](https://www.btq.com/blog/quantum-computing-a-timeline)). |
| Big black box, ~10 ft on a side | **True** | D-Wave's enclosures are roughly cube-shaped cabinets of that scale; the inner shielded volume is much smaller. |
| "Pulse tube dilution refrigerator" cools chip near absolute zero | **True** | D-Wave processors operate around **15 millikelvin** — a fraction of a degree above absolute zero ([Microsoft Quantum overview](https://quantum.microsoft.com/en-us/insights/education/concepts/superposition); standard for superconducting quantum hardware). |
| "Hundreds of times colder than interstellar space" | **True** | The cosmic microwave background is ~2.7 K; 15 mK is ~180× colder. |
| Pulse tube emits a ~1 Hz heartbeat-like sound | **True** | Pulse-tube cryocoolers cycle at roughly 1–2 Hz, producing a characteristic rhythmic thump — a well-known feature of these systems. |
| Chip is "thumbnail-sized" | **True** | D-Wave's processors are small superconducting chips on the order of 1 cm². |

### The "parallel universes" interpretation — physically loaded, not the mainstream view

This is where Rose's pitch leaves the consensus. Three things to disentangle:

1. **The math is real, but the "parallel universes" framing is one *interpretation*, not a fact.** A qubit's two basis states (0 and 1) can exist in **superposition** — a complex linear combination — and an *n*-qubit register has a state living in a 2ⁿ-dimensional Hilbert space ([Microsoft Quantum: Superposition](https://quantum.microsoft.com/en-us/insights/education/concepts/superposition)). The "parallel universes" picture is the **Many-Worlds Interpretation** (Everett/Deutsch). It is taken seriously by some physicists — notably David Deutsch, who argues quantum computers' speedups are evidence for it — but it is **not** uniquely required by the physics. Other interpretations (Copenhagen, pilot-wave, QBism, etc.) describe the same experiments without literal parallel worlds ([arXiv: Birth and Evolution of MWI](https://arxiv.org/html/2405.06924v1)).

2. **"Quantum computers work by farming out computation to parallel universes" is misleading even within Many-Worlds.** Scott Aaronson — a leading complexity theorist who has written extensively on this — repeatedly emphasizes that this naive picture is wrong: a quantum computer doesn't simply "try all 2ⁿ answers in parallel and pick the right one." The speedup comes from **interference** — engineering the amplitudes so that wrong answers cancel and right answers reinforce ([Aaronson on Many-Worlds, 2025](https://scottaaronson.blog/?m=202510); [YouTube interview](https://www.youtube.com/watch?v=uoUODOeG6KQ)). Rose's "dive in and grab resources from parallel worlds" is rhetorical flourish, not a working description of any quantum algorithm.

3. **D-Wave's machines specifically are quantum *annealers*, not gate-model quantum computers.** They do not run Shor's algorithm or general quantum circuits; they search for low-energy configurations of an Ising model. Whether they exploit genuine quantum effects (vs. behaving like classical thermal annealers) has been debated for over a decade. Recent peer-reviewed work — D-Wave's [March 2025 *Science* paper](https://postquantum.com/industry-news/d-wave-quantum-advantage/) — claims "quantum supremacy" on a magnetic-materials simulation, but [classical algorithms have already narrowed or matched the gap](https://thequantuminsider.com/2025/03/14/d-wave-ceo-responds-to-criticisms-about-quantum-supremacy-claim/) on related instances, and the result remains contested.

**Bottom line:** Rose says he's "using language a normal theoretical physicist probably wouldn't use." Most theoretical physicists and complexity theorists would go further and say it's *misleading* — the sentence "the shadows of these parallel worlds overlap with ours and we dive in and grab their resources" is poetry, not physics ([Kubuntu Forums critique](https://www.kubuntuforums.net/forum/general/community-cafe/59838-)).

### "Qubits doubled every year for nine years" — was true at the time, is no longer

This refers to **Rose's Law**, a quantum-computing analogue of Moore's Law that Steve Jurvetson coined after meeting Rose ([Wikipedia: Quantum computing scaling laws](https://en.wikipedia.org/wiki/Quantum_computing_scaling_laws)).

Rough D-Wave qubit timeline ([Quantum Insider history](https://thequantuminsider.com/2026/04/24/history-of-quantum-computing/), [BTQ timeline](https://www.btq.com/blog/quantum-computing-a-timeline), [TOP500](https://www.top500.org/news/d-wave-sets-stage-for-2000-qubit-quantum-computer/), [Jurvetson Flickr post](https://www.flickr.com/photos/jurvetson/50399541811)):

| Year | Qubits |
|---|---|
| 2007 | 16 (Orion prototype) |
| 2011 | 128 (D-Wave One) |
| 2013 | 512 (Vesuvius) |
| 2015 | 1,000+ (D-Wave 2X) |
| 2017 | 2,000 (D-Wave 2000Q) |
| 2020 | 5,000+ (Advantage) |
| 2025 | ~5,000 (Advantage2 prototype) |

So:

- **The mention of "~500 qubits"** dates the talk to roughly **2013**, just after the 512-qubit Vesuvius chip — consistent with the 2015 YouTube upload of the longer talk.
- **"Doubled every year for nine years"** was a *defensible* claim at that moment.
- **It did not continue.** As [Jurvetson noted in his 2020 update](https://www.flickr.com/photos/jurvetson/50399541811), the doubling time has stretched to roughly every 24 months over the past decade. Wikipedia now cites Rose's Law as "doubles roughly every 18 months" ([source](https://en.wikipedia.org/wiki/Quantum_computing_scaling_laws)). And critically, raw qubit count is no longer the headline metric — the field has shifted to **logical qubits, error correction, and gate fidelity** ([Quantum Insider](https://thequantuminsider.com/2026/04/24/history-of-quantum-computing/)). A 5,000-qubit annealer and a 100-qubit gate-model processor are not directly comparable.

### Summary scorecard

| Claim | Status |
|---|---|
| Burnaby, BC location | Accurate |
| Physical description of the dilution fridge | Accurate |
| "Heartbeat" sound from pulse tube | Accurate |
| Qubit = "two-state quantum device" | Accurate |
| 2ⁿ states scale with n qubits | Mathematically correct |
| "Each qubit = a parallel universe you grab resources from" | One interpretation, not consensus; misleading even within Many-Worlds |
| "Doubled every year for nine years" (as of ~2013) | True at the time |
| Implication that this rate would continue indefinitely | False — has slowed to ~18–24 months; metric itself has lost primacy |

---

## Video links

- Original Facebook clip: [facebook.com/share/v/18nmy1QZ4H](https://www.facebook.com/share/v/18nmy1QZ4H/?mibextid=wwXIfr)
- Resolved Facebook permalink: [facebook.com/MikeQEllis/videos/1335472437754345](https://www.facebook.com/MikeQEllis/videos/1335472437754345/)
- Longer source talk on YouTube — Geordie Rose, "Quantum Computing: Artificial Intelligence Is Here": [youtube.com/watch?v=PqN_2jDVbOU](https://www.youtube.com/watch?v=PqN_2jDVbOU)
- Re-upload framing the same clip ("Altar To An Alien God"): [youtube.com/watch?v=jgYKELUZVfc](https://www.youtube.com/watch?v=jgYKELUZVfc)

---

*Compiled from the Facebook video transcript and cross-referenced against D-Wave's published timeline, peer-reviewed press coverage, and quantum-computing reference material.*

---

## Repost variants

The same source video (Facebook video ID **1335472437754345**, posted by [MikeQEllis](https://www.facebook.com/MikeQEllis)) has been redistributed via multiple share-link aliases with different captions framing the identical Geordie Rose audio. These are not new content — they are the same clip relabeled.

| Share alias | Caption / framing | Notes |
|---|---|---|
| `18nmy1QZ4H` | Quantum-awe / "Altar to an Alien God" | Original framing analyzed in this document |
| `18VEExungw` | "AI Was Created For Satan By Satan" | 316K views, 7.9K reactions, uploaded ~May 2025; hashtags `#antimatrixfile #satan #demon #evil #wakeup`; outro swapped to a Madonna "Frozen / If I Could Melt Your Heart" snippet (1998) |

### Caption-level claims (new layer to fact-check)

| Caption claim | Verdict |
|---|---|
| Rose calls D-Wave "an altar to an alien god" | **True quote, misleading implication.** It is an aesthetic metaphor about the cryostat's appearance, not a theological statement. |
| "AI was created for Satan by Satan" | **Not a claim made by Rose or D-Wave.** Pure editorial overlay added by the reposting account. |
| Quantum computers "grab resources from parallel universes" therefore the technology is demonic | **Non-sequitur.** Many-Worlds is a physics interpretation; it has no doctrinal content about supernatural entities. |
| Rose's framing is occult | **Editorial opinion, not fact.** Mainstream critique of Rose (e.g. [Scott Aaronson](https://scottaaronson.blog/?m=202510)) targets the framing as misleading physics, not as occultism. |

### Transcript

The audio in this repost is identical to the original Idea City 2013 Rose talk transcribed at the top of this document. A verbatim transcript of the reposted clip is archived alongside this file at `dwave_video_transcript_satan_repost.txt`.

### Take-away

The substantive physics content is the same and the prior fact-check applies in full. The novel element in this repost is the caption, which attaches a religious-conspiracy interpretation to a 13-year-old quantum-computing keynote without any supporting claim from the speaker or the company.


## Integrity

- SHA-256 (over all bytes from the start of file up to and including the final newline of the *Take-away* paragraph above, after rstrip + single trailing newline): `74d814ba32e4ab4d4986e27a207e53ba7810cf07a85ca9dd83a373c448a48af6`
- Generated (UTC): 2026-04-26T20:27:27Z
- Algorithm: SHA-256 over UTF-8 bytes of the document content above this section, with trailing whitespace stripped and a single trailing newline appended
- Verify: `python3 -c "import hashlib,pathlib,re; b=pathlib.Path('file.md').read_bytes(); b=re.split(rb'\n## Integrity', b)[0].rstrip()+b'\n'; print(hashlib.sha256(b).hexdigest())"`
