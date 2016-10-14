---
layout: post
title: What Is It That You Do Again?
category: posts
---

"PM" is an overloaded acroynm in the software industry - it can mean Project Manager, Product Manager, Product Marketer, and (in the case of the MongoDB Server team) Program Manager.  The core of this Program Manager role is mostly traditional project management augmented by a "do all the little things needed to make us succeed" ethos left over from the company's youth.  But even with that description it's still not uncommon for a new employee to ask: "What is it that you do again?"

So, like any MongodB sub-team with a broad mission or potentially confusing scope of responsibilities, we have a Team Charter to answer three questions:

- What do we do?
- What do we *not* do?
- How do we measure our success?

That charter, as of October 2016, looks like this:

---
# Server Program Management Team
We devise and improve the structures, processes and tools (SPT) that help Server engineers deliver the **greatest number** of the **highest priority** requirements at the **highest quality** and in the **most predictable** time.

### Team Responsibilities and Mandate
- Invent and execute changes to SPT that improve our 4 key measures of success
  - Collect and present data to support these changes
- Deprecate and remove negative or neutral SPT
- Maintain a backlog, agreed to by both Engineering & Product, for each Server team
- Track internal documentation for each team and major project
- Schedule and run effective meetings by setting agendas and maintaining focus
  - Standups, Kickoffs, Scope/Design Review, Server Weekly
- Maintain accountability for engineering deliverables
- Ensure all associated teams (Cloud, Server, DX, etc.) are informed as quickly as possible about major changes that will affect them

### Non-Goals
- Product prioritization decisions
- Resource Allocation
- Deciding on necessary parties for technical decisions
- Global JIRA management

### Owned Infrastructure & Areas of Influence
- Owned JIRA projects: [a list of JIRA projects]
- Shared JIRA projects: [even more JIRA projects]
- Wiki spaces: [some wiki spaces]
- Google Calendar: [and some calendars]

---

It's not perfect.  For example, saying that we help deliver "the greatest number" of requirements is maddeningly imprecise; requirements come in all sizes and complexities so no single metric can capture our improvement.  If we finish Feature A in 3 months and then Feature B in 2 months, are we doing better?  How does one measure the value of the two features?

But I do like the summary sentence at the top for its pithiness and the values I see embedded in its phrases.

> devise and improve

Development processes can not be "set and forget".  Like bit rot, an eventual drift between the process and reality can set in, requiring awareness and adaptability.  PMs are charged with this continuous improvement of process.

> help Server engineers

PMs serve the team and not vice versa.  If a process is hindering some part of the Engineering team then it should be suspended and re-evaluated for that part of the team (if not the team as a whole).  This is reinforced by the Team Responsibility to remove not only negative processes but even neutral ones.  If it's not part of the solution...

> the greatest number...the highest quality

Poorly structured goals can create perverse incentives. One principle I liked from [High Output Management](http://www.goodreads.com/book/show/324750.High_Output_Management) was the importance of interlocking goals.  If you focus on a single goal, your team's behavior can be distorted in unhealthy ways - sacrificing quality in the name of calling a feature 'done' and moving onto the next one.  Setting and measuring your team by two intelligently counter-balanced goals can keep you from cheating yourself in this way.

> the most predictable time

Importantly, that's not "the shortest  time".  This was the original phrasing but nobody liked it since it's really a paraphrase  of "the greatest number".  Predictability, however, is critical as a company grows and downstream teams (in our case the Cloud team, Drivers team, Marketing, etc.) need to plan *their* operations around our promised output.

As the company and team changes, so will our goals.  So what's next?  We attach metrics to each of these goals that let us judge our improvement over time, starting with how we measure the quality of each release based number and severity of bugs reported.