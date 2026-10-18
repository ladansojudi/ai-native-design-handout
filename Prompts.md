# QuickBook Course — Prompts to Copy

Copy each prompt and fill in anything inside [brackets] with your own project details. The order is the order we use them in class.

## Session 1

### 6. A better instruction: six parts

**Empty template**

```text
ROLE
[One sentence: who AI should be for this job.]

ABOUT THE PRODUCT AND ITS USERS
[What the product is, who uses it, and how it works today.]

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
[Your files, data, user quotes or research, each one separate.
What we have no evidence for yet.]

WHAT I WANT YOU TO DO AND WHY
[The exact job, and why you need it.
Number the steps if the order matters.]

RULES AND WHY
- If you do not know something, say so.
- For each claim, say where it comes from.
- Use only the information I gave you.
[- Your own rules, each with a reason.]

FORMAT
[What the answer should look like. Add an example if you have one.]
```

**The example we saw in class**

```text
ROLE
You are a UX writer.

ABOUT THE PRODUCT AND ITS USERS
Loop is a habit app for adults recovering from burnout.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
Users say: "The app feels like another job."
We do not know which reminder wording works.

WHAT I WANT YOU TO DO AND WHY
Write 3 short daily reminders, so we can test them.

RULES AND WHY
Use only this information. Say when you do not know,
and label any guess, so we can check it.

FORMAT
A table: reminder | tone | based on
```

## Session 2

### 2. Writing the Brief

```text
- The salon has three branches.
- Some customers book an appointment but do not come (no-show).
- Receptionists spend a lot of time on booking calls.
- We think we may need something like Calendly.
- Please design a better booking experience for us.
```

```text
ROLE
You are a UX researcher helping a product design team.

ABOUT THE PRODUCT AND ITS USERS
QuickBook is a beauty salon with three branches.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
What we know (the client's email and the answers):
[paste the email and the answers here]
What we do not know:
[what the client could not answer, for example:
how many no-shows there are, and why]

WHAT I WANT YOU TO DO AND WHY
Write one short Discovery Brief for QuickBook,
because we need to see what we know and what we do not know
before we research.
Sections: Known facts, Unknowns, Research questions.
Turn each unknown into a research question.
Give each known fact an ID (K1, K2 …)
and each research question an ID (RQ1, RQ2 …).

RULES AND WHY
- Every known fact must come from the email or the answers,
  so we can check it.
- Keep known facts and unknowns separate,
  so I can see how sure we are.
- If information is missing, keep it as unknown, not a guess.
- Do not suggest features or UI,
  because we have not decided what to build.
- Keep these IDs stable in every later output,
  because later files refer to them.

FORMAT
One Brief, short. Stop after writing it.
```

### 3. How we work: a Project in Claude

```text
Discovery for QuickBook, a booking app for a service business:
understand the problem and its users from research and evidence,
before deciding what to build.
```

```text
ROLE
You are helping a product designer with the QuickBook
discovery project. Before any work, read README.md and state.md,
because they hold our rules and where the project is now.

RULES AND WHY
- Keep evidence, interpretation, guesses and unknowns separate,
  so I always know how sure we are.
- Write a guess as a guess, never as a fact.
- Say "I don't know" when our files do not answer something.
- Use only data, numbers, quotes and participants that exist
  in our files, because invented ones would mislead the design.
- Give a source for every important claim, so I can check it.
- Treat external research as evidence about other people,
  not about QuickBook users.
- Use our IDs (K1, RQ1 …) exactly as they are,
  because every file refers to them.
- Stay with understanding the problem: give UI or feature ideas
  only when I ask, because we have not decided what to build.
- Open only the files this task needs, and quote them by ID
  instead of copying them back, because long context uses
  more of my usage limit.
- Keep answers as short as the task allows, and ask before
  writing anything longer than one page, for the same reason.
```

### 4. Research plan

**Research plan**

```text
ABOUT THE PRODUCT AND ITS USERS
QuickBook is a beauty salon with three branches.
Customers book hair and nail services, mostly by phone and WhatsApp.
Receptionists take booking calls and serve walk-in customers.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
"Discovery Brief v2": what we know (the K IDs)
and what we do not know yet (the RQ IDs).

WHAT I WANT YOU TO DO AND WHY
Make a lightweight research plan.
Suggest the research methods that fit each question.
A question can need more than one method.
For each method, say in one line why it fits.
Why: I want to choose methods on purpose, not by habit.

RULES AND WHY
- Stop after the plan and wait for me,
  because I choose the methods before any research starts.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
One row per research question:
what we want to learn · method · input · expected output · why this method
```

### 5. Desk research

**Desk research**

```text
ABOUT THE PRODUCT AND ITS USERS
QuickBook is a beauty salon with three branches.
Customers book hair and nail services, mostly by phone and WhatsApp.
Receptionists take booking calls and serve walk-in customers.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
"Discovery Brief v2". We have no data of our own yet.

WHAT I WANT YOU TO DO AND WHY
Do desk research for the research questions in the Brief.
Why: I want to know what is already known outside our project,
so I know what to listen for in interviews.

RULES AND WHY
- Cover only the questions our research plan gives to desk research,
  because the others belong to the competitive analysis or the interviews.
- Use at most 3 strong sources per research question,
  because a few strong sources are easier to check than many weak ones.
- Give each source an ID (S1, S2 …) and each finding an ID (E01, E02 …),
  so later files can point to them.
- For each source, give its type, year, country and setting,
  because a finding from a hospital in another country may not fit us.
- Label every finding as external, because it is evidence
  about other people, not about QuickBook users.
- Quote the exact sentence from the source. If you could not
  capture it, say so and mark any paraphrase as a paraphrase,
  because I will check every quote against its source.
- Say "I don't know" where you found no good source.
- Stay with findings and leave out UI or feature ideas,
  because we have not decided what to build.

FORMAT
For every finding: ID · RQ · finding · exact sentence · source ID · link
```

### 6. Competitive analysis

**Step by step with screenshots**

```text
ABOUT THE PRODUCT AND ITS USERS
QuickBook is a beauty salon with three branches.
Customers book hair and nail services, mostly by phone and WhatsApp.
Receptionists take booking calls and serve walk-in customers.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
Screenshots I took myself, in order, while booking one appointment, then rescheduling and cancelling it
on my own Calendly booking page: [attach your screenshots]
The page link: [your own booking link]
The link from the confirmation email: [link]
We do not know yet how a booking tool handles booking,
rescheduling and cancelling, step by step.

WHAT I WANT YOU TO DO AND WHY
Go through my screenshots one by one. For each screenshot:
- give the screen an ID (SC01, SC02 …), so we can point to it later
- list what is on it: content, choices, buttons
- note what the customer has to decide here
Why: I want to see how an existing booking tool works,
so I can ask better questions in our interviews.

RULES AND WHY
- Describe only what is on the screenshots, because that is our evidence.
- If a step is missing between two screenshots, say "not seen"
  and do not guess it.

FORMAT
One block per screen: ID · what is on it · what the customer decides
```

**User flow and information architecture**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
My screenshots, attached again: [attach your screenshots]. Screen IDs: SC01 onwards.

WHAT I WANT YOU TO DO AND WHY
Draw:
1. The user flow: every step and decision
   for booking, rescheduling and cancelling.
2. The information architecture:
   how pages and content are grouped.
Why: a drawing shows the steps, the decisions and the structure
at one glance, so we can compare them with our questions.

RULES AND WHY
- Draw only what you saw, because a guessed step looks just as real.
- If a path exists but you did not open it, mark it "not seen".
- Put the screen IDs on every step, so I can check each one.

FORMAT
Draw both in FigJam: the user flow as a flowchart, the information architecture as a tree of pages.
```

**Analysis (competitive)**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
"Discovery Brief v2", the screens and the flow above.

WHAT I WANT YOU TO DO AND WHY
Analyse this flow against the research questions in the Brief that this tool can help with.
For each RQ:
- what Calendly shows, with screen IDs as evidence
- what it does not show, or cannot tell us
- questions to take into our interviews
Why: I want to know what this tool can tell us about our questions,
and what it cannot.

RULES AND WHY
- Treat this as one tool, not as evidence about
  QuickBook users or what they need.
- Keep what you saw separate from what you think it means,
  so I know which parts to check.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.
- Stay with analysis and leave out UI or feature ideas for QuickBook,
  because we have not decided what to build.

FORMAT
One section per RQ: shows · does not show · questions for interviews
```

### 7. Interviews

**Questions**

```text
ABOUT THE PRODUCT AND ITS USERS
QuickBook is a beauty salon with three branches.
Customers book hair and nail services, mostly by phone and WhatsApp.
Receptionists take booking calls and serve walk-in customers.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
"Discovery Brief v2"
"Desk Research v1"
"Competitive Analysis v1"
None of these is evidence about our own users yet.

WHAT I WANT YOU TO DO AND WHY
Write interview questions for two groups:
1. Customers
2. Receptionists
Why: external research and one tool cannot tell us
about our own users. Interviews can.

RULES AND WHY
- Ask about real past behaviour before opinions,
  because people describe what they did more accurately
  than what they would do.
- Ask open, neutral questions that name no solution or tool,
  because a named solution pushes the answer.
- Treat desk research and Calendly as ideas to test,
  not as facts about our users.
- Ask about what we do not know, not about what we think we know,
  so the interviews can surprise us.
- Write at most 10 questions per group, so an interview fits its time.
- Show the questions only and wait,
  because I approve the questions before we make sheets.

FORMAT
Next to each question, the research question it serves.
At the end, any research question that no question covers.
```

**Sheets**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
The questions above. They are approved.

WHAT I WANT YOU TO DO AND WHY
Create two interview sheet templates:
one for customers, one for receptionists.
Why: during an interview I have to listen, ask and take notes at once.
A sheet makes that easier, and every interview gets recorded the same way.

RULES AND WHY
- Keep the approved questions, in the same order and with no new ones,
  because they are already approved.
- Use the participant ID instead of a name, phone or email,
  because we keep no personal details.

FORMAT
Top of each sheet: participant ID, role, date, method.
Moderator part: how to open, and common mistakes to avoid.
For each question:
- what to listen for, and one follow-up question
- quick-check options (for me only, not to read aloud)
- space for notes and an exact quote
- a "not asked" box
End of each sheet: an evaluation table, one row per research question,
with columns: answered yes / partly / no, and a note.
```

**Analysis (interviews)**

```text
ABOUT THE PRODUCT AND ITS USERS
QuickBook is a beauty salon with three branches.
Customers book hair and nail services, mostly by phone and WhatsApp.
Receptionists take booking calls and serve walk-in customers.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
The sheets of C01, C02, C03 (customers), R01, R02 (receptionists).
This is simulated classroom data, not real research.
"Desk Research v1"
"Competitive Analysis v1"

WHAT I WANT YOU TO DO AND WHY
Analyze these five interview sheets.
Compare each pattern with the desk research and the Calendly analysis:
supports / contradicts / new / still unknown.
Why: I want to see what repeats, where people disagree,
and what fits or contradicts what we already found.

RULES AND WHY
- Say at the top that this is simulated classroom data,
  so no one reads it as real research.
- Give each pattern an ID (P1, P2 …) and link it to an RQ,
  so the dashboard can point to it.
- Keep what people said separate from what you think it means.
- For every pattern, list the participant IDs behind it,
  so I can check where it came from.
- Use real counts instead of "most" or "many",
  because five people is a small number.
- Show where participants contradict each other.
- Name which customer or staff situations are missing from our data.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.
- Stay with findings and leave out solutions and UI ideas,
  because we have not decided what to build.

FORMAT
A table: pattern ID · what they said · who · RQ ·
link to desk research or Calendly · what it might mean
```

### 8. Dashboard

**Skeleton**

```text
ABOUT THE PRODUCT AND ITS USERS
QuickBook is a beauty salon with three branches.
Customers book hair and nail services, mostly by phone and WhatsApp.
Receptionists take booking calls and serve walk-in customers.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
"Discovery Brief v2"
"Desk Research v1"
"Competitive Analysis v1"
"Interview Synthesis v1" (simulated classroom data)

WHAT I WANT YOU TO DO AND WHY
Show me only the structure of a project dashboard.
Why: I want to agree on the sections before anything is built,
because changing a structure is cheaper than changing a finished page.

RULES AND WHY
- Wait for my approval before building anything.

FORMAT
Section titles + one line describing each.
```

**Full dashboard**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
Only the four approved files above.

WHAT I WANT YOU TO DO AND WHY
Create an interactive artifact called: QuickBook Discovery Dashboard
At the top: version v1.0, today's date, what changed.
Show:
- what we know (K IDs), including each answered RQ as a new K
  (next free number), keeping its RQ ID and the pattern IDs behind it
- desk research findings (E IDs)
- competitive analysis findings (Calendly, screen IDs)
- interview findings (P IDs), labeled as simulated classroom data
- contradictions between the sources
- hypotheses: still open, and no longer believed (marked "Deprecated",
  with one very short reason)
- research questions still open
- the next step
Why: our findings are spread over several files. I want to see
in five seconds what we know, what we don't know yet, and what comes next.

RULES AND WHY
- Keep desk research, competitive analysis and interviews separate,
  because they come from different kinds of sources.
- Use a chart only where the files have real numbers,
  because a chart with invented numbers looks like evidence.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.
- Stay with findings and leave out UI ideas,
  because we have not decided what to build.

FORMAT
Visual first, short, easy to scan.
```

## Session 3

### 2. Problem

```text
ROLE
You are a UX researcher helping a product design team.

ABOUT THE PRODUCT AND ITS USERS
QuickBook, a booking app for a service business.
Its user groups are described in our dashboard.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: "Dashboard v1" (our interviews and desk research).
We do not know: anything the dashboard does not cover.

WHAT I WANT YOU TO DO AND WHY
Write the main problems for QuickBook, because we will choose
personas, a solution and flows from them.

RULES AND WHY
- Describe problems only. Solutions come later, after the personas.
- Maximum 4 problems, so we can discuss each one in class.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
For each problem:
- one sentence
- one very short reason, from our interviews or desk research
```

### 3. Persona

```text
ROLE
You are a UX researcher helping a product design team.

ABOUT THE PRODUCT AND ITS USERS
QuickBook, a booking app for a service business.
Its user groups are described in the dashboard.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: "Dashboard v1" (our interviews and desk research).
We do not know: anything the dashboard does not cover.

WHAT I WANT YOU TO DO AND WHY
Create a user persona for each user group in our dashboard,
because we will design the solution, flows and screens for them.

RULES AND WHY
- Describe each group by its role, not with an invented name, age
  or quote, because those are not in our evidence.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
For each persona:
- Maximum 6 lines: goal, what is hard, what they do today.
- End with one very short reason, from our interviews and desk research.
```

### 5. Solution

**How might we questions**

```text
ROLE
You are a product designer helping a design team.

ABOUT THE PRODUCT AND ITS USERS
QuickBook, a booking app for a service business.
Its users are the personas in "Persona v1".

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: the approved problems and personas.

WHAT I WANT YOU TO DO AND WHY
Write one "How might we…?" question for each problem,
because a question keeps us open to more than one solution.

RULES AND WHY
Questions only. We look for solutions in the next step.

FORMAT
One line for each question, so they are easy to compare.
```

**Three directions for each question**

```text
ROLE
You are a product designer helping a design team.

ABOUT THE PRODUCT AND ITS USERS
QuickBook, a booking app for a service business.
Its users are the personas in "Persona v1".

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: the approved problems, personas and the dashboard.
We do not know: whether any direction works for real users.

WHAT I WANT YOU TO DO AND WHY
For each question, give 3 different solution directions.
We will choose one direction per problem ourselves,
so we need real alternatives to compare.

RULES AND WHY
- Describe ideas, not screens or buttons. We design screens after the flows.
- If our evidence does not support a direction, write "no evidence",
  so we can see which ideas are guesses.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
For each direction:
- one sentence
- which persona and which problem it serves
- one very short reason, from our interviews or desk research
```

### 6. User flow

```text
ROLE
You are a product designer helping a design team.

ABOUT THE PRODUCT AND ITS USERS
QuickBook, a booking app for a service business.
Its users are the personas in "Persona v1".

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: the approved problems, personas and "Solution v1".
We do not know: how real users move through it yet.

WHAT I WANT YOU TO DO AND WHY
Write one flow for each persona, for the main thing that persona
does with QuickBook in the chosen solution,
because the screens we draw next will come from these steps.

RULES AND WHY
- Describe what the persona does, not screens or buttons,
  because we choose screens in the next step.
- Stay inside the chosen solution, because it is already approved.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
For each flow:
- Name it after the persona.
- Numbered steps, maximum 8.
- End with one very short reason, from our interviews or desk research.
```

**Drawing the flows in FigJam**

```text
WHAT I WANT YOU TO DO AND WHY
Draw the approved flows in FigJam,
because a picture makes missing or extra steps easy to spot.

RULES AND WHY
Draw only the approved steps, because the flow is already reviewed.

FORMAT
- One flowchart for each flow, one box for each step.
- Show the unhappy paths as dashed side branches.
```

### 7. Wireframe

**List of screens**

```text
ROLE
You are a product designer helping a design team.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: "Flows v1".

WHAT I WANT YOU TO DO AND WHY
List the screens we need to draw as low-fidelity wireframes.
We approve the list before drawing, so no extra screens slip in.

RULES AND WHY
- Only screens that come from a step in the flows.
- Give the list only. We draw after we approve it.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
One line for each screen: the persona, the step it comes from, and its name.
```

**Content of each screen**

```text
ROLE
You are a product designer helping a design team.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: the approved screen list and "Flows v1".

WHAT I WANT YOU TO DO AND WHY
For each screen on the approved list, write what will be on it.
We agree on the content before drawing, so the drawing only shows layout.

RULES AND WHY
- Keep it short, so we can review it in class.
- Write the content only. We draw after we approve it.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
For each screen:
- the main parts (maximum 4)
- the one thing the persona can do there
```

**Drawing the wireframes as an Artifact**

```text
ROLE
You are a product designer helping a design team.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: the approved screen list and the approved contents.

WHAT I WANT YOU TO DO AND WHY
Draw the approved screens as low-fidelity wireframes,
because we want to check the layout, not the look.
Create an interactive artifact called: QuickBook Wireframes

RULES AND WHY
- Grey boxes with labels only, because colour and images make a draft
  look finished.
- Use placeholder labels instead of final copy.
- Only what is on the approved list.

FORMAT
- One screen for each item on the approved list.
- At the top: version v1.0, today's date, what changed.
```

**Four states of one screen**

```text
ROLE
You are a product designer helping a design team.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We do not know: how the business handles most of these cases.

WHAT I WANT YOU TO DO AND WHY
Take screen [persona + screen name] and create 4 variants side by side:
Default, Empty (no free slots), Loading, Error.
Real users also see these states, not only the ideal one.

RULES AND WHY
- Same layout, grey boxes only, so only the state changes.
- If we don't know how the business handles it, write "ask the company",
  because that is the company's decision, not ours.

FORMAT
- Under each variant: one line on what the user can do next.
- Update the version and "what changed".
```

## Session 5

### 2. The setup prompt — runs once

```text
ROLE
You are setting up a new project for a designer who does not write code.

ABOUT THE PRODUCT AND ITS USERS
[QuickBook — a booking app for a service business with three branches.]
[It is a web app that people open in a browser.]
Who the users are is described in my approved files below.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
This folder is my course folder. My approved work from earlier sessions
is in it: [Discovery Brief, Problem Statement,
Persona, Flows, Wireframes].
Read these files before you do anything else, because they hold the
decisions the app must follow.
Leave the interview sheets closed: they are long and hold people's
personal details, and the findings in the approved files are enough.
We do not know anything the approved files do not cover.

WHAT I WANT YOU TO DO AND WHY
Set up the project for the rest of the course. Every future chat in
this folder starts from what you set up now, so set it up carefully.
Choose the tools yourself and tell me in one line what you chose.
Create:
1. The project itself, in a new folder called app, with a dev server I
   can start. Everything you create goes inside app.
2. The rules file that you read automatically at the start of every chat
   in this folder — use the file name your own tool expects, and tell me
   what you named it. Put these rules in it:
   - Read my approved files (listed above) before building any screen, so
     every screen comes from my research and not from a guess.
   - Ask before adding a new library, because each one adds weight and
     more things that can break.
   - Keep styles in one CSS file per component, so I can change the look
     of one part without touching the others.
   - Change only the files I ask about, so nothing I have already checked
     changes behind my back.
   - After every change, update state.md yourself: add a History row,
     correct the Status table, and add a Decisions row if a choice was
     made. This is the one exception to the rule above, because the next
     chat needs to know where we stopped.
   - Before saying something works, start the app and report any errors
     from the terminal, because "it should work" is not the same as "it
     runs". Say plainly that you have not looked at the screen — I check
     that.
   [- add your own rules here, each with its reason]
3. README.md, written from the research: what the product is, who the
   users are, and the list of screens we plan to build.
4. state.md with three tables: Status (what works now), Decisions (date,
   decision, reason), History (date, what changed).

RULES AND WHY
- Keep every file you create inside the app folder, so my course files
  stay exactly as they are.
- Build no screens yet. This chat is only for the setup; the screens
  come in the next prompt, with my wireframes.
- Write README.md only from my approved files, not from general
  knowledge, because it describes our product and our users.
- If something is not in the information above, say you do not know,
  so we can find it out.

FORMAT
In the header of every .md file write the version and the date yourself,
so I can tell versions apart. Ask me only for the creator name.
When you are done, show me the folder structure and tell me how to start
the app.
```

### 3. One prompt, all the pages

```text
ABOUT THE PRODUCT AND ITS USERS
QuickBook, a booking web app. The flow, the screens, the states and the
users are described in my approved files.

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
1. [My approved files] — my own research. The flow, the screens and the states
   are described there. Read all of it before anything else.
2. A flow map that lists every step and marks which screens I drew and
   which ones you design. Follow it.
3. The pictures I attached, drawn by me. The flow map says which
   screen each one is. Follow their layout.
   They are grey on purpose — there is no colour direction yet, so
   use plain neutral styling for now.
We do not know what should happen in cases the research does not cover.

WHAT I WANT YOU TO DO AND WHY
Build the whole QuickBook booking flow in one go. When all the screens
are built together, they share one structure. Screens added one by one
each get a new decision and stop looking alike.
1. Every screen in the flow and every state the research names.
   For the screens I drew, follow my pictures.
   For the screens I did not draw, design them yourself from the research.
2. Go through the whole flow as if you were using it, and list the cases
   the research does not cover — what happens when something fails, when a
   name is longer than the card, when I click twice, when I come back an
   hour later.
   For each one: the case in one line, what you propose, and whether it
   comes from my research or is your own suggestion, so I can see where you
   used my research and where you guessed.
   Order by how likely it is. Maximum 6. Build none of them yet, because I
   choose which ones go in.
3. A floating bar, pinned to the bottom centre of the window, always
   on top of the page, so I can show every state without clicking through
   the flow.
   - One button per screen and state, with its name on it.
   - The one I am looking at is clearly marked.
   - Clicking switches immediately, no reload.
   - Big enough to read on a projector.
   This bar is a tool for me, not part of the product: keep it in one file
   called StateSwitcher and give it its own plain look, unlike the product,
   so nobody mistakes it for part of the app and I can remove it in one
   step. Tell me the one line I delete to remove it.

RULES AND WHY
- Let the screens hand over to each other, without a routing library,
  because for a few screens a library only adds complexity.
- What the customer picked travels with them, so nothing is asked twice.
- One folder per screen, with its own .tsx and .css, so each screen can
  be changed on its own.
- Fake data in one file called data.ts, so I can change the examples in
  one place.
- Show every state with a word or a mark as well as colour, because not
  everyone can tell colours apart.
- Ask before adding any library, because each one adds things that can
  break.
- Keep the page working when the window gets narrower: a maximum width
  on the page, and things wrap instead of overflowing. Use flexible
  widths on the page itself, not fixed pixel widths, because people
  open it on screens of every size.
- Design for the desktop window only for now. I will ask for a phone
  version separately, after I have decided its layout myself.
[- If one of my screens is a time grid, build it as a single CSS
  grid: a time column plus one column per person, one row per
  30 minutes, and a booking spans rows — 30 min is 1 row, 60 min is
  2 rows — so a longer service takes more room on the grid.
  Delete this line if your project has no time grid.]
- If something is not in the information above, say you do not know,
  so we can find it out.

FORMAT
Before you build, give me one line per screen: which screens you are
going to make, and for the ones I did not draw, what goes on them and
what you decided to leave out. Then wait for me, because this is the
cheapest moment to change the plan.
```

```text
WHAT I WANT YOU TO DO AND WHY
Build cases 1, 3 and 5 from your list and leave the rest for now.
Add them to the StateSwitcher too, so I can see each one.

RULES AND WHY
- Keep everything that already works as it is, because I have already
  checked it.

FORMAT
One line for each case: what you built.
```

### 4. Design system — choose one

**Way one — from a published system**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
The source is the official documentation of [Material Design 3]:
[https://m3.material.io]
Read it from there, not from your memory, because remembered numbers
are often wrong.

WHAT I WANT YOU TO DO AND WHY
I want a design system for this project based on [Material Design 3],
so every screen uses one set of named values instead of guesses.
Take only the foundations — colour roles, the type scale, the spacing
scale and the corner radii. Leave out their components, their icons,
their illustrations and their brand colours, so the product looks like
ours and not like theirs.
Then write design-system.md into this folder.

RULES AND WHY
- Every value has a name, and next to it where you read it, so I can
  check where each number came from.
- If you cannot read a value from the page, say so and mark the one you
  chose as your own, so I know which values to check.
- The typeface may not be free to use, and this will be published on
  the web. If it is not free, pick a free one with the same proportions
  and tell me why you picked it.
- Six to eight spacing values and three radii, so the system stays small
  enough to remember.

FORMAT
A markdown file. One table per group: token, value, source, where to
use it. At the end: which values you read, and which you chose.
```

**Way two — from your own design system in Figma**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
The source is my own design system in Figma: [link to your Figma file].
Read the real variables and styles from the file with the Figma
connection, not from a screenshot, because the values in the file
are exact. Read:
- the colour variables and colour styles
- the text styles: font family, size, weight and line height
- the spacing and radius values used in the components
If the file has no status colours, say so.

WHAT I WANT YOU TO DO AND WHY
Write design-system.md into this folder yourself, from the values you
read, so every screen can use one set of named values. Put in it:
- Colour: brand colour, page and card surfaces, borders, text colours
  (primary, secondary, disabled), and status colours for success,
  warning and error.
- Type: one font family, and the sizes with their weight and line height.
- Spacing: one scale of six to eight numbers.
- Radius: three values — small, medium, large.

RULES AND WHY
- Use the values you actually read, and keep my Figma names, so I can
  find each value in Figma.
- Where something is not in the file, build it from what is, and say
  that you did, so I know which values are real.
- Take the foundations only: leave out components and layouts, because
  the screens are built from my wireframes.

FORMAT
A markdown file. One table per group: token, value, where to use it.
At the end, two short lists: which values you read, and which ones you
chose yourself.
```

**Way three — from an open-source design system**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
I added [file-name].md to this folder. It comes from an open-source
design system: [link to the source].
We do not know if every value in it is complete or fits QuickBook.

WHAT I WANT YOU TO DO AND WHY
Read that file and write design-system.md from it, so every screen
uses one set of named values. Keep only the foundations: colour, type,
spacing and radius. Leave out components, icons and illustrations, so
the product looks like ours.

RULES AND WHY
- Use only values that are in the file. Where something is missing
  (for example status colours), build it from what is there and mark it
  as your own choice, so I can check it.
- Every value has a name, so every screen can use it by name.
- Tell me what the licence of the source allows, because this will be
  published on the web.

FORMAT
A markdown file. One table per group: token, value, where to use it.
At the end, two short lists: which values you read, and which ones you
chose yourself.
```

### 5. Applying the design system

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
I have added design-system.md to the project folder.

WHAT I WANT YOU TO DO AND WHY
Apply it to every screen that already exists, so every screen gets its
look from one file and they all match.
- Turn every value in the file into a CSS variable in global.css.
- Replace every colour, size, spacing and radius in the components with
  those variables.

RULES AND WHY
- Keep the content, the flow and the behaviour as they are, because this
  step changes only the look.
- Use only values from design-system.md, so the look has one source.
- Where a screen needs something the file does not have, stop and ask
  me, because a value you invent quietly is one I never get to check.
- Show every state with a word or a mark as well as colour, because not
  everyone can tell colours apart.

FORMAT
When you are done, two short lists, so I can see where the file was not
enough:
1. every value you had to ask me about or invent
2. every place where the old value did not map to anything in the file
```

### 6. Four prompts — pick one based on your situation

**Layout and spacing are not right — the most important prompt today.**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
The content and the flow of [this screen] are right. The layout is not.
The design system gave colour, type and spacing, but not the layout.
What is wrong now:
[What you see with your own eyes. Example:]
- The content sits against the edges of the window and stretches as
  wide as the screen allows.
- Everything is crammed into the top third and the rest is empty.
- The buttons stretch to fill the width, so each one is far bigger than
  the text inside it.

WHAT I WANT YOU TO DO AND WHY
Rework the layout and spacing of [this screen] with the numbers below,
because I am giving the layout now.
Layout:
[Your own numbers. Example:]
- A container, maximum width 1200px, centred, 32px of air each side.
- Two columns: the main side, and a 340px summary column beside it.
- Any tappable cell at least 44px tall, and no wider than 160px — 44px
  is the smallest touch target Apple recommends.
- 32px between sections, 16px between cards, 24px inside a card.
  Use only these vertical numbers, so the rhythm stays even.
Responsive:
- One breakpoint at 900px. Above it, the layout above. Below it, one
  column: the summary moves under the main content and stops sticking
  to the top.
- Below 900px use flexible widths only, and the container padding drops
  from 32px to 16px.
- Any tappable cell stays at least 44px tall at every width.
- Tell me which parts cannot work in one column and what you suggest
  instead. Suggest a change to the existing screen rather than a new
  phone screen, because the phone layout is my decision.

RULES AND WHY
- Use only design-system.md, so the look keeps one source.
- Keep the content, wording and behaviour as they are, because this
  step is only about layout.

FORMAT
Tell me which numbers you used for the container, the columns and the
grid. Then tell me what changes at 900px, so I can check it against
what I asked.
```

**You do not like the whole look**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
The content of [this screen] is right, the look is not.

WHAT I WANT YOU TO DO AND WHY
Give me three different UI directions for the same screen — same
content, same flow, same design system — because I want to choose
between options rather than accept one guess.
Build all three and let me switch between them with the StateSwitcher.

RULES AND WHY
- Use only design-system.md, so all three stay in our system.
- Make them genuinely different, not three paddings of one layout, so
  the choice is a real one.

FORMAT
For each one, one line: what you made bigger, what you grouped, what
you took away.
```

**You know it is not good but not where**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
[This screen] works and it uses my design system. Judge it against:
1. design-system.md — is every value really coming from it?
2. [My approved files] — does the screen still serve the flow described there?
3. A first-time customer in a hurry — what is unclear or easy to get
   wrong.

WHAT I WANT YOU TO DO AND WHY
Tell me where it could be better, so I can choose what to improve.
Use the state switcher and look at every state, not only the normal
one, because problems often hide in the rare states.

RULES AND WHY
- Give me the list only and make no changes yet, because I choose what
  to apply.
- Maximum 8 items, so we can discuss each one.
- If something is fine, say so, so I leave it alone.
- For each claim, say which part of the information above it comes
  from, so we can check it.
- Use only the information above, because we have no other data.

FORMAT
A numbered list, most important first. For each: which state, what is
weak, what you would change, why it is better in one sentence, and the
size of the change — small / medium / rethink.
```

### 7. When something breaks

**You saw an error**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
I ran the app and got this error. Here is the full message:

[paste the whole error here]

WHAT I WANT YOU TO DO AND WHY
Tell me in one sentence what caused it, so I learn to recognise it next
time. Then fix it.

RULES AND WHY
- Change only what the error needs, because everything else is
  already checked.

FORMAT
One sentence for the cause, then the fix.
```

**Still not right after two fixes in a row**

```text
WHAT I WANT YOU TO DO AND WHY
Revert the last change and tell me what you would try differently,
because two fixes in a row have not worked.

RULES AND WHY
- Change nothing else until I answer, because I choose the next try.

FORMAT
Two short parts: what you reverted, and what you suggest instead.
```

**No error but the page is wrong**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
No error, but the screen is wrong. Here is what I see:
[describe it: the blocks overlap / the columns collapsed into one /
the summary card is under the grid instead of beside it]

WHAT I WANT YOU TO DO AND WHY
Fix only that, so nothing else changes.

RULES AND WHY
- Keep the content and the wording as they are, because they are
  already right.
```

**Installing both**

```text
EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
Both skills are in Anthropic's official repository:
https://github.com/anthropics/skills/tree/main/skills

WHAT I WANT YOU TO DO AND WHY
Add two skills to this project, so you can use them in every
future chat in this folder: frontend-design and webapp-testing.
Copy each skill folder into .claude/skills/ in this folder.

RULES AND WHY
- Copy only from that repository, because a skill can run code
  on my computer.
- Keep the skill files exactly as they are, so they keep working
  the way Anthropic wrote them.
- Tell me if a skill needs something installed first, so I can
  decide before you install it.

FORMAT
One line per skill: where you put it, and what it needs.
```

## Templates and skill files

### Project instructions template

```text
ROLE
You are helping [who] with [project name]. Before any work, read
README.md and state.md, because they hold our rules and where the
project is now.

RULES AND WHY
- [Rule 1], because [reason].
- [Rule 2], because [reason].
- Write a guess as a guess, never as a fact.
- Say "I don't know" when our files do not answer something.
- Give a source for every important claim, so I can check it.
```

### README.md template

```text
# [Product name] — README

Version: v1.0 · Date: [date] · Created by: [name]

Read this first. It holds the rules of this Project.
Where the project is right now lives in state.md.

## 1. Project

[Product name] is [one sentence: what it is and who uses it].
The client asked for [the request in one sentence].
Our current job is [the current job, for example: find where the problem really is, not design].

## 2. Files in Context

- Only approved files live in Context. Drafts stay in the chat.
- One version of each file. When a new version is approved, the old one is deleted from Context.
- Files are Markdown (.md), short, one topic per file.
- No names, phone numbers or full interview transcripts.

## 3. Naming

- Approved files: `Name vN.md`
- Chats: `NN — Topic vN` (for example `02 — Desk Research v1`). One task per chat.
- Ideas that do not belong to the current task go to the chat `Parking Lot`.
- Every file starts with: `Version · Date · Created by`.

## 4. IDs

Keep only the ID types you use. Add a type here the first time you use it.

| ID | Meaning | Example |
|---|---|---|
| K | Something we know | K3 |
| RQ | Research question: something we must find out | RQ2 |
| S | Source of external research | S1 |
| E | Finding from external research | E04 |
| H | Hypothesis (a guess, never a fact) | H1 |

- IDs never change and are never reused.
- When an RQ is answered, the answer becomes a new K and keeps its RQ as a reference.

## 5. Evidence

- Keep evidence, interpretation, guesses and unknowns separate.
- External research is evidence about other people, not about our users.
- Mark simulated or practice data clearly.
```

### state.md template

```text
# [Product name] — state

Version: v1.0 · Date: [date] · Created by: [name]

Where the project is right now. Read it at the start of every chat.
Keep it short: it is a summary, not a diary.

## 1. Status

| Item | Value |
|---|---|
| Current phase | [phase] |
| Approved files | README.md (v1.0); [other approved files] |
| Open research questions | [RQ IDs] |
| Next step | [next step and the chat name for it] |

## 2. Decisions

| Decision | Why | What we rejected |
|---|---|---|
| Only approved, short files live in Context | AI cannot tell which of two versions is right | Drafts and old versions |
| One task per chat | Short chats are clearer and use fewer tokens | One long chat for everything |

## 3. Open questions

| Question | Why it is open |
|---|---|
| [question] | [reason] |

## 4. History

| Version | Date | Created by | What changed | Why |
|---|---|---|---|---|
| v1.0 | [date] | [name] | Project created with README.md and state.md | Start of the project |
```

### Skill file: check-skill.md

```text
Name: check-skill
Use when I ask you to review or check an output.

Review this output before I approve it.

1. Check it against the approved project context.

2. Keep these separate:
- evidence
- interpretation
- assumption
- unknown

3. For every important factual or research claim:
- identify the exact claim
- identify the original source
- check whether the source supports the exact claim

4. Flag:
- unsupported claims
- invented information
- contradictions
- missing evidence
- assumptions presented as facts

5. When relevant, label claims as:
- Verified
- Partially supported
- Not supported
- Not relevant

Do not silently rewrite the output.
Show me what needs human review.
```

### Skill file: persona-skill.md

```text
Name: persona-skill
Use when I ask you to check something "as the persona".

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: "Persona v1", based on our evidence.
We do not know: anything the persona file does not say.

WHAT I WANT YOU TO DO AND WHY
When I ask you to check something "as the persona",
say how each persona would likely react,
so we can test an idea before we test it with real people.
1. Read what I give you.
2. For each persona, say how this persona would likely react.
3. For each point, quote the line in the persona file it comes from.
4. If the file does not say, write "not in persona".

RULES AND WHY
- Use only what the persona file says, because quotes, names, ages
  and feelings that are not in the file are inventions, not evidence.
- If something is not in the information above, say you do not know,
  so we can find it out.
- For each claim, say which part of the information above it comes from,
  so we can check it.
- Use only the information above, because we have no other data.

FORMAT
End with one line: this is a hypothesis
to test with real people, not a finding.
```

### Skill file: update-files-skill.md

```text
Name: update-files-skill
Use when I say "update project files".

EVIDENCE WE HAVE AND WHAT WE DO NOT KNOW
We have: README.md and state.md in Context,
and the file I just approved in this chat.
We do not know: anything else about the project.

WHAT I WANT YOU TO DO AND WHY
Update state.md after an approved file,
so the next chat knows where we stopped.
1. Status table: add the approved file, and correct
   the current phase, open research questions and next step.
2. Decisions table: add a row only if a choice was made,
   with the reason.
3. History table: add a row with version, date,
   created by, what changed and why.
4. Say whether README.md needs a change (a new ID type,
   a new file name). Do not change it unless I say so.

RULES AND WHY
- Change only state.md, because every other file is approved.
- You cannot put files in the Project, so show the full
  updated state.md in one code block for me to save.
- If something is not in the information above, say you do not
  know, so we can find it out.
- Use only the information above, because we have no other data.

FORMAT
The full updated state.md in one code block,
then one line: what changed.
```

---

© 2026 Ladan Sojudi. Licensed under CC BY-NC-ND 4.0.
