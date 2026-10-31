---
name: pmm-competitive-swot
description: Product marketing competitive intelligence from public sources, turned into the documents a PMM actually ships (a filled competitive intel checklist, a competitor SWOT with ranked strategies, a sales battlecard, or a short portfolio case study), fact-checked, specific down to named actors, numbers, sources and scope, written in the user's own voice, and adapted to who will read it. Use this whenever the user wants to fill in a competitive intel or SWOT template, compare their company against named competitors, build a battlecard from their research, refresh or fact-check earlier competitor research, tighten vague competitive claims, or make competitive work ready to send to companies, assessors or hiring managers. Prefer this over general competitor-research skills when there is a template to fill, when the output will be read outside the user's team, or when it's for a portfolio, even if the user just says "research these competitors" or "is this good enough to send".
---

# PMM Competitive Intelligence, SWOT and Battlecards

This skill takes one company and a set of named competitors, researches them from public sources, and turns the findings into the documents a product marketer needs. The work has to hold up in front of a skeptical reader: a sales rep in a live deal, a hiring manager, a course assessor, or someone who works at one of the companies named. Accuracy, specificity, fair tone and the user's own voice matter as much as coverage.

Supporting files, read only when the step calls for them:

- `references/battlecard.md`: structure and rules for sales battlecards.
- `references/external-and-portfolio.md`: wording, disclaimers and sharing for documents going outside the team, plus the portfolio case study outline.
- `references/voice-of-customer.md`: how to mine reviews for themes and buyer language.
- `scripts/check_specificity.py`: flags vague words, merged counts and em dashes in a draft.

## Two boundaries

**No fabrication.** Don't invent or infer facts no source supports: a company's existence, a number, a quote, a customer, a win story, a causal link between two facts, a "why" that isn't evidenced, or a stale fact presented as current. When something can't be found, say so and say what would find it. One invented figure discredits everything else in the document, so a late, honest answer beats an on-time one.

**Ethical collection.** Follow the SCIP code of ethics for competitive intelligence. Never misrepresent who you are or why you're asking: no posing as a prospect, job candidate, student or journalist to get pricing, demos or internal information. Don't use confidential documents, pay insiders, bypass paywalls, logins or bot checks, or record anyone without consent. If the user asks for any of this, decline briefly and offer legitimate routes instead: third-party pricing data (Vendr, G2 pricing pages), public tenders and procurement records, filings and investor material, reviews, analyst reports, or asking contacts openly while saying who you are and why. Companies hide prices on purpose; working around that deceptively can damage the user's reputation and may break the law.

## Be specific

A vague point can't be checked, acted on or defended. Sales reps can't use it in a call, hiring managers read it as shallow thinking, and people at the companies named can dismiss it. Every claim should let the reader picture exactly what happens and check it against a source. Before writing any point, answer six questions:

1. **Who?** Name the actor by role: "the support team's admin", "a Head of Support at a 200-person SaaS company". Avoid "buyers", "users" or "customers" unless the source says only that.
2. **Does what, to what?** Name the action and its object: "connects Fin to Zendesk and loads the help centre", not "sets it up"; "edits a Procedure and tests it in a simulation", not "changes it".
3. **How much, how fast, compared with what?** Give the number, unit, date range and denominator: "4 of the 10 most recent G2 reviews (31 Aug–24 Sept 2026)", "$0.99 per resolution vs. $1.50–2.00", "under an hour (Fin's claim)". Replace "many", "most", "fast", "easy", "cheaper", "strong" or "leading" with the figure behind them. If there's no figure, say so instead of reaching for an adjective.
4. **According to whom?** "Fin says", "Sacra estimates", "G2 reviewers", "my calculation".
5. **Where does it stop being true?** State the scope: which product, channel, segment, region or stage. "Public price for chat and email; voice is priced by sales." "The difference is getting started; both rivals now claim customers can edit agents later."
6. **One claim per count.** Don't merge themes into one number ("set up, train or use: 5 of 10"). Count each theme on its own so the number means one thing.

A "So what" is specific when it names the team, the concrete action, the asset or channel, and a timing or metric where one exists: "Marketing: add a timed, recorded build (sign up, connect the helpdesk, run a simulation, go live) to the Sierra comparison page", not "use their language on comparison pages".

> Vague: "Buyers can set it up and change it themselves."
>
> Specific: "A support team can trial and launch Fin without a sales call or engineering help. 14-day trial, no card; Fin says setup on an existing helpdesk takes under an hour; 4 of the 10 most recent G2 reviews praise setup or training, and 1 says setup was hard. Sierra and Decagon start with a demo and their own engineers. Both now claim customers can edit agents later, so Fin's clear difference is getting started."

Specific doesn't mean long: cut adjectives and filler to make room for the numbers. When being specific shows that a claim is narrower than it sounded, narrow the claim and say so. That is often the most useful finding.

## Before starting

1. **Find the user's voice guide.** Look in project instructions, the connected folder, and the user's Drive (titles with "voice", "style", "tone"). If there is one, read it and write in that voice. Stated preferences (for example "no em dashes") win over the guide's own examples. With no guide, use the plain-writing rules in "Voice and writing".
2. **Confirm the company and competitor set.** If a named company can't be verified, stop and ask. A competitor added mid-task is a scope change; confirm it.
3. **Confirm the readers and deliverables.** Ask if unclear. Common ones:
   - Internal research file (the full checklist), for the user and their team.
   - External submission (an assignment or SWOT sent to companies, assessors or hiring managers).
   - Sales battlecard, for reps in live deals.
   - Portfolio case study, 2–3 pages for a hiring manager.
4. **Copy the target template exactly** when there is one: title, columns, headers, row and category order, and question text word for word, including helper text. Assessors grade against the original, and users notice when a template gets "tidied".
5. **Follow project rules** on naming, folders and versions. Default to a new versioned file, never an overwrite. If asked to update a Google Doc and no Docs editor connector is available, say so and offer a new version.
6. **List any facts you're reusing** from earlier research and when each was last checked.

## Step 1: Scope from the buyer's side

Before researching vendors, write down what a buyer would actually choose between: the named competitors, plus doing nothing, building it themselves, and adjacent tools that solve the same problem another way. Name them specifically (for example "Agentforce, for teams already on Salesforce"), not as categories. Then note what buyers judge on (buying criteria), taken from reviews, RFP language and analyst coverage rather than assumed. Positioning is only meaningful against the alternatives buyers really consider, and "build it ourselves" is often the strongest competitor.

For each template question, mark whether it's answerable from public sources, answerable only with a specific tool (SEO or rank data, social analytics, job-board tracking), or not answerable from outside (sales-cycle length, internal decks). Flag the last two up front and name the tool that would answer them.

## Step 2: Research

For every claim:

- **Cite it** with a link, and track its tier. Tier 1: the company's own pages, the platform where a metric lives (G2 rating on G2, followers on LinkedIn), or your dated observation of a first-party page. Tier 2: independent journalism and research or data firms, even when they're the only source. Tier 3: blogs, aggregators and estimate sites; label figures from these as estimates. Note when a source has a commercial interest (a competing vendor's review page is not neutral).
- **Frame vendor claims as claims:** "X reports a 76% resolution rate".
- **Headline numbers** need Tier 1 or two independent Tier 2+ sources that agree.
- **Use a live browser** for pages a plain fetch can't render (LinkedIn, G2, JavaScript-heavy sites). Don't sign in or bypass gates; if a platform limits what's visible, say how many items you could see.
- **Show disagreements.** Give both sources, or the range for counts that vary by tracker, with dates.
- **Don't link facts by timing.** State a causal link only if a source states it.
- **Freshness check.** Re-check reused facts, starting with the ones most likely to move: ratings, review counts, prices, taglines, headcount, offices, events, and any "doesn't have X" claim. Otherwise keep them with a dated note.
- **Uniqueness check.** Before saying a company is the only one, the first, or distinctive in doing something, check every in-scope competitor's own site. If they all do it, the finding is that it's now common, which is often the more useful insight.
- **Close gaps before flagging them.** Try the company's site (homepage, newsroom, blog, events, careers, trust pages, pricing FAQs), the source platform, and a browser. If it's still a gap, say what would close it.

**Voice of customer.** Where reviews exist, read a sample for each vendor (aim for 30–50 recent ones) and count recurring praise and complaint themes, one theme per count, noting the sample size and dates. Keep a few short buyer phrases, attributed, for messaging and objection handling. See `references/voice-of-customer.md`. Themes backed by counts are evidence; a single vivid review is an anecdote.

## Step 3: The internal research file

Fill every template cell. Lead with the answer, then the evidence and link. Keep source tiers on each citation.

Where a finding changes what a team should do, add a function tag: `🎯 Team. Why: … So what: …`. Teams: PMM, Sales, Marketing, Product, Engineering, Customer success, Executive (mark Executive tags confirmed or inferred). The Why gives the data, context and implication; the So what gives the concrete action. Each Why has to reason on its own. Pointing back to another tag ("same as above") means the thinking isn't done, and a general claim with no source ("worries tend to surface at renewal") doesn't count as reasoning.

> Weak: "Why: same data point. So what: audit targeting."
>
> Strong: "Why: software is 23% of customers, a plurality but not a majority, so ad spend that assumes tech is the main buyer is weighted toward a minority. So what: audit campaign targeting against the real vertical mix."

When the file replaces an earlier version, add a short "What changed" section at the top listing corrected, withdrawn and added claims.

## Step 4: The SWOT

Derive every point from a researched row, not general knowledge.

- **Strengths and weaknesses are internal; opportunities and threats are external.** Test: if the company could decide it tomorrow, it's internal. "Expand into our installed base" is a strategy; "competitors stay sales-gated, so try-first buyers have two options" is an opportunity.
- **Top three per box, ranked** by impact on the user's company.
- **Each point:** a bold headline that says who does what and carries the key number (not a label like "Ease of use"), one or two sentences of evidence with numbers, sources and scope, then "So what (Team):" with the concrete action.
- **Detail first, then trim.** Write the detailed SWOT first, with every fact, count, source and scope limit a point depends on, and keep it as the detailed version. Then make the reader version by trimming: keep the headline, the one or two facts that prove it and the So what; move everything else to the detailed version or the research file. Aim for 30–60 words per point, and about 3–4 pages for a SWOT covering four companies. Trimming must not change a number or drop a scope limit that the point depends on (if "public price" is only true for chat and email, the trimmed point still says so). Link the detailed version and the research file from the trimmed one. Detailed drafting catches errors and vague claims; trimming makes the result readable.
- **Label perceived weaknesses** that come from reviews as perceived, and give the count.
- **Competitor threats** answer both halves: what threatens the competitor, and how the competitor threatens the user's company.
- **Ranked strategies:** pair internal with external factors (strength with opportunity, strength against threat, weakness with opportunity, weakness against threat). Three to five, ranked by how soon they could affect revenue, each with the factors it's built from, an owner, a success metric and the assumption it depends on.

## Step 5: Write for each reader

- **Internal research file:** full detail, all sources, tiers and function tags.
- **Battlecard:** read `references/battlecard.md`. One card per competitor, two pages at most, built only from sourced research, never with invented win stories. If the user has their own battlecard template, use it.
- **External submission or portfolio case study:** read `references/external-and-portfolio.md` for the context note, neutral wording, sharing checks and the case study outline. Keep plain-language team labels ("So what (Sales):"); strip tiers, emoji and tag notation.

## Voice and writing

With a voice guide, follow its structure, banned phrases and signature phrases. Use each signature phrase at most once so the writing doesn't sound formulaic.

Without one, write plainly: conclusion first; one idea per paragraph; bullets only when something breaks into parts; no emoji in external documents; few or no em dashes; numbers instead of intensifiers ("rose from $44M to $100M", not "grew significantly"); no hype words ("game-changing", "best-in-class" without proof, "unlock value", "seamless", "leverage"). Headings describe content. Keep the conversation with the user out of the document.

"Be specific" applies with or without a voice guide.

## Step 6: Verify before delivering

- Every figure in the SWOT, battlecard or case study traces to a research row and source. Re-read the claims a reader is most likely to challenge.
- Every "only", "first" and every causal "because" has a source.
- **Specificity and length.** Run `python scripts/check_specificity.py <draft>` on a text, Markdown or HTML copy and fix what it flags, including points over the word limit (`--max-words 60` for a trimmed SWOT). Then read each SWOT, battlecard and case-study point against the six questions in "Be specific": actor, action, number with denominator and date, whose claim, scope, one claim per count. Rewrite or narrow any point that fails.
- Template structure and question text match the original.
- External documents: no loaded words, emoji or internal notation; links open and point at the latest versions.
- Voice: banned phrases gone; signature phrases used at most once each.
- Saved as new versions with no name conflicts.

## Step 7: Deliver

In the reply, not the document: what changed since the last version, what's still unknown and what would close it, and anything the user must do (for example, set a doc to "Anyone with the link: Viewer"). Competitive facts in fast-moving markets go stale within weeks, so suggest a monthly refresh where it applies.

## Quality checklist

- [ ] Voice guide found and followed, or confirmed absent
- [ ] Readers and deliverables confirmed; each document written for its reader
- [ ] Buyer alternatives (named, including status quo and build-your-own) and buying criteria noted
- [ ] Collection was ethical; no misrepresentation, no sign-ins or gate bypassing
- [ ] Template structure and question text copied exactly
- [ ] Claims linked, estimates marked, vendor claims framed as claims, disagreements shown
- [ ] Reused facts re-checked or dated; uniqueness and causal claims sourced
- [ ] Review themes counted one theme per count, with sample size and dates
- [ ] Every point names who, does what, how much (with denominator and date), whose claim, and where it stops being true
- [ ] No vague words left without a number or example (specificity script run)
- [ ] Function tags internally, "So what (Team):" labels externally; every Why reasons on its own
- [ ] SWOT: top three per box, ranked, O/T external, competitor threats answer both halves
- [ ] Detailed SWOT written first; reader version trimmed to 30–60 words per point, with the same numbers and scope limits, linking back to the detailed version
- [ ] Ranked strategies with factors, owner, metric and assumption
- [ ] Battlecards and external documents follow their reference files
- [ ] Saved as new versions; nothing overwritten
