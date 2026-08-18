# Chapter 6: Illustrate: Drawing the Diagram

## Core Idea
Turning research into an alignment diagram is a compilation problem, not an artistic-talent problem: move iteratively between three interdependent factors — Layout (the diagram's form), Content (the information it holds), and Design (how that information is represented) — reducing raw findings to one cohesive, low-noise story. Quoting Tufte, the standard is "the greatest number of ideas in the shortest time" — with minimal ink and space.

## Frameworks Introduced
- **Three Interdependent Factors (Layout, Content, Design)**: the chapter's top-level structure. Layout = the diagram's overall form; Content = the information it contains; Design = the visual representation of that information. Work moves back and forth between the three rather than linearly — settle a layout, compile/format content into it, design its presentation, loop back as needed.
- **Layout selection**: some methods prescribe layout a priori (mental model diagrams → hierarchical towers; service blueprints → table). When layout is open, default to a table or timeline "to be on the safe side." Deviate to an alternative form (circular, spider/network, "snakes and ladders") only when the shape itself amplifies the message — e.g., Sofia Hussain used a circular layout for an event-planning app specifically to signal a goal of repeat use.
- **Displaying Chronology (four techniques)**: devices for non-sequential reality inside an otherwise linear map. Ongoing activity — mark the first occurrence, note it continues, extend a line rather than repeating the step. Variable order — a nonlinear, cloud-like shape for events with no fixed sequence. Repeat behavior — arrows/circles for actions that alternate. Alternate flows — a decision point with a temporary split for distinct sub-paths, kept to a minimum and rejoined afterward.
- **Content-formatting reduction (Table 6-1)**: an ordered method for compressing a research insight into diagram-ready text — start with insight clusters → natural language → consistent voice (first or third person, never mixed) → omit pronouns/articles → focus on root cause → be concise → abbreviate sparingly → let row/column position imply the rest.
- **Per-facet syntax convention**: fix one part of speech per information type so the whole diagram reads in one grammar. Actions = a verb ("download software"); Thoughts = a question ("Are there hidden fees?"); Feelings = adjectives ("nervous, relieved"); Pain points = a gerund ("waiting for installation"); Touchpoints = nouns ("email, customer hotline"); Opportunities = a change-verb ("increase the ease of installation").
- **Design principles — Simplify, Amplify, Clarify, Unify**: checks for the design pass. Simplify: cut decorative graphics, favor efficiency. Amplify: keep sponsor goals in mind, intensify the core message. Clarify: maximize legibility. Unify: make the display consistent, one cohesive whole.
- **Visual hierarchy technique set**: alignment to an invisible grid, weight/size differentiation (larger headers vs. body; bigger arrows for critical steps vs. small ones for routine motion), and layering (color/shading/size for added density without hurting readability) — applied together to direct the eye in priority order.

## Key Concepts
- **Chartjunk**: Tufte's term for anything unnecessary in an information display (e.g., heavy grid lines on every table cell) that adds ink without adding meaning.
- **Grid**: an invisible structure of equally spaced lines that diagram elements are justified to, producing clean vertical/horizontal lines of sight.
- **Visual hierarchy**: deliberately unequal visual weighting of elements so the eye perceives the most important information first.
- **Quantitative representation methods**: five ways to encode magnitude — numbers as text, bars for relative amounts (vertical easier to compare than horizontal), a plotted line for trend across touchpoints, size of a shape (used cautiously), and Sankey diagrams, which vary line width to show flow quantity (Minard's 1812 Napoleon march map is the classic example).
- **PrEmo (Product Emotion Measurement instrument)**: Pieter Desmet's tool that measures emotional response to a product via self-selected animated cartoon facial expressions.
- **Capturemo**: SusaGroup's follow-on tool integrating PrEmo-style facial-expression icons directly into a journey map to capture emotion at each step.
- **Color coding vs. background regions**: the two core uses of color — tagging one recurring facet (e.g., pain points) consistently across the map, versus using shaded values of a single hue to divide/contain regions (e.g., journey phases) without adding lines.
- **Icon key**: a legend for a diagram's icons — necessary, but risky if overused, since a reader forced to check the key constantly can no longer read the diagram directly.

## Mental Models
- Use a table or timeline layout by default; reach for a non-standard form only when that shape itself reinforces the diagram's central message.
- Treat the design pass as Simplify/Amplify/Clarify/Unify, not decoration — every graphic choice should remove noise or intensify the intended message, nothing else.
- Treat the plotted emotion curve as a readability convention, not a measurement: it looks quantitative but is almost always an intuitive estimate, and real experiences often carry mixed positive-and-negative emotion at once, not one value at a time.
- Work bottom-up (cluster raw findings) and top-down (let the draft map direct further consolidation) at the same time, alternating between the two, rather than finishing one pass before starting the other.

## Anti-patterns
- **Repeating an ongoing behavior across the timeline**: a continuous behavior should be marked once with a line extended across the diagram — repeating the box adds clutter, not information.
- **Letting alternate-flow splits multiply**: branching at every decision point produces an unreadable diagram; keep splits temporary and rejoin branches.
- **Dumping in everything from the research**: after being steeped in data, the instinct is to keep it all — this defeats the compact, single-glance purpose of an alignment diagram.
- **Mixing voice**: switching between first- and third-person within one diagram undercuts the natural-language reduction and reads as inconsistent.
- **Bordering every cell with dark grid lines**: textbook chartjunk — the ink competes with the data; use lighter lines or shaded backgrounds instead.
- **Overusing icons or colors**: past a handful of purposeful icons or hues, readers spend more time cross-referencing the key than reading the diagram; both have diminishing returns.
- **Presenting the emotion curve as measured data**: the plotted line implies a quantification it usually lacks — it's typically estimated intuitively, not derived from research data.
- **Designing only for the screen**: colors read darker on paper and can wreck text-background contrast once printed; proof a large or formal diagram before a costly plotter run.

## Reference Tables

Table 6-1: Guidelines for formatting content (two parallel research insights reduced toward a fictitious software company's customer journey map)

| Guideline | Description | Example 1 (pricing hesitation) | Example 2 (install difficulty) |
|---|---|---|---|
| Start with insights | Start with clusters of findings from research. | People hesitate/reconsider during acquisition because of the premium pricing model | Clear pain point deploying the solution, due to lack of technical knowledge |
| Use natural language | Use language reflecting the individual's own terms. | People reconsider when purchasing because they're nervous/anxious about the high cost | Users struggle to install the software first time without the required technical skills |
| Keep voice consistent | Rewrite in first or third person (pick one) — don't mix. | I reconsider when purchasing because I'm anxious and nervous about the high cost | I struggle to install the software first time because I lack the necessary technical skills |
| Omit pronouns and articles | Omit articles/pronouns to save space — they're implied. | Reconsider when making purchase due to anxiousness/nervousness over high cost | Struggle to install software first time without the necessary technical skills |
| Focus on the root cause | Reduce to underlying motivations and emotions. | Feel anxious/nervous when purchasing due to high cost, then reconsider | Struggle during installation due to lack of necessary technical skills |
| Be concise | Use as few words as possible; use a thesaurus if needed. | Feel anxious during purchase about cost, then reconsider | Struggle due to lack of technical skills during installation |
| Use abbreviations sparingly | OK only if widely used and accepted. | (unchanged) | Struggle due to lack of tech skills during installation |
| Rely on context of map | Position in the grid implies meaning — row/column headers carry it. | "anxious about cost" (col "purchase" × row "feelings"); "reconsider" (col "purchase" × row "actions") | "struggle/lack tech skills" (col "installation" × row "pain points") |

## Worked Example
**Mapping the Lab Test Experience — Mad*Pow Strategy & Service Design Team (Jon Podolsky, Ebae Kim, Paul Kahn, Samantha Louras)**

Client: an international laboratory and diagnostics company wanting to improve the patient's lab-test experience.

1. **Research first.** The team combined stakeholder and user interviews with direct exposure to the service, staff, and operations.
2. **Build a narrative, then stage it.** From research they wrote a narrative of the customer's interaction, organized its steps chronologically, and grouped steps into stages marking meaningful transitions. Research surfaced two upstream stages most teams would miss: "Awareness of a Health Problem," then "Evaluation Whether or Not to Seek Medical Help" — most patients research their own symptoms before contacting anyone. Mapping these showed the client how their service sits inside the patient's larger healthcare journey (Figure 6-17).
3. **Layer in a persona and emotion.** Selecting a persona from the research, the team built an individual scenario on the same stage structure (Figure 6-18) and added that persona's emotions at each step (Figure 6-19) — the layer that exposes which steps need to change. Moments of concern, discomfort, and anxiety were made visible through emotion symbols plus direct quotes, encoded with one color and varying facial expressions; color variation was reserved for the two moments where change would have the biggest positive impact. The anxiety-heavy "waiting for test results" step was split into three sub-steps to make the accumulating negative feeling visible rather than compressed into one box.
4. **Extend into a service blueprint.** Because the patient touches both the provider's office and the testing lab, the team added Front Stage processes for both, aligned against the Back Stage processes needed to support each touchpoint — extending the journey map into service-blueprint territory (Figure 6-20) without losing the readable journey-map layer underneath.

Outcome: a condensed, highly readable customer journey map with an option to layer in service-blueprint detail only as needed, used to point at concrete gaps and improvement opportunities.

## Key Takeaways
1. Settle layout first — default to a table or timeline, deviate only when an alternative shape reinforces the message itself.
2. Handle non-linear reality with the four chronology devices (line-extension, cloud shapes, arrows/circles, temporary rejoined splits) instead of forcing everything onto one strict sequence.
3. Compress research using Table 6-1's eight-step reduction plus the per-facet syntax convention (verb/question/adjective/gerund/noun/change-verb) so the whole diagram reads in one voice.
4. Run every design decision through Simplify/Amplify/Clarify/Unify; treat typography, lines, color, and icons as meaning-carrying choices, not decoration.
5. Build visual hierarchy on grid alignment, weight/size, and layering — then audit specifically for chartjunk before calling the design final.
6. Choose an emotion-representation strategy on purpose (text, an instrument like PrEmo/Capturemo, or a plotted curve), remembering the curve is a convention/estimate, not measured data.
7. Match tooling to formality: whiteboard/sticky-notes or a large-canvas spreadsheet for informal work; Illustrator/Omnigraffle/Visio or online tools (MURAL, Smaply, Lucidchart, Touchpoint Dashboard) when polish, collaboration, or database-driven tracking is required.

## Connects To
- **Ch2**: supplies the organization schemes (chronological, hierarchical, spatial, network) that this chapter's layout-selection guidance builds on.
- **Ch4**: the positive/negative-emotion excerpt used here (Figure 6-13) is the same diagram shown in full at Figure 4-9.
- **Ch5**: Investigate supplies the research clusters this chapter's content-formatting process (Table 6-1) reduces; the chapter opens by pointing back to the Amber Brown case study at the end of Ch5.
- **Ch7**: this chapter scopes itself to the current-state diagram only — future-state ideation and solutions are deferred to Align (Ch7) and Ch8.
- **Ch9 (Service Blueprints)**: the worked example's Front Stage/Back Stage addition is precisely the move of extending a journey map into a blueprint.
- **Ch10 (Customer Journey Maps)**: the worked example and the chapter's fictitious conference/software illustrations are journey-map-style diagrams built with this chapter's method.
- **Ch12 (Mental Model Diagrams)**: cited for its a priori hierarchical-tower layout and Indi Young's line that mental models "capture...the emotion, social environment, and cultural traits" of an experience, not just its cognitive intent.
- **External**: Tufte's graphical excellence and chartjunk (*The Visual Display of Quantitative Information*, *Envisioning Information*, *Visual Explanations*); Desmet's PrEmo and *Designing Emotions*; Bringhurst's *The Elements of Typographic Style*; Dan Roam's *Back of the Napkin*; Joel Katz's *Designing Information*.
