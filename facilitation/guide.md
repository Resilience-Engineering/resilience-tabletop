## Facilitation Guide

This short facilitation guide is providing a minimal set of instructions to support people wanting to run the [vignette](../scenario/vignette.md) scenario with their team, organization, or peers. It is not yet comprehensive and is intended to change based on the feedback we might receive from participants. We have so far divided it in 3 sections:

1. [Preparation](#preparation), defining the structure of the session
2. [Discussion](#discussion), helping structure conversations during the session
3. [Lessons & Learning](#lessons-learning), providing a framing for post-session discussions and introspection.

We are always receptive to feedback on how to improve these guidelines based on practical experience.

### Preparation

As a facilitator, you have a challenging role in this exercise. You are to both guide the group down a path that remains practicable for the vignette, while also making sure that you keep options open for interesting insights to come up.

We recommend the following preparation steps before involving the group:

- Read through the [vignette](../scenario/vignette.md) to get an overview of the direction it is going, which clues and elements mentioned in early steps become significant later, and so on
- Make a note of what people are trying to get out of the exercise; the vignette is intended to create a useful context in which to explore decision-making, and there may be a focal point there.
- Figure out how much time you have allocated to it, and try to mentally divide them in a schedule.  Keep it flexible to make sure not to interrupt a great discussion, as well.

For example, we could recommend the following schedule for a one hour run:

- 00-05 minutes: get everyone in place, go over the goals and logistics of the exercise, your role as a facilitator.
- 05-10 minutes: present the background information from the vignette introducing the organization and its project
- 10-15 minutes: describe phase 1 of the incident.
- 15-30 minutes: let the team discuss what they would do. Ask open questions and provide extra information they may need
- 30-33 minutes: conclude phase one and introduce phase two
- 33-43 minutes: discussion and questions again
- 43-45 minutes: conclude phase two and introduce phase 3
- 45-55 minutes: discussion and questions
- 55-60 minutes: closing words, gathering impressions, and  feedback

You can of course adjust the schedule, shorten the exercise, and instead add time for an overall discussion on lessons and learnings, or do it full length and follow-up later.

In general, there are no good or bad way for participants to react during the exercise: everything is data, and weird things may be better to practice in a simulation than in real incidents.

For first runs, we would recommend not imposing roles or job titles, and let participants self-selected based on their existing structure or procedures. Pay attention to what they do and what dynamics come up, but try not to steer them into a specific response patterns.

If you've grown comfortable with running the exerise as a facilitator, you may feel free to add or specify roles, or add an antagonistic role player or emphasize behaviours that could be considered “negligent” and get new insights from new participants, as well as you can with everyone being their normal selves.

To keep the exercise on topic, you can rely on the fact that the vignette is a bit hourglass-shaped between phases. Each section opens with a setting of a situation, a vague problem with high-level explanations, room to discuss where things go, and a resolution that can either fit many options or “ignores” the discussion (“an engineer not in the room stabilized the system by doing x”).

This means that you can give people some margin to play around with, and maintain “fog of war” on paths that would stray too far from narrowing the hourglass.

For example, if for phase 1 someone recommends permanently removing the cache altogether and you knowing it comes back in phase 2, feel free to say a senior engineer said it would not be possible without collapsing the system (or maybe they try and it doesn’t work). But if someone suggests opening a livestream to crowdsource a fix? That’s unconventional but doesn’t break any future phase!

Other useful excuses to hide information can include:

- The person in charge is on vacation/retired/ill/off the grid 
- Time pressure (say a major demo at an industry keynote) forces a decision or prevent more careful exploration
- Legacy systems whom nobody understands fully and the fix would take a bit too long
- The explanations given can be wrong out outdated (“a person who was on that team last year tells me …”)

Each phase of the vignette comes with a hand-drawn architecture diagram—meant to look like an engineer quickly put it together during incident response. Feel free to withold it, use it for your own support as facilitator, to show it, or to draw it yourself for your group if or when they ask for more information.

If you can record the session, do so; if you can’t, consider finding a note-taker who is neutral and aware of your role to support you.

### Discussion

The main element explored with the vignette and the questions are about **how do we make tradeoff decisions?** While there are a lot of interesting questions to ask, these would likely be our suggestions for each of the vignette's phases:

- Phase 1 questions:
  - What questions do you have about the problem?
  - What factors are you considering in how you want to handle this problem?
  - What risks are you considering (this may be technical risks for cascading failures, or organizational risks like damage to reputation or economic loss or may be something else). 
  - At this point, who do you believe should be involved in this incident response?
  - How might involving those parties impact the incident response?
  - As a manager you may not join every incident. At what point would you want to be made aware of this problem? (skip this question if you are an IC)
  - As an incident responder, at what point would you bring in additional parties to the incident response? (Skip this question if you are a manager)
- Phase 2 questions:
  - How does this unexpected behavior change your perspective on the incident?
  - What strategies might you take to minimize the risk to your company? What factors are you considering by using these strategies?
  - Since this is now public, with the information having gone out in marketing materials, how have your considerations changed?
- Phase 3 questions:
  - How do you consider moving on from this new development?
  - Please provide any other relevant thoughts or comments on your approach to this incident that we have not previously asked about

Other questions that can be useful for any phase (although they may anchor responses?):
  - How critical would you consider this incident to be?
  - Are you feeling like someone made an error in this scenario? What could you imagine making it seem _reasonable_ to do what they did?
  - ???

### Lessons & Learning

Once again, the focus in general is related to making tradeoff decisions. An interesting thing to do with the exercise is to see if the content it has can translate to situations within the organization(s) of the participants.

The following questions may help:

 - Would you consider this to be one incident or multiple incidents? What would influence your descision?
 - Can you identify clashing priorities and conflicts in the scenario? Are any of these value also in a state of tension within your organization?
 - If people asked questions or commented about the sources and causes of the incident, did they focus on dynamics, on the system, the processes, the components or individuals? 
 - How did you balance ensuring getting more accurate information with providing a timely response?
 - Are there elements that surprised you? How did you when that happened?

You may also want to compare this incident to other ones your organization had in the past, or see if any of the elements or challenges in this case could be probable with your organizations.
