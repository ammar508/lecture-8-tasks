---
name: wordpress-project-planner
description: Turns a raw client message (e.g. "I need a website for my dental clinic") into a full WordPress project plan - required pages, features, plugins, Elementor addons, paid Envato template kit suggestions, follow-up questions to ask the client, timeline, budget (excluding domain/hosting), possible problems, and a development checklist. Use this whenever the user pastes or describes a client inquiry, brief, or lead for a WordPress/Elementor website and wants it scoped, quoted, or turned into a proposal - even if they just paste the client's message with no further instructions. Also use when the user asks to "scope", "quote", "estimate", or "plan" a WordPress project, or asks what plugins/addons/template kit to use for a given type of website.
---

# WordPress Project Planner

## Purpose

A freelance WordPress/Elementor developer gets a short, often vague message from a client
("I need a website for my dental clinic"). Before any design or development work can start,
that vague ask has to become a real, quotable project: pages, plugins, addons, a template kit,
a timeline, a budget, and a list of questions the client still needs to answer.

This skill turns the raw client message into that project plan. The goal is to think like an
experienced WordPress agency account manager scoping a new lead - someone who has built dozens
of sites in this niche, knows exactly which plugins tend to be needed, knows where clients
under-specify things, and knows how to ask for the missing details without sounding like a
questionnaire.

## When to reach for this

Trigger this any time the input is a client's raw ask for a website - a single line, a paragraph,
a forwarded email, a WhatsApp message, a Fiverr/Upwork brief. It doesn't matter how short or
underspecified the message is; short messages are the normal case, not an edge case, since real
clients rarely spec things out. If the user gives extra context (existing brand, budget hints,
must-have plugins, competitor sites), fold it in rather than ignoring it.

## How to think about it

Every client message under-specifies the project. The skill's job is not to just answer with
generic WordPress boilerplate - it's to reason about *this specific business type* the way
someone who has actually built that kind of site before would. A dental clinic site needs
appointment booking and HIPAA-adjacent trust signals; a restaurant site needs a menu and maybe
online ordering; a real estate site needs property listings and search/filter. Let the business
type drive every section below, rather than reusing one generic list for everything.

When the message gives almost nothing to go on (just "dental clinic," no city, no size, no
existing brand), make reasonable assumptions for a **typical small local business of that type**
and say so briefly, rather than refusing to estimate until every question is answered. The
client-facing questions exist precisely to correct these assumptions later - the point of this
skill is to produce something the freelancer can act on or send to the client today, not to
stall on missing information.

Estimates (pages, timeline, budget) should be **ranges**, not fake precision. A single-location
service business site is a very different job from a multi-location clinic with a patient
portal, and the plan should make that branching visible rather than picking one number and
hiding the uncertainty.

## Output format

Always respond using this exact structure (headings and order). Keep each section tight -
bullet points, not paragraphs. This is a working document a freelancer will paste into a quote
or proposal, not an essay.

```markdown
# [Business/Project Name] - Website Project Plan

## Pages Needed
- Bullet list of recommended pages, grouped as Core (always include) vs. Optional (nice to
  have / depends on client answers). Note if a page implies extra build effort (e.g. a Booking
  page usually means a booking plugin, not just a static page).

## Features
- Functional capabilities the site needs (e.g. appointment booking, WhatsApp chat button,
  Google Maps + directions, patient/customer testimonials, before/after gallery, multi-language,
  online payments). Tie each feature back to *why* this business type needs it.

## Required Plugins
- Concrete plugin names (not categories), grouped by purpose: e.g. "Booking: Amelia / Bookly",
  "Forms: WPForms / Fluent Forms", "SEO: Rank Math", "Security/Backup: Wordfence, UpdraftPlus",
  "Speed/Cache: WP Rocket or free alternative". Prefer naming 1-2 real, current, well-regarded
  options per need rather than one single pick, and note which are free vs. typically paid.

## Elementor Addons
- Specific addon plugins/widgets that would help build this particular site (e.g. Essential
  Addons for Elementor, JetEngine for dynamic content, Crocoblock/JetBooking for bookings,
  HappyAddons). Only list ones actually relevant to the features above - don't pad the list.

## Suggested Envato Template Kit
- 1-3 *types* of Elementor template kits on ThemeForest/Envato Elements worth searching for,
  described by niche and style (e.g. "a dental/medical clinic Elementor kit with an appointment
  booking layout" or "a real estate listing kit with property search"). Since exact catalog
  listings change over time and can't be verified live, describe what to search for and what to
  check before buying (recent update date, good support rating, matches the required features)
  rather than inventing a specific product name/price that can't be confirmed.

## Questions to Ask the Client
- The specific, professional follow-up questions this project can't be accurately scoped
  without. Prioritize the ones that would change the page count, plugin choices, or budget the
  most (number of locations/services, existing branding/content, need for online payments,
  content-in-hand or needs copywriting, reference sites they like). Phrase these exactly as you
  would send them to the client - ready to copy-paste.

## Timeline
- A realistic range in weeks/days, broken down by phase (e.g. Discovery & content collection,
  Design, Development, Revisions, Launch). Note what would push it toward the low vs. high end
  of the range.

## Possible Problems
- Likely friction points for *this* project specifically - e.g. client won't have professional
  photos ready, scope creep on "just one more page," slow content/copy delivery, third-party
  booking system integration surprises, GDPR/HIPAA-style compliance needs, translation content
  lagging behind. Frame these as things to flag to the client or plan around, not just risks to
  list.

## Final Budget
- A budget RANGE in the client's likely local currency if inferable (default to PKR for
  Pakistan-based freelancers unless told otherwise, and also show a USD range if this looks like
  an international/Upwork/Fiverr client), explicitly excluding domain and hosting. Roughly
  break it down by category (design/dev, plugins/kit licensing if paid ones are recommended,
  content/copywriting if needed) so the client can see where the money goes.

## Development Checklist
- A concrete, sequential checklist (use `- [ ]` markdown checkboxes) covering the full build:
  discovery/content collection, environment setup, theme/kit install, page building, plugin
  configuration, forms/booking setup, SEO basics, speed/security hardening, cross-browser and
  mobile QA, client review, launch, and post-launch handoff (e.g. a short "how to edit your
  site" note or Loom video). This should be usable as-is as a project tracker.
```

## Notes on tone and judgment

- Write like a professional account manager preparing something to send to (or discuss with)
  the client - confident and specific, not hedgy, but honest about what's still unknown.
- Don't invent fake specifics that could mislead (e.g. a real named Envato product with a made-up
  price) - describe what to search for instead, as covered above.
- If the client's message already answers some of what would normally be a follow-up question
  (e.g. they mention "3 branches" or "we already have a logo"), don't ask about it again - use it
  to sharpen the plan and drop it from the questions list.
- If multiple very different project sizes are plausible from the message (e.g. "online store"
  could be 10 products or 500), say so and give both a lean-scope and full-scope estimate rather
  than silently picking one.
