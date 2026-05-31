# Facilitator Notes

**Event:** Can AI Give Good Feedback? Build One and Find Out  
**Duration:** 3 hours  
**Date:** June 17, 2026

---

## Pre-Event Setup

### Mentimeter Preparation

Create a Mentimeter presentation with the following slides:

**Slide 1: Summary Submission (Open Text)**
- Question: "Write a 50-100 word summary of the Mars article's main scientific findings"
- Settings: Open text field, 100 word limit
- Allow multiple submissions if time permits

**Slide 2: Vote for Best Summary**
- Question: "Which summary is strongest?"
- Type: Multiple choice (populate with anonymized submissions from Slide 1)
- Settings: One vote per participant

**Slide 3: What Made It Good? (Word Cloud)**
- Question: "Why did you vote for that summary? What made it good?"
- Type: Word cloud
- Settings: Allow 1-2 submissions per person

**Slide 4: How to Improve? (Word Cloud)**
- Question: "What could other summaries improve to be better?"
- Type: Word cloud
- Settings: Allow 1-2 submissions per person

### Materials Checklist
- [ ] Mentimeter link ready to share
- [ ] Projector/screen for displaying Mentimeter responses
- [ ] All participants have forked the repository
- [ ] GitHub Copilot access verified for all participants
- [ ] Team assignments prepared (3-4 people per team)
- [ ] Cross-testing assignments ready (which team tests which)

---

## Phase 1: Orientation & Elicitation (~40 min)

### Timeline:
- **0:00-0:05** — Welcome & introduce the Mars article
- **0:05-0:15** — Silent reading & writing (Mentimeter Slide 1)
- **0:15-0:17** — Vote for best summary (Mentimeter Slide 2)
- **0:17-0:22** — Discuss what made it good (Slide 3 word cloud)
- **0:22-0:27** — Discuss improvements (Slide 4 word cloud)
- **0:27-0:35** — Introduce the Universal Science Writing Rubric
- **0:35-0:40** — Evaluate example summary using rubric

### Facilitator Script:

**Introduction (5 min):**
> "Before we build AI feedback agents, let's experience the task ourselves. You'll find an article about Mars geology in assets/article.md. Read it, then write a 50-100 word summary in Mentimeter."

**After submissions (2 min):**
> "Here are all our summaries, anonymized. Vote for the one you think is strongest. Trust your instincts—we'll analyze why later."

**Quality discussion (5 min):**
> "Most of you voted for [winning summary]. What made it good? Submit 1-2 characteristics."
> 
> [Display word cloud]
> 
> "Notice these themes: [point out patterns—accuracy, clarity, completeness, etc.]. You're already experts at recognizing quality!"

**Improvement discussion (5 min):**
> "Now flip it: what could other summaries improve? What's missing or unclear?"
>
> [Display word cloud]
>
> "Great—you've just done what feedback agents need to do: identify quality AND explain how to improve."

**Rubric introduction (8 min):**
> "Your intuitions align with research. Let me introduce the Universal Science Writing Rubric—it formalizes the criteria you just discovered."
>
> [Walk through 5 dimensions: Content Accuracy, Interpretation, Audience, Organization, Writing Quality]
>
> "This rubric is your agent's foundation. Your job is to decide HOW it should use these criteria to help students."

**Example evaluation (5 min):**
> "Open assets/example-summary.md. Use the peer-rating worksheet to score it on each dimension. How does using the rubric compare to your gut instinct?"

---

## Phase 2: Agent Design (~60 min)

### Key Facilitator Moments:

**Kickoff (5 min):**
> "You've now experienced:
> - Writing under constraints
> - Identifying quality
> - Giving feedback
> - Using a rubric
>
> Time to build an agent that does this! In GitHub Copilot Chat: click the + button → Instructions → Configure Instructions → + New Instruction file. Name it with your group name (e.g., group1-feedback-agent.md). Write rules for how your agent should give feedback."

**Design questions to pose:**
- Should your agent score first or guide through questions?
- Focus on one dimension or all five?
- Correct errors or ask reflective questions?
- Sound like a teacher, peer, or coach?

**Mid-phase check-in (30 min mark):**
> "Teams: have you tested your agent with Copilot Chat yet? Try it on your own summary from Phase 1!"

---

## Phase 3: Cross-Testing (~25 min)

### Assignments:
Prepare team rotation (e.g., Team A tests Team B, Team B tests Team C, Team C tests Team A)

**Kickoff:**
> "Clone the team assigned to you. Test their agent on YOUR summary from Phase 1. Submit feedback via GitHub Issues using the template."

---

## Phase 4: Iteration (~30 min)

**Kickoff:**
> "Check your Issues tab. What did other teams notice? Pick 1-3 changes to make. Update your agent and test again."

---

## Phase 5: Showcase & Vote (~25 min)

### Setup:
- Teams at stations around room
- Laptops open to their agent + Copilot Chat
- Voting tool ready (e.g., Mentimeter poll or Google Form)

**Gallery walk (15 min):**
> "Visit every station. Submit your summary to their agent. Ask about their design choices."

**Vote (10 min):**
> "Vote for the most effective agent (not your own). Consider: usefulness, specificity, rubric use, tone, creativity."

**Closing:**
> "Winner: [Team Name]! Brief demo of their approach. Thank you all—your designs will help us understand what makes AI feedback truly useful."

---

## Post-Event

- Export all GitHub repositories (for research)
- Send thank-you email with research summary timeline
- Share winning agent as inspiration for future participants
