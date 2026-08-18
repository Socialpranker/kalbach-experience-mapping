# Chapter 5: Investigate: Researching the Experience

## Core Idea
An experience is constructed in the mind of the individual, not owned by the organization — so alignment diagrams must be grounded in direct investigation, moving from existing evidence through internal perspective to external field research, before any drawing begins.

## Frameworks Introduced
- **The Five Steps of Investigation**: the chapter's explicit structure — (1) Reviewing existing sources of information, (2) Interviewing internal stakeholders, (3) Creating a draft map, (4) Conducting research externally, (5) Analyzing the data. Presented as a logical sequence but "typically more iterative than linear... descriptive rather than prescriptive."
- **Evidence → Interpretations → Experience Implications**: three-step format for consolidating any existing source. Evidence = facts/quotes, no judgment. Interpretations = possible causes; consider more than one. Implications = the impact on the individual's experience, especially emotional factors. Use it to normalize disparate sources into one comparable format before pattern-spotting.
- **Three Key Areas for Internal Interviews**: Role and function (where they sit in the value chain), Touchpoints (their direct or indirect contact with the customer experience), Experience (what they believe customers do and feel, and where). Structures 30–60 minute open-questioning conversations with stakeholders.
- **Critical Incident Technique**: three steps to avoid generalizations in an interview — (1) recall a critical incident that went particularly badly, (2) describe the experience: what happened, what went wrong, how they felt, (3) ask what should have happened / what would have been ideal, which surfaces underlying needs and expectations.
- **Field Research's Four Steps**: preparing, conducting the interview, debriefing, analyzing the data — the formal structure for on-site qualitative research, rooted in contextual inquiry.
- **The Four Parts of an On-Site Interview**: (1) greet the participant, (2) conduct the interview, (3) make observations, (4) conclude.

## Key Concepts
- **Contextual inquiry**: qualitative method pioneered by Hugh Beyer and Karen Holtzblatt — interviewing participants on location, in the actual context of their experience.
- **Open questioning**: non-directed, free-flowing interviewing guided by a discussion guide rather than a scripted questionnaire; the interviewer probes rather than reads fixed questions.
- **Discussion guide**: a one- or two-page prompt document, not a survey — a reminder of topics, used out of order as the conversation flows.
- **Master-apprentice relationship**: the interviewer's stance on-site — interviewer as apprentice, participant as master; never instruct or correct, even when described behavior looks inefficient.
- **Mystery shopping**: role-playing a defined process as a customer would live it, to build a touchpoint inventory of physical evidence, digital touchpoints, and one-to-one contact.
- **Draft diagram**: a preliminary hypothesis of the experience, co-created early with stakeholders on sticky notes, whose job is to generate research questions — not to stand in as analysis.
- **Formal vs. informal analysis**: informal = clustering sticky notes or a shared spreadsheet; formal = full interview transcription plus coded analysis in a tool like MaxQDA.

## Mental Models
- Treat internal stakeholder interviews as generating **assumptions**, not facts — "their understanding may not match what customers actually experience" — so validate everything internal against subsequent field research.
- Use on-site field research when you need the richness of direct observation and environment; use remote interviews (phone/teleconferencing) when speed and reduced travel outweigh that richness.
- Think of the draft diagram as a **hypothesis that organizes your ignorance**: its value is in exposing what you don't yet know so later research has a target.
- Use qualitative research to discover and validate the *shape* of the experience; bring in quantitative research (surveys, usage metrics) only afterward, to measure the *scale* of what you already found — not to discover new themes.

## Anti-patterns
- **Turning the draft-diagram workshop into brainstorming**: solutions will surface — capture them — but the workshop must stay focused on the diagram and on generating research questions, not on solutioning.
- **Fielding more than two researchers per on-site interview**: a crowd creates an unnatural atmosphere that changes participant behavior and contaminates the insight.
- **Leading the participant**: asking yes-or-no questions or putting words in their mouth collapses open questioning into a poll; follow their line of thought and their language instead.
- **Video recording a full session without the resources to review it**: full-length video analysis takes very long; record short testimonials instead if you can't commit to review.
- **Switching rating scales mid-survey**: breaks comparability of results across questions.
- **Relying on mystery shopping alone for the touchpoint inventory**: it misses edge cases and exception flows (a paid multi-user account's emails differ from a solo trial's) — chase alternative touchpoints separately.

## Reference Tables

Table 5-1: consolidation of findings across two existing sources for a fictitious software service.

| Source | Evidence | Interpretations | Experience Implications |
|---|---|---|---|
| Email Feedback | Many emails cite installation trouble, e.g. "After going through the instructions and process several times, I gave up." | People lack the skill/patience to complete installation and get frustrated | Installation is a problematic phase in the journey |
| Email Feedback | Frequent questions about needing admin rights, e.g. "I got the message 'Please contact your IT admin' and didn't know what to do." | Many companies restrict software installs for security; contacting IT admin can be slow | For users without admin rights, installation ends the experience — a show stopper |
| Email Feedback | Some emails praised customer support, e.g. "really knowledgeable and helpful!" | People value speaking with a real person and feel personal attention | Customer support is a positive aspect of the current experience |
| Marketing Survey | Awareness channels ranked: word of mouth (62%), web search (48%), internet ads (19%), TV ads | Customers seek input from others; ads may be less effective than assumed | Word of mouth plays the greatest role in becoming aware of the service |
| Marketing Survey | 64% of customers regularly switch between computer and mobile during use | People need to use the software on-the-go | Customers experience the software across devices |
| Marketing Survey | A majority found installation difficult or very difficult | Installation isn't straightforward; instructions aren't clear | Installation is a source of frustration |

## Worked Example

**Music Curation: User Research and Diagramming at Sonos** (case study by Amber Brown, UX Researcher at Sonos). Sonos needed to diagram how people curate music through its app — which controls multiple services, rooms, and people — but first had to understand how and why people used the product at all.

Research spanned two weeks with ten Sonos households. Interviews began remotely, over teleconferencing with webcams, having participants demonstrate their phone app live; sessions were recorded for stakeholders who weren't present. Participants then kept a daily diary of their product interactions. Weekly check-ins produced the most eye-opening insights: when participants recounted stories, they often revealed deeper goals they hadn't stated outright.

The team clustered findings on sticky notes and a whiteboard into a model, then produced one diagram built around five elements:
1. **User Goals** — underlying motivations for playing music, drawn out by repeatedly asking "why."
2. **Supporting features** — app features mapped to each goal, explicitly applying Indi Young's mental-model-diagram method; revealed, for example, that queue functions carried disproportionate weight.
3. **Benefit of features** — the value each feature delivers, used deliberately to balance negative feedback and build stakeholder buy-in by showing what already works.
4. **Obstructions of actions** — the most consequential section: where the app failed to support user goals. This is what captured stakeholders' attention.
5. **Unused items** — features untouched during music playback, used to decide what could be removed with no impact on user goals.

The model outlived its initial readout: shown in meetings and workshops in paper and electronic form; printed and posted at colleagues' desks to keep the conversation alive; reused as a template for mapping new feature concepts by swapping in new supporting features; and mined for new benefit statements that became user stories for development teams. Because the model was grounded in first-hand investigation, product managers, engineers, and designers used it with confidence that their decisions traced back to real customer needs.

## Key Takeaways
1. Follow the five investigation steps as a default sequence, but expect to loop back — the process is iterative, not a strict waterfall.
2. Mine existing sources first (direct feedback, social media, reviews, market research, past user testing, industry reports) through Evidence → Interpretations → Implications before commissioning new research.
3. Interview a spread of internal roles, not just project sponsors — frontline staff (service desk, call center) often have the clearest read on what customers actually experience.
4. Co-create the draft diagram with stakeholders early; treat it as a hypothesis that generates research questions, not as an analytical deliverable — for small "lean" teams, this step alone may be sufficient.
5. Build the touchpoint inventory via mystery shopping, then patch its blind spots by separately chasing edge-case and exception flows.
6. On-site field research (contextual inquiry) is the gold standard for external investigation; use the critical incident technique to surface real needs instead of generalizations, and staff each session with exactly two researchers — one interviewer, one observer.
7. Layer in quantitative measurement (surveys, standardized instruments, usage metrics) only after qualitative work has told you what to measure — it scales confidence in findings, it doesn't discover them.

## Connects To
- **Ch1**: The touchpoint inventory technique (Figure 5-6) was built by Chris Risdon for the Rail Europe Experience Map introduced there as a worked example.
- **Ch2**: Drafting the initial diagram explicitly reuses this book's mapping fundamentals — point of view, scope, focus, and structure.
- **Ch4**: The "story of interaction" defined during Initiation is the guide this chapter invokes when synthesizing and analyzing the collected research data.
- **Ch6**: The direct successor — this chapter's analyzed, reduced findings are exactly what Illustrate turns into a drawn diagram; Ch6 also covers representing the quantitative data gathered here.
- **Ch10**: Customer journey maps are named as a direct destination for findings like the word-of-mouth awareness data in Table 5-1.
- **Ch12**: Mental model diagrams are referenced twice — sticky-note clustering per Indi Young's method (Figure 5-10), and directly as the technique behind the Sonos case study's "supporting features" step.
- **External**: *Contextual Design* (Hugh Beyer & Karen Holtzblatt) is the source method for field research; the critical incident technique and MURAL (debrief) and MaxQDA (formal coding) are named tools/techniques; NPS (Fred Reichheld, *The Ultimate Question*), SUS (System Usability Scale), SUMI (Software Usability Measurement Index), and GfK's proprietary UX Score are named standardized quantitative instruments.
